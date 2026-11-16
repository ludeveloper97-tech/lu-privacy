# ShortLook Privacy Policy

Last updated: 2026-11-15

ShortLook shows brief, private notification previews on Android devices. It is
designed so notification content is processed locally on the device.

## Data Collection

Notification content stays on your device. ShortLook does not sell data or use
data for advertising. No manual account registration is required. The Google Play
purchase build creates an anonymous Firebase identity to verify Pro access and
prevent purchase fraud; technical identifiers and purchase records are processed
by Firebase and the developer-operated verification backend.

## Notification Content

ShortLook does not store notification history. Notification titles, messages,
senders, contact photos, images, phone numbers, and email addresses must not be
written to persistent storage, analytics, crash reports, or remote services.

Notification content is used only transiently to decide whether a preview should
be shown and to draw that preview on screen.

The FlexWindow widget is a shortcut to ShortLook. It does not receive notification
text, sender photos, or other notification content, so Android cannot retain that
content in the widget after the app stops or the device locks.

## Network Access And Purchases

ShortLook’s notification processing remains local. The `withIap` build uses Google
Play Billing for payments and restoration, Firebase Authentication for an anonymous
technical user identifier, Firebase App Check / Play Integrity for app authenticity,
and Firebase Cloud Functions for server-side verification with Google Play.

The backend receives purchase tokens, package/product identifiers, the Firebase
user identifier and integrity attestations. It stores purchase-token hashes, order
identifiers when available, purchase state, verification timestamps, access records
and request-rate counters. Notification content is never included. Google Play
processes payment details; ShortLook does not receive card or bank information.

An Ed25519-signed license is stored on the device for up to 24 hours of offline Pro
access. Server rejection or expiry removes Pro access. The `withoutIap` build does
not contain Firebase or Billing and does not use this backend.

Server records support restoration and fraud prevention. Uninstalling the app does
not delete them. To request information or deletion, contact
ludeveloper97@gmail.com; deletion may require information to identify your purchase
and may affect restoration. No automatic server-retention period is currently set.

## Permissions

ShortLook may request notification listener access so Android can deliver
notifications to the app. This access is required for the main feature, but the
user may revoke it at any time in Android settings.

ShortLook may also ask for the optional overlay permission. The overlay is used
only as a fallback when Android or the device manufacturer prevents the regular
preview Activity from appearing. ShortLook can still run without this optional
permission, using a standard notification fallback when needed.

On Android versions that require runtime notification permission, ShortLook may
request permission to post its own fallback and status notifications.

On Android 9 and newer, ShortLook offers an optional accessibility service to
turn the screen off when returning the device to sleep after a preview. ShortLook
explains this use before opening Android accessibility settings; the user decides
whether to enable the service. The service only requests Android's screen-lock
action. It does not subscribe to accessibility events, read window contents, or
perform gestures, and it does not collect or transmit data through accessibility.

On Android 8, this optional feature uses device administrator access with only the
force-lock policy. Device administrator is not used to turn the screen off on
Android 9 or newer. Android controls the next unlock requirements; device
administrator locking may require a PIN, pattern, or password.

Screen off is not requested when the user opens a notification or when the screen
is already awake and unlocked. If access is missing, the service is disconnected,
or the lock action fails, ShortLook keeps its black-screen fallback until Android
puts the display to sleep. The user can disable this feature at any time.

To revoke permissions, open Android Settings, find ShortLook, and disable
notification access, overlay access, notification permission, accessibility
service access, or device administrator access. You can also open ShortLook
settings and use the permission shortcuts.

## Local Settings

ShortLook stores local preferences such as the selected privacy mode, preview
duration, allowed or blocked apps, language, and presentation options. It also
stores a cached Pro entitlement, counters used to decide when to request a review,
and up to 50 detected notification channels (app and channel names, identifiers,
and last-seen dates) for the duplicate-notification settings screen. Channel
metadata can be cleared from that screen. These local settings and channel records stay on the device;
clearing ShortLook's app data removes them.

Technical diagnostics are kept only in memory and exclude notification titles,
messages, senders, and images.

## Data Sharing

ShortLook does not sell data or share notification content with third parties. Google
Play processes optional purchases and in-app reviews under its own terms. Firebase
processes authentication and integrity information and hosts purchase verification
records for the developer. These services are not sent notification content.

## Children

ShortLook is a device utility and is not directed at children.

## Contact

For privacy questions, contact the developer at [ludeveloper97@gmail.com](mailto:ludeveloper97@gmail.com).
