# Firmware

This folder contains various firmwares available for the PathRF. The use of these firmwares range anywhere from simply demoing or testing the PathRF, to the "production" firmware.

## Requirements

All firmware is built using the PlatformIO extension inside Visual Studio Code. The firware that is built can then be drag-and-dropped to the RP2040 on the PathRF to program it like any other typical RP2040 based board (such as the Raspberry Pi Pico).

In order to put the RP2040 into programming mode, the programming header needs to be jumpered prior to powering the board, then connecting the board to a computer. The board will show up as a mass storage device that firmware can be drag-and-dropped onto.
