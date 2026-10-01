<p align="center">
  <img src="logo.svg" width="120" height="120" alt="SmartHub Logo" />
</p>

<h1 align="center">ElecMarketing SmartHub</h1>

<p align="center">
  <strong>Next-Generation Android IoT Controller & Industrial Booster Pump Management Suite</strong>
</p>

<p align="center">
  <a href="https://github.com/omseven/SmartHub_App/releases"><img src="https://img.shields.io/github/v/release/omseven/SmartHub_App?style=for-the-badge&color=0ea5e9&label=Latest%20Release" alt="Release"></a>
  <img src="https://img.shields.io/badge/Platform-Android%205.0%2B-10b981?style=for-the-badge&logo=android&logoColor=white" alt="Platform">
  <img src="https://img.shields.io/badge/Kotlin-1.9.22-7c3aed?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin">
  <img src="https://img.shields.io/badge/License-Proprietary-f43f5e?style=for-the-badge" alt="License">
</p>

---

## 📖 Overview

**ElecMarketing SmartHub** is an industrial Android application crafted for water management engineers, technicians, and operators. It provides seamless **auto-discovery**, **real-time dashboard telemetry**, **cloud firmware updates (OTA)**, and **in-app self-updates** for **WaterFix (WF001)** and **EMBF224** booster pump controllers.

---

## ✨ Features

- 🛰️ **Autonomous Radar Discovery:** Scans UDP broadcast/multicast and local subnets to instantly locate online controllers.
- ⚡ **Embedded Real-Time Dashboard:** High-speed WebView interface for direct configuration over SoftAP (`192.168.10.1` / `192.168.4.1`) or local LAN.
- 🔄 **GitHub In-App Auto-Update:** Checks for newer APK versions directly from this repository and triggers direct background download & installation.
- ☁️ **Cloud Firmware Sync:** Synchronizes the latest hardware firmware binaries from official GitHub releases for 1-tap wireless OTA flashing.
- 🏷️ **Controller Registry & Nicknames:** Save and organize multiple hardware units by custom name, serial number, and IP.
- 🌌 **Cyber Industrial Design:** Dark futuristic theme with fluid spring animations, radar sweeps, and live status banners.

---

## 📱 Tech Stack & Specs

| Specification | Details |
| :--- | :--- |
| **Package Name** | `ir.elecmarketing.boosterpump` |
| **Target SDK** | Android 14 (API Level 34) |
| **Minimum SDK** | Android 5.0 (API Level 21) |
| **Language** | Kotlin |
| **Package Installer** | `androidx.core.content.FileProvider` |
| **Build Tool** | Gradle 8.14+ |

---

## 📦 Download & Installation

You can get the latest pre-compiled Release APK directly from the [Releases](https://github.com/omseven/SmartHub_App/releases) page:

1. Download `ElecMarketing_SmartHub_V1.4_release.apk`.
2. Open the file on your Android smartphone or tablet.
3. Allow installation from unknown sources if prompted.
4. Enjoy automatic updates for all future releases!

---

## 🛠️ Building from Source

### Prerequisites
- Android Studio Hedgehog / Iguana / Ladybug or newer
- JDK 17
- Android SDK 34

### Build via Command Line
```bash
# Clone the repository
git clone https://github.com/omseven/SmartHub_App.git
cd SmartHub_App

# Build Debug APK
./gradlew assembleDebug

# Build Production Release APK
./gradlew assembleRelease
```
The output APK will be located at:
`app/build/outputs/apk/release/ElecMarketing_SmartHub_V1.4_release.apk`

---

<p align="center">
  <sub>Developed & Maintained by <b>ElecMarketing</b> Engineering Team</sub>
</p>

