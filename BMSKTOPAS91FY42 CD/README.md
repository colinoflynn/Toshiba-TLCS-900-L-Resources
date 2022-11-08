# Resource CD from BMSKTOPAS91FY42 Kit

The links to all these tools seems to be removed - be warned there was a [security vulnerability](https://toshiba.semicon-storage.com/us/semiconductor/knowledge/security-advisories/installers-of-development-tool-software-products-for-toshiba-original-core-based-microcontrollers-have-a-security-vulnerability.html) that may or may not apply to the installer, suggest to install in a VM, which is required for them to work anyway. 

Includes:

* Toshiba IDE for TLCS 900 (L only I assume)
* ToshLoad (Segger product, can't find any ref to elsewhere)
* Examples etc


When installing the IDE, the required CDKEY is 7921 (this is included in the PDF of the quick start guide, but you might miss it).

The USB driver won't work on recent Windows, as is only x86. Ultimately I installed everything on a Windows XP VM, and it worked fine then. See note above about security vulnerability.

When starting the Toshiba IDE, you need to set the directory of the tools the first time, otherwise you'll get an error that it can't run the C Compiler etc.


