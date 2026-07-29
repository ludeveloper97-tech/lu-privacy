# Privacy Policy for NextGenUI

Effective date: 2026-04-28

This Privacy Policy explains how NextGenUI (`com.ludev.nextgenui`) handles data.

Developer: Ludev  
Privacy contact: `ludeveloper97@gmail.com`

Before publication, replace the placeholder contact email and host this policy as a public web page.

## 1. Overview

NextGenUI is an Android launcher. A launcher needs access to information about installed apps so it can display an app drawer, search results, app icons, folders, widgets and home screen shortcuts.

NextGenUI is designed to work locally on the device. The app does not sell personal information and does not share personal information with third parties.

The app does not currently include advertising SDKs, analytics SDKs or named user accounts. A Firebase backend is used to verify Premium purchases and, if the optional weather widget is used, to request current weather without exposing the developer's weather API key in the app.

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

If the optional lockscreen HUD overlay or optional ShortLook notification HUD is enabled, notification access may also be used to show a compact notification feed or a focused hero notification overlay.

The optional lockscreen feed and ShortLook HUD may use notification information such as notification title, text preview, app label, app icon, package name, post time, clearable state and the notification's Android pending action when the user taps a notification item.

If the user dismisses a clearable notification from the lockscreen HUD, NextGenUI asks Android to cancel that notification through the notification listener service.

ShortLook uses recent notification information only to decide whether a focused alert should be displayed. It does not use charger events or generic screen-on events as notification content.

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

### 2.5.1 Premium Purchase Verification

NextGenUI uses Google Play Billing for the optional Premium unlock. To reduce purchase tampering, the app may send the Android package name, product id and Google Play purchase token to a Firebase backend operated by the developer. The backend verifies the purchase with Google Play and returns a signed entitlement token that is stored locally.

NextGenUI may also use Firebase anonymous authentication and Firebase App Check for this verification flow. The app does not store full payment card information.

### 2.5.2 Optional Weather Widget

If the user adds the optional weather widget and grants location permission, NextGenUI may use approximate device location to request current weather.

Purpose:

- Show current weather in the launcher widget.
- Avoid storing the weather API key inside the app.

The app sends approximate latitude, approximate longitude, language, Android package name and product id to a Firebase backend operated by the developer. The backend requests current weather from OpenWeather and returns only weather display data such as city, description, temperature, humidity and wind speed.

The weather widget is optional. Location permission is requested only when the user activates the widget action. The app does not request background location for this widget.

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

### 2.9 In-App Purchase

NextGenUI may offer a one-time premium unlock through Google Play Billing.

Purpose:

- Unlock premium launcher features selected by the user.
- Restore premium access on eligible devices/accounts.

Purchase processing is handled by Google Play. NextGenUI stores a local premium entitlement flag after a successful purchase or restore so the app can enable premium features.

NextGenUI does not process payment card details directly.

### 2.10 Optional Lockscreen HUD Overlay And ShortLook HUD

NextGenUI can show an optional HUD overlay while the device is locked. It can also show an optional ShortLook-style notification HUD for focused notification alerts.

Purpose:

- Display time and date in the NextGenUI HUD style.
- Display a compact notification feed if notification access is granted.
- Display a focused ShortLook hero notification if notification access is granted and the feature is enabled.
- Let the user tap the overlay to continue into Android's normal authentication flow.
- Let the user tap a notification feed item to open the related app or Android notification action when available.
- Let the user tap a ShortLook notification card to open the related app or Android notification action when available.
- Let the user dismiss clearable notifications from the overlay.
- Avoid repeatedly displaying the same ShortLook alert for the same notification.

The overlay and ShortLook HUD do not replace Android's real lockscreen security and do not bypass PIN, pattern, password or biometric authentication.

These surfaces are optional companion views. Android still controls real device authentication and final access to protected content.

## 3. Data Collection

NextGenUI stores launcher settings and layout locally on the device.

The current app uses a developer-operated Firebase backend for Premium purchase verification and optional current weather requests.

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
- The lockscreen HUD notification feed, ShortLook hero alerts, notification tap actions and notification dismissal require explicit notification access.
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

