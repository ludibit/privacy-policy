# Ludibit Privacy Policy

Effective date: **October 17, 2026**

Developer: **Ludibit**

Privacy contact: **[iamludibit@gmail.com](mailto:iamludibit@gmail.com)**

## Quick summary

- Your app content stays on your device by default. We do not receive it on our servers.
- You choose when to sync, export or share copies. Your device may also back up app data according to its settings.
- Apps with Google AdMob ads use advertising services that process device and usage information. We do not send your app content to AdMob.
- Stores handle optional purchases. See your app's section below for its features and privacy choices.

The full policy below explains these practices and their limits.

## Apps covered by this policy

This policy applies to the Ludibit apps and games listed here. The shared sections describe their common practices; each app's section provides its specific details.

- **[Ideal Timers](#ideal-timers)** — local boards, timers and history; optional local-network sync and backups; Android AdMob advertising and optional Premium purchases.

Other Ludibit apps and games are covered only when they are added to this list with the relevant details. Features described as optional apply only where the listed app provides them.

## Local content and your choices

The covered apps store the content you create and their settings on your device to provide their features. We do not operate a server that receives that content through these apps. Content you enter can contain personal information. Advertising and store services process separate information as described below.

When you choose an available sync, export or sharing feature, it can create copies on other devices or in destinations you select. A service you choose to receive a copy handles it under its own policy. Your operating system may separately back up or transfer app data according to its settings and provider. These copies are distinct from the app's local storage.

## Advertising and Google services

The Android apps identified above as having ads integrate Google AdMob through the Google Mobile Ads SDK.

Google documents collection and sharing of IP addresses, which can indicate approximate location; app/ad interactions, such as app launches, taps and video views; diagnostics, such as app launch time, freezes and energy usage; and device or account-related identifiers, including advertising and app-set identifiers where available. Google describes advertising, analytics and fraud prevention as processing purposes. The information processed depends on SDK behavior, device settings, consent and advertising configuration. Google's consent service also processes information needed to determine applicable requirements and manage privacy choices.

We do not supply content created or saved through the covered apps' features to AdMob. This includes timers, notes, history, boards, settings, schedules, wallpaper, keyboard shortcuts and backup contents in Ideal Timers. This content is separate from the device, interaction and diagnostic information processed by the advertising SDK.

Google may process advertising information on its infrastructure and with advertising partners. See [Google's Privacy Policy](https://policies.google.com/privacy), [Google's explanation of partner services](https://policies.google.com/technologies/partner-sites) and [Google's Mobile Ads SDK data disclosure](https://developers.google.com/admob/android/privacy/play-data-disclosure).

Privacy forms, advertising choices and the effect of purchasing an ad-free option are described in the relevant app section. Android also provides advertising identifier controls in system settings; availability varies by device. This policy does not itself obtain advertising consent.

## Optional store purchases

Where purchases are available, the platform store processes payment and supplies product information, purchase status and purchase records used to recognize, acknowledge and restore purchases. An app may cache entitlement status locally. We do not receive your full payment-card details.

Google Play handles Android purchases; supported Microsoft Store installations use Microsoft Store services. Their account, payment and transaction handling follows their respective policies: [Google](https://policies.google.com/privacy) and [Microsoft](https://privacy.microsoft.com/privacystatement). Availability and purchase benefits are described in the app and its section below.

## Retention and deletion

Local content remains until you change or delete it, an app's retention feature removes it, you replace it through an import, or you remove its storage. The app sections explain specific retention and reset behavior. Clearing local storage does not delete copies in exports, device backups, paired devices or services you selected. Delete those copies separately.

Removing app data does not cancel purchases or delete store transaction records. Advertising, store, email and backup providers retain information under their own policies and applicable requirements. We cannot erase their records through an app reset.

For information held by Ludibit, contact **[iamludibit@gmail.com](mailto:iamludibit@gmail.com)** with your question or deletion request. The covered apps do not require a Ludibit account, and we do not hold their local content on our servers.

## Support emails

If you email us, we use your email address, message and any attachments to respond to your request. Your email provider and ours also process the correspondence. Please avoid including sensitive app content unnecessarily.

Support correspondence is kept in our email account without a fixed automatic deletion period. You can request deletion by emailing **[iamludibit@gmail.com](mailto:iamludibit@gmail.com)**, and we will delete the requested support emails and their attachments from our mailbox. This does not delete copies in your mailbox or override email providers' backup and retention practices.

## Diagnostics and security

The covered apps have no separate developer-operated analytics or automatic crash-upload service. Advertising SDK diagnostics are described above. Diagnostic builds can keep local logs, and app errors or state changes may appear in system or developer logs. Review logs before choosing to share them.

Local files and manual exports are not encrypted by the apps unless an app's section says otherwise. Device security, backups and the destinations you choose for sharing also affect protection. Specific sync protections and limitations are described below.

## Privacy-policy website

This policy page is hosted by GitHub Pages. GitHub receives technical request information, including visitors' IP addresses, to provide and secure its service. Its handling of that information is explained in the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). We have not added analytics, advertising, tracking scripts or cookies to this page.

## Ideal Timers

Ideal Timers helps you organize boards, timers, schedules and timer history. You do not need to create an Ideal Timers account.

### Information stored on your device

The app stores board and timer names, durations, running state, counters, schedules, timer activity timestamps, history and any notes you add to history. It also stores language, appearance, sound, vibration and keyboard-shortcut preferences, a randomly generated installation identifier for sync, and cached Premium status and its last refresh time. If you choose a wallpaper image, the app saves a local copy.

These details support the features you use. The app does not ask for your name, email, contacts, precise GPS location, microphone recordings or camera access to run timers. Timer details may appear in on-screen timers, notifications and background timer controls; their visibility depends on your device and notification settings.

### Optional local-network sync

When you activate sync, the app discovers and connects directly to other devices on your network. Discovery and connection metadata can expose the device display name, installation identifier, network address and service port to other devices on that network. A display name may be based on the device manufacturer/model or computer hostname.

When you pair and sync, the app exchanges an encrypted backup containing boards, timers, history and notes, settings and available keyboard shortcuts with the paired device. Category choices control which information is applied during sync; the transmitted backup can contain other categories too. Timer content is not routed through a developer-operated cloud service. The app retains pairing secrets, device names/identifiers, sync timestamps, previous shared backups and unresolved versions locally for later sync and conflict resolution.

Sync backup contents are encrypted during transfer, but discovery metadata and connection envelopes are visible on the network. Use sync only with devices and networks you trust. Removing a saved device removes its local pairing record and saved sync versions; it does not erase copies already stored on the other device.

### Backups and files

Export creates a readable JSON file containing boards, timers, history and notes, settings, the installation identifier and available keyboard shortcuts. Exported files are not encrypted by the app. On mobile, a temporary copy is created for the system share sheet. You choose where to save or share it. Import reads the file you select and replaces app database content.

Operating-system backups can include the database and separate local files, depending on device settings, capabilities and provider.

### Android advertising, consent and Premium

The Android app checks Premium status before explicitly initializing the advertising SDK or requesting ads. For eligible non-Premium users, Google's User Messaging Platform checks consent requirements and presents a privacy form when required. Ads are requested only when that platform indicates they may be requested. When Google requires a privacy-options entry point, you can review or change your choices using “Advertising privacy” in Settings.

Premium removes ads. When Premium is recognized, the app skips explicit advertising SDK initialization and ad requests on startup. Unresolved purchase checks leave ads disabled. Upgrading during a session removes the ad placement and stops further ad requests, but does not unload an SDK already initialized earlier in that session or erase information already processed. Store purchase checks can still occur.

### History retention and reset limitations

History defaults to 90 days. The app prunes older entries during startup and history operations; retention choices can change that period, and a non-positive retention value disables automatic pruning. You can also clear history yourself.

“Reset all data” resets the app database to defaults. Separate files such as saved sync devices and their stored versions, wallpaper, keyboard-shortcut preferences and exported backups are not all removed by this action. Remove saved sync devices and wallpaper through their controls.

On Android, clearing app storage removes app-private local data; uninstalling generally removes it too, but system backups may restore it. On desktop, removing the application may leave its data directory. Delete exported files and copies on other devices or services separately.

### Intended audience

Ideal Timers is a general-purpose timer app. It is not specifically designed for or marketed to children.

## Changes to this policy

We will update this policy when the covered apps or their data practices change and update the effective date. For privacy questions or requests, contact **[iamludibit@gmail.com](mailto:iamludibit@gmail.com)**.
