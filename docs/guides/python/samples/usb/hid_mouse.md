# USB HID Mouse

## Overview

The USB HID Mouse sample demonstrates using the USB Human Interface Device (HID) module to implement a mouse input device that you can connect to your computer.

This sample code enumerates the nRF52840 Connect Kit into a HID mouse that has a left button connected to the __USER__ button.

!!! Tip
    `adafruit_hid` is pre-built into [CircuitPython] as a frozen module, so that it can be imported in the code directly.

## Requirements

Before you start, check that you have the required hardware and software:

- [nRF52840 Connect Kit](https://makerdiary.com/products/nrf52840-connectkit) running the [CircuitPython] firmware
- 1x USB-C Cable
- [Mu Editor]
- A computer running macOS, Linux, or Windows 7 or newer

## Running the code

To run the code, complete the following steps:

1. Connect nRF52840 Connect Kit to your computer using the USB-C Cable.
2. Start Mu Editor, click __Load__ to open `code.py` in the __CIRCUITPY__ drive.
3. Copy and paste the following code into `code.py` and click __Save__:

    ``` python linenums="1" title="CIRCUITPY/code.py"
    import time
    import board
    import digitalio
    import usb_hid
    from adafruit_hid.mouse import Mouse

    mouse = Mouse(usb_hid.devices)

    left_button = digitalio.DigitalInOut(board.USER)
    left_button.direction = digitalio.Direction.INPUT
    left_button.pull = digitalio.Pull.UP

    while True:
        if left_button.value is False:
            mouse.click(Mouse.LEFT_BUTTON)
            time.sleep(0.2)  # Debounce delay
    ```

4. Your code will run as soon as the file is done saving. The board will enumerate as a HID mouse. Press __USER__ button on the board, and observe that a left mouse click is activated.

[Mu Editor]: ../../getting-started.md#coding-with-mu-editor
[CircuitPython]: ../../getting-started.md#installing-circuitpython