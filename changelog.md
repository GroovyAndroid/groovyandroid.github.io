---
layout: default
---

# Changelog


* * *
### Build 20190923
* * *

#### project android/
*  manifest: Track our own gatekeeper

#### project build/
*  Bump Security String to 2019-09-05

#### project frameworks/base/
*  Fix Layout.primaryIsTrailingPreviousAllLineOffsets
*  HidProfile: sync isPreferred() with HidHostService
*  Clear the Parcel before writing an exception during a transaction

#### project frameworks/native/
*  Fix race between SensorManager ctor and callback
*  Free mObjects if no objects left to realloc on resize

#### project system/core/
*  Fix a memory leak in gatekeeper.

#### project external/libnfc-nci/
*  Prevent OOB read in rw_t4t.cc
*  Prevent integer overflow in NDEF_MsgValidate

#### project packages/apps/Email/
*  AOSP/Email - Create an empty Bundle if originalExtras doesn't exit. Backporting the fix to fix NullPointerException.
*  AOSP/Email - bug fix: do not allow composing message with hidden private data attachments.

#### project packages/apps/UnifiedEmail/
*  AOSP/UnifiedEmail - bug fix to composing messages.

* * *
### Build 20190814
* * *

#### project android/
*  Track our own versions of art and Telecomm

#### project art/
*  Use conservative permissions when creating files in ART

#### project build/
*  Bump Security String to 2019-08-05

#### project frameworks/av/
*  AMR WB encoder: prevent OOB write in ACELP_4t64_fx
*  httplive: detect oom if playlist is infinite
*  Fix overflow/dos in 3gg text description parsing
*  DO NOT MERGE: audiopolicy: Remove raw pointer references to AudioMix

#### project frameworks/base/
*  Protect VPN dialogs against overlay.
*  Make Lock task default behaviour consistent with Settings.

#### project frameworks/native/
*  libbinder: readCString: no ubsan sub-overflow
*  libbinder: Status: check dataPosition sets.

#### project packages/apps/Nfc/
*  Prevent OOB Read in Mfc_Transceive
*  Prevent OOB write in Mfc_Transceive
*  Prevent OOB write in phFriNfc_ExtnsTransceive

#### project packages/apps/Settings/
*  Make ScreenPinningSettings behaviour consistent with lock tasks.
*  Do not allow draw on top for App notification settings

#### project packages/services/Telecomm/
*  Add flag to default dialer change dialog

#### project hardware/qcom/audio-caf/msm8916/
*  policy_hal: Adapt to AudioMix API changes in f/av audiopolicy

#### project hardware/qcom/audio-caf/msm8952/
*  policy_hal: Adapt to AudioMix API changes in f/av audiopolicy

#### project hardware/qcom/audio-caf/msm8994/
*  policy_hal: Adapt to AudioMix API changes in f/av audiopolicy

#### project hardware/qcom/audio-caf/msm8996/
*  policy_hal: Adapt to AudioMix API changes in f/av audiopolicy

#### project hardware/qcom/audio-caf/msm8998/
*  policy_hal: Adapt to AudioMix API changes in f/av audiopolicy

#### project external/chromium-libpac/
*  Disable optimizing compiler for pac file

#### project external/libavc/
*  Decoder: Delete node from st if lt and st point to same

#### project external/libhevc/
*  Add push-pop for Neon D8-D15 registers

#### project external/libvpx/
*  Fixes a double free in ContentEncoding
*  Check there is only one settings per ContentCompression

#### project system/bt/
*  DO NOT MERGE Fix for Bluetooth connection being dropped after HCI Read Encryption Key Size
*  DO NOT MERGE Send HCI Read Encryption Key properly
*  DO NOT MERGE Drop Bluetooth connection with weak encryption key

#### project packages/inputmethods/LatinIME/
*  Add support for Georgian spell checking
*  Set proper keyboard for Georgian script
*  Add support for Bulgarian spell checking
*  Add new type for Bulgarian script
*  Add support for Portuguese spell checking
*  Add support for Hebrew spell checking
*  Add support for Croatian spell checking
*  Add support for Czech spell checking
*  Add support for Polish spell checking

#### project packages/inputmethods/LatinIME/
*  Add support for Ukrainian spell checking

#### project external/nano/
*  nano: Zero entire struct termios
*  nano: don't spam warnings as errors
*  nano: Zero entire struct sigaction struct
*  nano: fix another implicit declaration of time()
*  Adjust config.h for Nougat:
*  nano: Update config.h for 4.3
*  nano: Regenerate config.h
*  Merge tag 'v4.3' into lineage-15.1_v4.3-merge

#### project external/vim/
*  Adjust src/auto/config,h for Nougat

* * *
### Build 20190710
* * *

#### project android/
*  Track our own android_external_sfntly

#### project build/
*  Bump Security String to 2019-07-05

#### project frameworks/av/
*  Remove unused AVIExtractor source

#### project system/bt/
*  Fix potential OOB read in sdpu_get_len_from_type

#### project external/libhevc/
*  Add few more checks for invalid parameters in sps
*  Add bounds check for tile dimensions
*  Add missing return check for short_term_ref_pic_set()

#### project external/sfntly/
*  Fix uninitialized value in sfntly

#### project packages/providers/TelephonyProvider/
*  Check access to user and password fields in APN db

#### project external/chromium-webview/
*  Update Chromium Webview to 75.0.3770.101

* * *
### Build 20190618
* * *

#### project build/
*  Bump Security String to 2019-06-05

#### project frameworks/av/
*  AudioFlinger: Prevent multiple effect chains with same sessionId
*  audio: ensure effect chain with specific session id is unique
*  NuPlayerCCDecoder: fix memory OOB

#### project frameworks/base/
*  Adding SUPL NI Emergency Extension Time
*  Add cross user permission check - areNotificationsEnabledForPackage
*  Limit IsSeparateProfileChallengeAllowed to system callers
*  Permission Check For DPM.getPermittedAccessibilityServices
*  Added missing permission check to isPackageDeviceAdminOnAnyUser.

#### project system/bt/
*  DO NOT MERGE Don't persist bonds using sample LTK

#### project external/libnfc-nci/
*  Fix heap overflow in nfa_rw_store_ndef_rx_buf

#### project external/v8/
*  Fix type confusion in libpac

* * *
### Build 20190520
* * *

#### project build/
*  Bump Security String to 2019-05-05

#### project frameworks/av/
*  Reserve enough space for RTSP CSD

#### project frameworks/base/
*  DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot

#### project packages/apps/Settings/
*  Do not allow draw on top for default sms picker.

#### project external/v8/
*  Fix Integer Overflow in libpac
*  Fix type confusion in libpac
*  Fix OOB Access in libpac
*  Fix OOB read in libpac ast-numbering.cc
*  Fix type confusion in libpac

#### project external/wpa_supplicant_8/
*  [wpa_supplicant] Fix security vulnerability wpa_supplicant/wnm_sta.c:376

#### project packages/apps/SetupWizard/
*  SUW: Don't make google suw use material_light
*  SetupWizard: Update wizard script to fix flow

* * *
### Build 20190409
* * *

#### project build/
*  Bump Security String to 2019-04-05

#### project external/libnfc-nci/
*  Prevent OOB error in rw_i93_sm_update_ndef()
*  Prevent OOB error in rw_i93_sm_read_ndef()
*  Prevent OOB error in rw_i93_sm_detect_ndef()
*  Prevent OOB read in rw_i93_process_sys_info()
*  0ccd688 Prevent integer underflow in rw_t3t_act_handle_check_ndef_rsp()

#### project external/libmpeg2/
*  Add push-pop for Neon D8-D15 registers

#### project external/tremolo/
*  Add some error/overflow checks in codebook handling

#### project system/bt/
*  btm_proc_smp_cback: Don't access p_dev_rec if freed
*  process_l2cap_cmd: Fix OOB

#### project packages/apps/Jelly/
*  Jelly: Add support for multiple windows

* * *
### Build 20190311
* * *

#### project build/
*  Bump Security Patch Level to 2019-03-01

#### project frameworks/base/
*  Select only preinstaflled Spell Checker Services
*  RESTRICT AUTOMERGE Do not linkify text with RLO/LRO characters.

#### project frameworks/native/
*  Sanitize InputMessage before sending

#### project bootable/recovery/
*  DO NOT MERGE: Initialize the ZipArchive to zero before parsing

#### project external/libavc/
*  decoder: Signal IVD_RES_CHANGED error for change in crop params

#### project external/libhevc/
*  Decoder: Signal IVD_RES_CHANGED error for change in crop params

#### project external/libnfc-nci/
*  Prevent integer underflow in rw_t2t_handle_tlv_detect_rsp()
*  Prevent Out of bounds read in ce_t4t.cc
*  Prevent OOB read in rw_t3t_act_handle_ndef_detect_rsp()
*  Prevent Out of bounds write in rw_t3t_handle_get_sc_poll_rsp()
*  Fix heap overflow in NFA_SendRawFrame()
*  Prevent Integer Overflow in rw_t3t_act_handle_check_rsp()
*  Prevent OOB read in rw_t3t_update_block()
*  Prevent Out of bound error in phNxpNciHal_process_ext_rsp
*  Prevent Out of bound error in llcp_dlc_proc_rr_rnr_pdu()
*  Prevent Out of bounds read in llcp_util

#### project external/sqlite/
*  RESTRICT AUTOMERGE: Apply security patch to sqlite 3.9.

#### project system/bt/
*  DO NOT MERGE A security fix to check buffer length in l2c_lcc_proc_pdu

#### project hardware/ti/omap4/
*  libpower: update interactive governor params for performance

* * *
### Build 20190225
* * *

#### project android/
*  Drop legacy OpenCV from manifest

#### project build/
*  Bump Security Patch Level to 2019-02-05

#### project external/skia/
*  RESTRICT AUTOMERGE: Add SkAndroidFrameworkUtils::SafetyNetLog
*  RESTRICT AUTOMERGE: Fix heap buffer overflow

#### project packages/apps/Contacts/
*  Patch URI vulnerability in contact photo editing

#### project external/wpa_supplicant_8/
*  Use BoringSSL to get random bytes

#### project system/bt/
*  Fix potential usage of freed memory in btif_hl_proc_sdp_query_cfm
*  Fix buffer overflow in btif_dm_data_copy

#### project external/chromium-webview/
*  Update x86/x64 Chromium Webviews to 71.0.3578.99

#### project hardware/broadcom/libbt/
*  libbt: Align Samsung CID strings to those created by macloader

#### project packages/apps/Email/
*  AOSP/Email - Second part of the Security Vulnerability fix -   Email App: Malicious app is able to compose message with hidden   attachments and bypass attachments path checks attaching private files   from /data/data/com.android.email/*

#### project packages/apps/UnifiedEmail/
*  AOSP/Email - Fixed - Security Vulnerability - Email App: Malicious app is able to compose message with hidden attachments and bypass attachments path checks attaching private files from /data/data/com.android.email/*

#### project system/bt/
*  Fix possible OOB when AVDT data channel recive ACL data

* * *
### Build 20190123
* * *

#### project build/
*  Bump Security Patch Level to 2019-01-05

#### project external/libnfc-nci/
*  Prevent Out of bounds read in llcp_dlc
*  Prevent OOB error in nfc_ncif_proc_get_routing()
*  Prevent Out of bounds read/write in nfc_ncif_set_config_status
*  Improve AGF PDU integrity check to prevent OOB error

#### project external/wpa_supplicant_8/
*  WNM: Fix WNM-Sleep Mode Request bounds checking

#### project packages/apps/Contacts/
*  Patch URI vulnerability in contact photo editing

#### project packages/apps/ManagedProvisioning/
*  DO NOT MERGE: Don't Disable Pkg Verifier When Provisioning

#### project system/bt/
*  Fix possible OOB when AVDT data channel recive ACL data
*  MCAP: Check response length in mca_ccb_hdl_rsp
*  HH: Check parameter length in bta_hh_ctrl_dat_act
*  SDP: Check p_end in save_attr_seq and add_attr
*  HFP: Check AT command buffer boundary during parsing

#### project android/
*  Track our own Contacts app

#### project android/
*  Track own update-engine

#### project build/
*  Bump Security Patch Level to 2018-12-05

#### project frameworks/av/
*  CTS error while media dump()

#### project frameworks/base/
*  RESTRICT AUTOMERGE: Recover shady content:// paths.
*  Pass userId through to singleton ContentProviders
*  Changing SUPL_ES=1 for SUPL end point control

#### project external/v8/
*  Remove unrecognized compiler flag
*  Merge tag 'android-8.1.0_r52'

#### project external/v8/
*  Revert "Backport: Fix Object.entries/values with changing elements"

#### project system/update_engine/
*  Check metadata size in payload.

#### project external/aac/
*  Prevent out of bounds accesses in lppTransposer()

#### project external/libhevc/
*  Add limits check for the CTB position in a frame

#### project external/libnfc-nci/
*  Prevent OOB error for T2T read/writes

#### project external/libvpx/
*  libwebm: Cherrypick 5a41830 from upstream

#### project system/bt/
*  Fix possible OOB read
*  DO NOT MERGE - Check SDU lower bound before allocate p_data

#### project system/vold/
*  Fix signedness mismatch and integer underflow

#### project bootable/recovery/
*  Fix making adb use a custom prop for adb root
*  Make adb use a custom prop for adb root

#### project packages/apps/TvSettings/
*  Make adb use a custom prop for adb root

#### project external/aac/
*  Add sampling rate sanity check
*  Break audio element loop in case element_count becomes too large.

#### project external/aac/
*  Prevent bit buffer counter overflow.

* * *
### Build 20181112
* * *

#### project build/
*  Security string to 2018-11-05

#### project frameworks/av/
*  MediaExtractor: stop rendering when an error occurs

#### project frameworks/base/
*  Verify number of Map entries written to Parcel
*  RESTRICT AUTOMERGE: Hide overlay windows when requesting media projection permission.

#### project system/bt/
*  Check data length when parsing AVRCP vendor specific command responses
*  AVRCP: unify Get{Element,Item}Attributes response.

#### project libcore/
*  ZoneInfo: Exclude boundary tz transitions

#### project external/sonivox/
*  sonivox: prevent rejection of good but large MIDI files
*  sonivox: prevent infinite loop in OTA ringtones

#### project external/tremolo/
*  Fix OOB access in Tremolo

#### project system/bt/
*  Check AVRCP data length when parsing inside avrc_ctrl_pars_vendor_rsp()

* * *
### Build 20181101
* * *

#### project android/
*  manifest: Track our own chromium-libpac
*  manifest: Track our own external/v8

#### project build/
*  Security string to 2018-10-05

#### project external/skia/
*  BACKPORT: Cherry-pick "begin cleanup of malloc porting layer"

#### project frameworks/av/
*  Fix information disclosure in mediadrmserver
*  Fix information disclosure in mediadrmserver
*  Check for overflow of crypto size

#### project frameworks/base/
*  Fix crash during cursor moving on BiDi text
*  DO NOT MERGE. Persistable Uri grants still require permissions.
*  Always create grant structures when persistable.
*  Optimise the hit test algorithm
*  Add support for search in DownloadManager.
*  DO NOT MERGE. Extend SQLiteQueryBuilder for update and delete.
*  DO NOT MERGE. Execute "strict" queries with extra parentheses.

#### project packages/apps/Settings/
*  BACKPORT: Disable changing lock when device is not provisioned.

#### project packages/providers/DownloadProvider/
*  DO NOT MERGE. All untrusted selections must go through builder.
*  Enable search for Downloads.

#### project bionic/
*  zoneinfo: Update tzdata to 2018g

#### project external/icu/
*  icu: Update tzdata to 2018g

#### project external/chromium-webview/
*  Update webviews to Chromium 69.0.3497.109

#### project android/
*  Fork external/skia

#### project bionic/
*  zoneinfo: Update tzdata to 2018f

#### project external/icu/
*  icu: Update tzdata to 2018f

#### project external/v8/
*  Backport: Fix Object.entries/values with changing elements

#### project external/chromium-libpac/
*  Test for error in handling getters changing element kind.

#### project external/libmpeg2/
*  Adding check for min_width and min_height

#### project system/bt/
*  Checks the SMP length to fix OOB read
*  Add packet length check in smp_proc_master_id
*  DO NOT MERGE Fix OOB read before buffer length check
*  Check packet length in bta_av_proc_meta_cmd
*  Add missing AVRCP message length checks inside avrc_msg_cback
*  Add packet length checks in mca_ccb_hdl_req
*  Fix a wrong check in rfc_parse_data
*  Add bound check for rfc_parse_data
*  Check remaining frame length in rfc_process_mx_message
*  Fix copy length calculation in sdp_copy_raw_data
*  Fix OOB read in avrc_ctrl_pars_vendor_rsp

* * *
### Build 20180924
* * *

#### project android/
*  manifest: Track our own libxml2
*  manifest: Track our own neven

#### project build/
*  Security string to 2018-09-05

#### project frameworks/av/
*  M3UParser: handle missing EXT-X-MEDIA URIs
*  M3UParser: make url on demand

#### project frameworks/base/
*  Backport Prevent shortcut info package name spoofing
*  Fix TrackInfo parcel write
*  Resolve inconsistent parcel read in NanoAppFilter

#### project system/bt/
*  DO NOT MERGE HFP: Fix out of bound access in phone number processing
*  Don't use Address after it was deleted
*  HID Host: Check L2CAP packet data length
*  Add packet length checks in l2cble_process_sig_cmd
*  Fix OOB read in process_l2cap_cmd

#### project system/core/
*  Adaway hosts 20180913

#### project vendor/cm/
*  Update to Magisk v17.1 and MagiskManager v5.9.1

#### project system/bt/
*  DO NOT MERGE: SDP: Recalculate param_len after max_list_len
*  SDP: return error on offset bigger than atribute length

#### project external/neven/
*  Make bound check proper in bbf_Scanner_addOutPos

#### project external/libxml2/
*  RESTRICT AUTOMERGE: Update libxml2 to 2.9.8

#### project libcore/
*  Fix hostname parsing in java.net.URLStreamHandler.

#### project packages/providers/DownloadProvider/
*  Remove "public" download feature.

* * *
### Build 20180824
* * *

#### project android/
*  fork cm-14.1 repos

#### project build/
*  Security string to 2018-08-05

#### project frameworks/av/
*  Fix possible out of bounds read

#### project frameworks/base/
*  Make safe label more safe
*  ResStringPool: Prevenet boot loop from se fix
*  Fix DynamicRefTable::load security bug

#### project packages/apps/Messaging/
*  Messaging ignores file URIs shared via intent
*  Revert "Messaging: Request external storage permission before handling shared files"

#### project packages/apps/PackageInstaller/
*  RESTRICT AUTOMERGE: Always use safe labels

#### project packages/apps/Settings/
*  Merge translations of Bluetooth confirmation text
*  DO NOT MERGE Fix unexpected behavior in Bluetooth pairing

#### project packages/services/Telephony/
*  Fix potential NPE in EmergencyCallbackModeExitDialog.
*  DO NOT MERGE Revise security requirements for TelephonyManager#endCall.

#### project system/bt/
*  GATT: Use correct logging macro replacement

#### project external/chromium-webview/
*  Updated webviews to Chromium 67.0.3396.87

* * *
### Build 20180807
* * *

#### project android/
*  Track own external/bouncycastle

#### project build/
*  Security string to 2018-07-05

#### project frameworks/av/
*  Speed up id3v2 unsynchronization

#### project frameworks/base/
*  DO NOT MERGE Truncate newline and tab characters in BluetoothDevice name

#### project frameworks/native/
*  Increment when attempting to read protected Parcel Data
*  Disallow reading object data from Parcels with non-object reads
*  Don't pad before calling writeInPlace().

#### project packages/apps/Jelly/
*  Jelly: Show a Snackbar when removing an HistoryItem

#### project system/bt/
*  DO NOT MERGE SMP: Validate remote elliptic curve points

#### project kernel/asus/moorefield/
*  ramdisk: Replace init.power.mofd_v1.rc
*  defconfig: Enable RCU_FAST_NO_HZ
*  defconfig: Enable NTFS_RW
*  defconfig: Enable exFAT
*  fs: Add exFAT support
*  bcmdhd: reduce wakelocks
*  block: disable entropy contributions for nonrot devices
*  block: Reserve only one queue tag for sync IO if only 3 tags are available
*  readahead: make context readahead more conservative
*  fs/buffer.c: increase the buffer-head per-CPU LRU size
*  binfmt_elf.c: use get_random_int() to fix entropy depleting
*  gfx: Hardcode default APM latency and clock speed
*  gfx: Reduce APM latency to 3ms
*  i2c: designware: enable pm runtime
*  bt: bluetooth LPM driver wakelock adjustment
*  alarmtimer: adjust the duration of __pm_wakeup_event
*  mmc_ops: reduce mmc init time
*  mmc: remove the qos request for faster IO
*  intel_media: remove all pm_qos requests
*  display: decrease DSR_COUNT in order to sleep more
*  PM / autosleep: Use workqueue for user space wakeup sources garbage collector
*  PM / suspend: Make cpuidle work in the "freeze" state
*  cpuidle: don't disable cpuidle when entering suspend
*  cpuidle,x86: increase forced cut-off for polling to 20us
*  proc: Remove additional SafetyNet flags from /proc/cmdline
*  proc: Remove verifiedbootstate flag from /proc/cmdline
*  display: Don't restrict the brightness level
*  android: binder: use GPF_HIGHUSER flag since binder is designed for userspace
*  Makefile : Enable ccache
*  sound: Fix uninitialized errors
*  Remove '+' symbol from kernel version string
*  defconfig: Disable LOCALVERSION_AUTO
*  Automation
*  Update .gitignore

#### project android/
*  Fork frameworks_native

#### project external/bouncycastle/
*  Fix probable prime confidence calculations.

#### project external/libhevc/
*  Return error for invalid st/lt sps parameters

#### project packages/apps/Bluetooth/
*  Make sure server response doesn't exceed maximum allowable length

#### project system/bt/
*  DO NOT MERGE Prevent stack overflow in btif_storage
*  DO NOT MERGE: Check number of attributes before writing to a buffer
*  DO NOT MERGE AVRC: Add bound check for AVRC_EVT_APP_SETTING_CHANGE
*  Add bounds check to l2cble_process_sig_cmd L2CAP_CMD_DISC_REQ
*  DO NOT MERGE Fix unexpected behavior in smp_sm_event

* * *
### Build 20180612
* * *

#### project build/
*  Bump security string to 2018-06-05

#### project android/
*  manifest: Track own external/libvorbis

#### project frameworks/av/
*  Add check preventing div0 issue
*  Sanitize effect descriptors for AudioPolicyService binder calls.
*  Init gain config to prevent uninit leak.

#### project frameworks/base/
*  Rework thumbnail cleanup
*  ResStringPool: Fix security vulnerability

#### project frameworks/opt/telephony/
*  Fixed invalid pdu issue

#### project vendor/cm/
*  Update Lawnchair and Lawnfeed to v1.2.0.1878

#### project frameworks/opt/telephony/
*  Telephony: Fix "Keep preferred SMS Sim"

#### project external/libavc/
*  Encoder: Return error for odd resolution
*  Decoder: Modify setting short term reference field flag

#### project external/libhevc/
*  Add limits check for depth hierarchy sps parameters
*  Return error for invalid sps sub layers parameters
*  Return error for invalid reorder parameter

#### project external/libmpeg2/
*  Adding Check For Number of Skip MBs

#### project external/libvorbis/
*  CVE-2018-5146: Prevent out-of-bounds write in codebook decoding.

#### project external/libvpx/
*  DO NOT MERGE | libvpx: cherry pick fix to OOB of mv_cost index.

#### project external/sonivox/
*  sonivox: fix hang caused by bad meta-event

#### project packages/providers/MediaProvider/
*  Rework thumbnail cleanup
*  Fix deadlock in MediaProvider

#### project packages/providers/UserDictionaryProvider/
*  Check caller before accessing database

#### project system/bt/
*  DO NOT MERGE Drop LE CoC fragments when frame size is too big
*  DO NOT MERGE Fix OOB read in process_l2cap_cmd
*  [Backport] DO NOT MERGE Handle bad packet length in gatts_process_read_req
*  DO NOT MERGE Add bounds check for BNEP_Write
*  PAN: Always allocate in bta_pan_data_buf_ind_cback
*  DO NOT MERGE Fix unexpected behavior in bta_dm_sdp_result

#### project packages/apps/Snap/
*  SnapdragonCamera: Panorama, replace border drawable
*  Snap: remove unused shutter buttons

* * *
### Build 20180604
* * *

#### project packages/apps/Snap/
*  Snap: Remove leftover translations

#### project packages/apps/AudioFX/
*  AudioFX: Remove leftover translations

#### project packages/apps/Bluetooth/
*  Bluetooth: Remove a leftover test-string

#### project packages/apps/Email/
*  Email: Remove leftover translations

#### project packages/apps/Exchange/
*  Exchange: Remove leftover translation

#### project packages/apps/Snap/
*  Snap: Allow quickreader to work with secure device

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
