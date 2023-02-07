# Toshiba TLCS-900/L Series Tools, RE

This repo is a collection of various things I found when looking at a TLCS-900/L1 device (TMP91FW60) used in my oven.

Of most interest is the "Toshiba IDE" tool. I purchased a started kit with came with the CD ROM, and included a starter edition of it.

I'm not sure of all the differences, one thing is the emulators don't seem to be supported(?).

## Python Bootloader

You can find an implementation of the ToshLoad program at [PyToshLoad](https://github.com/colinoflynn/pytoshload). This allows programming of certain TLCS900/L1 devices using the hardware bootloader. Tested devices include:

* TMP91FW60/TMP91FW60DFG/TMP91FW60DG
* TMP91FW27UG

## Disassembling with IDE
