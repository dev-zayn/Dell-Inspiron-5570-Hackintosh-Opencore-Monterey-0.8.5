# OC_INSPIRON_5570_MONTEREY_0.8.2
This EFI was tested on DELL Inspiron 5570 core i7-8550U model. This EFI works with `Monterey 12.4`

Bootloader: Opencore 0.8.2 `Release`

# Issues
* Wifi & bluetooth due to there is no kext for Qualcomm board.

If you are having trouble  with sleep mode rest nvram,

# SMBIOS
Use GenSMBIOS to set your device Serial Number & Model.It's recomended to select `MacBookPro15,3` model.
## To install:

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
