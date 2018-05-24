---
layout: default
---

# Changelog

* * *
### Build 20180524
* * *

#### project system/core/
*  Adaway hosts 20180524

#### project vendor/cm/
*  Magisk to v16.4 and MagiskManager to 5.7.0

* * *
### Build 20180521
* * *

#### project android/
*  Fork android_packages_services_Telephony

#### project build/
*  Bump security patch level to 2018-05-05

#### project frameworks/av/
*  Handle bad bitrate index in mp3dec.
*  better mpeg2 TS elementary stream Access Unit parsing

#### project frameworks/base/
*  Add NETWORK_STACK permission
*  Copy PermissionChecker from support lib and use in RcognitionService
*  Fixed Security Vulnerability of DcParamObject
*  Add permission check to setAllowOnlyVpnForUids
*  Verify last array's length in readFromParcel
*  Update internal ViewPager's SavedState to match Support Library version

#### project packages/services/Telephony/
*  Enhanced permission checks for TelephonyManager#endCall() API.

#### project system/core/
*  String16: remove integer overflows

#### project external/libmpeg2/
*  Adding Internal Input Buffer

#### project bionic/
*  zoneinfo: update timezone data to tzdata2018e

#### project external/icu/
*  icu: update timezone data to tzdata2018e
*  icu: update ICU timzeone data to Android trunk
*  icu: update timezone code for ICU to support tzdata >= 2017c

* * *
### Build 20180508
* * *

#### project packages/apps/FlipFlap/
*  FlipFlap: Improve dotcase app notifications support
*  FlipFlap: Ignore low-priority notifications

#### project external/chromium-webview/
*  Update webviews to Chromium 66.0.3359.139

* * *
### Build 20180413
* * *

#### project android/
*  manifest: Track specific revision of svox to fix security vulnerability

#### project build/
*  Bump security patch level to 2018-04-05

#### project frameworks/av/
*  Refactor MediaPlayerBase's notify
*  Prevent MediaPlayerService::Client's use-after-free
*  Check NAL size before looking inside
*  M3UParser: detect variant streams without EXT-X-STREAM-INF

#### project frameworks/base/
*  Adjust URI host parsing to stop on \ character.
*  Check for null-terminator in ResStringPool::string8At
*  [RTT] ParcelableRttResults parcel code fix
*  Fix VerifyCredentialResponse parcelling code

* * *
### Build 20180411
* * *

#### project system/security/
*  key_store:Using euid instead of uid when upgrade wifi blobs
*  keystore: add upgradeKeyBlob call into keystore exportKey
*  Fix issue: upgradeKeyBlob call always return PERMISSION_DENIED

* * *
### Build 20180405
* * *

#### project project vendor/cm/
*  Update Lawnchair to v1.1.0.1872, Magisk to v16.3 and MagiskManager to 5.6.4

* * *
### Build 20180328
* * *

#### project device/asus/mofd-common/
*  [MEDIA] Improve AAC Quality
*  [GPS] Update URLs & Configuration
*  [GPS] Use 2Day LTO
*  [RIL] Signal Processing Hax v4

#### project vendor/cm/
*  Update Lawnchair and Lawnfeed to v1.1.0.1868

* * *
### Build 20180319
* * *

#### project system/core/
*  Adaway hosts 20180319

#### project vendor/cm/
*  Update to Magisk v16.2 and MagiskManager v5.6.3

* * *
### Build 20180315
* * *

#### project build/
*  Bump security patch level to 2018-03-05

#### project frameworks/av/
*  AACExtractor: check bounds during seek

* * *
### Build 20180314
* * *

#### project device/asus/mofd-common/
*  [RMD] All The Juice
*  [RMD] Asymmetric Minimum Frequencies
*  [RMD] Add Cache Trim Parameters

#### project frameworks/base/
*  [AMS] Kill Empty Activities Earlier

#### project vendor/cm/
*  Update MagiskManager to v5.6.2

* * *
### Build 20180309
* * *

#### project vendor/cm/
*  Restore previous Lawnchair build

* * *
### Build 20180308
* * *

#### project kernel/asus/moorefield/
*  [RMD] Do Not Edit Existing Files
*  lib/string: use glibc version
*  lib/memcopy: use glibc version
*  [RMD] Limit Background Apps
*  Integrate Wireguard 0.0.20180304
*  [RMD] Kill Lags
*  [DEFCONFIG] madvise Transparent Hugepages
*  [MM] Compact Every 45 Mins
*  mm: compaction: compact all zones when turning off screen
*  mm: vmscan: support complete shrinker reclaim
*  ion: adjust system heap pool orders
*  mm: vmpressure: dynamic window sizing.
*  mm: improve migration heuristic
*  mm: adjust page migration heuristic
*  UPSTREAM: mm: more aggressive page stealing for UNMOVABLE allocations
*  UPSTREAM: mm: always steal split buddies in fallback allocations
*  UPSTREAM: mm: page_alloc: use unsigned int for order in more places
*  UPSTREAM: mm: when stealing freepages, also take pages created by splitting buddy page
*  UPSTREAM: mm/page_alloc: prevent MIGRATE_RESERVE pages from being misplaced
*  UPSTREAM: mm: __rmqueue_fallback() should respect pageblock type
*  UPSTREAM: mm: get rid of unnecessary overhead of trace_mm_page_alloc_extfrag()
*  UPSTREAM: mm/page_alloc.c: fix the value of fallback_migratetype in alloc_extfrag tracepoint()
*  UPSTREAM: mm/page_allo.c: restructure free-page stealing code and fix a bug
*  [CPUFREQ] Prevent Wakeup Delay with Advanced Interactive
*  [CFQ] Tune Throughput & Latencies
*  [RMD] Fix Writeback Derp
*  Integrate Wireguard 0.0.20180218
*  [RMD] Dirty VM Parameters
*  Integrate Wireguard 0.0.20180202
*  [RMD] Update TCP Values
*  Integrate Wireguard 0.0.20180118

#### project device/asus/mofd-common/
*  [RMD] Decrease Powersave Bias
*  [RMD] Asymmetric Minimum Frequencies
*  [RMD] Limit Background Apps
*  [HW] Increment VSYNC Phase Offsets
*  [RMD] Fix Writeback Derp
*  Let There Be Nuts [1/2]
*  [CMD] Enable Basic Logging
*  [RMD] Dirty VM Parameters
*  [ART] Enable DexPreOpt
*  [OVERLAY] Rework Auto Brightness Arrays
*  [OVERLAY] Faster Screen Wakeup
*  [DOZE] Dynamic Pulse Intervals
*  [GPS] Use 2Day LTO
*  Pass Flags to CLANG Too
*  [RIL] Better Manage Wakelocks
*  Add Silvermont Specific TC Flags
*  [AUDIO] Make Sampling Rate Dynamic
*  Remove Inbuilt SU
*  [INIT] SayeedOS : Use SECCOMP Prioritization
*  [RIL] Signal Processing Hax v4
*  [DOZE] Reconfigure Timers
*  [MEDIA] Improve AAC Quality
*  [GPS] Update URLs & Configuration
*  [INIT] Go Easy On The Juice
*  Create "theme extras" directory This creates /data/system/theme in init.rc. Historically, this was done in ThemeService in CMTE. However, in a OMS/Subs environment, OverlayManagerService is strictly dedicated to handling overlays and nothing more. From http://gerrit.aicp-rom.com/#/c/33999/
*  Switch to ThemeInterfacer
*  [GPU] Drop APM Latency to 5ms
*  [RMD] Mimic Stock Behaviour

#### frameworks/base/
*  Tune up long press stuff
*  [CORE] Disable Warnings for Text Relocations
*  [AMS] Tighter Process Control
*  [VIEW] Compensate for Slow Touch
*  Disable More Debugging
*  Speed things up!!
*  Allow faster app switching
*  SwipeHelper: Let's cut Max Excape Animation in Half too
*  Increase Touch Sensitivity
*  Turn off some debugs
*  Speed up Orientation Listener
*  DO NOT MERGE Backporting potential usb tapjacking precaution.
*  mtp: fix double free of thumbnail data
*  Throw OOME if Bitmap.nativeCreate fails
*  Adjust Uri host parsing to use last instead of first @.

#### project vendor/cm/
*  Include latest Lawnchair v1 compiled from source

* * *
### Build 20180303
* * *

#### project vendor/cm/
*  Update Lawnchair to v1.1.0.1742

* * *
### Build 20180302
* * *

#### project packages/apps/ResurrectionOTA/
*  Update OTA updater app icons

* * *
### Build 20180301
* * *

#### project vendor/cm/
*  Restore OmniStyle, OmniSwitch, OmniJaws apps
*  Include Lawnchair and Lawnfeed in the next build
*  Use default AOSP bootanimation

* * *
### Build 20180228
* * *

*  Merge february security patch
*  Merge january security patch
*  Include Atom7 v1.5 as the default kernel
*  Update webviews to Chromium 64.0.3282.137
*  Update Magisk to v16.0
*  Update MagiskManager to v5.6.1
*  Update /etc/hosts to avoid ads system wide
*  Use the default AOSP bootanimation
*  Include Lawnchair and Lawnfeed
*  General rebranding
*  Resurrection Remix stats app has been removed
*  CM file manager has been removed

[> Back to homepage](./)
