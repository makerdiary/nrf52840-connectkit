# Reference

CircuitPython provides a variety of modules that can be used in your sample applications.

Here you can find documentation for these modules, including API reference.


| Module                                           | Description                              |
|--------------------------------------------------|------------------------------------------|
| [**`_bleio`**][_bleio]                           | Bluetooth Low Energy (BLE) communication |
| [**`_pixelmap`**][_pixelmap]                     | A fast pixel mapping library             |
| [**`adafruit_ble`**][adafruit_ble]               | Higher-level Bluetooth Low Energy functionality, building on the native [**`_bleio`**][_bleio] module |
| [**`adafruit_bus_device`**][adafruit_bus_device] | Hardware accelerated external bus access |
| [**`adafruit_hid`**][adafruit_hid]               | USB Human Interface Device (HID) class   |
| [**`adafruit_pixelbuf`**][adafruit_pixelbuf]     | A fast RGB(W) pixel buffer library for like NeoPixel and DotStar |
| [**`aesio`**][aesio]                             | AES encryption routines                  |
| [**`alarm`**][alarm]                             | Alarms and sleep                         |
| [**`analogio`**][analogio]                       | Analog hardware support                  |
| [**`array`**][array]                             | Arrays of numeric data                   |
| [**`atexit`**][atexit]                           | Atexit Module                            |
| [**`audiobusio`**][audiobusio]                   | Support for audio input and output over digital buses |
| [**`audiocore`**][audiocore]                     | Support for audio samples                |
| [**`audiomixer`**][audiomixer]                   | Support for audio mixing                 |
| [**`audiomp3`**][audiomp3]                       | Support for MP3-compressed audio files   |
| [**`audiopwmio`**][audiopwmio]                   | Audio output via digital PWM             |
| [**`binascii`**][binascii]                       | Binary/ASCII conversions                 |
| [**`bitbangio`**][bitbangio]                     | Digital protocols implemented by the CPU |
| [**`bitmaptools`**][bitmaptools]                 | Collection of bitmap manipulation tools  |
| [**`board`**][board]                             | Board specific pin names                 |
| [**`builtins`**][builtins]                       | Builtin functions and exceptions         |
| [**`busio`**][busio]                             | Hardware accelerated external bus access |
| [**`collections`**][collections]                 | Collection and container types           |
| [**`countio`**][countio]                         | Support for edge counting                |
| [**`digitalio`**][digitalio]                     | Basic digital pin support                |
| [**`displayio`**][displayio]                     | Native helpers for driving displays      |
| [**`errno`**][errno]                             | System error codes                       |
| [**`fontio`**][fontio]                           | Core font related data structures        |
| [**`framebufferio`**][framebufferio]             | Native framebuffer display driving       |
| [**`gc`**][gc]                                   | Control the garbage collector            |
| [**`getpass`**][getpass]                         | Getpass Module                           |
| [**`io`**][io]                                   | Input/output streams                     |
| [**`json`**][json]                               | JSON encoding and decoding               |
| [**`keypad`**][keypad]                           | Support for scanning keys and key matrices |
| [**`math`**][math]                               | Mathematical functions                   |
| [**`microcontroller`**][microcontroller]         | Pin references and cpu functionality     |
| [**`micropython`**][micropython]                 | Access and control MicroPython internals |
| [**`msgpack`**][msgpack]                         | Pack object in msgpack format            |
| [**`neopixel`**][neopixel]                       | Higher level NeoPixel driver that presents the strip as a sequence |
| [**`neopixel_write`**][neopixel_write]           | Low-level neopixel implementation        |
| [**`nvm`**][nvm]                                 | Non-volatile memory                      |
| [**`onewireio`**][onewireio]                     | Low-level bit primitives for Maxim (formerly Dallas Semi) one-wire protocol |
| [**`os`**][os]                                   | Functions that an OS normally provides   |
| [**`paralleldisplay`**][paralleldisplay]         | Native helpers for driving parallel displays |
| [**`pulseio`**][pulseio]                         | Support for individual pulse based protocols |
| [**`pwmio`**][pwmio]                             | Support for PWM based protocols          |
| [**`rainbowio`**][rainbowio]                     | Rainbowio Module                         |
| [**`random`**][random]                           | Pseudo-random numbers and choices        |
| [**`re`**][re]                                   | Simple regular expressions               |
| [**`rgbmatrix`**][rgbmatrix]                     | Low-level routines for bitbanged LED matrices |
| [**`rotaryio`**][rotaryio]                       | Support for reading rotation sensors     |
| [**`rtc`**][rtc]                                 | Real Time Clock                          |
| [**`sdcardio`**][sdcardio]                       | Interface to an SD card via the SPI bus  |
| [**`select`**][select]                           | Wait for events on a set of streams      |
| [**`sharpdisplay`**][sharpdisplay]               | Support for Sharp Memory Display framebuffers |
| [**`storage`**][storage]                         | Storage management                       |
| [**`struct`**][struct]                           | Manipulation of C-style data             |
| [**`supervisor`**][supervisor]                   | Supervisor settings                      |
| [**`synthio`**][synthio]                         | Support for MIDI synthesis               |
| [**`sys`**][sys]                                 | System specific functions                |
| [**`terminalio`**][terminalio]                   | Displays text in a TileGrid              |
| [**`time`**][time]                               | Time and timing related functions        |
| [**`touchio`**][touchio]                         | Touch related IO                         |
| [**`traceback`**][traceback]                     | Traceback Module                         |
| [**`ulab`**][ulab]                               | Manipulate numeric data similar to numpy |
| [**`usb_cdc`**][usb_cdc]                         | USB CDC Serial streams                   |
| [**`usb_hid`**][usb_hid]                         | USB Human Interface Device               |
| [**`usb_midi`**][usb_midi]                       | MIDI over USB                            |
| [**`vectorio`**][vectorio]                       | Lightweight 2D shapes for displays       |
| [**`watchdog`**][watchdog]                       | Watchdog Timer                           |
| [**`zlib`**][zlib]                               | zlib decompression functionality         |


[_bleio]: https://docs.circuitpython.org/en/latest/shared-bindings/_bleio/index.html
[_pixelmap]: https://docs.circuitpython.org/en/latest/shared-bindings/_pixelmap/index.html
[adafruit_ble]: https://docs.circuitpython.org/projects/ble/en/latest/api.html
[adafruit_bus_device]: https://docs.circuitpython.org/en/latest/shared-bindings/adafruit_bus_device/index.html
[adafruit_hid]: https://docs.circuitpython.org/projects/hid/en/latest/
[adafruit_pixelbuf]: https://docs.circuitpython.org/en/latest/shared-bindings/adafruit_pixelbuf/index.html
[aesio]: https://docs.circuitpython.org/en/latest/shared-bindings/aesio/index.html
[alarm]: https://docs.circuitpython.org/en/latest/shared-bindings/alarm/index.html
[array]: https://docs.circuitpython.org/en/latest/docs/library/array.html
[analogio]: https://docs.circuitpython.org/en/latest/shared-bindings/analogio/index.html
[atexit]: https://docs.circuitpython.org/en/latest/shared-bindings/atexit/index.html
[audiobusio]: https://docs.circuitpython.org/en/latest/shared-bindings/audiobusio/index.html
[audiocore]: https://docs.circuitpython.org/en/latest/shared-bindings/audiocore/index.html
[audiomixer]: https://docs.circuitpython.org/en/latest/shared-bindings/audiomixer/index.html
[audiomp3]: https://docs.circuitpython.org/en/latest/shared-bindings/audiomp3/index.html
[audiopwmio]: https://docs.circuitpython.org/en/latest/shared-bindings/audiopwmio/index.html
[binascii]: https://docs.circuitpython.org/en/latest/docs/library/binascii.html
[bitbangio]: https://docs.circuitpython.org/en/latest/shared-bindings/bitbangio/index.html
[bitmaptools]: https://docs.circuitpython.org/en/latest/shared-bindings/bitmaptools/index.html
[board]: https://docs.circuitpython.org/en/latest/shared-bindings/board/index.html
[builtins]: https://docs.circuitpython.org/en/latest/docs/library/builtins.html
[busio]: https://docs.circuitpython.org/en/latest/shared-bindings/busio/index.html
[collections]: https://docs.circuitpython.org/en/latest/docs/library/collections.html
[countio]: https://docs.circuitpython.org/en/latest/shared-bindings/countio/index.html
[digitalio]: https://docs.circuitpython.org/en/latest/shared-bindings/digitalio/index.html
[displayio]: https://docs.circuitpython.org/en/latest/shared-bindings/displayio/index.html
[errno]: https://docs.circuitpython.org/en/latest/docs/library/errno.html
[fontio]: https://docs.circuitpython.org/en/latest/shared-bindings/fontio/index.html
[framebufferio]: https://docs.circuitpython.org/en/latest/shared-bindings/framebufferio/index.html
[gc]: https://docs.circuitpython.org/en/latest/docs/library/gc.html
[getpass]: https://docs.circuitpython.org/en/latest/shared-bindings/getpass/index.html
[io]: https://docs.circuitpython.org/en/latest/docs/library/io.html
[json]: https://docs.circuitpython.org/en/latest/docs/library/json.html
[keypad]: https://docs.circuitpython.org/en/latest/shared-bindings/keypad/index.html
[math]: https://docs.circuitpython.org/en/latest/shared-bindings/math/index.html
[microcontroller]: https://docs.circuitpython.org/en/latest/shared-bindings/microcontroller/index.html
[micropython]: https://docs.circuitpython.org/en/latest/docs/library/micropython.html
[msgpack]: https://docs.circuitpython.org/en/latest/shared-bindings/msgpack/index.html
[neopixel]: https://docs.circuitpython.org/projects/neopixel/en/latest/
[neopixel_write]: https://docs.circuitpython.org/en/latest/shared-bindings/neopixel_write/index.html
[nvm]: https://docs.circuitpython.org/en/latest/shared-bindings/nvm/index.html
[onewireio]: https://docs.circuitpython.org/en/latest/shared-bindings/onewireio/index.html
[os]: https://docs.circuitpython.org/en/latest/shared-bindings/os/index.html
[paralleldisplay]: https://docs.circuitpython.org/en/latest/shared-bindings/paralleldisplay/index.html
[pulseio]: https://docs.circuitpython.org/en/latest/shared-bindings/pulseio/index.html
[pwmio]: https://docs.circuitpython.org/en/latest/shared-bindings/pwmio/index.html
[rainbowio]: https://docs.circuitpython.org/en/latest/shared-bindings/rainbowio/index.html
[random]: https://docs.circuitpython.org/en/latest/shared-bindings/random/index.html
[re]: https://docs.circuitpython.org/en/latest/docs/library/re.html
[rgbmatrix]: https://docs.circuitpython.org/en/latest/shared-bindings/rgbmatrix/index.html
[rotaryio]: https://docs.circuitpython.org/en/latest/shared-bindings/rotaryio/index.html
[rtc]: https://docs.circuitpython.org/en/latest/shared-bindings/rtc/index.html
[sdcardio]: https://docs.circuitpython.org/en/latest/shared-bindings/sdcardio/index.html
[select]: https://docs.circuitpython.org/en/latest/docs/library/select.html
[sharpdisplay]: https://docs.circuitpython.org/en/latest/shared-bindings/sharpdisplay/index.html
[storage]: https://docs.circuitpython.org/en/latest/shared-bindings/storage/index.html
[struct]: https://docs.circuitpython.org/en/latest/shared-bindings/struct/index.html
[supervisor]: https://docs.circuitpython.org/en/latest/shared-bindings/supervisor/index.html
[synthio]: https://docs.circuitpython.org/en/latest/shared-bindings/synthio/index.html
[sys]: https://docs.circuitpython.org/en/latest/docs/library/sys.html
[terminalio]: https://docs.circuitpython.org/en/latest/shared-bindings/terminalio/index.html
[time]: https://docs.circuitpython.org/en/latest/shared-bindings/time/index.html
[touchio]: https://docs.circuitpython.org/en/latest/shared-bindings/touchio/index.html
[traceback]: https://docs.circuitpython.org/en/latest/shared-bindings/traceback/index.html
[ulab]: https://docs.circuitpython.org/en/latest/shared-bindings/ulab/index.html
[usb_cdc]: https://docs.circuitpython.org/en/latest/shared-bindings/usb_cdc/index.html
[usb_hid]: https://docs.circuitpython.org/en/latest/shared-bindings/usb_hid/index.html
[usb_midi]: https://docs.circuitpython.org/en/latest/shared-bindings/usb_midi/index.html
[vectorio]: https://docs.circuitpython.org/en/latest/shared-bindings/vectorio/index.html
[watchdog]: https://docs.circuitpython.org/en/latest/shared-bindings/watchdog/index.html
[zlib]: https://docs.circuitpython.org/en/latest/shared-bindings/zlib/index.html
