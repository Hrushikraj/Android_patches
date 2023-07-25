# Android Reverse Engineering Patches

Welcome to the Android Reverse Engineering Patches repository! This collection of patches is designed to assist and streamline the process of reverse engineering Android applications. Whether you're a security researcher, an Android enthusiast, or simply curious about the inner workings of Android apps, this repository aims to provide you with valuable resources and tools.

Reverse engineering Android applications can be a complex task, requiring a deep understanding of the Android platform and its underlying architecture. This repository aims to simplify the process by offering a curated collection of patches that address common challenges encountered during reverse engineering. These patches are carefully crafted to patch and modify specific aspects of Android apps, making them more amenable to analysis and exploration.

In this repository, you will find a wide range of patches covering various aspects of Android app reverse engineering. From bypassing license checks and removing advertisements to disabling anti-tampering mechanisms and exposing hidden functionality, these patches are intended to empower researchers and developers to dig deeper into Android apps and gain valuable insights.

We encourage you to explore the different categories and patches available in this repository. Each patch comes with detailed documentation and instructions on how to apply it to an Android app effectively. Additionally, you'll find helpful resources, such as tutorials and guides, to assist you in your reverse engineering journey.
## Patches Info:
* AntiAds-v2.2.zip - Magisk Module to Block Ads, Porn, Trackers and Phishing Sites on your Android Device. (Author=Kero309x)
* Fake Android ID.zip -The Android Id is faked or replaced so that the application cannot obtain the device's original data.  
* Cnfix - Cnfix patch can kill signatures of android applications with pv hook (Same as of Cnfix App)
* GooglePlayServices by Edik1d.zip - This patch is used to remove googleplay services from the APK.
* patch_RemoveAds+Offline.zip - This patches for removing ads from apps created by TheDarkOnion.
It contains 3 patches to remove ads and 1 patch to disable internet:
1. First try RemoveAds-R1
2. If you face any problem of crash or server error with RemoveAds-R1 then try RemoveAds-R2
3. RemoveAds-R3 is enough for disabling ads and safe from errors
4. DisableInternet patch will make your application into offline mode
* Fake_device_information.zip - Patch to apply fake random information to apps
  (≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡)
An example of the changes that this patch applies
(••••••••••••••••••••••••••••••••••••••••••••••)

build.model: Nexus 5
build.hardware: hammerhead
build.product: hammerhead
version.codename: REL
build.cpu_abi: armeabi-v7a
build.cpu_abi2: armeabi
version.incremental: eng.nickv.20170513.192248
build.display: N2G47O
build.user: nickv
build.host: virtualpenguin
build.type: user
build.tags: test-keys
build.serial: 065dc5710aca8f51
version.release: 7.1.2
build.id: N2G47O
build.bootloader: HHZ20f
build.device: hammerhead
build.board: hammerhead
build.brand: google
build.fingerprint: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
build.manufacturer: LGE
━━━━━━━━━━━━━━━━━━━━━━
Using this patch, you can provide random fake information.
I have updated a small part of this regex [ ]
Good luck.
━━━━━━━━━━━━━━━━━━━━━━
Created by Reza


## Contributing

Contributions to this repository are highly welcome! If you have created or discovered useful patches that could benefit the reverse engineering community, we invite you to contribute them here. To contribute:

1. Fork the repository.
2. Create a new branch for your contribution.
3. Make your changes and test them thoroughly.
4. Submit a pull request detailing your changes.


Please note that the patches provided in this repository are intended for educational and research purposes only. It's crucial to respect the intellectual property rights of the original app developers and to abide by any applicable laws and regulations in your jurisdiction.



