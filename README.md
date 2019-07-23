# Gigabyte-z390-aorus-pro-wifi-hackintosh

## Guides used

Morgonout - Building a Hackintosh

https://www.youtube.com/watch?v=fA9AotXqkqA

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/fA9AotXqkqA/0.jpg)](http://www.youtube.com/watch?v=fA9AotXqkqA)

OSX Version: Mojave 10.14.5
Clover Version: 2.5 r5027 https://github.com/Dids/clover-builder/releases/tag/v2.5k_r5027


## Hardware
+ Motherboard: Gigabyte Z390 Auros Pro Wifi
+ CPU: Intel I5 9600k
+ GPU: MSI Vega 56 Air Boost 8GB HBM2
+ Ram: G.Skill 32 GB DDR4-3200 CL16 G.Skill RipJaws V Noir 4*8 sticks
+ Boot Drive: Corsair MP510 480 GB NVMe PCIe Gen3 x 4 M.2 Solid State Drive
+ PSU: Corsair TX850M  Semi-Modular 80 PLUS Gold
+ CPU cooler: Cooler Master Hyper 212X
+ Case: NZXT H500

## Bios Settings

1. Bios updated to version F10 - see source files or http://download.gigabyte.eu/FileList/BIOS/mb_bios_z390-aorus-pro_f10.zip
2. Load optimise defaults
3. MIT > Advanced Memory Settings > XMP > Profile 1
4. Bios > Fastboot > Disabled 
5. Bios > Windows 8/10
6. Bios > CSM Support > Enabled (Morgonaout says this can be problematic for some)
7. Peripherals > Initial Display Output > PCIe 1 Slot 
8. Peripherals > Trusted computing > Security Device Support > Disabled
9. Peripherals > USB > Enable All * PERHAPS NOT EHCI Hand-off *
10. Peripherals > SATA > Sata mode selection > AHCI
11. Chipset > VT-d > Disabled
12. Chipset > Internal Graphics > Enabled



##Preparing USB installer
1. Download Mojave from Apple App store
2. Insert USB drive (Min 8gb / Max 32gb) Open Disk Utility > View > Show all Devices
3. Select USB Drive and erase and call it INSTALLER  
4. Choose Mac Os Journaled & GUID partion
5. Close Disk utility
6. Open Terminal and paste
```
sudo /Applications/Install\ macOS\ Mojave.app/Contents/Resources/createinstallmedia --volume /Volumes/INSTALLER
```
7. Enter your password / confirm erasing of disk and then wait around half an hour.








## Working
+ All memory showing and working at speed XMP enabled

## Not Working

## TODO

GPU no fans . 
Ethernet
• Sound 

• HDMI Port on AMD RX580 / 590 ( Ensure you disable BIOS CSM if using HDMI on RX580 / RX590 )

• HDMI Port on Aorus Z390 Motherboard ( Ensure you have correct BIOS settings as per this guide for Intel only)

• Ethernet Port

• WiFi

• SSD Trim

• USB 3.0 & 2.0 

• AirDrop

• iCloud

• Hardware Acceleration

• iMessages

• Facetime

• Handoff

• Continuity


