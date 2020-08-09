# Dell-Inspiron-15-3567-EFI Hackintosh

EFI Folder for Dell Inspiron 15 3567 with 6th Gen i3 with Clover UEFI
 
<img src="/Images/Sept-MacBook-Images.png?raw=true" alt="macOS Mojave" align="center">
 
### How to Get it?

- Open Terminal with Command: $ `git clone https://github.com/MrRitwik97/Dell-Inspiron-15-3567-EFI-Hackintosh.git`
 
--------------------------------------------------------------------------------------------
 
### Specs :

- [x] <b>BIOS</b>: Dell 2.11.0
- [x] <b>Model Laptop/Notebook</b>: Dell Inspiron 15-3567
- [x] <b>Processor</b>: Intel Core i3-6006U (2) @ 1.99GHz Skylake
- [x] <b>Graphics</b>: Intel HD Graphics 520
- [x] <b>RAM</b>: 8 GB 2133 MHz DDR4
- [x] <b>HDD</b>: 1TB SATA HDD (GUID Partition Table) will be replaced to SSD soon
- [x] <b>Audio</b>: REALTEK ALC 3234
- [x] <b>Wifi+BT</b>: Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter + TP LINK TL-WN725N WiFi USB Adapter
- [x] <b>Ethernet</b>: Realtek PCI Express Gigabit Ethernet
- [x] <b>Others</b>: USB2.0 ports, WebCam, Synaptics TouchPad PS/2, HDMI

--------------------------------------------------------------------------------------------

### BIOS Configuration

Bios Config | Setting 
:---:| :---:
Security -> Secure Boot | Disabled
Intel Virtualization    | Disabled
VT-d | Disabled
SATA Mode | AHCI
Boot Mode | UEFI

 
--------------------------------------------------------------------------------------------
 
### What's Working?

- [x] Intel HD Graphics 520 1536 MB
- [x] Audio ALC3234 aka ALC255 with layout-id 17 + Internal Microphone (Lilu.kext + AppleALC.kext)
- [x] Display brightness PNLF and Fn Keys (SSDT-OLA.ami + SSDT-PNLF.ami)
- [x] LAN Ethernet Realtek
- [x] Synaptics TouchPad PS/2
- [x] Battery Indicator
- [x] WebCam for Facetime HD Camera Built-In
- [x] USB2.0 Port + Power/Speed (USBInjectAll.kext + Remove Port Limit Kext to Patches in config.plist)
 
--------------------------------------------------------------------------------------------
 
### Not Working?

- Inbuilt WiFi
- AirDrop, Handoff, Continuity, Because this chipset and module not supported
- Etc..

--------------------------------------------------------------------------------------------

### Not Tested?

- HDMI
 
--------------------------------------------------------------------------------------------
 
### Special Thanks and Credits to :

[Apple](https://www.apple.com) | [Clover](https://sourceforge.net/projects/cloverefiboot) | [Acidanthera](https://github.com/acidanthera) |  [InsanelyMac](https://www.insanelymac.com/forum), [Olarila](http://olarila.com/forum) and [OSXLatitude](https://osxlatitude.com/forums) Forum | <b>And Other Developers</b> who aren't mentioned.
