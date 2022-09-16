# AMD Ryzen Hackintosh

[![MacOS version](https://img.shields.io/badge/Monterey-12.6-informational.svg)](https://www.apple.com/macos)
[![OpenCore version](https://img.shields.io/badge/OpenCore-0.8.4-informational.svg)](https://github.com/acidanthera/OpenCorePkg)

## Disclaimer
Use at your own risk. I take no responsiblity if your rig explodes. Create unique SMBios values for your rig. Don't copy ones shown in the config.plist!!!

## Important information
* This EFI supports only MacOS versions catalina(10.15) and higher. Your system will not boot if you use this on Mojave and High Sierra.

## Specification

| Component        | Model                                              |
| ---------------- | ---------------------------------------------------|
| CPU              | AMD Ryzen 7 5700G                                  |
| MotherBoard      | MSI B450-A PRO MAX                                 |
| OS Disk          | Samsung 870 Evo SSD 1TB 2.5'' SATA III             |
| RAM              | 2x8GB DDR4 Corsair Vengeance Pro                   |
| GPU              | AMD Radeon RX6600 8GB                              |
| Cooler    	     | Arctic Freezer A35 A-RGB          		              |

## Working

* iCloud
* Bluetooth
* Ethernet
* iServices & drm

## Not Working ( only ones I have tried, there may be more )

* Sleep ( on Monterey )

## Patches, Drivers & Kexts

* [AppleALC](https://github.com/acidanthera/AppleALC)
* [AppleMCEReporterDisabler](https://github.com/acidanthera/bugtracker/files/3703498/AppleMCEReporterDisabler.kext.zip)
* [BrcmPatchRAM](https://github.com/trulyspinach/SMCAMDProcessor)
* [Kernel Patches](https://github.com/AMD-OSX/AMD_Vanilla) For more information on this subject, click [here](https://github.com/AMD-OSX/AMD_Vanilla#read-me-first).
* [Lilu](https://github.com/acidanthera/Lilu)
* [NVMeFix](https://github.com/acidanthera/NVMeFix)
* [RadeonSensor](https://github.com/aluveitie/RadeonSensor)
* [OpenCore](https://github.com/acidanthera/OpenCorePkg)
* [RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X)
* [VirtualSMC](https://github.com/acidanthera/VirtualSMC)
* [USBToolBox](https://github.com/USBToolBox/kext)
* [WhateverGreen](https://github.com/acidanthera/WhateverGreen)

## Bootloader

I use OpenCore to multiboot Windows(10) and MacOS(Monterey)

## Credits and links

* [OpenCore install guide](https://dortania.github.io/OpenCore-Install-Guide)
* [Hackintool](https://www.hackintosh-forum.de/forum/thread/38316-hackintool-ehemals-intel-fb-patcher)
* [OpenCore-Legacy-Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher)
* [OpenCore-Legacy-Patcher guide](https://dortania.github.io/OpenCore-Legacy-Patcher)
* [sileshn's Ryzentosh](https://github.com/sileshn/Ryzentosh/)
