This Privacy Policy describes how **Stud Finder – Wall Scanner** ("we", "our", or "the App") collects, uses, and discloses information when you download, install, and use our mobile application.

We take your privacy seriously. The App is engineered as a local hardware utility tool designed to operate with minimal data processing.

---

## 1. Information We Collect

### A. Personal Information
We **do not collect, store, or transmit any Personally Identifiable Information (PII)**. You can use all core features of the App without registering an account, providing your name, email address, phone number, location, or contacts.

### B. Device Sensor Data (Magnetometer)
* **What we access:** The App accesses your device's built-in 3-axis magnetic hardware sensor (`android.hardware.sensor.compass`).
* **Why we access it:** To detect magnetic flux density fluctuations (measured in microTeslas, $\mu\text{T}$) caused by ferrous metals, drywall screws, framing clips, electrical conduits, and wall studs.
* **How it is processed:** All magnetic calculations and digital filtering are performed **strictly in-memory on your local device in real time**. 
* **Zero Storage / Zero Transmission:** Sensor readings are never recorded, logged to disk, or transmitted to any external server or cloud service.

---

## 2. Device Permissions Used

The App requests the following Android permissions strictly to fulfill its utility functions:

| Permission | Technical Name | Purpose |
| :--- | :--- | :--- |
| **Magnetometer Access** | `android.hardware.sensor.compass` | Measures magnetic field strength to detect wall studs and metal objects. |
| **Vibrate** | `android.permission.VIBRATE` | Provides haptic alert pulses when a target or stud is centered/detected. |
| **Internet Access** | `android.permission.INTERNET` | Required by third-party ad networks (Google AdMob) and crash diagnostics (Firebase). |
| **Network State** | `android.permission.ACCESS_NETWORK_STATE` | Checks network connectivity to optimize ad loading. |
| **Keep Screen Awake** | `android.permission.WAKE_LOCK` | Optional user toggle to prevent the screen from dimming while scanning walls. |

---

## 3. Third-Party Services and Analytics

To support ongoing development and keep the App free to use, we integrate third-party software development kits (SDKs). These third parties may collect anonymous, non-personally identifiable diagnostic and advertising data:

### A. Google AdMob (Google LLC)
* We use Google AdMob to display banner, interstitial, and native advertisements.
* **Information Processed:** AdMob may collect and process device identifiers (such as the Google Advertising ID / AAID), coarse IP address, device model, carrier, and interaction data to serve contextual or personalized ads and detect ad fraud.
* **Privacy Policy:** [Google Privacy Policy](https://policies.google.com/privacy)
* **Ad Personalization Controls:** [Google Technologies Ads](https://policies.google.com/technologies/ads)

### B. Google Firebase Crashlytics & Analytics (Google LLC)
* We use Firebase Crashlytics to monitor application stability and debug crashes.
* **Information Processed:** Crash stack traces, device state information, operating system version, and general non-personalized performance metrics.
* **Privacy Policy:** [Firebase Privacy and Security](https://firebase.google.com/support/privacy)

---

## 4. User Rights and Choices (GDPR & CCPA/CPRA)

### A. Ad Personalization and Advertising ID
You have full control over the advertising identifier used by Google AdMob on Android:
* Open your device **Settings**.
* Navigate to **Google** $\rightarrow$ **Ads**.
* Tap **"Reset advertising ID"** or **"Delete advertising ID"** to opt out of interest-based ad tracking.

### B. Offline Functionality
The core magnetic stud detection features function entirely offline without internet connectivity.

---

## 5. Children's Privacy (COPPA)

Our App is a home improvement and DIY hardware utility. It is not directed at children under the age of 13. We do not knowingly collect personal information from children under 13. If you believe a child has provided us with personal information through a third-party SDK, please contact us so we can investigate and remove the data.

---

## 6. Data Security and Retention

Because we do not collect or store your personal data on any server, there is no risk of your personal information being breached from our databases. Any temporary diagnostics processed by third-party services (such as Google AdMob or Firebase) are handled according to Google's standard security and retention protocols.

---

## 7. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices or applicable legal regulations. Any updates will be posted with an updated "Effective Date" at the top of this policy and accessible directly inside the App settings.
