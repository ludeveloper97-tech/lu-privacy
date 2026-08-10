# Cupertino Privacy Policy

**Effective date: August 3, 2026**

This policy explains how **Cupertino** (`com.ludev.cupertino`) handles
information while operating as an Android launcher. Developer contact:
[ludeveloper97@gmail.com](mailto:ludeveloper97@gmail.com).

## Summary

Cupertino is designed to perform most processing on the device. It includes no
developer-operated advertising, analytics, or account server. We do not sell
personal information.

Some optional features require Android permissions or a connection to an
external service. You choose whether to use them and may revoke permissions in
Android Settings.

## Information processed locally

Depending on enabled features, the app may process:

- launcher profile names, avatars, preferences, and configuration;
- salted password hashes for profiles, never plain-text passwords;
- the biometric success or failure returned by Android, never fingerprint or
  face templates;
- installed apps, icons, usage time, and app launches;
- titles, text, icons, and timestamps of visible notifications;
- files, folders, photos, videos, audio, PDFs, and Trash items used by Finder,
  Preview, wallpapers, Camera, or backups;
- calendars and events when access is granted;
- network, Wi-Fi, battery, brightness, and media playback status;
- launcher Terminal commands and local history.

This information is used to display and perform requested features. It is not
sent to the developer.

## Artificial intelligence assistant

If you configure and use Gemini, Cupertino sends the prompt, interface language,
up to five contextual turns, and any attachment you select to the Google Gemini
API. Requests use HTTPS and ask for `store: false`. By default, an authenticated
Firebase Function handles the request with a credential stored in Secret Manager
and applies limits per anonymous identity. If you configure a personal API key,
it is encrypted on device and used in BYOK mode.

Google processes this data under its own terms and privacy policy. Do not submit
sensitive information you do not want to share with that provider.

If you unlock ChatGPT through a Google Play subscription, the prompt, language,
up to five contextual turns, and the attachment you select are sent to OpenAI.
An authenticated Firebase Function processes the HTTPS request with `store:
false`. The OpenAI key remains in Secret Manager and is not included in the app.

To validate access, the app sends the product identifier and Google Play
purchase token to the backend. Only a token hash, entitlement state, and expiry
are retained; Cupertino does not receive or store card or payment details.

## Web apps

Embedded web apps only allow HTTPS addresses. A visited website may receive the
information normally associated with a web connection and may apply its own
privacy, cookie, and sign-in policies. Cupertino does not control those services.
The last URL is retained only when it belongs to the configured host.

## Permissions and special access

Cupertino may request camera, microphone, notifications, biometrics, calendar,
media, and file access. Finder may request all-files access; Screen Time may
request usage access; and Notification Center may request notification access.
Android displays consent screens for sensitive access.

You may revoke permissions at any time. The related feature may stop working,
while the rest of the launcher remains available whenever technically possible.

## Storage, security, and backups

Preferences and credentials are encrypted with AES-256-GCM using a non-exportable
Android Keystore key. Profile passwords use salted PBKDF2-HMAC-SHA256 derivation.
Android cloud backup is disabled.

Manual Time Machine backups are encrypted with AES-256-GCM and a recovery
password chosen by you. API keys are excluded from the archive. You control the
backup destination and deletion. No system is infallible; protect your device and
keep recovery passwords in a secure place.

## Retention and deletion

Data remains on the device while the profile or app exists. You can delete
profiles, histories, files, and backups through their features, revoke permissions,
or clear all app data in Android Settings. Uninstalling Cupertino removes its
private storage but does not automatically delete files or backups that you saved
outside it.

## Sharing and sale

We do not sell personal information or share it with advertisers. Data is
transferred to a third party only when you explicitly use Gemini, a web app, or
Android's sharing function, as described above.

## Children

Cupertino is not specifically directed to children and does not knowingly seek
their personal information. A parent or guardian may contact us if they believe a
child has submitted personal information.

## Changes

We may update this policy when features, permissions, or legal requirements
change. The revised policy will show its effective date and be published at the
same address linked from Google Play.

## Contact

For applicable privacy requests, questions, or reports, contact
[ludeveloper97@gmail.com](mailto:ludeveloper97@gmail.com).

Before release, host this text at a stable public HTTPS URL that is accessible
without sign-in or geographic restriction.
