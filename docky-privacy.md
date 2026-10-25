# Docky Privacy Policy

Last reviewed: 2026-10-25 — Docky 1.1.11 (27)

Developer: LuDev / Docky. Contact: ludeveloper97@gmail.com.



## Scope

Docky is an Android launcher with local features and online services, including NearbyVerse, Mii rendering and Docky Plus purchases. Using an online feature sends information to its service providers. A pseudonymous community identity or anonymous Firebase account is still an identifier; it does not mean that no user data is processed.

This policy applies to Docky distributed through Google Play (`com.ludev.docky`). Docky Plus purchases use Google Play Billing.

## Information stored on the device

The Android app inventory is used locally to display, search, group and launch apps. Docky does not upload that inventory as part of these launcher functions.

Launcher slots, groups, settings, icon-pack selection, interface preferences, local profile information, recent play activity, selected backgrounds, imported images and saved Mii designs are stored on the device. NearbyVerse also keeps local drafts and saved content. This local storage is distinct from information submitted to online features.

Images are selected through user-initiated pickers. The community image picker uploads an image only when it is included in a submitted post or profile. Selecting a local background does not itself publish it to NearbyVerse.

Backups are exported at the user's request and may contain settings, app package names, local profile names, groups, recent activity and selected images. Docky does not automatically upload these backup files. Users control exported copies and any sharing of them.

## NearbyVerse community

NearbyVerse connects to community services at `www.mrrubik.com`. Community access can create a pseudonymous identity with a recovery key, even without an email address. The identity is used to associate requests, content and account recovery. Keep recovery keys private.

When creating or editing a community profile, Docky sends the chosen name, biography, age group, acceptance of terms, and an indication of guardian approval where applicable. If a saved Mii is selected, its appearance data, portrait and expression image are sent too. The guardian PIN, exact birth date and guardian contact details are not included in these profile requests.

Submitting community content sends its text and any selected image or drawing, together with relevant community, language, mood, tag, spoiler status, reply reference or journal game title. Reactions, blocking, reports and notification-read actions also send the identifiers and action details needed to perform them. Reports include the explanation entered by the user.

Profile presentation and published content are intended to be visible to other community users. Do not include information you do not want to publish. Moderation reports are submitted to the service for review; they are not ordinary public posts.

The purposes are to provide community accounts, publishing, interaction, recovery, notifications and moderation. Community identity is separate from the Firebase identity used for purchases.

## Notifications

If community notifications are enabled, the current Android implementation periodically contacts the community server in the background using the community identity and a notification cursor. It displays the resulting notifications locally. This implementation does not use an FCM registration token. Disabling notifications stops this background scheduling; opening the community still makes normal service requests.

## Mii rendering and other online resources

Generating Mii previews sends character/render parameters to a remote renderer. The distribution build without private overrides uses `mii-unsecure.ariankordi.net` over HTTPS for the editor; community portrait rendering is configured to use the renderer at `www.mrrubik.com`. A test or custom build may configure a different renderer. Rendering a character and publishing that character to a community profile are separate operations.

Online game artwork retrieval requests game titles/platform information or matching artwork paths from Libretro thumbnails and TheGamesDB. These requests do not upload ROM contents. Service operators receive the network information needed to answer requests, including the connecting IP address. Their actual access-log and cache retention must be confirmed before making retention claims.

## Accounts and purchases

Docky uses Firebase Authentication, Firebase App Check and backend entitlement verification for Docky Plus. Entitlement checks can occur on startup, not just when a purchase is made. They can create an anonymous Firebase identity and transmit authentication/attestation information, the Docky package and product identifier. Purchase verification also transmits the purchase token. A signed entitlement token is cached locally.

Google Play Billing handles payment processing for Docky Plus. Docky's purchase backend verifies the purchase and entitlement status. The launcher does not store payment card numbers in its local settings.

Providers also process technical information associated with service requests. For Firebase's SDK disclosures, see [Firebase Android data disclosure](https://firebase.google.com/docs/android/play-data-disclosure). The scope of SDK processing depends on the enabled products and release configuration.

## Recipients and security

Recipients include the community hosting service, the configured Mii renderer, artwork providers, Google/Firebase for authentication and purchase verification, and Google Play for payment processing. Public community content is also available to community users. A transfer needed to provide a feature is still a data flow that must be disclosed.

The community, renderer and purchase endpoints reviewed use HTTPS. This is transport encryption, not end-to-end encryption of posts or a guarantee about all downstream storage. No advertising or analytics SDK was identified in the reviewed app dependencies; this does not imply that providers keep no operational logs. No data-sale functionality was identified in the client.

## Deletion, retention and contact

Clearing Android app storage or uninstalling Docky removes app-local data, but does not delete published content, remote accounts or exported backups.

NearbyVerse includes actions to delete owned posts and request deletion of the community profile. These actions require a successful server request. The client alone cannot establish whether all associated records, shared Community Shop identity, logs, backups and caches are deleted, or the time this takes.

For privacy questions or deletion requests, contact ludeveloper97@gmail.com. Do not send passwords, full payment-card details or recovery keys by email. The operator must verify the request through an appropriate process.



## Changes

Update the published policy, the in-app policy and the applicable store declarations whenever these data flows change.
