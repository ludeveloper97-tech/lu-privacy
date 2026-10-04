# Metro UI Privacy Policy

Effective date: October 4, 2026

Metro UI is an Android launcher developed by Ludev. This policy explains how Metro UI (Android package: com.ludev.metroui) handles information when you use the launcher, its built-in features and its connected services. For privacy questions or requests, contact ludeveloper97@gmail.com.

## 1. Information kept on your device

Metro UI stores your launcher layout, pinned apps and folders, tile sizes, colours, selected wallpapers and tile images, icon-pack selection, preferences and first-run completion on your device. It reads the names, icons and launch identifiers of available apps to display and open them. It does not send your installed-app inventory to our backend or to the AI service.

Depending on the features you use, local storage may also contain selected contacts and their photos, calendar entries you create locally, calendar display preferences, notes, message drafts, alarm presets, playlists, selected media, browser history and favourites, weather locations and cached forecasts, Kids Corner selections, and widget identifiers and settings. This information is not automatically uploaded to our backend as a copy of your device content.

Files selected through Android's pickers may be referenced using a system-granted file reference or copied into the app's private storage. Removing the original file does not necessarily remove an imported copy. Your Android device backup and restore settings may allow the operating system to back up app data through your chosen backup provider.

## 2. Optional device access

Notification access: if you enable Android's notification access for Metro UI, the notification centre can read current notifications from other apps, including the sending app, title, message, timestamp and available open or dismiss actions. This can include private messages or other sensitive content contained in a notification. Metro UI displays this information locally so you can view, open or dismiss notifications. It does not send notification content to our servers, OpenAI or advertisers, and does not maintain a separate notification history. Access is optional and can be revoked in Android's notification-access settings. The launcher remains usable without it.

Calendar: if you grant calendar read permission, Metro UI can display the calendars and events available through Android's calendar provider, including event titles, times, locations and descriptions. These details are processed on the device and are not uploaded to our backend. Creating or editing a device-calendar event uses the system calendar editor, where you confirm the operation. Your calendar account provider may synchronise those events under its own policy.

Location: weather can use approximate foreground location if you choose the location option and grant permission. You can instead search for a city. Metro UI does not request precise or background location permission.

Camera and media: camera permission is used when you choose to take a picture. Photos, music, videos and backup files are selected through Android's system interfaces. Captured or imported media is not automatically uploaded to our backend. A file provider or destination you choose may itself be a cloud service.

Contacts, calls and messages: you can choose individual contacts through Android's contact picker. Metro UI can store those selected details locally for People and pinned tiles. It does not request unrestricted address-book, SMS or call-log access. Calling, sending a message or composing an email opens an appropriate external app for that action.

Widgets: adding a native Android widget may require system approval or provider configuration. Metro UI stores its placement and host information locally. Widget providers may obtain or transmit information according to their own privacy policies.

Other system features: network status, audio controls, available storage, battery information and available data counters are used to present device features. Metro UI does not request Android Usage Access for Data Sense. Its music playback service may keep playback active in the background. These features do not upload a history of your device activity to our backend.

## 3. Connected services and security

Metro UI uses Google Firebase Authentication, Cloud Functions, Firestore and App Check, including Google Play Integrity in production, to authenticate service requests, protect the backend, verify purchases and enforce usage limits. Firebase can create an anonymous user identifier without asking you to create a named account. Anonymous means there is no email/password sign-in; the identifier can still distinguish requests and is not a claim that all associated data is anonymous.

Purchase restoration and entitlement checks can contact these services when the launcher starts or resumes, even if you have not opened weather or the AI assistant. Services process authentication and app-integrity tokens, the app/package identifier and relevant request data. Hosting and security providers may also process IP addresses, request times, status codes and other technical information needed to operate and secure the service.

Backend access is controlled and app-to-backend communication uses HTTPS. No method of storage or transmission can guarantee absolute security. The current app does not include advertising SDKs, Firebase Analytics or Crashlytics, and we do not sell personal information or share it for targeted advertising.

## 4. Cortana / AI assistant

The assistant presented as Cortana in Metro UI is an AI feature powered by the OpenAI API through our backend. It is not Microsoft's Cortana service, and it does not require your personal ChatGPT account.

When you submit a request, your question, language preference and a limited number of recent conversation turns are sent to our backend and then to OpenAI to generate a reply. Do not include information you do not want processed by these services. Notifications, contacts, calendar events and local photos are not automatically attached to your requests. Metro UI does not record microphone audio for this feature.

The current implementation keeps the visible conversation in app memory and does not save a conversation archive in our database. You can clear the conversation in the app; ending the app process also removes this in-memory conversation. Our backend stores usage counters and timestamps associated with your anonymous identifier to enforce limits, rather than saving your prompts in those records.

We send AI requests with response storage disabled. This does not eliminate all provider retention: OpenAI may retain content in abuse-monitoring logs for up to 30 days by default, or longer for legal or safety reasons, and other limited technical retention may apply. OpenAI states that API content is not used to train its models by default unless the API customer opts in. See [OpenAI's API data controls](https://developers.openai.com/api/docs/guides/your-data).

## 5. Weather

Weather searches send the city text you enter, or the selected location coordinates, together with your language preference to our backend. The backend queries OpenWeather for place names, current conditions and forecasts. Coordinates are rounded to one decimal place before requesting a forecast from OpenWeather. Our backend still receives the coordinates supplied by the app.

Selected locations and forecast results are cached locally. The backend also uses a bounded in-memory weather/search cache to reduce repeat requests; cached results are eligible for reuse for 30 minutes. This cache is not a location-history feature. Request quotas are associated with your anonymous identifier. OpenWeather receives the information required for the weather lookup, not your launcher layout, notifications or Firebase user identifier.

## 6. Purchases and subscriptions

Personalisation is a one-time purchase and the AI assistant uses a separate subscription. Google Play handles payments. Metro UI and our backend do not receive your full payment-card details or bank credentials.

To verify and restore access, the app sends purchase tokens and product identifiers to our backend using its authenticated connection. The backend checks them with Google Play. Verification records may include a hashed purchase token, product and app identifiers, an order identifier, anonymous user identifier, purchase or subscription state, expiry and verification timestamps. The app also keeps signed entitlement information locally so it can determine available features.

Purchase and subscription records are used to provide access, restore purchases, process entitlement changes and prevent fraud. Google Play may send subscription-status updates to the backend. Uninstalling Metro UI or requesting deletion does not cancel a Google Play subscription; manage or cancel it in Google Play.

## 7. Backups and external services

Manual launcher backups export your launcher configuration and selected custom images to a ZIP file in a destination you choose. Restoring a backup reads the configuration and supported images from your selected ZIP or extracted backup file. This is not a backup of every built-in app's private data or your purchase entitlement. Exported backups are not encrypted by Metro UI. Anyone with access to a backup may be able to read its contents; you control where you store, share or delete it.

Websites opened in the built-in browser, searches sent to its search provider, external apps, widgets, Android services and file providers have their own data practices. They may receive URLs, search terms, network information or information you intentionally provide. Website security depends on the site, including whether it uses HTTPS. Kids Corner does not change the privacy practices of apps placed in it.

When you contact support, we receive your email address, message and any attachments you choose to send. We use them to respond to your request. Avoid sending passwords, full purchase tokens or unrelated sensitive information.

## 8. Retention and deletion

Local preferences and imported data remain until you remove them through available app controls, clear Metro UI's app storage or uninstall the app. Clearing app storage resets first-run onboarding. Files you exported, data stored by another app and operating-system backups may remain separately and must be managed through their respective providers. Removing calendar access does not delete events from your calendar provider.

Backend authentication, entitlement and usage-limit records are retained while needed to operate the services, restore access, enforce limits, resolve disputes, prevent fraud or meet applicable legal obligations. The current backend does not automatically delete all of these records when you uninstall the app or when a subscription ends. Technical logs and provider-held data follow the relevant provider's retention rules. Support correspondence is kept while needed to handle the request and related obligations.

To request deletion of personal information held by us, email ludeveloper97@gmail.com with the subject “Metro UI privacy request”. Where possible, contact us before clearing app storage, since the anonymous identifier may be needed to locate records. We may ask for limited information to verify and locate your request, such as the affected app installation or a purchase order reference. We will not ask for your Google password or full payment-card details. Some records may need to be retained for legal obligations, security or legitimate purchase-related disputes; we will explain applicable limitations. Deleting verification data may affect access restoration and does not itself request a refund.

## 9. Your choices and rights

You can decline or revoke optional Android permissions, choose a city instead of sharing location, avoid using connected AI features, clear local data and manage your backups. Revoking access stops future access through that permission but does not automatically delete information already copied or sent when you used a feature.

Where applicable under data-protection law, you may request access, correction, deletion or a portable copy of your personal information, object to certain processing, restrict processing or withdraw consent. You may also complain to your local data-protection authority. To exercise these rights, contact ludeveloper97@gmail.com. We respond in accordance with applicable law and may need to verify your request.

Where the EEA or UK rules apply, our legal bases depend on the activity: providing a service you request, your consent for optional access where required, legitimate interests in operating and securing the service and preventing fraud, or compliance with legal obligations. You may withdraw consent without affecting processing lawfully carried out before withdrawal.

## 10. Providers and international processing

We use Google/Firebase for app infrastructure, authentication, integrity checks and purchase verification, OpenAI for AI responses, and OpenWeather for weather information. These providers may process information in countries other than your own, including countries with different data-protection laws. Applicable provider agreements and legally required transfer safeguards govern those transfers.

Further information is available in [Google's Privacy Policy](https://policies.google.com/privacy), [Firebase privacy and security information](https://firebase.google.com/support/privacy), [OpenAI's Privacy Policy](https://openai.com/policies/privacy-policy/) and [OpenWeather's Privacy Policy](https://openweather.co.uk/privacy-policy).

## 11. Children

Metro UI is a general-purpose launcher and is not specifically directed at children. Kids Corner lets an adult curate shortcuts and content on the device; it is not an independent child account, a replacement for Android parental controls or a guarantee that third-party content is suitable for children. If you believe a child has provided personal information to our connected services without appropriate authorisation, contact us so we can investigate and address it.

## 12. Changes and contact

We may update this policy as features or data practices change. The effective date above identifies this version. Material changes will be communicated in the app or through the updated published policy as appropriate.

Developer: Ludev. App: Metro UI. Privacy and support contact: ludeveloper97@gmail.com.
