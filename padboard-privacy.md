# PadBoard Privacy Policy — Google Play Version

Last updated: September 30, 2026

## 1. Scope and contact

This Privacy Policy explains how PadBoard processes information when you use the Android app distributed through Google Play, with package name `com.ludev.padborad`.

The developer responsible for PadBoard is **Ludev** (“we,” “us,” or “our”). For privacy questions or requests concerning your personal information, contact **ludeveloper97@gmail.com**.

This policy applies only to the Google Play version of PadBoard.

## 2. Keyboard input

PadBoard processes keyboard input on your device to provide touch typing, gamepad input, glide typing, suggestions, autocorrection, and cursor controls.

- We do not collect a general typing history or send your keystrokes, typed text, or glide gestures to our servers.
- Glide recognition and word suggestions use local dictionaries. Gesture traces are not saved as a history.
- Autocorrection may temporarily read nearby text, including the preceding word, to suggest corrections and support undo. This context is processed locally and is not stored as a typing history.
- Words are added to your personal dictionary only when you explicitly choose the add-word action. PadBoard does not automatically learn a history of everything you type.
- Suggestions and glide typing are disabled in fields that the receiving app identifies as password fields.

Basic keyboard input works offline and does not require a PadBoard account or a purchase. Android displays a standard warning when you enable a third-party keyboard; that warning describes the access a keyboard can have, rather than indicating that PadBoard uploads your text.

Text you enter is delivered to the app in which you are typing. That app may store or transmit the text according to its own privacy practices.

## 3. Information stored on your device

PadBoard stores the information needed to preserve your settings and selected features in its private app storage:

| Information | Purpose |
| --- | --- |
| Keyboard and interface languages, layout preferences, sound and vibration settings, and gamepad button mappings | Apply your preferred keyboard behavior |
| Themes, custom colors, and font selections | Preserve your chosen appearance |
| Words you explicitly add to the personal dictionary | Offer local word suggestions |
| Quick phrases, recent emoji settings, emoji selection counts, and sticker preferences | Provide shortcuts and frequently used content |
| Imported TTF/OTF font files and their display names | Display your selected keyboard font |
| A signed purchase entitlement and associated user identifier | Check whether purchased customization is available, including during a limited offline period |
| Configuration-use dates and counters, and review-prompt attempt dates and counts | Decide when to offer an optional Google Play review prompt |

Keyboard settings, personal dictionary words, quick phrases, emoji usage, and imported fonts are not sent to our purchase backend. The review counters are local; PadBoard does not receive your rating or learn whether you submitted a review through the review prompt.

PadBoard does not provide its own cloud synchronization for keyboard content. However, Android's backup, restore, or device-transfer services may copy eligible app preferences and files, depending on your device and backup settings. This can include data described as locally stored in this policy. These system services are controlled by Android and your backup provider. See [Android's backup documentation](https://developer.android.com/identity/data/autobackup).

## 4. Clipboard, fonts, stickers, and voice input

**Clipboard.** PadBoard reads the current Android clipboard item to display it while you use the keyboard's Clipboard page. It does not maintain a private clipboard history or send clipboard contents to our servers. If you insert clipboard text, the receiving app gets that text.

**Imported fonts.** You choose a font through Android's file picker. PadBoard copies the selected file into its private storage; it does not request general access to all your files or upload the font to our servers. If you select a file from a cloud document provider, that provider handles access under its own terms. Removing an imported font deletes PadBoard's copy and its saved font entry, without deleting your original file.

**Stickers.** PadBoard checks locally whether the receiving app supports image input. It generates PNG stickers locally and grants the receiving app temporary read access when you insert one. The receiving app can then use, save, or transmit the sticker. PadBoard does not upload this media or the receiving app's media-compatibility information to our backend. GIF insertion is not currently implemented.

**Voice input.** The voice button can switch to a separate enabled voice input method. PadBoard does not record audio or provide its own speech-recognition service. The selected voice provider may process audio locally or online under its own privacy policy.

## 5. Google Play purchases and verification

Optional paid customization uses Google Play Billing. Google handles payment details through its payment interface. PadBoard's purchase verification backend does not receive your full payment card number or card security code.

The settings app may contact Google Play when opened or resumed to load product information and restore or check existing purchases. You do not need to initiate a new purchase for these checks to occur.

When a purchase needs verification, Firebase Authentication creates or reuses an anonymous authentication identity. This is a technical identifier linked to purchase verification; “anonymous” does not mean the purchase record is unidentifiable. The Google Play version does not ask you to create an email-and-password PadBoard account.

Verification sends the following to our backend through Firebase Cloud Functions:

- The app package name and purchased product identifier.
- The Google Play purchase token.
- A Firebase authentication credential identifying the anonymous user.

The backend checks the purchase with Google Play and stores purchase and entitlement records in Firestore. These include the user identifier, package and product identifiers, a hash of the purchase token, order identifier when available, purchase and acknowledgement status, and purchase or verification timestamps. They are used to verify ownership, restore access, prevent duplicate or invalid claims, and manage paid features.

The app stores a signed entitlement locally. The current Google Play entitlement can allow purchased customization for up to 30 days after verification without another successful online check. Expiry of that local permission does not delete the server's purchase record.

The keyboard itself does not contact the purchase backend while you type. Purchase requests do not contain typed text, clipboard contents, personal dictionary words, quick phrases, or font files.

## 6. Service providers and technical information

We use Google Play for billing and optional reviews, and Google Firebase services for authentication, purchase verification, and purchase-record storage.

These services may process technical information needed to operate and secure requests. Firebase identifies IP addresses and user-agent information among the data processed for authentication and service operation. This information is separate from keyboard content. See [Firebase's privacy information](https://firebase.google.com/support/privacy).

The purchase functions are configured in Google's `europe-west1` region. This does not mean all Google processing, authentication, support, or backups occur exclusively in that region. Google may process information internationally as described in its applicable terms and [Google Privacy Policy](https://policies.google.com/privacy).

PadBoard does not include advertising, Google Analytics, Firebase Analytics, or an app-level Crashlytics integration. We do not sell keyboard content or use it for advertising. Google Play and Android may independently process store, device, or diagnostic information under their own policies and your settings.

## 7. Retention and deletion

Local settings and content remain in app storage until you remove them using available controls or clear the app's storage. You can:

- Use **Reset learned words** in the keyboard menu to erase the personal dictionary.
- Edit or remove your saved quick phrases and configurable recent emoji entries in settings.
- Remove imported fonts from the keyboard font settings.
- Clear PadBoard's storage in Android settings or uninstall the app to remove its local app data. Clearing storage also resets settings and cached purchase access.

Android backups may retain separate copies or restore eligible data on reinstall. Manage those copies through your device or backup provider. These actions do not erase text already inserted into another app, your original font files, or the system clipboard.

Firebase authentication identities and backend purchase records are separate from local app data. Uninstalling PadBoard does not automatically delete them or Google's transaction records. Purchase records support ongoing ownership verification and restoration; additional retention may be necessary for applicable accounting, security, or dispute-handling obligations. Exact backend retention and deletion periods must be confirmed before this policy is published.

You may request deletion of backend information using the privacy contact above. The current Google Play app does not offer an in-app control for deleting its Firebase identity or backend purchase records. Removing ownership records may affect purchase restoration. We may need an order reference or other limited information to identify the relevant record and verify your request; do not send passwords or full payment card details.

Google retains information it processes independently, such as payment records, under its own policies. Firebase describes its authentication retention and deletion timelines in its [privacy information](https://firebase.google.com/support/privacy).

## 8. Your choices and rights

You can disable PadBoard at any time in Android's keyboard settings. You can use basic typing without purchasing customization, choose which words to add to the dictionary, and choose whether to import fonts or use clipboard, sticker, and external voice features.

Depending on the law that applies to you, you may have rights to access, correct, delete, restrict, object to the processing of, or receive a copy of your personal information. Contact us using the details in Section 1 to make a request. You may also have the right to complain to your local data protection authority. We cannot retrieve keyboard content that is stored only on your device.

## 9. Security

PadBoard uses Android's private app storage for local data and HTTPS for Firebase purchase-verification requests. Its native keyboard validates signed purchase entitlements before enabling paid customization. PadBoard does not use an Accessibility Service to monitor other apps and does not request microphone, contacts, or location permissions for its keyboard features.

No device or network service can provide an absolute security guarantee. Your device security and the privacy practices of apps receiving your input also affect how your information is protected.

## 10. Changes to this policy

We may update this policy when PadBoard's features or data practices change. The date at the top identifies the latest revision. Any material changes requiring additional notice will be communicated as required by applicable law.
