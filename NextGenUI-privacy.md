# Privacy Policy for NextGenUI

Effective date: 2026-04-26

This Privacy Policy explains how NextGenUI (`com.ludev.nextgenui`) handles data.

Developer: Ludev  
Privacy contact: `ludeveloper97@gmail.com`

Before publication, replace the placeholder contact email and host this policy as a public web page.

## 1. Overview

NextGenUI is an Android launcher. A launcher needs access to information about installed apps so it can display an app drawer, search results, app icons, folders, widgets and home screen shortcuts.

NextGenUI is designed to work locally on the device. The app does not sell personal information and does not share personal information with third parties.

The app does not currently include advertising SDKs, analytics SDKs, user accounts or a backend service that receives user launcher data.

## 2. Data Accessed or Used by the App

### 2.1 Installed Apps

NextGenUI accesses information about installed launchable apps.

This may include:

- App name.
- Package name.
- App icon.
- Launch activity.
- Whether the app is a system/protected app.

Purpose:

- Display the app drawer.
- Provide app search.
- Launch apps.
- Add apps to the home canvas.
- Create folders.
- Display app icons.
- Restore launcher backups.
- Remove missing apps from the layout after uninstall.

This information is processed locally on the device.

### 2.2 App Icons and Icon Packs

NextGenUI loads app icons and may detect compatible installed icon packs.

Purpose:

- Display app nodes.
- Display drawer rows.
- Apply selected icon packs.

This information is processed locally on the device.

### 2.3 Notification Badges

If the user grants Android notification access, NextGenUI may read notification-related information needed to display badge counts.

Purpose:

- Show notification badges on supported launcher items.

Notification access is optional. The user can enable or disable it in Android system settings.

If the optional lockscreen HUD overlay is enabled, notification access may also be used to show a compact notification feed on that overlay.

NextGenUI does not use notification access to sell or share notification content.

### 2.4 Device Admin for Double Tap Screen Off

If the user enables double tap to sleep, NextGenUI may request Device Admin access.

Purpose:

- Lock the screen when the user performs the configured launcher gesture.

Device Admin access is optional. It is used only for screen locking and can be disabled in Android settings.

### 2.5 Launcher Settings

NextGenUI stores launcher preferences locally.

Examples:

- Theme selection.
- Icon pack selection.
- Motion settings.
- Badge visibility setting.
- Label visibility setting.
- Neural network line visibility.
- Onboarding completion.
- Haptic feedback preference.

Purpose:

- Preserve the user’s launcher configuration.

### 2.6 Home Layout

NextGenUI stores the user’s launcher layout locally.

Examples:

- App node positions.
- Folder positions.
- Widget positions.
- Folder contents.
- Neural link curves.
- Label visibility per node.

Purpose:

- Restore the user’s customized home screen.

### 2.7 Backups

NextGenUI can create local/exportable backups.

Backups may contain:

- Launcher settings.
- Home layout.
- App node references.
- Folder definitions.
- Widget definitions.
- Theme selection.
- Icon pack selection.
- Neural network link data.

Backups are created as local files chosen or exported by the user. The app does not upload backups to a server.

The user is responsible for where exported backup files are stored or shared.

### 2.8 In-App Review

NextGenUI may use Google Play’s in-app review feature.

Purpose:

- Let users rate or review the app through Google Play.

The review prompt and store listing are handled by Google Play. NextGenUI stores only local counters used to avoid requesting reviews too frequently.

### 2.9 Optional Lockscreen HUD Overlay

NextGenUI can show an optional HUD overlay while the device is locked.

Purpose:

- Display time and date in the NextGenUI HUD style.
- Display a compact notification feed if notification access is granted.
- Let the user tap the overlay to continue into Android's normal authentication flow.

The overlay does not replace Android's real lockscreen security and does not bypass PIN, pattern, password or biometric authentication.

## 3. Data Collection

NextGenUI stores launcher settings and layout locally on the device.

The current app does not collect user data on a developer-operated server.

The current app does not transmit the user’s installed app list, launcher layout, notification data, backups or settings to the developer.

## 4. Data Sharing

NextGenUI does not sell personal information.

NextGenUI does not share personal information with third parties.

Some features rely on Android or Google Play system flows:

- Google Play in-app review.
- Android notification access settings.
- Android Device Admin settings.
- Android lockscreen/authentication flow.
- Android uninstall confirmation.
- Android file picker/export flows.

Those flows are provided by the operating system or Google Play services.

## 5. Legal Bases and User Control

Sensitive features are optional and user-controlled:

- Notification badges require explicit notification access.
- The lockscreen HUD notification feed requires explicit notification access.
- Double tap screen-off requires explicit Device Admin activation.
- Backup import/export requires user action.
- Default launcher selection is controlled by Android settings.

Users can continue using core launcher features without enabling every optional permission.

## 6. Data Retention

Local launcher data remains on the device until:

- The user clears app data.
- The user uninstalls the app.
- The user restores another backup.
- The user manually changes or removes items in the launcher.

Exported backups remain wherever the user saves them. NextGenUI cannot delete copies stored outside the app unless the user selects and manages those files through Android storage tools.

## 7. Data Deletion

Users can delete local NextGenUI data by:

- Clearing app data in Android settings.
- Uninstalling the app.
- Removing nodes, folders or widgets inside the launcher.
- Deleting exported backup files from the location where they were saved.

NextGenUI does not create user accounts, so there is no account deletion process.

## 8. Security

NextGenUI uses Android platform APIs and local storage mechanisms.

Sensitive optional access is requested through Android system screens so the user can see and control the permission.

No method of local storage is guaranteed to be perfectly secure. Users should store exported backups carefully if they consider their launcher layout or app list sensitive.

## 9. Children

NextGenUI is not specifically directed to children. The app does not knowingly collect personal information from children.

## 10. International Users

NextGenUI stores launcher data locally on the user’s device. The current app does not transfer launcher data to developer-operated servers in another country.

## 11. Changes to This Policy

This Privacy Policy may be updated when the app changes its data practices or adds new features.

If the policy changes, the effective date should be updated.

## 12. Contact

For privacy questions, contact:

`ludeveloper97@gmail.com`

## 13. Publication Notes for Google Play

Before submitting to Google Play:

- Host this policy as a public web page.
- Do not use a PDF as the primary privacy policy URL.
- Make sure the URL is accessible without login.
- Make sure the URL is not geofenced.
- Make sure the URL is not editable by public users.
- Make sure the policy contact email is real.
- Make sure Google Play Data safety answers match the production app behavior.

Official references:

- [Google Play User Data policy](https://support.google.com/googleplay/android-developer/answer/10144311)
- [Google Play Data safety section guidance](https://support.google.com/googleplay/android-developer/answer/10787469)
