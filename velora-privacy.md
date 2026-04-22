# Velora Launcher Privacy Policy

Reference date: April 22, 2026.

## Summary

Velora Launcher is an Android launcher designed to run locally on the device. Its main purpose is to show launchable apps, open them and provide a customizable home experience.

The current version does not use user accounts, remote analytics, advertising SDKs or a proprietary backend.

## Data used by the app

Velora Launcher may use these local data points:

- Installed launchable apps: app label, package name, launcher activity and icon.
- Local icon order, folders, hidden items and protected app selections.
- Visual preferences such as icon size, spacing, opacity, background color, background image and icon style.
- Local onboarding status.
- Notification counts per app if the user voluntarily enables notification access.
- Local premium unlock state tied to the device installation.
- Local backup and restore files when the user exports or imports a layout.

## In-app purchase

Velora Launcher can offer a one-time non-consumable premium unlock through Google Play Billing. The billing transaction itself is handled by Google Play.

Velora Launcher does not store card data, bank data or full payment credentials. The app only stores the local state needed to remember that premium features were unlocked on this installation.

## In-app review

After a successful premium unlock, Velora Launcher may ask Google Play to show the official in-app review prompt if the platform allows it. This flow is controlled by Google Play and may or may not be shown depending on platform quotas and eligibility.

Velora Launcher does not collect or process the rating text directly.

## Notification badges

Notification access is optional. If enabled by the user in Android settings, Velora Launcher uses it only to count active notifications per app and show badges.

Notification content is not used for advertising, profiling or analytics.

## Background image

If the user chooses a background image, Android's system picker is used. Velora Launcher stores only the local reference needed to display that image in the launcher.

## Double-tap lock

The double-tap lock feature is optional. If enabled, Android device admin access is used only for the screen lock policy needed to call `lockNow`.

Velora Launcher does not use this access to silently block uninstall, apply enterprise policies or monitor user activity.

## Protected apps

Velora Launcher can require biometrics or the device credential before opening selected apps from inside the launcher. This verification is performed locally through the operating system.

Velora Launcher does not store fingerprints, face data, PINs, patterns or passwords. It only stores which apps are marked as protected.

## Uninstall action

When the user chooses to uninstall an app from Velora Launcher, the app opens Android's official uninstall confirmation flow. Apps are never removed silently.

## Backup and restore

Velora Launcher can export and import a local JSON file containing icon order, folders, visibility choices, protected apps and visual settings.

The app does not require broad storage access for this feature.

## Data sharing

Velora Launcher does not sell personal data and does not share launcher data with third parties in the current version.

## Storage

Preferences are stored locally in the app's private storage. If the app is uninstalled or its data is cleared, those local preferences can be lost.

## Future changes

If future versions add cloud sync, accounts, analytics or remote services, this policy should be updated before release.

## Contact

Provisional project owner: Ludev.

ludeveloper97@gmail.com

