# Ideal Timers Privacy Policy

> Draft for review, prepared 2026-10-17. Not published. Developer name and contact confirmed by the user. Before publication, confirm the effective date, hosting provider and URL, and final ads/consent configuration. This draft describes the reviewed app; it does not promise consent controls that have not yet been implemented.

Effective date: **[Confirm before publication]**

Developer: **Ludibit**

Privacy contact: **iamludibit@gmail.com**

## Quick summary (TL;DR)

- Your timer content stays on your device by default and is not sent to our servers.
- When you choose to sync or export a backup, you can copy your data to the devices or destinations you select. Your operating system may separately back up app data according to your device settings.
- Android ads use Google AdMob, which collects device identifiers, IP addresses, interactions (such as app launches, taps, and video views), and diagnostics (such as app launch time, freezes, and energy usage). The app does not send your timers, notes, history, boards, settings, or other content created or saved through its features to AdMob.
- Stores process optional Premium purchases. Premium removes ads.

The full policy below explains data handling, deletion, and your choices.

## Full privacy policy

Ideal Timers helps you organize boards, timers, schedules, and timer history. You do not need to create an Ideal Timers account. Your timer content is stored on your device. We do not operate a server that receives your timer content through the app. Android advertising and optional store purchases involve third-party services, as explained below.

## Information stored on your device

The app stores board and timer names, durations, running state, counters, schedules, timer activity timestamps, history, and any notes you add to history. It also stores preferences such as language, appearance, sound, vibration, and keyboard shortcuts, a randomly generated installation identifier for sync, and cached Premium status and its last refresh time. If you choose a wallpaper image, the app saves a local copy.

These details support the features you use. Names and notes can contain personal information if you enter it. The app does not ask for your name, email, contacts, precise GPS location, microphone recordings, or camera access to run timers.

Timer details may appear in on-screen timers, notifications, and background timer controls. Their visibility depends on your device and notification settings.

## Optional device sync

When you activate sync, the app discovers and connects directly to other devices on your network. Discovery and connection metadata can expose the device display name, installation identifier, network address, and service port to other devices on that network. A display name may be based on the device manufacturer/model or computer hostname.

When you pair and sync, the app exchanges an encrypted backup containing boards, timers, history and notes, settings, and available keyboard shortcuts with the paired device. Category choices control which information is applied during sync; the transmitted backup can contain other categories too. Timer content is not routed through a developer-operated cloud service. The app retains pairing secrets, device names/identifiers, sync timestamps, previous shared backups, and unresolved versions locally to support later sync and conflict resolution.

Use sync only with devices and networks you trust. Removing a saved device removes its local pairing record and saved sync versions. It does not erase copies already stored on the other device.

## Backups, files, and device backup services

When you export a backup, the app creates a readable JSON file containing boards, timers, history and notes, settings, the installation identifier, and available keyboard shortcuts. Exported files are not encrypted by the app. On mobile, a temporary copy is created for the system share sheet. You choose where to save or share it; a chosen cloud-storage or messaging service handles that copy under its own policy. Import reads the file you select and replaces app database content.

Your operating system may also back up or transfer app data according to its settings, device capabilities, and backup provider. This can include the database and separate local files. Such backups are distinct from the app's manual export feature.

## Android advertising

The Android app integrates Google AdMob through the Google Mobile Ads SDK. The app checks Premium status before explicitly initializing the advertising SDK or requesting ads. For eligible non-Premium users, Google's User Messaging Platform checks consent requirements and presents a privacy form when required. Ads are requested only when that platform indicates they may be requested. When Google requires a privacy-options entry point, you can review or change your choices using “Advertising privacy” in Settings.

Google documents collection and sharing of IP addresses (which can indicate approximate location), app/ad interactions (such as app launches, taps, and video views), performance and diagnostic information (such as app launch time, how often the app freezes, and energy usage), and device or account-related identifiers, including advertising and app-set identifiers where available. Google uses these categories for advertising, analytics, and fraud prevention. The information processed depends on SDK behavior, device settings, and advertising configuration. Google's consent service also processes information needed to determine applicable requirements and manage your choices.

The app does not supply your timers, notes, history, boards, settings, schedules, wallpaper, keyboard shortcuts, backup contents, or other content created or saved through its features to AdMob. This content is separate from the device, interaction, and diagnostic information processed by the advertising SDK as described above. Google may process advertising information on its infrastructure and with advertising partners. See [Google's Privacy Policy](https://policies.google.com/privacy) and [Google's explanation of partner services](https://policies.google.com/technologies/partner-sites).

When Premium is recognized, the app skips explicit advertising SDK initialization and ad requests on startup. Unresolved purchase checks leave ads disabled. Upgrading during a session removes the ad placement and stops further ad requests, but does not unload an SDK already initialized earlier in that session or erase information already processed. Purchase checks through the store can still occur. Android provides advertising identifier controls in system settings; availability varies by device. This policy does not itself obtain advertising consent.

## Optional Premium purchases

Where store purchases are available, the platform store processes payment and supplies product information, purchase status and purchase records used to recognize, acknowledge, and restore Premium. The app stores a local Premium-status cache. It does not receive your full payment-card details. Google Play handles Android purchases; a supported Microsoft Store installation uses Microsoft Store services. Their account, payment, and transaction handling follows their respective policies: [Google](https://policies.google.com/privacy) and [Microsoft](https://privacy.microsoft.com/privacystatement).

## Retention and deletion

Board, timer, and settings data stays locally until you change or delete it, replace it by importing a backup, reset the database, or remove app storage. History defaults to 90 days. The app prunes older entries during startup and history operations; retention choices can change that period, and a non-positive retention value disables automatic pruning. You can also clear history yourself.

“Reset all data” resets the app database to defaults. Separate files such as saved sync devices and their stored versions, wallpaper, keyboard-shortcut preferences, and exported backups are not all removed by this action. Remove saved sync devices and wallpaper through their controls. On Android, clearing app storage removes app-private local data; uninstalling generally removes it too, but system backups may restore it. On desktop, removing the application may leave its data directory. Delete exported files and copies on other devices or services separately.

Resetting local data does not cancel a purchase or delete store transaction records. Google, Microsoft, backup providers, and any service you choose for sharing retain information under their own policies and applicable requirements. We cannot erase their records by resetting your timers.

## Diagnostics and security

The reviewed app has no separate developer-operated analytics or automatic crash-upload service. Advertising SDK diagnostics are described above. Diagnostic builds can keep local timer logs, and app errors/state changes may appear in system or developer logs. Review logs before sharing them.

Sync backup contents are encrypted during transfer, but discovery metadata and connection envelopes are visible on the network. Local database files and manual exports are not encrypted by the app. Device security and the destinations you choose for sharing also affect protection.

## Changes and contact

We will update this policy when the app's data practices change and update the effective date. For privacy questions, contact **iamludibit@gmail.com**. If you choose to email us, your email provider and ours process that correspondence; do not send sensitive timer content unnecessarily.

Support correspondence is kept in our email account without a fixed automatic deletion period. You can request deletion by emailing **iamludibit@gmail.com**, and we will delete the requested support emails and their attachments from our mailbox. This does not delete copies in your mailbox or override the email providers' own backup and retention practices.

## Intended audience

Ideal Timers is a general-purpose timer app. It is not specifically designed for or marketed to children.

> Publication follow-up: review the chosen hosting provider's request logs and disclosures; reconcile this text with the production SDKs, configured AdMob privacy messages, consent flow, store configuration, target-audience declaration, and actual release artifact. The Premium/consent paragraphs describe this implementation and still require release verification. Do not publish the draft notes or placeholders.
