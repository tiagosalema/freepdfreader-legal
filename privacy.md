# Privacy Policy — Free PDF Reader

_Last updated: 8 May 2026._

This privacy policy describes what data the **Free PDF Reader** Android app (the "App") processes and why. It is published by Tiago Salema (Salema Technologies), the sole developer.

The App is designed to process **as little data as possible**. The PDFs you open, the highlights and bookmarks you make, and your reading position stay on your device by default.

## Data the App processes on your device

- **PDF files you open.** Files are accessed only when you explicitly pick them through Android's system file picker. The App opens each file read-only via the Storage Access Framework (SAF). The App does **not** scan your device storage, browse other folders, or access any file you have not explicitly chosen.
- **Highlights and bookmarks.** Stored locally as JSON sidecar files in the App's private folder. They are **not** uploaded anywhere and **not** synced across devices.
- **Last reading position, zoom, and pan offset.** Stored locally so the App can resume where you left off.
- **Recently opened files list.** The list of file names you have opened and the URI references through which Android granted the App temporary access to each file. Stored locally.
- **All of the above is excluded from Android Auto Backup and device-to-device transfer** (`allowBackup="false"`). It stays on your device until you delete it or uninstall the App.

## When you explicitly share content from the App

Some user-initiated actions hand content to other apps on your device via Android Intents. The App does not transmit this data itself; you choose the receiving app, and what it does with the data is governed by **its** privacy policy:

- **Share PDF** — passes a temporary read-only reference to the chosen PDF to the app you pick (e.g. email, messaging, Drive).
- **Export annotations** — passes Markdown-formatted text of your highlights and bookmarks to the app you pick.
- **Look up** — passes the highlighted text as a search query to your default search or browser app.
- **Send feedback** — pre-fills a message addressed to `hello@salematechnologies.com` in your default email app. Content is whatever you choose to type and send.

## Data sent off your device by the App

The App uses two third-party Google services that may collect technical, non-personal information:

### 1. Firebase Crashlytics (crash reporting)

If the App crashes or encounters a non-fatal error, an automated crash report is sent to Google's Firebase Crashlytics service. A crash report contains:

- App version, Android version, device model, locale.
- A stack trace of the error (function names; no file contents).
- A randomly-generated installation identifier (does not identify you personally).
- Non-personally-identifying technical metadata about the document open at the time of the crash — specifically the **page count** and **page dimensions** of the PDF. This helps reproduce the bug. **No filenames, file contents, highlight text, bookmark text, or URIs** are included.

Privacy details: [Firebase Privacy and Security](https://firebase.google.com/support/privacy). To stop sending crash reports, uninstall the App.

### 2. Google AdMob (advertising)

The free version of the App displays one native ad in the Recents list on the home screen.

**Consent first.** Before any ad-related data is collected, you may see a consent dialog (provided by Google's User Messaging Platform). The dialog appears on first launch in jurisdictions where consent is required (UK, EEA, Switzerland, applicable US states). You can revisit and change your choice at any time via the **⋮ menu → Privacy choices** on the home screen. If you decline consent, no ads are served to you.

**What AdMob may collect (after consent, where required):**

- The Android Advertising ID (a resettable, non-permanent identifier).
- IP address, device model, OS version, app version, language.
- Coarse approximate location (derived from IP).
- Ad interaction events (impression, click).

**On Android 13 and later**, AdMob uses Android's Privacy Sandbox APIs (Topics API and Attribution Reporting API) where available, in addition to or instead of the Advertising ID. These are Google-provided, on-device alternatives that limit cross-app tracking.

Details and controls:
- Reset or delete your Advertising ID: **Android Settings → Privacy → Ads → Delete advertising ID**.
- AdMob's data handling: [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites).
- Opt out of personalised ads: [Google Ads Settings](https://adssettings.google.com/).

If you purchase the optional in-app ad-removal upgrade in a future App version, no ads will be shown and AdMob will not be used for that install.

## Data we do not collect

To be explicit: the App does **not**:

- Require an account or login.
- Process your name, email address, phone number, contacts, calendar, or any other personally identifying information.
- Read, transmit, or store the **contents** of your PDFs, your highlights, or your bookmarks anywhere off your device.
- Track your reading habits.
- Use any analytics SDK other than Firebase Crashlytics.
- Access your camera, microphone, photos, or location (beyond the coarse IP-based location AdMob inherently uses).

## Children

The App is **not directed at children under 13**. The Recents native ad slot is configured as not child-directed and not for users under the age of consent. We do not knowingly process data from children under 13.

## Permissions

The App declares no runtime permissions and never asks the user to grant one. A small set of install-time permissions is added automatically by Google's Crashlytics and AdMob SDKs to support crash reporting, ad serving, and the Privacy Sandbox APIs. These are granted by the Android system without prompting and are not used to access your personal data on the device.

## Data retention

- Local data (highlights, bookmarks, recents, reading positions) stays on your device until you delete it (via the App's Annotations Library, the Recents "Delete" action, or by uninstalling the App).
- Crash reports are retained by Firebase per [Google's retention schedule](https://firebase.google.com/support/privacy).
- AdMob data is retained per [Google's retention policy](https://policies.google.com/technologies/retention).

## Your rights

If you are in the UK, EU/EEA, or other jurisdictions with similar laws, you have the right to access, correct, delete, or restrict processing of your data. Because the App does not collect data that personally identifies you on our side, there is generally no data the developer holds to action. For data held by Google (Crashlytics, AdMob), see the linked privacy policies above. For consent withdrawal, use **⋮ menu → Privacy choices** in the App.

## Changes to this policy

If this policy changes materially, the "Last updated" date at the top will be updated. Continued use of the App after a change indicates acceptance of the revised policy.

## Contact

Email: **hello@salematechnologies.com**
