Welcome to **Endoscope Camera** (the "Application" or "App"), developed to provide precision real-time viewing, recording, and media management for USB endoscope, borescope, otoscope, and inspection cameras on Android devices.

We recognize the importance of your privacy and are committed to protecting it. This Privacy Policy explains our practices regarding the collection, use, and disclosure of information when you download, install, and use our Application.

By installing and using the Application, you agree to the collection and use of information in accordance with this Privacy Policy. If you do not agree with any part of this policy, please do not use the Application.

---

## 2. Summary of Key Principles

* **Zero Personal Information Collection:** We do not collect, harvest, store, or sell personally identifiable information (such as your name, email, phone number, address, or contacts).
* **On-Device Media Processing:** All camera video streams, snapshots, and audio recordings remain strictly on your device. They are never uploaded to any external server by our application.
* **Direct Hardware Communication:** USB and OTG communication occurs directly between your mobile device and your camera hardware without cloud intermediaries.
* **Transparent Advertising:** We use trusted third-party advertising services (Google AdMob) that may process anonymous device identifiers and diagnostic data to deliver advertisements.

---

## 3. Information We Collect and Process

### A. Information You Do NOT Provide to Us
The Application does not require account creation, registration, or login. You can access and utilize all features of the Application without submitting any personal data.

### B. Device Permissions & Sensitive Data Usage
To perform its core functions as an inspection camera viewer and recorder, the Application requests specific system permissions. Here is how each permission is used:

| Permission | Purpose & Scope | Data Handling |
| :--- | :--- | :--- |
| **Camera** (`android.permission.CAMERA`) | Allows the app to initialize video streams from connected USB UVC inspection cameras and built-in cameras. | Frames are rendered directly to your screen in real time. No images are transmitted to external servers. |
| **Microphone / Audio** (`android.permission.RECORD_AUDIO`) | Allows the app to capture audio commentary when you record video inspections. | Audio is encoded directly into the local video file on your device. Never transmitted externally. |
| **Storage & Photos/Videos** (`READ_MEDIA_IMAGES`, `READ_MEDIA_VIDEO`, `WRITE_EXTERNAL_STORAGE`, `READ_EXTERNAL_STORAGE`) | Required to save captured photos and video inspections to your device's gallery and display them in the app's Media Vault. | All media is saved locally on your device in standard media folders (e.g., `Pictures/` and `Movies/`). |
| **Foreground Service & Camera** (`FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_CAMERA`) | Ensures continuous, stable video recording when navigating between screens or during extended inspection tasks without interruption by OS battery savers. | Displays an ongoing system notification during active recording sessions. Terminates immediately when recording ends. |
| **Notifications** (`POST_NOTIFICATIONS`) | Displays recording status and controls in the system notification shade while an inspection recording is actively running. | Used solely for real-time foreground service notifications. No marketing or push notifications are sent. |
| **USB Host** (`android.hardware.usb.host`) | Enables direct hardware communication with UVC-compliant USB endoscope, borescope, and webcam devices via OTG. | Communication stays entirely within the device’s local USB subsystem. |
| **Internet Access** (`INTERNET`, `ACCESS_NETWORK_STATE`) | Required to serve advertisements (via Google AdMob) and receive remote configuration values (via Firebase Realtime Database). | Used strictly by third-party advertising SDKs. |

---

## 4. Third-Party Services and Advertising

The Application integrates third-party software development kits (SDKs) to support advertising and remote configuration:

### A. Google AdMob (Google LLC)
We use Google AdMob to display advertisements (banner, interstitial, native, and app-open ads). AdMob may automatically collect and process certain non-personal device data, such as:
* Mobile advertising identifiers (e.g., Google Advertising ID / GAID)
* IP address (for general approximate location, such as city/country)
* Device model, operating system version, and screen resolution
* Ad interaction events (views, clicks, and impressions)

For more information on how Google collects and uses your data, please review:
* [Google Privacy Policy](https://policies.google.com/privacy)
* [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

### B. Google User Messaging Platform (UMP) SDK
For users in the European Economic Area (EEA), United Kingdom (UK), and California, we implement the Google UMP SDK to obtain user consent for personalized advertising in compliance with GDPR, ePrivacy, and CCPA/CPRA regulations. You have the right to modify or revoke your consent preferences at any time.

### C. Firebase Realtime Database (Google LLC)
We use Firebase Realtime Database solely to fetch non-personalized remote configuration values (such as Ad unit identifiers). No user data or analytics telemetry is transmitted to our database.

---

## 5. Data Storage, Retention, and Deletion

* **Local Storage Only:** Photos and videos captured using the Application are stored exclusively in your device's internal or external storage.
* **User Control:** You maintain 100% control over your media files. You may view, share, or permanently delete any captured photo or video at any time through the in-app Media Vault or via your device's default file manager/gallery app.
* **Uninstalling the App:** If you uninstall the Application, photos and videos saved to public MediaStore directories (e.g., `Pictures/` and `Movies/`) will remain in your device gallery unless you delete them manually before uninstalling.

---

## 6. Children's Privacy (COPPA Compliance)

The Application is not directed to children under the age of 13 (or under 16 in the European Union). We do not knowingly collect personal identifiable information from children. If you are a parent or guardian and believe that your child has provided personal information through our Application, please contact us immediately so we can take appropriate corrective measures.

---

## 7. Rights Under Regional Privacy Regulations

### A. European Economic Area (EEA) and UK (GDPR)
If you reside in the EEA or UK, you have rights regarding your data under the General Data Protection Regulation (GDPR):
* Right to access any personal data processed about you.
* Right to withdraw consent for personalized advertising at any time via device settings or in-app consent dialogs.
* Right to request erasure or restriction of data processing by third-party advertising providers.

### B. California Residents (CCPA / CPRA)
If you are a California resident, you have rights under the California Consumer Privacy Act:
* Right to know what categories of personal information are collected and shared.
* Right to opt-out of the "sale" or "sharing" of personal information for cross-context behavioral advertising (which can be exercised through your device's "Opt out of Ads Personalization" setting).
* Right to non-discrimination for exercising your privacy rights.

---

## 8. Security of Your Information

We prioritize the security of your data. Because all inspection feeds and media files are stored locally on your device, their security is tied to your device's security configurations (screen lock, encryption, and installed software). We do not transmit or store your files on external cloud servers.

---

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices, legal requirements, or Application features. When we make updates, the revised policy will be posted with an updated "Last Updated" date at the top of this document. We encourage you to review this Privacy Policy periodically.
