# Privacy Policy — Similia Assistant

Last updated: December 2025  
This policy keeps personal and sensitive data transparent for Google Play and your users.

## Data we collect
- **FCM token** so we can send announcements and reminders via Firebase Cloud Messaging.
- **Crash reports** that are automatically sent to Firebase Crashlytics for debugging, along with anonymized stack traces.
- **Device/installation identifiers** that help derive the encrypted SQLCipher key so the bundled database stays tied to each device.
- **App settings** such as dark mode, font scale, and saved user preferences stored locally.

## Why we collect it
- Firebase Messaging needs the token to route notifications to your device.
- Crashlytics keeps us aware of crashes so we can fix bugs quickly.
- The device-bound key workflow means the database is encrypted per install and cannot be reused on another device without the original key.
- Local preferences make the experience accessible without syncing any user profile.

## Storage, sharing & retention
- All data stays on the Android device and is encrypted (SQLCipher + AES) except for the tokens and reports sent to Firebase.
- Firebase (Google) is the only third party involved; we do not share or sell any personal information.
- Uninstalling the app removes the encrypted database and all settings by design.

## Your control
- Disable or adjust notifications from Android’s app settings to stop FCM usage.
- Reinstall the app to force a fresh database rebuild if you suspect corruption.
- Contact `kabir.cse10@gmail.com` to ask for data-handling clarifications.
- We honor Firebase’s privacy/security guarantees; no personal data leaves the device unless it is part of crash/FCM telemetry.
