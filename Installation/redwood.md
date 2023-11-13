<img src="https://raw.githubusercontent.com/DroidX-UI-Devices/Official_Devices/13/banners/install.png" />

CLEAN FLASH :-

1.) Download The Boot , Dtbo  And Vendor_boot Images  

2.) Connect To Pc

3.) Reboot To Fastboot  (  Press  Both Power_button_key + Vol_down_key)

4.) fastboot flash boot boot.img

5.) fastboot flash vendor_boot  vendor_boot.img

6.) fastboot flash dtbo dtbo.img 

7.) fastboot reboot recovery

8.)Select Wipe Data/factory Reset & Confirm

9.) Select 'apply Update' From Adb

10.) adb sideload  Rom_Name.zip

11.) Select Wipe Data/factory Reset & Confirm

12.) After Installation Complete, Reboot System.



DIRTY FLASH :-

1. Reboot to recover by holding power button and volume up simultaneously

2. In the recovery menu select Apply update through ADB

3. adb sideload Rom*.zip(or drag down the rom zip to cmd)

4. After installation complete, Reboot system.
