## Magisk File Host

This repository hosts Magisk related files

<img src="https://img.shields.io/badge/MagiskVersion-f69ca8252-green.svg?longCache=true&style=flat-square" alt="Version" /> <img src="https://img.shields.io/badge/MagiskVersionCode-23001-orange.svg?longCache=true&style=flat-square" alt="Version" /> <img src="https://img.shields.io/badge/StubVersionCode-21-yellow.svg?longCache=true&style=flat-square" alt="Version" />

## Custom Magisk

Custom Magisk by [TheHitMan7](https://github.com/TheHitMan7). Always synced with official changes including Magisk Hide, Hide the Magisk app, Magisk-Module-Repository features.
It will spoof/alter/manipulate non-Magisk related signals or traces to circumvent device state detection. Although included features are officially removed from Magisk.
I added them back while keeping the latest changes including Zygisk - Magisk in Zygote.

* [Custom Repository](https://github.com/TheHitMan7/Magisk.git)
* [Custom Builds](https://github.com/TheHitMan7/Magisk-Files/tree/master/files)

<details>
<summary><b>Check Safetynet Response</b></summary>
<p align="center">
  <img src="https://raw.githubusercontent.com/TheHitMan7/Magisk-Files/master/images/f69ca8252.jpg" width="500"/>
</p>
</details>

## Sources

* [Official Repository](https://github.com/topjohnwu/Magisk.git)
* [Official Builds](https://github.com/topjohnwu/magisk-files.git)

## Bug Report

1. Do not report issues from Custom Magisk in Official Repository issues section.
2. Do not report issues from Custom Magisk in Custom Repository issues section.
3. Do not report issues from Official Magisk in Custom Repository issues section.

## Note

* Custom Repository is not official Magisk repository
* Custom Magisk Builds are not official Magisk builds

## Conflict

Do not use `MagiskRelease.apk` instead use `MagiskDebug.apk`. Options like Hide the Magisk app, Magisk-Module-Repository, Check Safetynet does not work with stable APK release.
Latest version of App is also **N/A** with stable APK release. It looks like a check against **Official** and **Unofficial** Magisk release. Hence prevent certain features.

> **Completely uninstall previous Magisk before installing custom Magisk build. Even switching between custom Magisk builds also require full uninstall.**

## Installation

* Uninstall previous Magisk
* Require reboot to system
* Install Custom Magisk

> **In case, CTS profile is failing, you can follow either of below steps.**

1. Wipe data and cache, Restore original boot, Reboot to recovery, Install custom Magisk.
2. Clean flash ROM and install custom Magisk.

## Requirement

Keystore [Patch](https://github.com/kdrag0n/safetynet-fix#rom-integration) in ROM or use Universal Safetynet Fix Magisk [Module](https://github.com/kdrag0n/safetynet-fix/releases).

1. Magisk Hide and Keystore Patch in ROM.
2. Magisk Hide and Universal Safetynet Fix.
3. Magisk Hide and BiTGApps Safetynet [Patch](https://github.com/BiTGApps/BiTGApps-Files/raw/master/Tools/BiTGApps-safetynet-patch_signed.zip).

You can follow any of above method to pass CTS profile.

> **BiTGApps Safetynet Patch**

It has everything that is required for passing CTS profile.

* Spoof build fingerprint to Pixel 5
* Spoof System/Vendor build property
* Update System/Vendor Security Patch Level
* Update Boot Security Patch Level
* Shipped with Patched Keystore

## Author

Magisk is developed and owned by [topjohnwu](https://github.com/topjohnwu)
