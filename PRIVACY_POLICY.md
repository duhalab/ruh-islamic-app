# Privacy Policy for Ruh - Quran, Prayer & Islamic

**Effective Date:** November 5, 2026  
**Last Updated:** November 5, 2026  
**App Name:** Ruh - Quran, Prayer & Islamic  
**Effective Date:** November 7, 2026  
**Last Updated:** November 7, 2026  
**Application Name:** Ruh - Quran, Prayer & Islamic (রূহ – ইসলামিক ও মুসলিম অ্যাপ)  
**Package Name:** `com.duhalab.ruh.islamic`  
**Developer:** Duha Lab  
**Developer:** DuhaLab  
**Support Email:** [duhalab.bd@gmail.com](mailto:duhalab.bd@gmail.com)  

---

## 1. Introduction & Overview

Welcome to **Ruh - Quran, Prayer & Islamic** ("we", "our", or "us"). We are deeply committed to protecting your privacy and providing a serene, authentic, and safe digital experience for Muslims worldwide.
Welcome to **Ruh - Quran, Prayer & Islamic** ("we", "our", or "us"). We are deeply dedicated to protecting your privacy and providing a peaceful, authentic, and completely safe digital environment for Muslims worldwide.

**Ruh is built with a strict "Privacy-First" and "Offline-First" philosophy.**  
We believe that your acts of worship, Quran recitation, prayer times, and personal supplications are sacred. We do **not** sell, rent, monetize, profile, or transmit your personal data, location records, or reading habits to remote servers or any third-party marketing entities.
**Ruh is built upon a strict "Privacy-First" and "Offline-First" philosophy.**  
We strongly believe that your personal devotions, Quran recitations, prayer schedules, and supplications are sacred. We do **not** sell, rent, monetize, profile, or transmit your personal data, location history, or usage habits to remote servers or third-party advertising networks.

---

## 2. Information We Access & How We Use It

Ruh operates client-side on your device. To provide essential Islamic utilities such as automated prayer times, Qibla compass direction, and background Quran audio recitation, the app requires specific device permissions:
Ruh operates client-side on your device. To provide essential Islamic utilities such as accurate prayer times, Qibla compass direction, and background Quran audio recitation, the app requests specific device permissions:

### A. Location Data (GPS & Network Location)
* **What We Access:** Approximate (Coarse) and Precise (Fine) location coordinates (latitude, longitude).
* **Why We Need It:**
  1. To calculate mathematically precise prayer times (Fajr, Dhuhr, Asr, Maghrib, Isha), Sunrise, Tahajjud, and Sehri/Iftar schedules based on your exact geographical position.
  2. To compute the compass bearing towards the Holy Kaaba (Qibla) in Makkah from your current position.
* **How It Is Handled:** 
  - Your location coordinates are processed **strictly on-device** using local astronomical formulas.
  - Location coordinates are **never** transmitted to any external server, logged remotely, or shared with third parties.
  - **Manual District Selection Option:** If you prefer not to grant GPS location access, you can manually select your district or city from our pre-configured offline database without granting any location permissions.
* **Permissions Requested:** `ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`
* **Purpose:**
  1. To calculate mathematically precise prayer times (Fajr, Sunrise, Dhuhr, Asr, Maghrib, Isha, Tahajjud, and Sehri/Iftar) based on your exact geographical coordinates.
  2. To compute the compass bearing towards the Holy Kaaba (Qibla) in Makkah from your current location.
* **Privacy Assurance:** 
  - Location data is processed **strictly on-device** using local astronomical formulas.
  - Your coordinates are **never** transmitted to any external server, logged remotely, or shared with third parties.
  - **Offline District Selection:** If you prefer not to grant location permissions, you can manually select your district or division from our offline database without granting any location access.

### B. Device Sensors (Magnetometer & Accelerometer)
* **What We Access:** Device magnetic field and rotation/orientation sensors.
* **Why We Need It:** Used exclusively by the **Qibla Compass** feature to detect true North and point towards the Holy Kaaba.
* **How It Is Handled:** Sensor readings are processed in real-time in device memory and are immediately discarded when you exit the Qibla screen.
* **Data Accessed:** Device magnetic field and rotation vector sensors.
* **Purpose:** Used exclusively by the **Qibla Compass** feature to determine true North and point towards the Holy Kaaba.
* **Privacy Assurance:** Sensor readings are processed in real-time in device RAM only and are discarded immediately when you leave the Qibla screen.

### C. Notifications & Exact Alarms
* **Permissions Used:** `POST_NOTIFICATIONS`, `SCHEDULE_EXACT_ALARM`, `USE_EXACT_ALARM`.
* **Why We Need It:** To deliver timely Adhan audio alerts and prayer reminders at exact times, even when your device is locked, the screen is turned off, or the app is closed.
* **How It Is Handled:** Schedules are managed locally inside your Android device's AlarmManager. We do not use remote push tracking services.
* **Permissions Used:** `POST_NOTIFICATIONS`, `SCHEDULE_EXACT_ALARM`, `USE_EXACT_ALARM`, `RECEIVE_BOOT_COMPLETED`
* **Purpose:** To trigger timely Adhan audio alerts and prayer reminders at exact times, even when your device is locked, in Doze mode, or the app is closed.
* **Privacy Assurance:** All notification schedules are managed locally inside your Android device's native `AlarmManager`. We do not use remote push tracking services.

### D. Foreground Service & Audio Playback
* **Permissions Used:** `FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_MEDIA_PLAYBACK`, `WAKE_LOCK`.
* **Why We Need It:** To provide uninterrupted background audio playback for Quran recitation and Islamic audio when your phone screen turns off or while you switch to other applications, with a standard Android Media notification controller.
* **Permissions Used:** `FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_MEDIA_PLAYBACK`, `WAKE_LOCK`
* **Purpose:** To provide continuous, uninterrupted audio recitation of the Holy Quran when your device screen is turned off or while switching between apps, with standard Android media notification controls.

### E. Local Storage & Database
* **Permissions & Technology:** SQLite local database (`quran_db_ruh.sqlite`), `SharedPreferences`, and local application sandbox storage.
* **What Is Stored:** Your Quran reading bookmarks, last-read Ayahs, Tasbih counter tally, daily deeds tracker logs, Zakat calculator inputs, and downloaded offline audio/PDF files.
* **How It Is Handled:** All data resides exclusively in your device's sandboxed private storage. If you uninstall the app or clear app data, this locally saved data is deleted.
* **Technology:** SQLite local database (`quran_db_ruh.sqlite`), `SharedPreferences`, and internal application sandbox storage.
* **Data Stored:** Quran reading bookmarks, last-read Ayahs, Tasbih counter tally, daily deeds tracker logs, Zakat calculator entries, and offline audio/PDF files.
* **Privacy Assurance:** All data resides strictly inside your device's private sandboxed app directory. Clearing application data or uninstalling the app permanently erases this data from your phone.

---

## 3. Third-Party Services & Analytics
## 3. Third-Party Services & Advertisements

* **No Tracking or Advertising SDKs:** Ruh does **not** integrate third-party ad networks (e.g., AdMob, Unity, AppLovin) or invasive user-tracking SDKs (e.g., Facebook SDK, AppsFlyer).
* **Audio Recitations CDN:** When downloading or streaming Quran recitation audio from certified Qaris, the app requests standard MP3 files from reputable Islamic audio CDNs (such as `everyayah.com` and `mp3quran.net`). These requests contain standard HTTP headers and do not transmit any personal user identifiers.
* **100% Ad-Free Experience:** Ruh contains **zero** advertisements. We do not integrate any advertising SDKs (e.g., Google AdMob, Unity, AppLovin, Meta Ads).
* **Zero Tracking / Analytics SDKs:** Ruh does **not** include invasive tracking libraries or user-profiling SDKs (e.g., Facebook SDK, AppsFlyer, Adjust).
* **Audio Recitation CDN:** When downloading or streaming online Quran recitation audio from certified Qaris, the app requests standard MP3 files from trusted Islamic audio CDNs (such as `everyayah.com` and `mp3quran.net`). These requests contain standard HTTP headers and do not transmit any personal user identifiers.

---

## 4. Children’s Privacy (COPPA & Family Policy Compliance)
## 4. Children’s Privacy & Family Policy Compliance

Ruh is completely family-safe and suitable for users of all ages, including children. 
* We do not knowingly collect, request, or store any personal information from children or adults.
* Because the app is 100% ad-free and tracker-free, it is safe for children learning Quran, Salah, and Hadith.
Ruh is family-safe and suitable for users of all ages, including children.
* We do not collect, store, or solicit personal information from children or adults.
* Because the app is completely ad-free and tracker-free, it provides a safe, educational learning platform for children studying the Holy Quran, Salah, and Hadith.
* The application complies with the **Children’s Online Privacy Protection Act (COPPA)** and Google Play Family Policy requirements.

---

## 5. Security of Your Information
## 5. Data Security

Because we do not collect or transmit your data to remote servers, your data is as secure as your personal device. We recommend using standard device security features (such as screen lock and biometric authentication) to protect your device.
Because your personal religious data and location coordinates are stored and processed solely on your device, your information is as secure as your phone. We recommend utilizing device-level security features such as screen locks and biometric authentication.

---

## 6. Changes to This Privacy Policy
## 6. User Rights & Data Deletion

We may update this Privacy Policy from time to time. Any changes will be posted on this page with an updated "Last Updated" date. We encourage you to review this policy periodically.
You retain complete control over your data:
* You can reset your Tasbih counters, daily deeds logs, or Quran bookmarks at any time from within the app settings.
* Uninstalling the application or clearing the app storage from Android Settings permanently deletes all local records and downloaded files.

---

## 7. Contact Us
## 7. Changes to This Privacy Policy

If you have any questions, feedback, or concerns regarding this Privacy Policy or our privacy practices, please contact us:
We may periodically update this Privacy Policy to reflect app enhancements or legal requirements. Any modifications will be posted here with an updated "Last Updated" date.

* **Developer / Organization:** Duha Lab
* **Email:** support@duhalab.com (or your designated support email)
* **GitHub Repository:** https://github.com/duhalab/ruh-islamic-app
---

## 8. Contact & Support

If you have any questions, feedback, bug reports, or privacy inquiries regarding Ruh - Quran, Prayer & Islamic, please reach out to us:

* **Developer:** DuhaLab  
* **Support Email:** [duhalab.bd@gmail.com](mailto:duhalab.bd@gmail.com)  
* **Official Repository:** [https://github.com/duhalab/ruh-islamic-app](https://github.com/duhalab/ruh-islamic-app)  
