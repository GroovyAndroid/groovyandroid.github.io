---
layout: default
---

# Installation

* * *

> This tutorial is based on the official ASUS unlock tool that only works under stock Android L. Migrations from stock M are know to have issues with both sim cards not being detected. If you are running Android M you can downgrade (links below provided).

* * *

### 	Check your model
[Follow these steps](https://www.asus.com/support/FAQ/1014441) to check if your device is **Z00A (ZE551ML)** or **Z008 (ZE550ML).**

* * *

### Unlock the bootloader
Only needed if coming from stock firmware. If you are running any custom ROM, jump to the next step.

#### Z00A (ZE551ML)
1.  Make sure you are running stock Android L V2.20.40.139 or later. If you are running a previous version or Android M [click here to download a compatible one.](https://www.asus.com/Phone/ZenFone_2_ZE551ML/HelpDesk_Download/)
1.  Download the bootloader unlock app for your [Z00A/ZE551ML.](https://sourceforge.net/projects/zenfone-2-tools/files/UnlockApp_ze551ml_20150723.apk/download)
1.  Install the APK, open it and follow the steps required to unlock (the app is pretty self explanatory).
1. Next time you reboot, you  will see a white Asus splash screen. That means that the bootloader has been successfully unlocked.

#### Z008 (ZE550ML)
1.  Make sure you are running stock Android L firmware V2.20.40.59 or later. If you are running a previous version or Android M [click here to download a compatible one.](https://www.asus.com/Phone/ZenFone_2_ZE550ML/HelpDesk_Download/)
1.  Download the bootloader unlock app for your [Z008/ZE550ML.](https://sourceforge.net/projects/zenfone-2-tools/files/UnlockApp_ze550ml_20150723.apk/download)
1.  Install the APK, open it and follow the steps required to unlock (the app is pretty self explanatory).
1. Next time you reboot, you  will see a white Asus splash screen. That means that the bootloader has been successfully unlocked.

* * *

### Upgrade bootloader and install recovery
This package will install MM bootloader and TWRP 3.2.1.0

#### Z00A (ZE551ML)
1.  Connect the device to your PC and [enable USB debugging.](https://www.asus.com/zentalk/thread-5590-1-1.html) After enabling USB debugging, Android will ask you to confirm the first time you are accessing from your PC. Pay atention to the phone screen, too.
1.  Download the upgrade package for your [Z00A/ZE551ML.](https://sourceforge.net/projects/zenfone-2-tools/files/M_BL_upgrade_for_zf2_551ml_6.0.zip/download)
1.  Unzip the package.
1.  Open a terminal window and navigate to the folder where you unzipped the bootloader upgrader.
1.  **From the command line** run the upgrade script relative to your OS with administrator privileges: upgrade.bat for Windows, upgrade_linux.sh for Linux, upgrade_mac.sh for Mac.
1.  The phone must enter fastboot mode and after that the process continues until TWRP is flashed. It takes a while, so be patient (if for some reason the script says that it was unable to install the recovery, [it has to be flashed manually via fastboot.](https://wiki.lineageos.org/devices/Z00A/install#installing-a-custom-recovery-using-fastboot-1) In this case both tools, [ADB and fastboot](http://groovyandroid.ga/adb-and-fastboot-installation) are needed).
1.  Once upgraded, before booting up your device will say __"Your device has failed verification and may not work properly.”__ Don't worry, it's just a warning and cannot be removed.

#### Z008 (ZE550ML)
1.  Connect the device to your PC and [enable USB debugging.](https://www.asus.com/zentalk/thread-5590-1-1.html) After enabling USB debugging, Android will ask you to confirm the first time you are accessing from your PC. Pay atention to the phone screen, too.
1.  Download the upgrade package for your [Z008/ZE550ML.](https://sourceforge.net/projects/zenfone-2-tools/files/M_BL_upgrade_for_zf2_550ml_6.0.zip/download)
1.  Unzip the package.
1.  Open a terminal window and navigate to the folder where you unzipped the bootloader upgrader.
1.  **From the command line** run the upgrade script relative to your OS with administrator privileges: upgrade.bat for Windows, upgrade_linux.sh for Linux, upgrade_mac.sh for Mac.
1.  The phone must enter fastboot mode and after that the process continues until TWRP is flashed. It takes a while, so be patient (if for some reason the script says that it was unable to install the recovery, [it has to be flashed manually via fastboot.](https://wiki.lineageos.org/devices/Z00A/install#installing-a-custom-recovery-using-fastboot-1) In this case both tools, [ADB and fastboot](http://groovyandroid.ga/adb-and-fastboot-installation) are needed).
1.  Once upgraded, before booting up your device will say __"Your device has failed verification and may not work properly.”__ Don't worry, it's just a warning and cannot be removed.

* * *

### Install the ROM
1.  Download the [latest build](http://groovyandroid.ga/downloads), Open GApps [x86, 7.1, pico or nano](http://opengapps.org/) and copy both ZIP packages to the device.
1.  With the device powered off, hold **Volume Up + Power**. Once the device is on, release the **Power** button and keep holding the **Volume Up**. On the next screen (fastboot mode) use **Volume Down** to scroll to “RECOVERY” and then press **Power** to select.
1.  Once in TWRP, select **Wipe** and then **Advanced Wipe.** Select Cache, System, Data and Dalvik partitions to be wiped and then Swipe to Wipe.
1.  Go back to return to main menu, then select **Install.**
1.  Navigate to the folder where you saved the ROM package, and select it.
1.  Follow the on-screen prompts to install the package.
1.  Install GApps (pico or nano) using the same method.
1.  Once installation has finished, return to the main menu, select **Reboot,** and then **System.** First boot may take a while, so be patient.

* * *

[> Back to homepage](./)
