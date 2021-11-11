# Alienware-Aurora-R11-Hackintosh
 Full working OpenCore version for 10th Gen Intel and macOS (Z370 and Z470)
 
My Hardware: Alienware Aurora R11
 - 10th Gen Intel Core i9 10900KF (10-Core, 20MB Cache, 3.7GHz to 5.3GHz) 
 - 32GB Dual Channel HyperX FURY DDR4 XMP 3200MHz 
 - AMD RX 5700 XT (ECS) 
 - 1TB Samsung 970 EVO Plus NVMe M.2 SSD 
 - Qualcomm QCA9377 (DW1810) WiFi+Bluetooth
 - Lunar Light chassis with High- Performance CPU Liquid Cooling and 1000W Power Supply
 
This is a collection of files that worked for my setup. The credit for these files go to the resource owners used over the time it took to compile something that worked. 
The config.plist was updated using ProperTree and following the Coffee Lake Documentation provided by Dortania (Thanks a ton!)

Mostly this area is for me so that I have documentation and access. your performance and setup may not work
 
Some issues:
  - Killer Wi-Fi AX1650 - did not work (Changed to Fenvi FV-T919 then to DW1830)
  - Hynix 1Tb NVMe SSD did not work (Changed to 970 Evo Plus)
  - Bluetooth not working properly (Not much time spent in troubleshooting)
  
BIOS Settings: (These are my current settings, yours may be different)
 - Reset to Optimized Defaults
 - Advanced -> PCIe Resizable Base Address Register - Disabled
 - Advanced -> Power Options -> Deep Sleep Control - Disabled
 - Advanced -> Power Options -> USB PowerShare (S4/S5) - Disabled
 - Advanced -> Performance Options -> Overclocking Feature - Enabled
 - Advanced -> Performance Options -> Core Overclocking Level - OC LV 2
 - Advanced -> Performance Options -> XMP Memory - XMP1
 - Security -> Absolute - Disabled
 - Security -> Firmware TPM - Disabled
 - Security -> Windows SMM Security Mitigations Table (WSMT) - Disabled
 - Security -> Secure Boot -> Secure Boot - Disabled
 - Save and Reset (F10 + Enter)
 - Reset NVRAM on first boot (Use Opencore Menu Option)
 
Resources:
 - https://dortania.github.io/OpenCore-Install-Guide/
 - https://github.com/jianghaizhi/DELL-Alienware-Aurora-R7-macOS
