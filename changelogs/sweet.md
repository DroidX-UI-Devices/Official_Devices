==================
Device Changelogs
==================


==================
Date: 21-08-2023
------------------
sweet : sync with latest source release 

Date: 30-07-2023
------------------
sweet: ueventd: Remove all permissions from /sys/devices/soc0/serial_number
sweet: Kang libspl.so from LA.UM.9.1.r1-12900-SMxxx0.0
sweet: Switch to AutoSingleLayer Android 13 Setting
sweet: Disable SurfaceFlinger EGL image tracking
sweet: rootdir: Enable suspend to RAM
sweet: rootdir: Use s2idle instead of deep
sweet: Import missing audio & sensor libraries
sweet: sepolicy: Allow recovery to access /sys/fs/pstore/*
sweet: overlay: adjust rounded corner radius top and bottom padding
sweet: sepolicy: allow system app access zram0
sweet: Move power-mode.cpp to configs/power
Revert "sweet: overlay: SystemUI: increase front camera ring size"
sweet: rootdir: Remove vbmeta_system from fstab
sweet: Update hotword blobs from V14.0.2.0.TKFMIXM
sweet: sepolicy: Allow SF to read firmware
sweet: Remove non-existent modules
sweet: Disable backpressure prop
sweet: Switch BtAudio to HIDL
sweet: Disable zram writeback
sweet: props: Kang sf props from pixel(raven)
sweet: configs: audio: Fix "Earpiece" audio output
sweet: overlay: Increase start and end padding of status bar
sweet: Update GPS blobs from hanoip S2RIS32.32-20-7-7
sweet: configs: update GPS configs from hanoip S2RIS32.32-20-7-7
Revert "sweet: overlay-voltage: Reduce no. of max visible notification icons"
sweet: overlay: Fix padding
sweet : Nuke VoltageOS configs
sweet: Change DROIDX_BUILDTYPE to DROIDX_BUILD_TYPE
sweet: Checkout audio configs from MIUI 13
sweet: gps: Update to LA.UM.9.1.r1-12900-SMxxx0.0
sweet: Reduce the list of pinned acdb files
sweet: Override doze mode support
sweet: sepolicy: Label Spi IR node
sweet: overlay: Limit screen recorder to 90fps
sweet: overlay: SystemUI: increase front camera ring size
sweet: sepolicy: Label wakeup node
sweet: overlay: Disable battery light settings
sweet: Update blobs from sweet V14.0.3.0.TKFEUXM
sweet: Drop Lineage livedisplay
sweet: Convert xiaomi_framework_compatibility_matrix.xml into device_framework_matrix.xml
sweet: overlay: Update vibration patterns
sweet: Update Audio HIDL to 7.1
sweet: Drop support for F2FS compressions and garbage collector
sweet: Build missing bluetooth libs
sweet: Remove hotword permission and whitelist xml files
sweet: overlay-voltage: Reduce no. of max visible notification icons
sweet: Disable continuous transaction tracing on all build types
Revert "sm6150-common: Enable backpressure propagation in SF"
sweet: Move BT profiles props to vendor
sweet: Clean up sepolicy
sweet : sepolicy: Label certain Xiaomi specific property labels
sweet : sepolicy: Allow rild to read default_prop
sweet: sepolicy: fix wifi denial
sweet: sepolicy: add ro.hardware.chipname prop
sweet: vintf: Declare hals
sweet: Remove duplicate mixer paths
sweet: overlay: Adjust status bar paddings
sweet: Don't latch unsignal buffers
sweet: Disable Skia tracing by default
sweet: Remove max ZRAM compression streams setting
sweet: sepolicy: Remove no longer existing properties
sweet: Fix IMS symlink as per dynamic partitions
Revert "sm6150-common: Force restorecon for /mnt/vendor/persist"
sweet: Set no_sehash_xattr on /mnt/vendor/persist
sweet: Add hotword enrollment blobs from vayu
sweet: Add missing DRM dependencies
sweet : Enable Camera Vendor Tags for Xiaomi devices

Notes -
No Lecia Cam in this build, will be added in next one.
Dolby Atmos added
Vantom Kernel by default
Use BitGapps Core for the vanilla build
Use the latest Orangefox recovery
latest fw recommended for your region

==================
Date: 27-05-2023
------------------
- sweet : overlay: Increase status bar top padding
- sweet: Build missing omx libs
- sweet: Add newly added blobs to public.libraries.txt
- sweet: Add some missing blobs
- sweet: Remove discard command tuning
- sweet: overlay: Disable NearbyMessagingService
- sweet: overlay: Disable DiscoveryService
- sweet: Set correct manufacturer
- sweet: overlay: Disable subtle tick vibration when revealing shelf
- sweet: Update Adreno to LA.UM.9.14.r1-21000-LAHAINA.QSSI13.0
- sweet: Update DPM, IMS, and RIL system blobs
- sweet: Import missing blobs
- And many more underwood changes


note : Clean flash required
       Flash latest fw for your region.
       Leica cam added
       Vantom Kernel by default.
       
credits : @mrfox2003 for dt and vt
          Vantom for kt
          @nutelladev for help to fic Leica cam.
          @Coolaslikeice for testing
          @JYR_RC for Lecia cam.

------------------
Date: 19-04-2023
------------------
- Converted common tree into sweet tree
- Set VENDOR_SECURITY_PATCH to platform 
- Updated app/sf durations from MIUI
- Addressed some denials
- Fixed some log spams
- Added missing vintf entries
- Updated telephony package list to LA.QSSI.12.0.r1-05600qssi.0
- Removed references to a2dp module 
- Added props for smoother scrolling and better responsiveness 
- Enabled backpressure propagation in SF 
- Updated blobs from sweet V14.0.2.0.TKFEUXM
- Switched to jemalloc for libc 
- Updated CarrierConfig from LA.UM.9.1.r1-12900-SMxxx0.0
- Updated graphics (adreno), DPM, IMS, RIL blobs from LA.UM.9.1.r1-12900-SMxxx0.0
- Synced brightness overlays with miui 
- Labeled new telephony properties 
- Configure RefreshRate brightness thresholds 
- Uprev audio hal to 7.1 
- Dropped per app refresh rate profiles
- Imported power profile from MIUI V14.0.2.0.TKFEUXM
- Support F2FS compressions and garbage collector
- Updated fingerprints
- Enabled ro.hwui.render_ahead 
- Fix EGL symlink 
- Updated audio from sweet V14.0.1.0.TKFMIXM
- Added custom msm_irqbalance.conf 
- Improved pinner configuration 
- Allowed neural networks HAL to read ADSP properties
- Disabled hwcomposer's dynamic fps
- init: Add support for JAPAN region 
- Added wakelock to citsensor service group 
- Merged latest CAF tags in kernel
- Disabled some log spams in kernel
- Updated dolby config values from oneplus

Note: Clean flash required
      Flash latest fw for your region.
      No MIUI/Lecia Cam.
      Vantom Kernel by default.

