#Resource CD from BMSKTOPAS91FY42 Kit

Includes:

* Toshiba IDE for TLCS 900 (L only I assume)
* ToshLoad (Segger product, can't find any ref to elsewhere)
* Examples etc


When installing the IDE, the required CDKEY is 7921 (this is included in the PDF of the quick start guide).

The USB driver won't work on recent Windows, as is only x86. Manually forcing the USB serial driver didn't seem to let ToshLoad work.

Ultimately I installed everything on a Windows XP VM, and it worked fine then.

When starting the Toshiba IDE, you need to set the directory of the tools the first time, otherwise you'll get an error that it can't run the C Compiler etc.


