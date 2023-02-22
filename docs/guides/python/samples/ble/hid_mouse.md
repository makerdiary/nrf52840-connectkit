# BLE HID Mouse

## Overview

The BLE HID Mouse sample demonstrates how to use the GATT Human Interface Device (HID) Service to implement a mouse input device that you can connect to your computer.

This sample code enumerates the nRF52840 Connect Kit into a BLE HID mouse that has a left button connected to the __USER__ button.

!!! Tip
    `adafruit_ble` and `adafruit_hid` are pre-built into [CircuitPython] as frozen modules, so that they can be imported in the code directly.

## Requirements

Before you start, check that you have the required hardware and software:

- [nRF52840 Connect Kit](https://makerdiary.com/products/nrf52840-connectkit) running the [CircuitPython] firmware
- 1x USB-C Cable
- [Mu Editor]
- A computer running macOS, Linux, or Windows 7 or newer, with Bluetooth LE supported

## Running the code

To run the code, complete the following steps:

1. Connect nRF52840 Connect Kit to your computer using the USB-C Cable.
2. Start Mu Editor, click __Load__ to open `code.py` in the __CIRCUITPY__ drive.
3. Copy and paste the following code into `code.py` and click __Save__:

    ``` python linenums="1" title="CIRCUITPY/code.py"
    import time
    import board
    import digitalio

    from adafruit_hid.mouse import Mouse

    import adafruit_ble
    from adafruit_ble.advertising import Advertisement
    from adafruit_ble.advertising.standard import ProvideServicesAdvertisement
    from adafruit_ble.services.standard.hid import HIDService
    from adafruit_ble.services.standard.device_info import DeviceInfoService

    left_button = digitalio.DigitalInOut(board.USER)
    left_button.direction = digitalio.Direction.INPUT
    left_button.pull = digitalio.Pull.UP

    # Use default HID descriptor
    hid = HIDService()
    device_info = DeviceInfoService(
        software_revision=adafruit_ble.__version__, manufacturer="Makerdiary"
    )
    ble = adafruit_ble.BLERadio()
    ble.name = 'CIRCUITPY MOUSE'
    advertisement = ProvideServicesAdvertisement(hid)
    advertisement.complete_name = ble.name
    advertisement.appearance = 962
    scan_response = Advertisement()

    if ble.connected:
        for c in ble.connections:
            c.disconnect()

    print("advertising")
    ble.start_advertising(advertisement, scan_response)

    mouse = Mouse(hid.devices)

    while True:
        while not ble.connected:
            pass
        while ble.connected:
            if left_button.value is False:
                mouse.click(Mouse.LEFT_BUTTON)
                time.sleep(0.2)  # Debounce delay

        ble.start_advertising(advertisement)

    ```

4. Your code will run as soon as the file is done saving. A Bluetooth mouse with the name __`CIRCUITPY MOUSE`__ can be discovered by your computer. Connect to the mouse.

    ![](../../../../assets/images/circuitpy_ble_mouse.png)

5. Press __USER__ button on the board, and observe that a left mouse click is activated.

[Mu Editor]: ../../getting-started.md#coding-with-mu-editor
[CircuitPython]: ../../getting-started.md#installing-circuitpython
