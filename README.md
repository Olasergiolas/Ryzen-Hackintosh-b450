# Ryzen-Hackintosh-b450

These are my OC files to boot the latest Big Sur release using a Ryzen 5 3600 with a supported AMD GPU. Everything seems to be working fine except iServices. In order to make those work refer to the link below. [IOUSBHIDDriverDescriptorOverride.kext](https://github.com/thefloweringash/iousbhiddriver-descriptor-override) is needed in order to get working some TKL keyboards that do not work with mac os out of the box.

Complete build:</br>
Ryzen 5 3600</br>
MSI B450 A-PRO MAX (Realtek 8111H)</br>
SAPPHIRE R9 380</br>
Samsung 970 Evo SSD</br>

## Important note
New AMD kernel patches require you to add your CPU's CoreCount before you can boot your system. Currently, these patches are configured to work with a 6 core CPU (ryzen 5 3600) but if you own a CPU with a different CoreCount you should check [this](https://github.com/AMD-OSX/AMD_Vanilla#read-me-first) before trying to boot with my OC folder.


This was achieved thanks to the people at https://dortania.github.io/OpenCore-Desktop-Guide/
