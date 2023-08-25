---
title: Introducing CircuitPython
date: 2023-06-26
authors:
  - makerdiary
cover: cover.png
description: >
  CircuitPython is an implementation of Python for microcontrollers. Once you get your board set up, open any text editor, and start editing code.
---

![](cover.png){ loading=lazy }

# Introducing CircuitPython

## What is CircuitPython?

CircuitPython is a programming language designed to simplify experimenting and learning to program on low-cost microcontroller boards. It makes getting started easier than ever with no upfront desktop downloads needed. Once you get your board set up, open any text editor, and get started editing code. It's that simple.

CircuitPython is an implementation of Python, which is a high-level programming language which means it's designed to be easier to read, write and maintain. It supports modules and packages which means it's easy to reuse your code for other projects. It has a built in interpreter which means there are no extra steps, like compiling, to get your code to work. And of course, it is Open Source Software which means it's free for anyone to use, modify or improve upon.

## Why CircuitPython?

CircuitPython is a fork of [MicroPython](https://micropython.org/), and offers unified Python core APIs and a growing list of 300+ device libraries and drivers that work with it. You can see [differences from MicroPython](https://github.com/adafruit/circuitpython#differences-from-micropython).

Here is some reasons to use CircuitPython:

- __You want to get up and running quickly.__ Create a file, edit your code, save the file, and it runs immediately. There is no compiling, no downloading and no uploading needed.
- __You're new to programming.__ CircuitPython is designed with education in mind. It's easy to start learning how to program and you get immediate feedback from the board.
- __Easily update your code.__ Since your code lives on the disk drive, you can edit it whenever you like, you can also keep multiple files around for easy experimentation.
- __The serial console and REPL.__ These allow for live feedback from your code and interactive programming.
File storage. The internal storage for CircuitPython makes it great for data-logging, playing audio clips, and otherwise interacting with files.
- __Strong hardware support.__ CircuitPython has builtin support for microcontroller hardware features like digital I/O pins, hardware buses (UART, I2C, SPI), audio I/O, and other capabilities. There are also many libraries and drivers for sensors, breakout boards and other external components.
- __It's Python!__ Python is the fastest-growing programming language. It's taught in schools and universities. CircuitPython is almost-completely compatible with Python. It simply adds hardware support.

## How to get started?

To use CircuitPython, you need to choose a microcontroller board well supported by CircuitPython. There are [300+ boards](https://circuitpython.org/downloads) that can run CircuitPython.

Here we have ported CircuitPython to our nRF52840 Connect Kit and offer an extensive set of documentation and samples to help you get started quickly:

[Getting Started with CircuitPython](../../../guides/python/index.md){ .md-button .md-button--primary }
