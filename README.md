# OC_INSPIRON_5570_MONTEREY_0.8.2
This EFI was tested on DELL Inspiron 5570 core i7-8550U model. This EFI works with `Monterey 12.4`

Bootloader: Opencore 0.8.2 `Release`

# Issues
* Wifi & bluetooth due to there is no kext for Qualcomm board.

# Notes you should know before Installing

* when you choose `install macOS Monetery` if it stucks on apple logo for too long. restart you device and choose `modGRUBShell (1)` and type the following one by one.

    `setup_var 0x795 0x2` ->
    `setup_var 0x796 0x3` ->
    `setup_var 0x4ED 0x0` ->
    `setup_var 0x272 0x0` ->
    `reboot`

* If you are having trouble  with sleep mode Rest NVRAM.

# SMBIOS
Use GenSMBIOS to set your device Serial Number & Model.It's recomended to select `MacBookPro15,3` model.
## To install GenSMBIOS:

Do the following one line at a time in Terminal:

    git clone https://github.com/corpnewt/GenSMBIOS
    cd GenSMBIOS
    chmod +x GenSMBIOS.command
    
Then run with either `./GenSMBIOS.command` or by double-clicking *GenSMBIOS.command*

# SPECS

|SPEC|TYPE|
|---|---|
|Device name|  DELL inspiron 5570 15.6"|
|CPU| Mobile Intel Core i7-8550U|
|RAM| 24 GB (DDR4 RAM)|
|iGPU:| Intel UHD Graphics 620|
