# X104F1 Unofficial 6.6 Backport (PLEASE READ THE DESCRIPTION)

This project is a kernel 6.6 backport for Lenovo Tab E10 (TB-X104F1) that aims to make this tablet compatible with Android versions newer than Android 10.

**WARNING:** Before flashing this kernel, please get a proper backup of your boot image. This kernel is WIP and untested, so I'm NOT responsible for any damage on your tablet. Use it only if you know what you're doing.

* I'm not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed (like it did for me...).
* YOU are choosing to make these modifications, and if you point the finger at me for messing up your device, I will laugh at you.
* Your warranty will be void if you tamper with any part of your device / software.

**WARNING 2:** This kernel is **EXPLICITLY** for TB-X104F1 variant of Lenovo Tab E10. It may not work properly on other variants (TB-X104F, TB-X104X, etc.).

**WARNING 3:** This kernel is being tested in a build of AndyYan's LineageOS 17.1 GSI. Other GSIs might have extra problems. I'd recommend sticking with a device specific custom ROM or the stock ROM.

## Instructions for Installing This Kernel:
 - Download the latest flashable zip from the Releases page and transfer the zip to the tablet (to an SD card or directly to the internal storage if you've disabled encryption).
 - Boot to TWRP (you can download an unofficial TWRP port [here](https://xdaforums.com/t/recovery-unofficial-x104-f-f1-l-x-twrp-for-lenovo-tab-e10.4534221/), and pls note that I'm not affiliated with them).
 - (Optional but extremely recommended) Go to **Backup**, select only **Boot** and backup.
 - Go to **Install Zip**, locate to the downloaded flashable zip and flash.
 - Clear cache partition and Dalvik/ART cache.
 - Reboot and try if it boots at all. (If it doesn't, you can always revert by restoring that boot image backup, if you don't have a boot image backup, you can't do jackshit, your tablet is soft-bricked.)

