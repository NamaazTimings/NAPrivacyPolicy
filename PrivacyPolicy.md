# Privacy Policy for NamaazAwqaat

**Effective Date:** November 11, 2026  
**Last Updated:** November 11, 2026  
**Application Name:** NamaazAwqaat  
**Package Name:** `com.farooq.namaazawqaat`  
**Developer Contact:** `Sadaqa.E.Jaariyah@gmail.com`  

---

## 1. Introduction
**NamaazAwqaat** ("we", "our", or "us") is dedicated to protecting your privacy. This Privacy Policy outlines how our application collects, uses, and safeguards information when you use our mobile application. 

NamaazAwqaat is built as a modern, privacy-first prayer timing application designed to function offline without requiring user registration, personal account creation, or tracking.

---

## 2. Information Collection and Use

### A. Location Data (`ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`)
- **How We Use It:** When you choose to use the "My Location" (GPS) feature, NamaazAwqaat accesses your device's geographical coordinates (latitude and longitude) **on-device** to calculate astronomical prayer times and determine the precise Qibla direction relative to the Kaaba.
- **Storage & Transfer:** Location data is processed locally on your device. We do **not** transmit, store on external servers, sell, or share your location coordinates with any third parties. Reverse-geocoding queries standard system Android APIs to resolve city/locality names locally.

### B. Device Sensors (Compass / Orientation)
- **How We Use It:** NamaazAwqaat accesses your device's rotation vector and magnetometer sensors solely to render the real-time Qibla compass needle on screen.
- **Storage & Transfer:** Sensor data is read in real time while the Qibla tab is open and is never logged, saved, or transmitted.

### C. Alarms and Notifications (`POST_NOTIFICATIONS`, `SCHEDULE_EXACT_ALARM`, `RECEIVE_BOOT_COMPLETED`, `VIBRATE`)
- **How We Use It:** To deliver exact prayer alarms, Sehri caution alerts, Azaan audio notifications, and Friday Surah Kahf reminders, the app uses Android `AlarmManager` and notification services.
- **Storage & Transfer:** Alarm schedules and settings are stored locally on your device in private application preferences.

### D. Firebase Cloud Messaging (FCM) & Push Announcements
- **How We Use It:** NamaazAwqaat integrates optional Firebase Cloud Messaging (FCM) to deliver lightweight public announcements (such as festival updates or Eid notices).
- **Subscribed Topics:** The app subscribes to non-identifying public notification topics based strictly on language choice (e.g., `lang_en`, `lang_ur`, `lang_te`, `lang_hi`) and city selection (e.g., `city_hyderabad`, `city_khammam`).
- **Data Privacy:** FCM does not collect personal identifiers, user credentials, phone numbers, or contacts.

---

## 3. Third-Party Services
NamaazAwqaat does **not** include third-party advertising SDKs, behavioral analytics tracking, or data brokers. The only third-party framework integrated is Google Firebase Cloud Messaging for optional push notifications.

- **Google Play Services / Firebase Privacy Policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

---

## 4. Children’s Privacy
Our application does not address anyone under the age of 13 intentionally, nor does it collect personally identifiable information from children. If you are a parent or guardian and are aware that your child has provided us with personal information, please contact us so we can take necessary actions.

---

## 5. Data Security
We value your trust in using NamaazAwqaat. All application preferences, custom alarm offset settings, theme configurations, and city choices are stored securely inside your device's private application storage (`SharedPreferences`). No personal data is transmitted over the internet.

---

## 6. Your Rights & Choices
- **Location Access:** You can enable or disable location permissions at any time via your device's System Settings (`Settings > Apps > NamaazAwqaat > Permissions`).
- **Notification Access:** You can enable, disable, or customize notification channels at any time in system settings or via the in-app **Alerts** and **Settings** tabs.

---

## 7. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. Any changes will be posted on this page with an updated effective date. You are advised to review this Privacy Policy periodically for any changes.

---

## 8. Contact Us
If you have any questions or suggestions regarding our Privacy Policy, please feel free to contact us at:

- **Email:** `SadaqaJaariyah.App@gmail.com`
- **Application:** NamaazAwqaat (`com.farooq.namaazawqaat`)
