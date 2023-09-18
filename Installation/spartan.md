 <img src="https://raw.githubusercontent.com/DroidX-UI-Devices/Official_Devices/13/banners/install.png" />


# Flasing steps :-

## From Stock Rom

-Go to bootloader

-flash twrp

-boot to twrp

-flash rom zip {either copy or sideload}

-format

-reboot system

## From Custom Rom

-Flash rom zip via recovery / sideload the rom zip

-Gapps Not Needed since already included in build

-Format Data

-reboot system

# Note:

- If flashing fails -- wipe Dalvik , metadata and data in advanced wipe then proceed with previous steps
- You can use Ofox, Twrp , Pbrp recovery
- If you can't copy files to recovery use the following command-
        adb push filename.zip /sdcard/.
- If you want to change kernel , backup default boot.img in backup section and then proceed.
