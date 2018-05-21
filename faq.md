---
layout: default
---

# Frequently asked questions

1. **How can I install the ROM?**
Follow the steps in the [installation area](http://groovyandroid.ga/installation). If you get stuck, search in the forum, google your issue or ask a friend from a friend. Don't post right away.

2. **How can I remove the red/yellow message I get before boot?**
It's just a warning that says that your bootloader has been unlocked. There's no way to remove it.

3. **Can you add _whatever-you-can-think_ app or functionality to the ROM?**
No, we are just "builders". This means that we download the sorce code from RR official repository, compile it and share the resulting builds. At this moment we have no developers around for our device so this is not possible.

4. **I found a bug, I'll post about it in the forum right away.**
Don't. Before assuming that it's a general bug, try to check if it's something related to your setup. Use the forum's search tool. And in case you don't find anything, make a nandroid backup, wipe system, data, dalvik and cache. Clean install the latest build and pico or nano GApps. No other third party app, no custom kernel, no Xposed, etc. And test, test, test. If your problem persists, post it in the forum. Still, we have no developers for our device so...

5. **It's been a while since the latest release, when will there be a new one?**
Sometimes there are no changes in the code repository, sometimes we don't have time, sometimes we try to have a life away from the keyboard. New builds will come when they come.

6. **This ROM is awesome, but now that the new Android version is out I'll ask when will it be available for our device.**
Asking for ETAs is really annoying. Please, avoid such kind of questions.

7. **What are the changes included in _whatever_ build?**
RR Team does not provide a detailed changelog. Additionally, we share some repositories with LineageOS. This makes changelogs difficult to follow up. If possible, changes will be published in this site. They can also be accessible throught the OTA menu. But it is possible that some build could come out without a changelog. If that happens, you can visit [Groovy Android Git](https://github.com/GroovyAndroid) and check the latest commits for yourself.

8. **Google Playstore says my favourite app is not compatible with my device anymore.**
Some apps (banking, money transfer, Netflix, etc) require that devices can pass SafetyNet check. Otherwise, they will not even be shown by Google Playstore. Magisk helps you to achieve that, unless you use modules or Xposed. So, if you want to pass SafetyNet, remove all modules and Xposed.

9. **Before booting up my phone says _"Your device has failed verification and may not work properly"_**.
It’s just a warning that appears after upgrading the bootloader. It cannot be removed.

10. **Does this ROM support OTA updates?**
The system will show you a notification whenever there's a new build available. But after that, the new package must be flashed manually (dirty flashing).

11. **My device is soft bricked, I'm in shock.**
If your phone shows a black screen and is only vibrating or you can't use fastboot, you are unable to start or install firmware, etc. Don't panic. [Visit this thread and follow the instructions carefully.](https://forum.xda-developers.com/zenfone2/help/thead-bricked-phone-updating-to-mm-tips-t3452785)

12. **I'm having issues with some third party app, what should I do?**
The easiest way to know if it's a general bug or if it's something related to your own setup is to make a nandroid backup, wipe everything (system, data, dalvik and cache) and clean install the latest build with pico GApps. No custom kernel, no Xposed, etc. Then install the app with issues and see what happens.

[> Back to homepage](./)
