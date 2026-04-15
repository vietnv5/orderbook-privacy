
# Privacy Policy for Sổ Đơn

**Last updated:** 2026-04-15

## Introduction

Sổ Đơn ("we", "our", or "us") respects your privacy.

This application is designed to work **offline-first** with optional cloud features.
We do **not collect, track, analyze, or sell personal data**.

---

## Data Collection

Sổ Đơn **does not collect or send personal information** to the developer.

All data entered by users, including:

* Orders
* Products
* Customers
* Images added to orders or products

is stored **locally on the user's device**, unless the user explicitly chooses to use backup or online sync features.

---

## Text Input Features

The app provides tools to help you quickly enter order information by analyzing text you paste from other sources (such as Facebook comments, messages, etc.).

- All text analysis is performed **locally on your device**
- The app does not connect to external services for text processing
- You can review and edit all analyzed information before saving

---

## Voice Input

Sổ Đơn may provide an **optional voice input feature** that allows users to create or edit orders using speech.

* The microphone is used **only when the user explicitly activates voice input**
* Audio is processed by the device’s **speech recognition service** to convert speech into text
* The app does **not record, store, or transmit audio recordings to the developer**
* Only the recognized text is used within the app to assist with order creation

Voice input is entirely **user-initiated** and can be stopped at any time.

---

## Backup & Restore

Sổ Đơn provides **manual backup and restore features**, including **local backup** and **Google Drive backup**.

### Local Backup & Restore

* Backup files are created **only when the user explicitly requests**
* Backup files are stored locally on the device or in a user-selected location
* All local backup and restore operations are performed entirely on the user’s device
* The app does not automatically upload local backup files

### Google Drive Backup & Restore

Sổ Đơn also provides an **optional backup and restore feature using Google Drive**.

* Google Drive backup and restore are performed **only when the user explicitly initiates the action**

* Backup data is stored **only in the user’s Google Drive App Data folder**

* The app uses the Google Drive API scope:

  `https://www.googleapis.com/auth/drive.appdata`

* The app can access **only its own app data folder** and cannot access other files in the user’s Google Drive

* Backup data is **not visible to the developer**

* Sổ Đơn does **not store any user data on its own servers**

---

## Online Sync (Firestore)

Sổ Đơn provides an **optional online sync feature** using **Google Firestore**.

* Online sync runs **only when the user explicitly enables sync**
* When Online mode is enabled, the app syncs data (such as orders, products, customers, and related metadata) to Firebase Firestore
* Synced data can be managed online by the user through the web platform: [https://sodon-vsoft.vercel.app/](https://sodon-vsoft.vercel.app/)
* Access to online management requires the user to sign in with a Google account
* Synced data is stored in cloud infrastructure provided by Google Firebase (Firestore), under the user account/context configured in the app and web platform
* The developer does not use synced data for analytics, advertising, or data selling
* Users can disable online sync at any time and continue using the app offline

---

## Google Sign-In

Google Sign-In is used **for authentication purposes** to:

* Enable online sync and web access for managing synchronized data
* Enable access to Google Drive App Data for backup and restore (when used)

* No personal information is collected or stored by the app
* Authentication is handled securely by Google
* The developer does not receive or store Google account information

---

## Permissions

The app may request the following permissions to support core features:

### Camera

Used only to allow users to take photos (e.g. product or order images).
Photos are stored locally on the device and are **not uploaded or shared**, unless the user explicitly includes them in a backup.

### Photos / Media / Storage Access

Used only to:

* Select images from the device gallery
* Save app data locally
* Export or import backup files (local or Google Drive, when initiated by the user)

### Microphone

Used only when the user chooses to create or edit orders using **voice input**.

Audio is processed by the device’s speech recognition service to convert speech into text.
The app does **not record, store, or transmit audio recordings**.

All permissions are **optional** and are used **only when the user explicitly performs related actions**.

---

## External Links

The app may open external applications such as web browsers or email clients
when the user chooses to contact support or view related information.

No data is shared automatically with external services.

---

## Third-party Services

Sổ Đơn uses third-party services only to provide user-requested features:

* **Google Drive API** for optional backup and restore
* **Google Firebase Firestore** for optional online sync
* **Google Sign-In / Google Authentication** for secure login
* **Sổ Đơn web platform** at [https://sodon-vsoft.vercel.app/](https://sodon-vsoft.vercel.app/) for online data management

* Data is transferred only when the user initiates backup/restore or enables sync
* No data is shared for advertising purposes or sold to third parties
* The app does **not use**:

  * Analytics services
  * Advertising networks
  * Tracking SDKs

Google service usage follows Google’s Privacy Policy.

---

## Children’s Privacy

Sổ Đơn is **not specifically designed for children under the age of 13**
and does not knowingly collect personal data from children.

---

## Data Security

All data is stored locally on the user's device and, when enabled by the user, may also be stored in Google services (Google Drive App Data and/or Firebase Firestore).
Users who enable online sync may also access and manage synchronized data through the Sổ Đơn web platform.

The developer does not access user data for profiling, analytics, or advertising.
Users are responsible for protecting access to their devices and Google accounts.

---

## Changes to This Policy

We may update this Privacy Policy from time to time.
Any changes will be posted on this page with an updated revision date.

---

## Contact

If you have any questions about this Privacy Policy, please contact:

**Email:** [vsoft102@gmail.com](mailto:vsoft102@gmail.com)

