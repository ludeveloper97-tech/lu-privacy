# BlueTwo Privacy Policy

Effective date: 2026-09-04

BlueTwo is an Android launcher designed to provide a nostalgic, fullscreen launcher experience using original assets, local device features, and user-selected content.

BlueTwo does not sell personal data. BlueTwo does not include advertising SDKs, tracking SDKs, or analytics SDKs.

Some features can transmit limited data off the device when the user uses online or premium functionality. This policy explains what is processed locally, what may be sent off device, and why.

## Data Stored Locally

BlueTwo stores launcher preferences on the device, including selected language, visual preferences, animation settings, sound and haptic settings, app volume, nostalgia mode, notification badge preference, selected console mode, selected icon pack, preferred emulator, memory unit configuration, selected app package names, custom launcher icons, locally selected game folder URIs, and recently launched app information used for the disc-style shortcut.

This data is stored locally using Android app storage and Flutter shared preferences. It is not sold, used for advertising, or used to build tracking profiles.

## Installed Apps

BlueTwo can read launchable apps installed on the device so it can display them inside the launcher, memory units, search, Android TV mode, and app selection screens.

Installed app information is used locally to render shortcuts, launch apps, open Android app information screens, and detect compatible external emulators. BlueTwo does not upload the installed app list to BlueTwo servers.

## Notification Access

Notification badges are optional. If the user enables this feature, Android may ask for notification listener access.

When enabled, BlueTwo uses notification information locally to show per-app badge counts in the launcher. Notification content is not uploaded, sold, shared, or used for analytics.

## Local Files, Classic Games, and Custom Icons

When the user creates a classic game memory unit, BlueTwo may ask the user to select a local folder. The app scans only the folder selected by the user to find compatible local files and optional cover/icon images.

BlueTwo may read file names, folder metadata, game image headers, sidecar cover images, and save-data icon assets inside the selected folder so it can display the memory unit and launch the selected local file through a compatible external emulator.

Custom images, icon packs, save-data ZIP files, 3D icon objects, textures, and animations selected by the user are processed locally. They are copied or cached inside app storage only for launcher display and are not uploaded.

BlueTwo does not provide games, emulator cores, BIOS files, ROMs, ISOs, copyrighted media, or third-party console assets. Users are responsible for using files they are legally allowed to use.

## Optional Online Cover Lookup

If the user enables online game cover lookup, BlueTwo may send a search query derived from a local game entry, such as a game title or disc identifier, to an external cover database in order to find cover art.

This feature is optional and is used only to display covers for the user's local game entries. BlueTwo does not use this lookup for advertising, analytics, or tracking.

## In-App Purchase and Premium Verification

BlueTwo uses Google Play Billing through Flutter's in-app purchase plugin for the Google Play version. Google Play handles payment methods, billing account data, purchase UI, receipts, refunds, and payment processing.

BlueTwo receives purchase state information needed to unlock premium features. To verify purchases, BlueTwo uses Firebase anonymous authentication, Firebase App Check, Cloud Functions, and a backend entitlement verification call.

During purchase verification or restore, limited technical and purchase-related data may be transmitted, including purchase token, product ID, package name, Firebase anonymous user ID, Firebase app/device integrity signals, Firebase app identifiers, IP address, user agent information, and function request metadata.

After verification succeeds, BlueTwo stores a signed entitlement token locally on the device. BlueTwo does not receive or store credit card numbers or payment credentials.

Some non-Google Play distributions may use Stripe PaymentSheet instead of Google Play Billing. In those builds, Stripe handles payment entry and processing, while BlueTwo verifies the resulting entitlement through the same backend flow.

## In-App Review

BlueTwo may request a Google Play in-app review after a positive local action. The review prompt, eligibility, rating submission, and any review text are handled by Google Play.

BlueTwo stores only local counters and timestamps used to decide whether asking for a review is appropriate. BlueTwo does not receive or store the user's rating.

## Third-Party Services and SDKs

BlueTwo may use the following services depending on build flavor and enabled features:

- Google Play Billing, for in-app purchases.
- Google Play In-App Review, for optional review prompts.
- Firebase Authentication, for anonymous premium entitlement verification.
- Firebase App Check and Play Integrity, for backend abuse prevention.
- Firebase Cloud Functions, for premium verification and entitlement requests.
- Stripe, only in builds that use Stripe payments.
- External cover database requests, only when online cover lookup is enabled.

These services may process data according to their own privacy terms and SDK behavior. BlueTwo uses them for app functionality, purchase verification, fraud prevention, security, and compliance.

## Security

Data transmitted for online cover lookup, premium verification, payment-related flows, and Firebase services is sent over HTTPS/TLS where supported by the service.

Local launcher preferences remain in app storage. Android may remove this local data when the app is uninstalled or when the user clears app data.

## Data Deletion

Most BlueTwo launcher data is stored locally. Users can delete local launcher data by clearing BlueTwo app storage in Android settings or uninstalling the app.

Premium entitlement records associated with backend verification may be linked to an anonymous Firebase user ID. Users can contact the developer support email listed in Google Play to request assistance with deletion or entitlement data questions.

## Children

BlueTwo is not directed at children and does not knowingly collect personal data from children.

## Changes

This policy may be updated when BlueTwo adds, removes, or changes functionality. The policy should remain consistent with the app's Google Play Data safety declaration and the actual SDKs included in the app.

## Contact

Before publishing, replace this line with the developer support email configured in Google Play Console.
