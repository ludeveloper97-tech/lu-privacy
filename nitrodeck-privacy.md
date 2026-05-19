# NitroDeck Privacy Policy

Last updated: 2026-05-19

## Introduction

This privacy policy explains how NitroDeck handles data in the current codebase. It should be reviewed before publication and hosted at a stable public URL for Google Play submission.

NitroDeck is an independent Android launcher. It is not affiliated with, endorsed by, sponsored by, or connected to any console maker, operating system vendor, emulator project, storefront, or third-party brand. Product names, app names, app icons, and emulator names shown by the launcher belong to their respective owners and are displayed only when they are installed, selected, or configured by the user.

## Contact

- Email: `support@nitrodeck.app`

## Data Stored On Device

NitroDeck stores local preferences such as:

- language;
- display name;
- accent color;
- alarm hour and minute;
- selected console surface;
- selected application or game entry;
- recent application and game entry list;
- selected game folders;
- selected emulator preference by supported game type;
- custom icon and icon pack preferences;
- sound, haptic, notification badge, and launcher settings;
- selected local photos for the photo surface;
- premium unlock state and purchase-related local flags.

These values are stored on the user device through platform local storage.

## Installed App Catalog

On Android, NitroDeck reads launchable applications so the user can open apps from the launcher interface. This may include app names, package names, and app icons. The current code uses this information locally for app search, app launch, selected/recent entries, icon customization, and notification badge display. NitroDeck does not send the installed app catalog to a developer server.

## Local Game Library

When the user selects game folders, NitroDeck scans those folders locally to show supported game entries. The launcher may use file names, file URIs, platform type, and extracted cover artwork where available. This information is used locally to display and launch the selected game through an emulator app chosen by the user or detected on the device.

NitroDeck does not provide game files and does not upload the user's game library to a developer server in the current implementation.

## Photos And Custom Icons

The user can choose local photos for the photo surface and local image files for custom app icons. These files are used for local personalization in the launcher. NitroDeck uses user-selected files and does not request broad photo library access for this feature in the current Android build.

## Notification Badges

If enabled by the user, NitroDeck may use Android notification listener access to show app badge counts inside the launcher. This information is used locally for badge display. NitroDeck does not send notification contents or badge information to a developer server.

## Bluetooth Scan Results

When the proximity scan deck is opened, the app may scan nearby Bluetooth devices and show available device names in the interface. The Android manifest marks Bluetooth scanning as not used for location. The current code uses scan results locally and does not send Bluetooth scan results to a developer server.

## Purchases

NitroDeck uses Google Play Billing through the app store to unlock premium features. Purchase processing is handled by Google Play. NitroDeck may store the local premium entitlement state so paid features stay unlocked after restart. NitroDeck does not store full payment card information.

## External Links

The contact deck can open the user's email application. Any external app or service opened by the user is governed by that third party's terms and privacy policy.

Game launching opens emulator applications installed on the device. Those apps are governed by their own terms and privacy policies.

## Local Media

NitroDeck bundles local visual, audio, and typography assets in the application package. These assets are used locally by the interface and are not downloaded from a developer server in the current implementation.

## Sharing

NitroDeck does not sell user data. The current implementation does not share installed app catalog data, selected photos, selected files, notification badge information, Bluetooth scan results, or local game library details with a developer server.

External apps opened by the user, such as email apps, emulator apps, camera apps, file pickers, or Google Play purchase flows, may process data under their own privacy policies.

## Retention And Deletion

Local preferences remain on the device until the user changes them, clears app data, uninstalls the app, or uses an available reset/restore option. User-selected folders, photos, custom icons, icon packs, selected apps, selected games, and premium local flags can be removed by clearing app data or changing the related setting where available.

Backup files created by the user are stored locally in the app's external files area. The user can delete those files with a file manager or by clearing app data.

## Security

NitroDeck stores launcher state locally using platform storage APIs. The current implementation does not operate a custom backend and does not transmit launcher state to a developer server.

## Not Present In Current Code

The current codebase does not include:

- developer-operated accounts;
- a custom backend;
- analytics SDKs;
- advertising SDKs;
- user-generated public content.
