# Privacy Policy — Free PDF Reader

_Last updated: 8 May 2026._

This privacy policy describes what data the **Free PDF Reader** Android app (the "App") processes and why. It is published by Tiago Salema, the sole developer.

The App is designed to process **as little data as possible**. Most user content — the PDFs you open, the highlights and bookmarks you make — stays on your device and is never sent anywhere.

## Data the App processes on your device

- **PDF files you open.** Files are accessed only when you explicitly pick them through Android's system file picker. The App opens each file read-only via the Storage Access Framework (SAF). The App does **not** scan your device storage, browse other folders, or access any file you have not explicitly chosen.
- **Highlights and bookmarks.** Stored locally on your device as JSON sidecar files in the App's private folder. They are **not** uploaded anywhere, **not** synced across devices, and **not** included in Android Auto Backup.
- **Last reading position, zoom, and pan offset.** Stored locally so the App can resume where you left off.
- **Recently opened files list.** The list of file names and the URI references you have granted the App access to. Stored locally.

None of this data leaves your device.

## Data sent off your device

The App uses two third-party services that may collect technical, non-personal information:

### 1. Firebase Crashlytics (crash reporting)

If the App crashes or encounters a non-fatal error, an automated crash report is sent to Google's Firebase Crashlytics service to help fix bugs. A crash report contains:

- App version, Android version, device model, locale.
- A stack trace of the error (function names, no file contents).
- A randomly-generated installation identifier (does not identify you personally).

Crash reports do **not** include PDF file names, file contents, highlight text, bookmarks, URIs, or any text you have selected. We have explicitly designed the App to keep this kind of data out of crash reports.

Privacy details: [Firebase Privacy and Security](https://firebase.google.com/support/privacy). You can disable crash reporting by uninstalling the App.

### 2. Google AdMob (advertising)

The free version of the App displays one native ad in the Recents list on the home screen. Ads are served by Google AdMob. AdMob may collect:

- The Android Advertising ID (a resettable, non-permanent identifier).
- IP address, device model, OS version, app version, language.
- Coarse approximate location (derived from IP).
- Ad interaction events (impression, click).

AdMob uses this information to serve relevant ads and to detect invalid traffic.

Details and controls:
- Reset or delete your Advertising ID: **Android Settings → Privacy → Ads → Delete advertising ID**.
- AdMob's data handling: [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites).
- Opt out of personalised ads: [Google Ads Settings](https://adssettings.google.com/).

If you purchase the optional in-app ad-removal upgrade in a future App version, no ads will be shown and AdMob will not be used for that install.

## Data we do **not** collect

To be explicit: the App does **not**:

- Require an account or login.
- Process your name, email address, phone number, contacts, calendar, or any other personally identifying information.
- Read or transmit the **contents** of your PDFs, your highlights, your bookmarks, or any text you select.
- Track your reading habits.
- Use any analytics SDK other than Crashlytics.
- Access your camera, microphone, photos, or location (beyond the coarse IP-based location AdMob inherently uses).

## Children

The App is **not directed at children under 13**. The Recents native ad slot may serve ads from Google's general advertising network and is not configured for child-directed treatment under COPPA. We do not knowingly process data from children under 13.

## Permissions

The App declares no runtime permissions. The only install-time permissions are `INTERNET` and `ACCESS_NETWORK_STATE`, used solely by Crashlytics and AdMob.

## Data retention

- Local data (highlights, bookmarks, recents) stays on your device until you delete it (via the App's Annotations Library, the Recents "Delete" action, or by uninstalling the App).
- Crash reports are retained by Firebase per [Google's retention schedule](https://firebase.google.com/support/privacy).
- AdMob data is retained per [Google's retention policy](https://policies.google.com/technologies/retention).

## Your rights

If you are in the UK, EU/EEA, or other jurisdictions with similar laws, you have the right to access, correct, delete, or restrict processing of your data. Because the App does not collect data that personally identifies you, there is generally no data on the developer's side to action. For data held by Google (Crashlytics, AdMob), see the linked privacy policies above.

## Changes to this policy

If this policy changes materially, the "Last updated" date at the top will be updated. Continued use of the App after a change indicates acceptance of the revised policy.

## Contact

Email: **tiagof.salema@gmail.com**
