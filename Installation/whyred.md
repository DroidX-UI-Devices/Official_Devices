How to Install x aosp for Whyred with Dynamic Partition for the First Time aka from non-Dynamic partition ROM

Read carefully now :-

1) Put required files (x ROM & anand dynamic partition supported ofox) to your microsd

2) Backup any files inside internal storage

3) Reboot to recovery and Go to your microsd

4) Select ofox recovery zip file from step 1

then Swipe to Install

5) Reboot to dynamic partition recovery

6) Select rom and flash

7) Ignore any error message (because your partition didn’t yet on dynamic type)

8) After installation complete, select “Factory Reset”

9) Select “Format data/factory reset”

10) Select “Format data”

11) Go back to Main Menu

12) Select “Reboot to System”

Enjoy!



How to dirty flash build:

• Reboot into recovery

• select rom zip

• flash rom zip

• flash magisk if needed

• do wipe cache and reboot



Additional Notes:

• Don’t try to dirty flash from or to any non-dynamic x rom or official build

• If you got bootloop, try format data again from ofox Recovery

• If you have been done repartitioning process to install some rom port before, please revert back to original partition if you haven’t done it

• If want to install magisk, at least complete first setup (if you clean flash before)

• Not all kernel build is compatible for this build, just make sure if the kernel is supporting dynamic partition (ask the kernel developer)

• The step for installing kernel is same as magisk step above



How to Revert Back to Non-Dynamic Partition :-

Read carefully:-

• Put flashable normal recovery zip file (OrangeFox or PBRP, in this tutorial I’m using Shekhwat2’s OrangeFox build) into your microsd

• Backup any files inside internal storage

• Reboot to recovery

• Select “Install"

• Select the recovery file from step 1

• Wait it until rebooted to the recovery you’ve flashed

• Go to Wipe menu, select Dalvik/ART Cache, Cache, System and Vendor, and then Swipe to Wipe

• Now go to Format Data section, type yes and press enter

• Also if you want to change Data partition to F2FS, go to Menu section

• Select Manage Partition

• Select Data and press the checkmark

• Select Change FS

• Select F2FS and then Swipe to Change

• Now press Back, and make sure File system is listed as f2fs

• Go to Menu, select Reboot

• Select Recovery

• After booted to recovery again, now you are ready to flash any non-dynamic rom

Flashing steps credit @Yuu_kiho.
