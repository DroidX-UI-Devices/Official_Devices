 <img src="https://raw.githubusercontent.com/DroidX-UI-Devices/Official_Devices/13/banners/install.png" />

 **Please note that OOS13.1 EX01 firmware is included in these builds**

 First Time Install / Clean Flash from OOS/Other Custom ROM

1. Be on OOS13 and have an unlocked bootloader
2. Download dtbo, vendor_boot, boot & rom for your device from SourceForge
3. Reboot to bootloader
4. fastboot flash dtbo dtbo.img
fastboot flash vendor_boot vendor_boot.img
fastboot flash boot boot.img
fastboot reboot recovery
5. While in recovery navigate to Factory reset -> Format data/factory reset and confim to format the device.
6. When done formatting, go back to the main menu and then navigate to Apply update -> Apply from ADB
7. adb sideload rom.zip (replace "rom" with actual filename)
8 (optional). Reboot to recovery to sideload any add-ons (e.g magisk)
9. Reboot to system & Enjoy

Update
1. Reboot to recovery
2. While in recovery, navigate to Apply update -> Apply from ADB
3. adb sideload rom.zip (replace "rom" with actual filename)
4. Reboot to system & Enjoy
