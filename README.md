<div align="center">

# 🌿 Ruh - Quran, Prayer & Islamic
### রূহ – কুরআন, নামাজ ও ইসলামিক মুসলিম অ্যাপ

[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?logo=dart)](https://dart.dev)
[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android)](https://www.android.com/)
[![Ads](https://img.shields.io/badge/Ads-100%25%20Ad--Free-brightgreen)](#)
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Offline--First-blue)](#)
[![License](https://img.shields.io/badge/License-MIT-orange)](#)

**A serene, privacy-first, 100% ad-free, and battery-optimized Islamic utility application crafted with love for the Muslim Ummah.**

[Privacy Policy](PRIVACY_POLICY.md) • [Terms of Service](TERMS_OF_SERVICE.md) • [Support](mailto:duhalab.bd@gmail.com)

</div>

---

## 📖 About The App

**Ruh (রূহ)** is a comprehensive Islamic companion developed to fulfill your daily spiritual devotions and Islamic learning needs. Designed from the ground up with an **"Offline-First"** and **"Privacy-First"** philosophy, Ruh ensures your worship, recitation, and supplications remain sacred, uninterrupted, and free from intrusive advertisements or analytics trackers.

### 🌟 Core Philosophy
- **100% Ad-Free Forever:** Pure worship experience with zero banner ads, interstitial pop-ups, or commercial interruptions.
- **Privacy-Centric:** No account creation required, no cloud tracking, no analytics SDKs. All bookmarks, notes, and trackers stay strictly on your device.
- **Battery-Friendly & Fast:** Ultra-optimized SQLite queries, smooth 60/120 FPS animations, and minimal battery consumption even during long Quran listening sessions.

---

## ✨ Features Overview

### 1. 📖 Al-Quran Al-Kareem (আল-কুরআনুল কারীম)
- **Authentic Arabic Text:** High-resolution Uthmani script with crystal-clear Quranic typography.
- **Translations & Tafseer:** Complete Bengali and English translations alongside detailed scholarly Tafseer.
- **Audio Recitations:** Ayah-by-ayah and continuous Surah recitation by world-renowned Qaris (Mishary Rashid Alafasy, Abdul Basit, etc.).
- **Background Playback:** Runs smoothly in the background when your screen is locked, complete with native Android MediaStyle notification controls (Play, Pause, Skip).
- **Hifz & Memorization:** Dedicated Hifz companion with audio repetition, range loops, and memorization progress tracking.
- **Smart Bookmarks & Last Read:** Never lose your place with automatic last-read bookmarking.

### 2. 🕌 Prayer Times & Adhan (নামাজের সময়সূচি ও আযান)
- **High-Precision Calculations:** Mathematical prayer schedules (Fajr, Sunrise, Dhuhr, Asr, Maghrib, Isha, Tahajjud, Sehri, and Iftar) based on astronomical positioning.
- **Custom Adhan Audio:** Authentic Fajr and standard Adhan alerts with exact alarm scheduling (`AlarmManager`).
- **Offline District Selection:** Works 100% offline with pre-configured district databases if GPS location permission is not granted.

### 3. 🧭 Qibla Direction (কিবলা কম্পাস)
- Real-time magnetic compass sensor integration pointing precisely to the Holy Kaaba in Makkah.
- Visual alignment indicators and gentle haptic feedback upon exact Qibla alignment.

### 4. 📿 Digital Tasbih & Daily Amal Tracker (আমল ট্র্যাকার ও তাসবীহ)
- **Customizable Tasbih:** Digital counter with haptic vibrations, custom Dhikr targets, and daily tally records.
- **Amal Tracker:** Daily spiritual deeds checklist (5 prayers, Quran reading, Sadaqah, Istighfar) with streak statistics.

### 5. 📚 Islamic Library (ইসলামিক জ্ঞান ভাণ্ডার)
- **Sahih Hadiths:** Curated collections of authentic Hadiths categorized by topics.
- **Hisnul Muslim (হিসনুল মুসলিম):** Daily Masnoon Duas for morning, evening, travel, illness, and protection with Arabic, pronunciation, and translation.
- **Asmaul Husna:** The 99 Beautiful Names of Allah with meanings and benefits.
- **Zakat Calculator:** Instant and accurate Zakat assessment based on modern Nisab thresholds.
- **Hijri Calendar:** Islamic lunar calendar with significant Islamic dates and events.

---

## 🛠️ Tech Stack & Architecture

- **Framework:** [Flutter](https://flutter.dev) (Channel stable, Material 3)
- **Language:** [Dart](https://dart.dev) (v3.x)
- **State Management:** [GetX](https://pub.dev/packages/get)
- **Local Database:** [sqflite](https://pub.dev/packages/sqflite) (`quran_db_ruh.sqlite`)
- **Key-Value Storage:** [shared_preferences](https://pub.dev/packages/shared_preferences)
- **Audio Engine:** [audioplayers](https://pub.dev/packages/audioplayers) with custom Android Foreground Service (`QuranPlayerService.kt`)
- **Astronomical Calculations:** [adhan](https://pub.dev/packages/adhan)
- **Notifications:** [flutter_local_notifications](https://pub.dev/packages/flutter_local_notifications) with exact alarm scheduling

---

## 📁 Project Structure

```text
ruh_islamic/
├── android/                  # Native Android configuration & services
│   └── app/src/main/kotlin/com/duhalab/ruh/islamic/
│       ├── MainActivity.kt          # MethodChannel & platform bridge
│       └── QuranPlayerService.kt   # Background media playback service
├── assets/
│   ├── database/             # Pre-populated SQLite Quran database
│   ├── fonts/                # Authentic Arabic & Bengali fonts
│   ├── icons/logo/           # Production launcher & branding logos
│   └── audio/                # Adhan audio alerts
├── lib/
│   ├── controllers/          # Business logic & GetX controllers
│   ├── core/
│   │   ├── constants/        # AppAssets, AppColors, AppTheme
│   │   ├── localization/     # English & Bengali translations
│   │   ├── notifications/    # Local notifications & scheduling
│   │   └── services/         # Audio, location & calculation services
│   ├── models/               # Data classes & SQLite entities
│   ├── views/                # Modular UI screens:
│   │   ├── calendar/         # Hijri calendar
│   │   ├── home/             # Main dashboard
│   │   ├── library/          # Hadith, Duas, Asmaul Husna, Zakat
│   │   ├── mosque/           # Nearby mosques map
│   │   ├── qiblah/           # Qibla compass
│   │   ├── quran/            # Quran reader, audio player & Hifz
│   │   ├── settings/         # Preferences & about screen
│   │   └── tasbih/           # Digital Tasbih counter
│   └── main.dart             # Application entrypoint
└── pubspec.yaml              # Dependencies & asset declarations
```

---

## 🚀 Getting Started

### Prerequisites
- [Flutter SDK](https://docs.flutter.dev/get-started/install) (`^3.13.0` or higher)
- [Android Studio](https://developer.android.com/studio) / Android SDK (API 34+)
- Java JDK 17

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/duhalab/ruh-islamic.git
   cd ruh-islamic
   ```

2. **Install Flutter dependencies:**
   ```bash
   flutter pub get
   ```

3. **Verify analyzer status:**
   ```bash
   flutter analyze
   ```

4. **Run on a connected device/emulator:**
   ```bash
   flutter run
   ```

5. **Build release APK:**
   ```bash
   flutter build apk --release
   ```
   *Output binary will be located at:*  
   `build/app/outputs/flutter-apk/app-release.apk`

6. **Build release App Bundle (AAB for Google Play):**
   ```bash
   flutter build appbundle --release
   ```
   *Output bundle will be located at:*  
   `build/app/outputs/bundle/release/app-release.aab`

---

## 🔒 Permissions & Security

| Permission | Purpose |
|:---|:---|
| `ACCESS_FINE_LOCATION` | Calculate exact prayer times and Qibla compass direction (Client-side only). |
| `POST_NOTIFICATIONS` | Deliver Adhan prayer alerts and daily reminder notifications. |
| `SCHEDULE_EXACT_ALARM` | Precise on-time Adhan playback at exact prayer times. |
| `FOREGROUND_SERVICE_MEDIA_PLAYBACK` | Uninterrupted background Quran audio playback with Android media controls. |
| `WAKE_LOCK` | Prevent playback disruption when device screen is turned off. |

---

## 🤝 Contribution & Feedback

We welcome community feedback, corrections to translations or typographical errors, and feature suggestions to serve the Ummah better.

If you discover any error in Quranic text, Hadith, or prayer calculations, please report it immediately:
- 📧 **Support Email:** [duhalab.bd@gmail.com](mailto:duhalab.bd@gmail.com)
- 🐛 **Issue Tracker:** [GitHub Issues](https://github.com/duhalab/ruh-islamic-app/issues)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).  
*The Holy Quran text and authentic Hadiths belong to all humanity and the Muslim Ummah.*

---

<div align="center">
  <b>Developed with devotion by DuhaLab</b><br>
  <i>"May Allah accept this effort as Sadaqah Jariyah for all who contributed and use it."</i>
</div>
