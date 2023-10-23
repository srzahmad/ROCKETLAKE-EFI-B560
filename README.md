# ASRock B560 Pro4 Motherboard Hackintosh EFI - macOS VENTURA
## Please follow [this guide](/Pre-install.md) before using the bundled EFI.
OpenCore bootloader that makes your ASRock B560M Pro4 runs macOS Big Sur and up!

![image](https://user-images.githubusercontent.com/73286927/215160208-4051dcdd-5c66-408c-bc20-543cc0b578b8.png)

Minecraft running smoothly on the same hack.

![image](https://user-images.githubusercontent.com/73286927/215159086-580b0a70-ffad-46e7-9a9f-f91189c16561.png)

## PC Specs:
```
CPU: Intel® Core™ i7-11700F
RAM: 4x 8GB G.Skill Ripjaws V F4-3200C16S-8GVKB
GPU: ASROCK RX6600XT CLD 8GO
SSD: Kingspec KC3000 1TB
HDD: WD Blue 1TB WD10EZEX
Motherboard: ASRock B560 Pro4
PSU: ANTEC NeoECOMODULAR 650 WATTS
Cooler: STOCK INTEL
Case: ANTEX NX 290 
Wireless Card: FENVI-T919
```

## Motherboard Specs:
![image]([https://user-images.githubusercontent.com/73286927/161385543-b69f7e3a-aea9-41d3-92e3-2e5b2392a48e.png](https://www.asrock.com/mb/photo/B560%20Pro4(L2).png))
* Name: ASRock B560M Pro4
* Chipset: Intel B560
* Supports 10th Gen Intel® Core™ Processors and 11th Gen Intel® Core™ Processors
* Ethernet: Intel® Gigabit LAN
* Audio: Realtek ALC897 (layout-id 11)
* Expansion Slots: 1x PCI-E (GEN 3) x16 socket, 1x M.2 socket 1 Key-A, 1x PCIe 4.0 x16, 1x PCIe 3.0 x16, 1x PCIe 3.0 x1, 1x M.2 Key-E for WiFi, 1x Hyper M.2 (PCIe Gen4 x4), 1x Ultra M.2 (PCIe Gen3 x4 & SATA3)

**For more detailed info please visit [https://www.asrock.com/mb/Intel/B560M%20Pro4/](https://www.asrock.com/mb/Intel/B560%20Pro4/index.asp)**

## ✅ Whats workin'
* Full graphics acceleration with supported GPUs (`iMacPro1,1` or `MacPro7,1` is recommended)
* DRM with AMD dGPU (`iMacPro1,1` and `MacPro7,1`) configuration. Please follow [**this guide**](https://dortania.github.io/OpenCore-Post-Install/universal/drm.html) for more information.
* USB 2.0 and 3.0 (all)
* Ethernet
* Audio
* Sleep & Wake works perfectly (with USB mapping and [**GPRW Instant Wake Patch**](https://dortania.github.io/OpenCore-Post-Install/usb/misc/instant-wake.html))
* CPU Power Management
* iServices (using **this guide: https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html**)
* Wake on LAN
* SMBUS
* Continuity features (such as AirDrop, Handoff and Universal Control) **(requires a compatible Broadcom wireless card)**
* Pretty much anything else
## ❌ Not workin'
* **You tell me**

## Credits
* [Apple](https://apple.com) for [**macOS**](https://apple.com/macos)
* [acidanthera](https://github.com/acidanthera) for [**OpenCore**](https://github.com/acidanthera/OpenCorePkg), [**Lilu**](https://github.com/acidanthera/Lilu), [**WhateverGreen**](https://github.com/acidanthera/WhateverGreen) and [**AppleALC**](https://github.com/acidanthera/AppleALC)
* [Dortania](https://dortania.github.io) for [**OpenCore Install Guide**](https://dortania.github.io/OpenCore-Install-Guide)
