[![](https://img.shields.io/badge/Gitter%20HL%20Community-Chat-informational?style=flat&logo=gitter&logoColor=white&color=ed1965)](https://gitter.im/Hackintosh-Life-IT/community)
[![](https://img.shields.io/badge/EFI-Release-informational?style=flat&logo=apple&logoColor=white&color=9debeb)](https://github.com/Lorys89/ASROCK_Z490M-ITX-AC/releases)
[![](https://img.shields.io/badge/Telegram-HackintoshLifeIT-informational?style=flat&logo=telegram&logoColor=white&color=5fb659)](https://t.me/HackintoshLife_it)
[![](https://img.shields.io/badge/Facebook-HackintoshLifeIT-informational?style=flat&logo=facebook&logoColor=white&color=3a4dc9)](https://www.facebook.com/hackintoshlife/)
[![](https://img.shields.io/badge/Instagram-HackintoshLifeIT-informational?style=flat&logo=instagram&logoColor=white&color=8a178a)](https://www.instagram.com/hackintoshlife.it_official/)
# ASROCK Z490M ITX/AC Hackintosh

EFI for ASROCK Z490M ITX/AC with OpenCore bootloader

![descrizione](./Screenshot/pc.jpg)

### Computer Spec:

| Component        | Brank                              |
| ---------------- | ---------------------------------- |
| CPU              | Intel i5 10600K (6C-12T 12MB CML)  |
| iGPU             | Intel® UHD Graphics                |
| GPU              | SHAPPIRE NITRO+ RX570 4GB GDDR5    |
| Lan 2.5 GBPS     | Realtek 8125                       |
| Lan 1.0 GBPS     | Intel I219 V11                     |
| Audio            | Realtek ALC1200                    |
| Ram              | CORSAIR DDR4 3600 MHz 32GB         |
| Wifi + Bluetooth | BCM94352Z (DW1560)                 |
| 1° NVMe          | SAMSUNG 970 EVO PLUS 500 GB (MACOS)|
| 2° NVMe          | SAMSUNG 970 EVO PLUS 500 GB (WIN)  |
| SSD              | SAMSUNG 860 EVO 500 GB (DATI)      |
| SmBios           | iMac 20,1                          |
| BootLoader       | OpenCore 0.6.6                     |
| macOS            | Big Sur 11.3 (Beta)                |


![infomac](./Screenshot/infomac.png)

## Peripherals & Bench

![infohack](./Screenshot/hackintooldevice.png)
![infodp2](./Screenshot/DpciScreen2.png)
![infopci](./Screenshot/PCISEZ.png)
![Fan&Temp](./Screenshot/fantemp.png)
![Speedtest](./Screenshot/speedtest.png)
![bench](./Screenshot/RAM-NVME.png)
![CPU](./Screenshot/cpu.png)
![OPENCL](./Screenshot/opencl.png)
![METAL](./Screenshot/metal.png)
![videoproc](./Screenshot/videoproc.png)


### What works and What doesn't or WIP:

- [x] Intel UHD iGPU HDMI/DP Output
- [x] Intel UHD iGPU - H264 & HEVC
- [x] SHAPPIRE NITRO+ RX570 HDMI/DP Output
- [x] SHAPPIRE NITRO+ RX570 - H264 & HEVC
- [x] ALC1200 Native Combojack headphones
- [x] ALC1200 Combojack microphone
- [x] ALC1200 HDMI/DP Audio Output
- [x] ALC1200 jack LINE-IN
- [x] All USB Ports 
- [x] SpeedStep / Sleep / Wake
- [x] HID Key PWRB & SLPB 
- [x] Wi-Fi and Bluetooth BCM94352Z (DW1560) Module
- [x] 1° CONTROLLER NVME PciE Gen3x4
- [x] 2° CONTROLLER NVME PciE Gen3x4
- [x] CONTROLLER SATA III
- [x] All Sensors (CPU, IGPU, GPU, NVME, SATA, MOBO, FAN)
- [x] Realtek RTL8125 LAN
- [x] Intel I219 V11 LAN
- [x] NVRAM
- [x] Windows 10 boot from OpenCore



### Special Config:

- Usb port mapping performed
- Applied cosmetics pci-dev

See [ioreg](./ioregMacmini.ioreg) for more clarification

### MacOS bootable USB creation:
- Read the Dortania guide for creating your USB from Windows or macOS
- [Guide Dortania](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/) - USB creation


## Bios settings
### Enable :
* SATA Operation : AHCI
* Fastboot : Thorough
* Integrated NIC : Enable


### Disable : 
* Secure Boot
* Absolute
* TPM2.0 Security On
* Intel SGX
* Enable UEFI Network Stack

## Credits

- [Apple](https://apple.com) for macOS;
- [Acidanthera](https://github.com/acidanthera) for OpenCore and all the lovely hackintosh work.
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/icelake.html) For great and detailed guides.
- [Hackintoshlifeit](https://github.com/Hackintoshlifeit) Support group for installation and post installation.

# If you need help please contact us on [Telegram](https://t.me/HackintoshLife_it) or [Web](https://www.hackintoshlife.it/)
