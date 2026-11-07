# Privacy Policy for Ruh - Quran, Prayer & Islamic

**Effective Date:** November 5, 2026  
**Last Updated:** November 5, 2026  
**App Name:** Ruh - Quran, Prayer & Islamic  
**Package Name:** `com.duhalab.ruh.islamic`  
**Developer:** Duha Lab

---

## 1. Introduction & Overview

Welcome to **Ruh - Quran, Prayer & Islamic** ("we", "our", or "us"). We are deeply committed to protecting your privacy and providing a serene, authentic, and safe digital experience for Muslims worldwide.

**Ruh is built with a strict "Privacy-First" and "Offline-First" philosophy.**  
We believe that your acts of worship, Quran recitation, prayer times, and personal supplications are sacred. We do **not** sell, rent, monetize, profile, or transmit your personal data, location records, or reading habits to remote servers or any third-party marketing entities.

---

## 2. Information We Access & How We Use It

Ruh operates client-side on your device. To provide essential Islamic utilities such as automated prayer times, Qibla compass direction, and background Quran audio recitation, the app requires specific device permissions:

### A. Location Data (GPS & Network Location)

* **What We Access:** Approximate (Coarse) and Precise (Fine) location coordinates (latitude, longitude).
* **Why We Need It:**
  1. To calculate mathematically precise prayer times (Fajr, Dhuhr, Asr, Maghrib, Isha), Sunrise, Tahajjud, and Sehri/Iftar schedules based on your exact geographical position.
  2. To compute the compass bearing towards the Holy Kaaba (Qibla) in Makkah from your current position.
* **How It Is Handled:**
  - Your location coordinates are processed **strictly on-device** using local astronomical formulas.
  - Location coordinates are **never** transmitted to any external server, logged remotely, or shared with third parties.
  - **Manual District Selection Option:** If you prefer not to grant GPS location access, you can manually select your district or city from our pre-configured offline database without granting any location permissions.

### B. Device Sensors (Magnetometer & Accelerometer)

* **What We Access:** Device magnetic field and rotation/orientation sensors.
* **Why We Need It:** Used exclusively by the **Qibla Compass** feature to detect true North and point towards the Holy Kaaba.
* **How It Is Handled:** Sensor readings are processed in real-time in device memory and are immediately discarded when you exit the Qibla screen.

### C. Notifications & Exact Alarms

* **Permissions Used:** `POST_NOTIFICATIONS`, `SCHEDULE_EXACT_ALARM`, `USE_EXACT_ALARM`.
* **Why We Need It:** To deliver timely Adhan audio alerts and prayer reminders at exact times, even when your device is locked, the screen is turned off, or the app is closed.
* **How It Is Handled:** Schedules are managed locally inside your Android device's AlarmManager. We do not use remote push tracking services.

### D. Foreground Service & Audio Playback

* **Permissions Used:** `FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_MEDIA_PLAYBACK`, `WAKE_LOCK`.
* **Why We Need It:** To provide uninterrupted background audio playback for Quran recitation and Islamic audio when your phone screen turns off or while you switch to other applications, with a standard Android Media notification controller.

### E. Local Storage & Database

* **Permissions & Technology:** SQLite local database (`quran_db_ruh.sqlite`), `SharedPreferences`, and local application sandbox storage.
* **What Is Stored:** Your Quran reading bookmarks, last-read Ayahs, Tasbih counter tally, daily deeds tracker logs, Zakat calculator inputs, and downloaded offline audio/PDF files.
* **How It Is Handled:** All data resides exclusively in your device's sandboxed private storage. If you uninstall the app or clear app data, this locally saved data is deleted.

---

## 3. Third-Party Services & Analytics

* **No Tracking or Advertising SDKs:** Ruh does **not** integrate third-party ad networks (e.g., AdMob, Unity, AppLovin) or invasive user-tracking SDKs (e.g., Facebook SDK, AppsFlyer).
* **Audio Recitations CDN:** When downloading or streaming Quran recitation audio from certified Qaris, the app requests standard MP3 files from reputable Islamic audio CDNs (such as `everyayah.com` and `mp3quran.net`). These requests contain standard HTTP headers and do not transmit any personal user identifiers.

---

## 4. Children’s Privacy (COPPA & Family Policy Compliance)

Ruh is completely family-safe and suitable for users of all ages, including children.

* We do not knowingly collect, request, or store any personal information from children or adults.
* Because the app is 100% ad-free and tracker-free, it is safe for children learning Quran, Salah, and Hadith.

---

## 5. Security of Your Information

Because we do not collect or transmit your data to remote servers, your data is as secure as your personal device. We recommend using standard device security features (such as screen lock and biometric authentication) to protect your device.

---

## 6. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be posted on this page with an updated "Last Updated" date. We encourage you to review this policy periodically.

---

## 7. Contact Us

If you have any questions, feedback, or concerns regarding this Privacy Policy or our privacy practices, please contact us:

* **Developer / Organization:** Duha Lab
* **Email:** support@duhalab.com (or your designated support email)
* **GitHub Repository:** https://github.com/duhalab/ruh-islamic-app
