# MSI-GS66-Stealth-OC-Hackintosh
# MSI GS66 Stealth 10SFS-480IT Hackintosh

| Specifications | Details |
|:-: |:-: |
| Processor | i7-10875H Hexa Core  |
| RAM | 16GB DDR4 |
| SSD | 2xNVMe |
| Graphics Card | Intel UHD Graphics |
| eGPU | Nvidia GeForce RTX 2060  (disabled with -wegnoegpu) |
| Monitor | 15.6" Full HD 300Hz |
| Sound Card |  |
| Network Card | Killer 1650i (Intel AX201NGW) |


#### To enter the Advanced BIOS
While in the BIOS, press F2, Left ALT, Right SHIFT, Right CTRL
Now you can verify that DVMT Pre-Allocated is set to 64MB and DVMT Total Gfx Mem is set to Max
Also, and most important, set CFG Lock to Disabled, to enable native PM (also you would probably get a KP without it, if using current version of the EFI)

#### IMPORTANT

Please generate a new SMBIOS (MacBookPro16,1 or MacBookPro16,4) as I deleted my serials. 
Use https://github.com/corpnewt/GenSMBIOS
