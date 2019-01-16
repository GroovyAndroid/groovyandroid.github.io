---
layout: default
---


#### 01/16/2019
# [](#z00d-and-z00l-support-and-monthly-builds)Z00D and Z00L support and monthly builds

Since the last couple of months, support for Z00D and Z00L devices has been added. Though testing for those devices is out of reach, feedback from several users has been positive.

Due to lack of developement for the Nougat branch, the building cycle will be monthly. Once security patches are merged, a new release will come out.

Don't expect new features or big changes, Nougat future builds will be all about stability and security patches until the LineageOS' N end of life.

* * *

#### 01/31/2018
# [](#official-lineageos-14-1-end-of-life)Official LineageOS 14.1 end of life

As many you probably already know, [official support for LineageOS, our base ROM, has been discontinued for Z00A and Z008.](https://forum.xda-developers.com/showpost.php?p=75362052&postcount=5446)

Fortunately, our friend [nutcasev1.5](https://forum.xda-developers.com/member.php?u=7074010) will keep developing [his own ROM, NutOS.](https://forum.xda-developers.com/zenfone2/development/linos-14-1-nutos-slimified-lineage-zf2-t3654552) Basically, that will give us two important things: (high quality) unofficial slimified LineageOS builds and the chance for us to use that LineageOS base to keep Resurrection Remix alive for our devices.

Regarding to the kernel, unless moorefield gets support we will probably have to move to some fork. A proper announcement will be made if that happens.

Keep enjoying!

* * *

#### 12/26/2017
# [](#magisk-15-is-out)Magisk v15.0 is out

[Magisk v15.0 is now available](http://rrz2.ml/downloads). Remember the steps to install:
1.  Uninstall any previous version of Magisk.
1.  Install Magisk v15.0.
1.  Flash Verified Boot Sigher to avoid bootloop.

* * *

#### 12/05/2017
# [](#magisk-update-needed)Magisk update needed

Since build 20171205, those using Magisk will have to use [version 14.5](http://rrz2.ml/downloads). Otherwise, the system will not boot. This is due to the latest [changes in RR](https://github.com/ResurrectionRemix/android_vendor_resurrection/commit/bb1146a7070eab1fef05e15d2fa6ca11b553dcb5).

To update, follow these steps:

1. Uninstall Magisk
2. Flash build 20171205
3. Install Magisk 14.5
4. Install Verified Boot Signer

All the files needed are in the download area: [http://rrz2.ml/downloads.](http://rrz2.ml/downloads)

* * *

#### 11/29/2017
# [](#nougat-builds-frequency)Nougat builds frequency

[As the RR team said in late September,](https://plus.google.com/113273376518805179283/posts/XE5CN2XjYjA) developement for Nougat started to slow down. We are mostly getting updates from LineageOS repository. We're still not sure if we will get Oreo for our devices, but in the meantime we will keep releasing new builds whenever we find commits that make us think they are worth for compiling. How often? Once a week? Twice a week? Once a year? Don't EVER ask, [because it really grinds my gears.](https://www.pelletonpellet.co.uk/wp-content/uploads/2016/07/8mS65Uk.jpg)

* * *

#### 10/17/2017
# [](#wpa2-wifi-protocol-vulnerability-krack)WPA2 WiFi Protocol Vulnerability KRACK

The guys from the LineageOS team [have been working](https://twitter.com/LineageAndroid/status/920143977256382464) on the recently discovered [WPA2 WiFi Protocol Vulnerability](https://www.xda-developers.com/wpa2-wifi-protocol-vulnerability-krack/). These [changes](changelog) were included in our 20171017 build. [Updating](downloads) is highly recommended.

* * *

#### 10/11/2017
# [](#known-issues)Known issues

**Asus FM radio not included:** requires proprietary source code that Asus never released to the community (and most likely never will).

**LineageOS' limitations:** video encoder/decoder, Asus Pixelmaster Camera App, SIM 2 cannot be disabled.

* * *

#### 10/10/2017
# [](#about-this-microsite)About this microsite

The main goal of this site is to gather all the required Resurrection Remix's information related to ASUS Zenfone 2 (Z00A and Z008) devices.

XDA's thread will remain as the base of all the interaction between users, developers and compilers. However, sometimes it may become difficult to find certain information. At that point, this site will try to summarize what could be considered as more important or more repeated questions.

Enjoy!!
