# Android Reverse Engineering Patches

Welcome to the Android Reverse Engineering Patches repository! This collection of patches is designed to assist and streamline the process of reverse engineering Android applications. Whether you're a security researcher, an Android enthusiast, or simply curious about the inner workings of Android apps, this repository aims to provide you with valuable resources and tools.

Reverse engineering Android applications can be a complex task, requiring a deep understanding of the Android platform and its underlying architecture. This repository aims to simplify the process by offering a curated collection of patches that address common challenges encountered during reverse engineering. These patches are carefully crafted to patch and modify specific aspects of Android apps, making them more amenable to analysis and exploration.

In this repository, you will find a wide range of patches covering various aspects of Android app reverse engineering. From bypassing license checks and removing advertisements to disabling anti-tampering mechanisms and exposing hidden functionality, these patches are intended to empower researchers and developers to dig deeper into Android apps and gain valuable insights.

We encourage you to explore the different categories and patches available in this repository. Each patch comes with detailed documentation and instructions on how to apply it to an Android app effectively. Additionally, you'll find helpful resources, such as tutorials and guides, to assist you in your reverse engineering journey.
## Patches Info:
1. **AntiAds-v2.2** - Magisk Module to Block Ads, Porn, Trackers and Phishing Sites on your Android Device. (Author=Kero309x)
2. **Fake Android ID** -The Android Id is faked or replaced so that the application cannot obtain the device's original data.
3. **Cnfix** - Cnfix patch can kill signatures of android applications with pv hook (Same as of Cnfix App)
4. **GooglePlayServices by Edik1d** - This patch is used to remove googleplay services from the APK.
5. **Patch_RemoveAds+Offline** - This patches for removing ads from apps created by TheDarkOnion.
It contains 3 patches to remove ads and 1 patch to disable internet:
  * First try RemoveAds-R1
  * If you face any problem of crash or server error with RemoveAds-R1 then try RemoveAds-R2
  * RemoveAds-R3 is enough for disabling ads and safe from errors
  * DisableInternet patch will make your application into offline mode <br>
6. **Fake_device_information.zip** - Patch to apply fake random information to apps<br>
≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡ <br>
An example of the changes that this patch applies <br>
•••••••••••••••••••••••••••••••••••••••••••••• <br>

  [build.model: Nexus 5 <br>
  build.hardware: hammerhead <br>
  build.product: hammerhead <br>
  version.codename: REL <br>
  build.cpu_abi: armeabi-v7a <br>
  build.cpu_abi2: armeabi <br>
  version.incremental: eng.nickv.20170513.192248 <br>
  build.display: N2G47O <br>
  build.user: nickv <br>
  build.host: virtualpenguin <br>
  build.type: user <br>
  build.tags: test-keys <br>
  build.serial: 065dc5710aca8f51 <br>
  version.release: 7.1.2 <br>
  build.id: N2G47O <br>
  build.bootloader: HHZ20f <br>
  build.device: hammerhead <br>
  build.board: hammerhead <br>
  build.brand: google <br>
  build.fingerprint: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys <br>
  build.manufacturer: LGE ] <br>
━━━━━━━━━━━━━━━━━━━━━━ <br>
Using this patch, you can provide random fake information. <br>
I have updated a small part of this regex [ ] <br>
**Created by Reza** <br>
7. **Google Pairip bypass.lpzip** -  This Patch can bypass Google pairip..
  How to use: <br>
      1) Open it with zip viewer<br>
      2) Change Adrian_package.name.txt <br>
      {package.name} to your target app app package  name <br>
      3) And open this patch with lucky patcher <br>
      4) And patch your Target app <br>


## Contributing

Contributions to this repository are highly welcome! If you have created or discovered useful patches that could benefit the reverse engineering community, we invite you to contribute them here. To contribute:

1. Fork the repository.
2. Create a new branch for your contribution.
3. Make your changes and test them thoroughly.
4. Submit a pull request detailing your changes.


Please note that the patches provided in this repository are intended for educational and research purposes only. It's crucial to respect the intellectual property rights of the original app developers and to abide by any applicable laws and regulations in your jurisdiction.



