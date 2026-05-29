# Privacy Policy

Last updated: May 29, 2026

## 1. Data controller

This Privacy Policy describes how information is accessed, used, stored, and shared in connection with the `N3D Launcher` app (Android package `com.ludev.threedlauncherm`) in its Google Play version.

Data controller:

- Email: [ludeveloper97@gmail.com](mailto:ludeveloper97@gmail.com)

If you publish the app under another entity or email address, replace these details before submitting the app to Google Play.

## 2. Scope

This policy covers:

- data the app accesses on the device;
- data the app stores locally;
- data the app may transmit outside the device;
- permissions requested by the current Google Play version;
- data retention and deletion.

## 3. Privacy Summary

The current Google Play version mainly works as an Android launcher and personalization experience. Most information used by the app is processed locally on the user's device.

The reviewed `play` build:

- includes notification badges as an optional feature, disabled by default, which requires the user to first enable the setting inside the app and then grant Android's special notification access;
- does not use pedometer data or internal coins;
- may use Nearby/Bluetooth for nearby avatar profile exchange if the user enables Nearby;
- does not use a `ForegroundService`, persistent notification, or local/mDNS fallback in the `play` version;
- does not use Firebase or a proprietary backend;
- does not use broad storage access;
- offers an optional one-time purchase managed by Google Play to unlock advanced personalization;
- may access contacts if the user grants permission when opening `Friends List`;
- may manage a local library of compatible files chosen by the user through the system file picker.

The app is not designed to sell personal data or use personal data for advertising purposes.

## 4. Data Accessed or Processed Locally

### 4.1 Installed Apps and Basic Metadata

The app may read information about launchable installed apps in order to:

- display them in the launcher;
- allow search and launch;
- organize them into folders;
- set default shortcuts in launcher modules.

Data processed locally may include:

- app name;
- Android package name;
- icon;
- version;
- installation date.

### 4.2 Camera and Visual Content

If the user grants camera permission, the app may:

- use the camera inside the corresponding module;
- capture images inside the app;
- allow the user to use selected images for personalization features.

In the reviewed Google Play version, video recording with audio is disabled and the app does not request microphone permission.

### 4.3 Contacts

If the user grants contacts permission when opening `Friends List`, the app may locally read contacts from the device in order to:

- display the friends list inside the launcher;
- search contacts by name;
- display name, phone number, and local thumbnail when provided by the system;
- start a phone call or open WhatsApp with the number chosen by the user;
- allow creating a contact from the friends screen.

Contacts are processed locally on the device. The current build does not use Firebase or a proprietary backend to upload contacts to a server.

The app shows an explanation before requesting contacts permission:

```text
N3D Launcher uses your contacts only to show the friends list and allow calls or opening WhatsApp from this screen. Contacts are not uploaded to any server.
```

### 4.4 Files Selected by the User

The app may access files voluntarily chosen by the user through the system file picker in order to:

- import images or animations;
- configure custom backgrounds;
- import compatible files for the local library.

The app does not request `MANAGE_EXTERNAL_STORAGE` or broad storage access.

### 4.5 Local Library of Compatible Files

The app may allow the user to select compatible files, such as `.3ds`, `.cia`, `.3dz`, `.nds`, `.dsi`, `.gba`, `.gbc`, or `.gb`, to display them in a local library inside the launcher.

When the user imports one of these files, the app may locally process:

- file name;
- file path selected by the user;
- internal content identifier when available;
- embedded thumbnail when exposed by the file format;
- approximate platform based on file extension;
- preferred emulator chosen by the user.

The extracted thumbnail is stored locally in the app's internal storage so it can be displayed again inside the library. If no valid thumbnail is available, the app displays a local generic placeholder.

### 4.6 Preferences, Backgrounds, and Local Content

The app may locally store information such as:

- themes and gradients;
- custom backgrounds;
- folders and grid configuration;
- drawn notes;
- usage logs inside the app;
- local protection state for selected access points.

### 4.7 Local Device Authentication

The app may use device authentication, such as biometrics or secure lock screen authentication, to protect access to selected apps or folders inside the launcher.

The app does not receive or store the user's biometric fingerprint. It only receives the authentication result from Android.

### 4.8 Google Play In-App Purchases

The `play` version may offer an optional one-time purchase to unlock premium personalization features, icon packs, and advanced local library features.

When the user starts a purchase, the transaction is handled by Google Play Billing. The app may receive and locally process technical information needed to unlock the content, such as:

- purchased product identifier;
- purchase or restoration status;
- transaction identifier when provided by Google Play.

The app does not directly process payment card data or payment credentials on its own servers.

### 4.9 Nearby / Nearby Profile Exchange

If the user enables Nearby, the `play` version may use Google Nearby Connections to detect other nearby devices that also have N3D Launcher open and Nearby enabled.

The app may exchange a basic avatar profile that may include:

- local technical device identifier;
- username/avatar name;
- short phrase;
- selected nationality;
- last visible module/app when applicable;
- limited-size icon/avatar when available.

Received profiles are stored locally in the app's plaza. The `play` version does not use a proprietary server for this feature, does not use Firebase, and does not keep Nearby active through a `ForegroundService`. The feature may stop searching if the app goes to the background or the device is locked.

### 4.10 Notification Badges

The app may offer an optional feature to show notification counters on launcher icons.

This feature:

- is disabled by default;
- requires the user to manually enable it from the launcher settings;
- requires the user to grant Android's special notification access from system settings;
- may locally read which apps have active notifications in order to calculate a counter per app;
- does not need to read or display message content to work;
- is used only to update visual badges inside the launcher.

Counters are processed locally on the device. The app does not send notifications, message texts, senders, or badge counters to a proprietary server, and does not use them for advertising, analytics, automation, or remote control.

The user can disable this feature from the launcher settings and can also revoke notification access from Android settings at any time.

## 5. Data That May Be Transmitted Outside the Device

According to the current review of the `play` flavor, the app does not use Firebase and is not designed to transmit personal data to a proprietary backend as part of its main flow.

However:

- the app may open websites, email, or other external apps when the user chooses to do so;
- the optional premium purchase is handled by Google Play;
- if the user enables Nearby, a basic avatar profile may be exchanged directly with other nearby devices through Google Nearby Connections;
- if the user enables notification badges, notification data is processed locally and is not transmitted to a proprietary server;
- if remote features are re-enabled in a future version, this policy must be updated before publishing that build.

## 6. Purposes of Processing

The app processes data to:

- provide a functional home screen/launcher;
- display, organize, and launch installed apps;
- allow visual personalization of the launcher;
- show the friends list from local contacts if the user grants permission;
- manage a local library of compatible files selected by the user;
- protect local access points through device authentication;
- save preferences and user-created content;
- allow optional nearby avatar profile exchange when the user enables Nearby;
- show optional notification badges on launcher icons when the user enables the feature and grants Android's special notification access;
- check the status of an optional premium purchase made through Google Play.

## 7. Legal Basis

Depending on the feature used, processing may be based on:

- performance of the functionality requested by the user;
- the user's consent when enabling optional permissions or features;
- performance of an optional purchase requested by the user through Google Play;
- the controller's legitimate interest in operating and maintaining the app within applicable legal limits;
- compliance with legal obligations, where applicable.

## 8. Data Sharing

According to the current review of the `play` build, the app is not designed to share personal data with third parties through a proprietary backend.

The app may interact with third parties only when requested by the user, for example:

- Google Play, for an optional in-app purchase;
- external apps or external links opened by the user, such as phone or WhatsApp when opened from `Friends List`;
- other nearby devices that have N3D Launcher open and Nearby enabled, only to exchange the basic avatar profile described above.

Data used for notification badges is not shared with third parties by the app or with a proprietary backend.

## 9. Data Retention

### 9.1 Local Data

Data stored on the device is normally retained until:

- the user deletes it from within the app;
- the user clears the app data from Android settings;
- the user uninstalls the app.

### 9.2 Purchase Data

The app may keep minimal local state for user experience, but in the `play` flavor the premium entitlement is synchronized again with Google Play and is not considered valid based only on local storage.

## 10. Data Deletion

The user can:

- uninstall the app;
- clear the app data from Android settings;
- delete local content using available features;
- request additional information by contacting [ludeveloper97@gmail.com](mailto:ludeveloper97@gmail.com).

## 11. Security

The app applies reasonable technical measures appropriate to the nature of the product and the local storage it uses. However, no transmission or storage system is completely infallible.

## 12. Children

The app is not specifically directed at children unless the published store listing and final configuration state otherwise. If a parent or guardian believes that a child has provided data contrary to expectations, they may contact the controller to request review or deletion where possible.

## 13. Third-Party Links and Services

The app may open websites, social networks, emails, or external apps. When the user uses those links or services, data processing is governed by the corresponding third party's policies.

For in-app purchases, Google Play terms and policies also apply.

## 14. Changes to This Policy

This Privacy Policy may be updated to reflect legal, technical, or functional changes. The current version will be the one published at the official URL associated with the app and, where applicable, also inside the app.

## 15. Contact

For questions about privacy, access, rectification, deletion, or data use, you can contact:

- Email: [ludeveloper97@gmail.com](mailto:ludeveloper97@gmail.com)
