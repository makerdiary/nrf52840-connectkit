# nRF52840 Connnect Kit

[![Documentation](https://github.com/makerdiary/nrf52840-connectkit/actions/workflows/documentation.yml/badge.svg?branch=main)](https://github.com/makerdiary/nrf52840-connectkit/actions/workflows/documentation.yml?query=branch%3Amain)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?color=informational)](/.github/CONTRIBUTING.md)

> Connected Prototyping Kit featuring the nRF52840 SoC

## Introduction

nRF52840 Connect Kit is an open-source prototyping kit designed for connected projects. It is built using the nRF52840 SoC, which has protocol support for Bluetooth LE, Bluetooth mesh, Thread, Zigbee, 802.15.4, ANT and 2.4 GHz proprietary stacks. It provides Arm TrustZone® CryptoCell cryptographic unit as well as numerous peripherals such as USB 2.0, NFC-A, GPIO, UART, SPI, TWI, PDM, I2S, QSPI, PWM, ADC, QDEC to support a wide range of applications.

The design is available in an easy-to-use form factor with USB-C and 40 pin DIP/SMT type, including up to 32 multi-function GPIO pins (7 can be used as ADC inputs) and Serial Wire Debug (SWD) port. It features RGB LED, Buttons, external 64 Mbit QSPI flash and flexible power management with various options for easily powering the unit from USB-C, external supplies or batteries, and also has Chip antenna and U.FL receptacle options to support various wireless scenarios.

nRF52840 Connect Kit supports [nRF Connect SDK][ncs-guide], which integrates the Zephyr RTOS, protocol stacks, samples, hardware drivers and much more. We also offer [Python support][python-guide], allowing you access hardware-specific functionality and peripherals with Python programming language.

![product hero](./docs/assets/images/nrf52840_connectkit_hero.png)

## Key Features

* Nordic Semiconductor nRF52840 SoC

    - 64 MHz Arm® Cortex-M4 with FPU
    - 1 MB Flash + 256 KB RAM
    - Bluetooth LE, Bluetooth mesh, Thread, Zigbee, 802.15.4, ANT and 2.4 GHz proprietary
    - Arm TrustZone® Cryptocell 310 Security Subsystem
    - 2.4 GHz Transceiver with +8 dBm TX Power
    - GPIO, UART, SPI, TWI(I2C), PDM, I2S, QSPI, PWM, QDEC, 12-bit ADC support
    - Integrated USB 2.0 Full-speed Controller
    - Integrated NFC-A Tag

* Ultra low power 64 Mbit QSPI flash memory
* User programmable RBG LED and Buttons
* Up to 32 multi-function General Purpose IOs (7 can be used as ADC inputs)
* Arm Serial Wire Debug (SWD) port via edge pins
* Flexible power management with various options for easily powering the unit 
* Wide input voltage range: 1.8 V to 5.5 V, output 3.3V and up to 2A when Input ≥ 2.3 V
* 3.3V IO Operating Voltage
* Reversible USB-C connector
* Available in Chip antenna and U.FL receptacle options
* 40 pin 55.88mm x 20.32mm (2.2" x 0.8") DIP/SMT form factor
* Shipped with UF2 Bootloader supporting Drag-and-drop programming over USB drive
* Built on open source, supporting nRF Connect SDK, Zephyr RTOS, Python, etc.

## Hardware Diagram

The following figure illustrates the nRF52840 Connect Kit hardware diagram. The design is available in Chip antenna and U.FL receptacle options, both have most of the same components except the antenna interface.

[![Hardware Diagram](./docs/assets/images/pinout.png)](./docs/assets/attachments/nrf52840-connectkit-quick-start-guide.pdf)

## Documentation

We offer an extensive set of documentation such as out of box experience, getting started and developer guides, which can help you save big by reducing development effort.

* [nRF52840 Connect Kit Wiki][wiki]
* [nRF52840 Connect Kit Product Brief][product-brief]
* [nRF52840 Connect Kit Out-of-box Experience][out-of-box-experience]
* [How to program the nRF52840 Connect Kit][programming]
* [Develop with nRF Connect SDK & Zephyr RTOS][ncs-guide]
* [How to Code in Python][python-guide]
* [nRF Sniffer for Bluetooth LE][ble-sniffer]
* [nRF Sniffer for 802.15.4][nrf802154-sniffer]
* [nRF52840 Connect Kit Quick Start Guide][quick-start]
* [nRF52840 Connect Kit Hardware Description][hardware-description]
* [nRF52840 Connect Kit Schematic V1.0][schematic]
* [nRF52840 Connect Kit 3D CAD STEP Models][3d-models]

## Where to buy

nRF52840 Connect Kit is available on the following channels (click to go directly to the product):

<a href="https://makerdiary.com/products/nrf52840-connectkit"><img alt="makerdiary store" display="inline" src="./docs/assets/images/makerdiary-store.png" width="260"></a>
<a href="https://zaowubang.taobao.com"><img alt="Taobao" display="inline" src="./docs/assets/images/taobao-store.png" width="143"></a>
<a href="https://www.tindie.com/products/zelin/nrf52840-connectkit/"><img alt="Tindie" display="inline" src="./docs/assets/images/tindie-store.png" width="128"></a>

## Community Support

Community support is provided via [GitHub Discussions][discussions]. You can also reach us on
[Makerdiary Community][community].

We would love to have more developers contribute to this project! If you're passionate about making this project better, see our [Contributing Guidelines][contributing] for more information.

## License

Copyright (c) 2016-2023 Makerdiary. See [LICENSE](./LICENSE) for further details.

[ncs-guide]: https://wiki.makerdiary.com/nrf52840-connectkit/guides/ncs
[python-guide]: https://wiki.makerdiary.com/nrf52840-connectkit/guides/python
[wiki]: https://wiki.makerdiary.com/nrf52840-connectkit
[product-brief]: https://wiki.makerdiary.com/nrf52840-connectkit/introduction
[out-of-box-experience]: https://wiki.makerdiary.com/nrf52840-connectkit/out-of-box-experience
[programming]: https://wiki.makerdiary.com/nrf52840-connectkit/programming
[ble-sniffer]: https://wiki.makerdiary.com/nrf52840-connectkit/guides/ble-sniffer
[nrf802154-sniffer]: https://wiki.makerdiary.com/nrf52840-connectkit/guides/nrf802154-sniffer/
[quick-start]: https://wiki.makerdiary.com/nrf52840-connectkit/nrf52840-connectkit/assets/attachments/nrf52840-connectkit-quick-start-guide.pdf
[hardware-description]: https://wiki.makerdiary.com/nrf52840-connectkit/hardware
[schematic]: https://wiki.makerdiary.com/nrf52840-connectkit/assets/attachments/nrf52840-connect-kit-schematic-v1.0.pdf
[3d-models]: https://wiki.makerdiary.com/nrf52840-connectkit/assets/attachments/nrf52840-connect-kit-3d-cad-step-models.zip
[discussions]: https://github.com/makerdiary/nrf52840-connectkit/discussions
[community]: https://community.makerdiary.com
[contributing]: https://wiki.makerdiary.com/nrf52840-connectkit/CONTRIBUTING
