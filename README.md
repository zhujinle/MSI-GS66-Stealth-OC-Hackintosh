# MSI-GS66-Stealth-OC-Hackintosh

| Specifications | Details |
|:-: |:-: |
| Processor | i7-10875H Hexa Core  |
| RAM | 16GB DDR4 |
| SSD | 2xNVMe |
| Graphics Card | Intel UHD Graphics |
| eGPU | Nvidia GeForce RTX 2060  (disabled with -wegnoegpu) |
| Monitor | 15.6" Full HD 240Hz |
| Sound Card |  |
| Network Card | Killer 1650i (Intel AX201NGW) |

# Current Functionality

| Function | Performance |
|:-: |:-: |
| USB Patching | Excellent |
| Sleep* | Not tested 有人能告诉我这个怎么弄吗 |
| Disable dGPU | Excellent |
| Enable iGPU | Excellent |
| Audio | Excellent |
| WiFi** | Very Good but some bugs with AirportItlwm.kext|
| Ethernet | Excellent|
| Bluetooth | Good |
| Thunderbolt | Not Tested |
| CPU Optimisation | Excellent |
| Battery | Not Tested |
| Brightness & Sound Keys | Excellent |
| General stability | Excellent |

#
#### To enter the Advanced BIOS
While in the BIOS, press F2, Left ALT, Right SHIFT, Right CTRL
Now you can verify that DVMT Pre-Allocated is set to 64MB and DVMT Total Gfx Mem is set to Max
Also, and most important, set CFG Lock to Disabled, to enable native PM (also you would probably get a KP without it, if using current version of the EFI)

#### IMPORTANT

Please generate a new SMBIOS (MacBookPro16,1 or MacBookPro16,4) as I deleted my serials. 
Use https://github.com/corpnewt/GenSMBIOS
