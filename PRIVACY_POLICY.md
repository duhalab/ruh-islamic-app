# Privacy Policy for Ruh - Quran, Prayer & Islamic

**Effective date:** November 7, 2026  
**Last updated:** November 7, 2026

- **App name:** Ruh - Quran, Prayer & Islamic (রূহ – ইসলামিক ও মুসলিম অ্যাপ)
- **Android package:** `com.duhalab.ruh.islamic`
- **Developer:** DuhaLab
- **Contact:** [duhalab.bd@gmail.com](mailto:duhalab.bd@gmail.com)

## 1. Overview

Ruh is designed around privacy and offline use. The app provides Islamic features such as prayer-time calculations, a Qibla compass, Quran reading, reminders, and audio playback.

We do not operate an account system or a server that receives your precise location, bookmarks, counters, or other information stored locally in the app. Some features—such as streaming or downloading Quran audio—require an internet connection and involve requests to third-party audio providers. Details are explained below.

## 2. Information and permissions used by the app

### Location

If you grant location permission, Ruh accesses your approximate or precise location to calculate prayer times and determine the Qibla direction.

- Location is used on your device for these features; Ruh does not send your coordinates to its own server.
- You can deny location access and select a district or city from the app’s offline location list instead.
- Android permissions: `ACCESS_COARSE_LOCATION` and `ACCESS_FINE_LOCATION`.

### Device sensors

The Qibla compass uses the device’s magnetic-field and rotation sensors to determine direction. Sensor readings are processed on your device while you use the compass and are not sent to Ruh’s servers.

### Prayer reminders and alarms

If enabled, prayer reminders and Adhan alerts are scheduled locally using Android’s alarm and notification features. Depending on your Android version and enabled features, the app may request `POST_NOTIFICATIONS`, `SCHEDULE_EXACT_ALARM`, `USE_EXACT_ALARM`, and `RECEIVE_BOOT_COMPLETED`. These permissions support local reminders; Ruh does not use a remote push-notification service for them.

### Audio playback

The app may use Android foreground-service and wake-lock capabilities to continue Quran audio playback when you switch apps or turn off the screen. Relevant permissions may include `FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_MEDIA_PLAYBACK`, and `WAKE_LOCK`.

### Information stored on your device

The app may store Quran bookmarks and last-read position, Tasbih counts, daily deeds entries, Zakat calculator inputs, preferences, and downloaded audio or PDF files. This information is stored in the app’s local storage, including its SQLite database and preferences. It is not sent to Ruh’s servers. Clearing app data or uninstalling the app removes locally stored information and downloads.

## 3. Third-party services and internet use

Ruh does not include advertising or analytics SDKs, and we do not sell or use your app data for advertising or profiling.

When you stream or download Quran recitations, your device connects to the relevant audio provider or content-delivery network (for example, `everyayah.com`, where applicable). As with any internet request, the provider may receive your IP address and standard technical request information. The provider’s own privacy practices apply to that connection. Location coordinates and locally stored app records are not included in these audio requests by Ruh.

## 4. Children’s privacy

Ruh is intended to be suitable for users of all ages. The app does not ask users to create accounts or provide personal information. We do not knowingly collect personal information from children. If you believe that a child has provided personal information to us, please contact us so we can review the matter.

## 5. Your choices and data deletion

- You can deny or revoke location and notification permissions in your Android settings. Some features may then be unavailable or require manual location selection.
- You can remove locally stored information by clearing Ruh’s app data or uninstalling the app.
- You can stop online audio requests by not streaming or downloading audio.

## 6. Security

Ruh stores the information described in this policy in the app’s private on-device storage. No method of storage or transmission is completely secure, so we recommend using your device’s security features, such as a screen lock, and keeping Android up to date.

## 7. Changes to this policy

We may update this policy when the app or its practices change. We will post the revised policy here and update the “Last updated” date. Please review this page periodically.

## 8. Contact

For questions or privacy-related requests, contact:

**DuhaLab**  
[duhalab.bd@gmail.com](mailto:duhalab.bd@gmail.com)  
[https://github.com/duhalab/ruh-islamic-app](https://github.com/duhalab/ruh-islamic-app)
