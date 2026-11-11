# Privacy Policy for NextGenUI

Version 1.0.5 · Updated 11 November 2026

Developer: Ludev · Android package: `com.ludev.nextgenui`

Privacy and deletion requests: [ludeveloper97@gmail.com](mailto:ludeveloper97@gmail.com)

## The launcher on your device

NextGenUI reads the names, identifiers and icons of launchable apps to display the drawer, find apps and build your home layout. Icon packs and Android widgets use the providers you choose. The launcher stores your layout, folders, settings and preferences on the device. You can remove items, clear the app’s storage or uninstall it. Exporting a backup writes a file to the location you select. You can delete that file separately. Purchase entitlements are excluded from layout backups.

If you grant Android notification access, NextGenUI uses notification icons, titles, text and actions to display badges, the lock screen and ShortLook. The lock screen can display the public version of a notification when Android hides its private contents. You can choose which apps trigger ShortLook. Music controls use active Android media sessions to display artwork, track information and playback state and to send playback commands. These display and control features process notification and media information on the device.

On Android 9 and later you can enable the optional accessibility service to lock the screen after a double tap on Home or when a ShortLook alert ends on the lock screen. The service uses Android’s screen-lock action. It does not read window content, record gestures or transmit screen contents. Android controls the secure lock and biometric authentication. Older supported Android versions use an optional Device Admin permission for locking. You can revoke these permissions in Android Settings.

## Veronica and the microphone

Veronica is an optional voice assistant with a separate Google Play subscription. You can start a conversation manually. If you choose voice activation, a foreground microphone service with an Android notification uses a supported on-device speech recognizer to detect “Veronica”. Voice activation is off by default. Words spoken together with the activation phrase can become the opening request.

During an active conversation, NextGenUI sends your microphone audio to OpenAI over an encrypted WebRTC connection so that Veronica can understand the request and reply by voice. Language, voice preferences, instructions, the opening request and results of requested tools can also be sent. For example, asking which calculator to open can send matching installed-app information. A request about your device can send its battery level, temperature or a sensor reading. Location and sensor tools have separate controls, initially off. Location also requires Android permission. The accessibility service used for screen locking is separate from Veronica’s tools.

You can end a session, disable voice activation or revoke microphone permission. The launcher closes inactive conversations and releases the microphone used by the session. If you enabled wake-word listening, local listening can resume after the conversation. NextGenUI does not keep a local conversation history or save voice recordings or transcripts in the launcher. Remote providers process data under their own service and retention arrangements.

## Reporting a Veronica response

In the Veronica settings, select “Report a Veronica response”, choose a reason and optionally describe what happened. When you select Send, the developer receives the reason and the text you wrote. Avoid including personal details in the description. The launcher does not attach your microphone audio or a transcript. Firebase checks the request and limits submissions using a technical identifier. Ludev records the reason, comment, review status and submission time. Keep the receipt shown after delivery if you wish to contact us about the report or request its deletion.

Ludev uses reports to review potentially harmful responses and improve safeguards. Each report is marked for automatic deletion 90 days after submission. Cloud deletion runs asynchronously after expiry.

## Weather and image searches

If you enable the weather widget and grant approximate location, NextGenUI sends coordinates, language and app/product identifiers to Ludev’s Firebase backend. The backend queries OpenWeather and caches results briefly. Location for weather is separate from enabling location for Veronica. The launcher does not request background location for weather.

If you ask Veronica to find an image, the backend receives the search terms and language and searches Wikipedia for existing images. Search results are cached briefly. When the launcher displays an external image, your device contacts its host, which receives the request and your IP address.

## Purchases, access and service records

Google Play processes the optional one-time Premium purchase and the separate Veronica subscription. For verification and restoration, NextGenUI sends the package, product identifier and purchase token to developer-operated Firebase functions. The backend checks Google Play and stores entitlement records, including a token hash and subscription status or expiry where applicable. The launcher can keep a signed entitlement locally. Ludev does not receive full payment-card information through these flows.

Firebase anonymous authentication supplies a technical user identifier. Firebase App Check with Play Integrity helps verify requests from the Play build. To start voice, the backend issues a short-lived OpenAI credential and associates a pseudonymous safety identifier with the request. The backend keeps usage counters, session reservations, timestamps and operational records to administer quotas, investigate failures and limit abuse. Deleting the app from the device does not itself delete those remote records.

## Recipients, security and user choices

Ludev uses Google Play and Firebase for store, authentication and backend services, OpenAI for live voice, OpenWeather for weather and Wikimedia or image hosts for image requests. These services may process data outside your country. Network features use encrypted connections. NextGenUI does not sell personal information.

You can use the launcher without enabling voice, notification access, weather or screen locking. Turn features off in NextGenUI and revoke optional permissions in Android Settings. Manage or cancel your Veronica subscription in Google Play.

Local settings remain until changed, cleared or deleted. Remote purchase and access records are used to restore purchases and verify entitlements. Usage and security records support limits, abuse prevention and troubleshooting. If you wish to request access to or deletion of developer-held data, contact Ludev at the address above and identify the app and feature involved. We may need information to locate the relevant record. Certain records may need to be retained for legal obligations or purchase disputes. Google Play manages its own transaction history.

NextGenUI is not specifically directed to children. We will update this policy when our data practices change.
