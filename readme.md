# Privacy Policy for Notiva Music Player

**Last Updated: February 20, 2026**

---

## Introduction

Welcome to Notiva, developed by **Novatra** ("we," "our," or "us"). We respect your privacy and are committed to protecting your personal data. This privacy policy explains how we handle information when you use our Notiva Music Player application ("App").

---

## Information We Collect

### 1. Local Data (Stored on Your Device Only)
We access the following data **locally on your device** to provide core functionality:

| Data Type | Purpose | Storage |
|-----------|---------|---------|
| Audio files | Play your music | Your device only |
| Audio metadata | Display song info (title, artist, album, cover art) | Your device only |
| Playlists | Manage your music collections | Your device only |
| Favorites | Track your favorite songs | Your device only |
| Lyrics files | Display song lyrics | Your device only |
| App preferences | Remember your settings (theme, language, playback) | Your device only |

**Important:** This data never leaves your device and is never transmitted to our servers.

### 2. Crash Reports & Analytics (Firebase)
We use **Firebase Crashlytics** and **Firebase Analytics** (by Google) to improve the app's stability and performance:

| Service | Data Collected | Purpose |
|---------|---------------|---------|
| Firebase Crashlytics | Crash logs, device model, OS version, app version | Identify and fix bugs |
| Firebase Analytics | Anonymous usage patterns, screen views, feature usage | Improve user experience |

**Important:**
- This data is **anonymous** and cannot be used to identify you personally
- No personal information, song titles, or music library contents are included
- You can opt out of analytics by disabling "Share usage data" in your device settings
- Firebase data is processed by Google under their [Privacy Policy](https://policies.google.com/privacy)

### 3. Network Requests
The App connects to the internet for the following purposes:

| Feature | Service | Data Sent |
|---------|---------|-----------|
| Lyrics Search | Third-party lyrics APIs | Song title, artist name |
| In-App Web Search | Google Search (via WebView) | Your search query |

**Note:** When you search for lyrics, only the song title and artist name are sent to retrieve matching lyrics. No personal information is transmitted.

---

## Information We Do NOT Collect

We want to be clear about what we **do not** do:

- ❌ We do **not** collect personal information (name, email, phone number)
- ❌ We do **not** track your location
- ❌ We do **not** access your contacts
- ❌ We do **not** show advertisements
- ❌ We do **not** sell or share any data with third parties
- ❌ We do **not** create user accounts or profiles
- ❌ We do **not** have access to your music library contents from our servers

---

## Permissions We Request

| Permission | Why We Need It |
|------------|----------------|
| `READ_MEDIA_AUDIO` | Access your music files to play them |
| `READ_MEDIA_IMAGES` | Display album artwork |
| `READ_EXTERNAL_STORAGE` | Access music files on Android 12 and below |
| `MANAGE_EXTERNAL_STORAGE` | Edit song metadata (title, artist, album, cover art) and save embedded lyrics - required for modifying audio file tags |
| `INTERNET` | Search for lyrics online, crash reporting |
| `FOREGROUND_SERVICE` | Keep music playing in background |
| `POST_NOTIFICATIONS` | Show playback controls in notification |
| `WAKE_LOCK` | Prevent device from sleeping during playback |
| `MODIFY_AUDIO_SETTINGS` | Adjust equalizer and audio settings |
| `WRITE_SETTINGS` | Set songs as ringtone (optional) |

---

## Third-Party Services

### Firebase (Google)
We use Firebase Crashlytics and Firebase Analytics to monitor app stability and improve the user experience. Firebase is operated by Google and is subject to [Google's Privacy Policy](https://policies.google.com/privacy). The data collected is anonymous and used solely for improving the App.

### Lyrics Search
When you use the lyrics search feature, your request is processed through third-party lyrics providers:

- The only data transmitted is the song title and artist name
- No personal or device information is included
- Searches are not linked to any user profile

### WebView Browser
The in-app browser (WebView) is used for:
- Searching lyrics on Google
- Opening external links

When using the WebView, standard web browsing data may be processed by the websites you visit. We recommend reviewing Google's privacy policy when using the search feature.

**Important:** The WebView operates independently, and Notiva does not access or collect any cookies, login credentials, or browsing history from your web sessions. Any data you enter in the WebView is handled directly by the visited websites, not by our App.

---

## Data Storage and Security

- **All user data is stored locally** on your device
- Crash reports and anonymous analytics are processed by Firebase (Google)
- We use Android's standard security features to protect stored data
- We do not have servers that store your personal information
- Uninstalling the app removes all locally stored data from your device

---

## Data Deletion

Since all user data is stored locally on your device, you have full control:

- **Delete all app data:** Go to Android Settings → Apps → Notiva → Storage → Clear Data
- **Delete cache only:** Go to Android Settings → Apps → Notiva → Storage → Clear Cache
- **Complete removal:** Uninstall the App to remove all locally stored data

For Firebase data, anonymous crash/analytics data is automatically deleted after the retention period set by Google (typically 90 days for Crashlytics, 14 months for Analytics).

---

## Children's Privacy

Notiva is a general audience app and does not knowingly collect information from children under 13. If you believe we have inadvertently collected such information, please contact us immediately.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:
- Updating the "Last Updated" date
- App update notes (if significant changes)

We encourage you to review this Policy periodically.

---

## Your Rights

You have the right to:
- ✅ Access all your data (it's already on your device!)
- ✅ Delete your data (uninstall the app or clear app data)
- ✅ Deny permissions (some features may not work)
- ✅ Use the app offline (except lyrics search and crash reporting)

---

## Contact Us

If you have any questions about this Privacy Policy or our practices, please contact us:

- **Developer:** Novatra
- **Email:** info@novatra-app.online
- **Website:** [novatra-app.online](https://novatra-app.online)

---

## Summary

**In simple terms:** Notiva is primarily an offline music player. Your music and personal data stay on your device. We use Firebase to collect anonymous crash reports and usage data to improve the app. We only connect to the internet for lyrics search and crash reporting. We don't collect, store, or share your personal information.

---

*This privacy policy is effective as of February 20, 2026*

---

© 2026 Novatra. All rights reserved.
