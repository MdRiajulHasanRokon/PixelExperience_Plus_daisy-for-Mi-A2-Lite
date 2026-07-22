# PixelExperience Plus for Xiaomi Mi A2 Lite (daisy) - Custom ROM

Welcome to the official repository for the **PixelExperience Custom ROM** tailored specifically for the **Xiaomi Mi A2 Lite (daisy)**. 

## What is PixelExperience?
PixelExperience is an **AOSP based Custom ROM**, with Google apps included and all Pixel goodies (launcher, wallpapers, icons, fonts, boot animation). Our mission is to offer the maximum possible stability and security, along with essential and useful features for the proper functioning of your Android device.

**Based on Android 13** - Experience the latest features and security updates.

## What's Working?
Almost everything you need for a daily driver is functional on this Android 13 build for Mi A2 Lite:
- Wi-Fi & Hotspot
- RIL (Calls, SMS, Microphone)
- Mobile Data
- GPS / Location Services
- Camera & Camcorder
- Flashlight
- Bluetooth
- FM Radio
- Fingerprint Reader
- Face Unlock
- Notification Lights
- Sound & Vibration

## Known Issues
- Nothing yet!
- If you find any bugs, please let us know.

---

## 📥 Installation & Download Links

> **⚠️ IMPORTANT: DON'T FLASH GAPPS, THEY'RE ALREADY INCLUDED!**

You can find all necessary files in the **[Releases](https://github.com/MdRiajulHasanRokon/PixelExperience_Plus_daisy-for-Mi-A2-Lite/releases)** section of this repository:
- **Download ROM**
- **Download Recovery Image** (`PixelExperience_Recovery_daisy`)
- **Download Firmware** (`fw_daisy_miui_DAISYGlobal`)

## 🛠️ Installation

> **NOTE:** Installing using other recoveries isn't tested, please use the PixelExperience recovery provided in the releases.

1. **Download ROM, Recovery, and firmware files** from the download links.
2. Reboot to **fastboot mode** and flash the recovery file using:
   ```bash
   fastboot flash boot PixelExperience_Recovery_daisy_20231105.img
   ```
3. Reboot to PixelExperience recovery.
4. **Format data**.
5. Flash firmware using **Apply update > Apply from ADB**:
   ```bash
   adb sideload fw_daisy_miui_DAISYGlobal_V11.0.21.0.QDLMIXM_c6721a4b58_10.0.zip
   ```
6. It will ask you to reboot to recovery again, tap **Yes**.
7. Flash the ROM file using **Apply update > Apply from ADB**:
   ```bash
   adb sideload <romfilename>.zip
   ```
   > *(Do not flash GApps, they are already included)*
8. Reboot your device.

## 🪄 Installing Magisk (Optional)
1. Download and rename the Magisk `.apk` file to `.zip`.
2. Reboot to recovery.
3. Flash the `Magisk.zip` file using **Apply update > Apply from ADB**:
   ```bash
   adb sideload <magiskfilename>.zip
   ```
4. Reboot.
5. Open the Magisk app and it will ask you to install again > use the **Direct Install (recommended)** option.
6. Reboot.

## 📝 Notes
> I had to remove some of the prebuilt Google apps from the ROM to fit it inside the system partition. You can install these apps or any alternatives from the Play Store or APKMirror as user apps without any issue. 

**Removed Apps:**
- Google Chrome
- Google Photos
- Google Recorder
- Google Speech Recognition & Synthesis
- Android Accessibility Suite (talkback)
- Sound Amplifier (Accessibility)
- Live Transcribe & Notification (Accessibility)

> **⚠️ Please do not report bugs without proper logs.**

## 📋 Changelog
**21/07/2026:**
- Initial release (Plus edition)

## Support & Donate
If you like the project and want to support the development:
- [Buy me a coffe ☕](https://buymeacoffee.com/riajul124)
- DM me directly if you want to support this specific device maintainer!

---
*Tags: Xiaomi Mi A2 Lite, daisy, Custom ROM, Android 13, PixelExperience, AOSP, Firmware, Recovery Image, GApps*
