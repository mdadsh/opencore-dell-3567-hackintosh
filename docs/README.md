### opencore-dell-3567-hackintosh

## Upgraded to Big Sur 11.1 from Catalina 10.15.7
<img src="/docs/desktop.png?raw=true" alt="MacOS Big Sur 11.1" align="center">

--------------------------------------------------------------------------------------------

### Comments

This Hackintosh build may NOT fully work in your default conditions. Please KNOW YOUR HARDWARE and also be aware as what is supported under Apple flag and make changes accordingly. If you have the components verbatim to mine then go right ahead and use this repo. This will be true for any laptop having these components. This guide has been tested on MacOS Catalina 10.15.3, 10.15.5-7, 11.0 and 11.1. Also read through all the available material/guides/FAQs and double check everything before committing changes.

I replaced my WiFi card from stock DW1810 to DW1820a and HDD to SSD.

--------------------------------------------------------------------------------------------

### Specs :

- [x] <b>CPU</b>: Intel® Core™ i7-7500U Processor (Kaby-Lake)
- [x] <b>iGPU</b>: Intel® HD Graphics 620 @1920x1080 60Hz
- [x] <b>dGPU</b>: AMD® Radeon™ R5 M430 2GB
- [x] <b>LAN</b>: Realtek® RTL8106E PCI Express Fast Ethernet
- [x] <b>WiFi/Bluetooth</b>: BCM94350ZAE (DW1820a)
- [x] <b>Audio</b>: Realtek® ALC256 High Definition Audio

--------------------------------------------------------------------------------------------

### BIOS Configuration

BIOS Config | Setting
:---:| :---:
Security -> Secure Boot | Disabled
Intel Virtualization    | Disabled
VT-d | Disabled
SATA Mode | AHCI
Boot Mode | UEFI

--------------------------------------------------------------------------------------------

### Not Tested

- [x] FileVault

--------------------------------------------------------------------------------------------

### Not Working

- [x] Sleep can be buggy sometimes

--------------------------------------------------------------------------------------------

### Next challenge
- [x] TBD

--------------------------------------------------------------------------------------------

### Special Thanks and Credits to :

- [Apple](https://apple.com)
- [Opencore Laptop Guide](https://dortania.github.io/vanilla-laptop-guide/)
- [acidanthera](https://github.com/acidanthera)
- [corpnewt](https://github.com/corpnewt)
- [Aleksandar Vacić](https://aplus.rs/tags/opencore)
- [comsysto](https://comsysto.github.io/Display-Override-PropertyList-File-Parser-and-Generator-with-HiDPI-Support-For-Scaled-Resolutions/)
- [avibrazil](https://github.com/avibrazil/RDM)
