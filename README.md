# Alienware-Aurora-R11-Hackintosh
 Full working OpenCore version for 10th Gen Intel and macOS
 
My Hardware: Alienware Aurora R11
 - 10th Gen Intel Core i9 10900KF (10-Core, 20MB Cache, 3.7GHz to 5.3GHz) 
 - 32GB Dual Channel HyperX FURY DDR4 XMP 3200MHz 
 - AMD RX 5700 XT (ECS) 
 - 1TB Samsung 970 EVO Plus NVMe M.2 SSD 
 - Qualcomm QCA9377 (DW1810) WiFi+Bluetooth
 
This is a collection of files that worked for me. The credit for them go to the resources used over the time it took to compile something that worked for me. 
The config.plist was updated using ProperTree and following the Coffee Lake Documentation provided by Dortania (Thanks a ton!)
 
Some issues:
  - Killer Wi-Fi AX1650 - did not work (Changed to Fenvi FV-T919 then to DW1830)
  - Hynix 1Tb NVMe SSD did not work (Changed to 970 Evo Plus)
  - Bluetooth not working properly (Not much time spent in troubleshooting)
  
BIOS Settings:
 - Reset to Default
 - Reset NVRAM on first boot (Use Opencore)
 
Resources:
 - https://dortania.github.io/OpenCore-Install-Guide/
 - https://github.com/jianghaizhi/DELL-Alienware-Aurora-R7-macOS
