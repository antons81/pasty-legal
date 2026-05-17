# Privacy Policy — NimbusDB

**Last updated:** May 17, 2026

**Developer:** Anton Stremovskiy (aSoft)

NimbusDB is a native macOS database management application. Your privacy is important to us. This policy explains what data NimbusDB collects, how it is used, and how it is stored.

## Data Collection

NimbusDB does **not** collect, transmit, or store any personal data on external servers. All data stays on your device.

### What NimbusDB stores locally

- **Connection credentials** (API Tokens, Server-to-Server Keys) are stored exclusively in the macOS Keychain, the system-level secure storage provided by Apple.
- **Connection metadata** (connection names, container IDs, record type lists) is stored in a local SwiftData database on your device. If iCloud is enabled, this metadata may sync across your devices via your personal iCloud account.
- **Purchase information** is managed entirely by Apple through StoreKit. NimbusDB verifies purchase status locally using Apple's Transaction API.

### What NimbusDB does NOT collect

- No analytics or tracking data
- No personal information (name, email, location)
- No usage statistics
- No crash reports sent to the developer
- No advertising identifiers

## Network Communication

NimbusDB communicates **only** with Apple's CloudKit Web Services API (`api.apple-cloudkit.com`) to perform database operations (read, create, update, delete records) on your behalf. These requests are authenticated using your own credentials (Server-to-Server Keys) and are sent directly from your Mac to Apple's servers.

NimbusDB does **not** route traffic through any intermediary or third-party servers. There is no backend operated by the developer.

## Third-Party Services

NimbusDB does not integrate any third-party analytics, advertising, or tracking services.

The only external service used is Apple's CloudKit Web Services API, which is subject to [Apple's Privacy Policy](https://www.apple.com/privacy/).

## Data Security

- All credentials are stored in the macOS Keychain, protected by the operating system's encryption.
- NimbusDB runs within the macOS App Sandbox, limiting access to only the resources it needs.
- Network communication uses HTTPS exclusively.

## Data Retention and Deletion

All data is stored locally on your device. Uninstalling NimbusDB removes the application and its local data. Keychain entries may persist after uninstallation and can be removed manually via Keychain Access.

## Children's Privacy

NimbusDB does not knowingly collect any data from children under the age of 13. The app is a developer tool and is not directed at children.

## Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be posted at this URL. Continued use of NimbusDB after changes constitutes acceptance of the updated policy.

## Contact

If you have questions about this Privacy Policy, contact us at:

**Email:** stremovskiy@gmail.com
**Website:** [https://asoft-dev.lemonsqueezy.com](https://asoft-dev.lemonsqueezy.com)
