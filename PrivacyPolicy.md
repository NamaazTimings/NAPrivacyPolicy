# Privacy Policy for Namaaz Awqaat

**Last updated: 2026-11-16**

Namaaz Awqaat ("the app") shows prayer times, the Qibla direction, prayer alerts and the Hijri date. This policy explains what the app does with information. It is written from how the app actually works.

## In short
* The app has **no accounts, no ads, no analytics and no crash-reporting tools**.
* Your **location stays on your phone**. It is used only to work out prayer times and the Qibla, and only after you tap the location button.
* The app uses **Google's Firebase** for announcements (only if you switch them on) and a small silent update of Hijri-calendar corrections.
* We do **not sell** your information and do not share it for advertising.

## Who is responsible
Contact: **SadaqahJaariyah.App@gmail.com**

## What the app uses, and why

### Location (precise or approximate)
* **When:** only after you grant the location permission **and** tap the location button on the Timings screen.
* **What for:** to calculate prayer times, the Qibla direction and the time zone for the place you are in.
* **Where it goes:** the coordinates and the place name are **saved on your phone** so the app can show your times next time. They are **not sent to the developer** and not to any server run by the developer.
* **Place name:** to show a readable place name the app asks **Android's built-in geocoder** (the same one other apps use). Depending on your phone, that system service may send the coordinates to its provider (usually Google) to get the name. This is done by the Android system, not by us, and we never receive it.
* You can stop at any time by choosing a city from the list instead, or by turning off location permission in Android settings.

### Settings stored on your phone
Language, city or saved place, Asr and calculation method, alert switches and sound, theme, font, text size, app-icon style, Hijri-date adjustment, and a few flags (for example "guide seen", "compass calibrated", "background question answered") and the time of your last test alert, used only to tell you if it did not arrive. They stay on your phone.

### Compass sensors
The Qibla compass reads your phone's motion and magnetic sensors **on the phone only**. Nothing is recorded or sent.

### Prayer alerts
Alerts use Android's alarm-clock alarms and notifications so they arrive on time, even when the phone is idle. Android may therefore show your next prayer alert as an alarm in the status bar. The app sets them again after the phone restarts. After the first-run guide (and once after an update) it asks whether the app may run in the background, which is Android's battery-optimisation setting, so alerts are not delayed. It is optional and Android asks you to confirm; you can change it any time in Settings. All of this happens on your phone.

### Firebase Cloud Messaging (announcements), only if you turn announcements on
* If you switch announcements on in Settings, the app subscribes your phone to a few general **topics** (all users, your language, and your city if it is one of the built-in cities) so it can receive occasional announcements.
* To deliver them, Google's Firebase assigns your phone an **installation ID / messaging token** and processes technical details such as app version, device model, Android version and IP address.
* Announcements are **not personalised**. We only see how many phones are subscribed to each topic, not who they are.
* Turning announcements off in Settings removes the subscriptions.

### Firebase Remote Config (Hijri-date corrections)
* Moon-sighting dates differ between regions, so the app downloads a small file of **calendar corrections** from Firebase when it opens. This happens quietly and does not depend on the announcements switch. It never shows a notification.
* To do this, Firebase receives standard technical information (installation ID, app version, device model, Android version, language and region, IP address). The app does not add your location or any personal details to this request.
* If you are offline, the last saved corrections or the built-in calendar are used.

### Feedback
The feedback button only opens **your own email app** with our address and a subject line filled in. Nothing is sent unless you write and send the email yourself.

## What the app does not do
* No sign-up, no accounts, no user profiles.
* No advertising, no ad networks, no tracking across apps or websites.
* No analytics or crash-reporting libraries.
* No access to your contacts, photos, files, microphone or camera.
* No sale of personal information.

## Permissions the app asks for
| Permission | Why |
|---|---|
| Notifications | Prayer alerts and, if enabled, announcements |
| Receive boot completed | Set your alerts again after the phone restarts |
| Vibrate | Vibration alerts |
| Ignore battery optimisations (optional) | Stop the system delaying alerts |
| Internet | Firebase announcements and calendar corrections |
| Location (precise / approximate) | Prayer times and Qibla for where you are, after you tap the location button |

## Who else handles information
Google (Firebase Cloud Messaging and Firebase Remote Config) processes the technical information described above on our behalf. Their handling is described at https://policies.google.com/privacy and https://firebase.google.com/support/privacy. Android's system geocoder is part of your phone's software.
If your phone has Android or Google backup switched on, Android may save the app's settings (which can include a saved place) to your own Google account. That is controlled by your phone settings.
We may disclose information if the law requires it, but the developer does not hold personal data about you.

## How long information is kept
* Information on your phone stays until you clear the app's storage or uninstall it.
* Firebase keeps installation and messaging identifiers for as long as the app is installed and as described in Google's policies.

## Your choices
* Pick a city instead of using location, or revoke the permission at any time.
* Turn announcements off in Settings.
* Clear the app's storage or uninstall it to remove all information saved on the phone.

## Security
The app does not collect accounts or passwords. Communication with Firebase uses encrypted connections.

## Children
The app is a general prayer-time tool. It does not knowingly collect personal information from anyone, including children. The "Kids" option in Settings is only a style for the app icon.

## Changes to this policy
If the app changes how it handles information, this page and the date at the top are updated.

## Contact
Questions about this policy: **SadaqahJaariyah.App@gmail.com**
