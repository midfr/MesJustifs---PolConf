# Privacy Policy — MesJustifs

**Last updated: June 22, 2026**

## Summary

MesJustifs is a **100% local** application. Your documents, metadata and extracted keywords are stored on your device. No data is transmitted to the developer or any third-party service (other than Apple iCloud for private sync, at your discretion).

## 1. Data Controller

The MesJustifs application is published by Mohamed Moukah ("the Publisher").
Contact: mmoukah@gmail.com

## 2. Data processed

### Data stored locally on your device
- Images of scanned or imported documents (PDF, JPEG)
- Metadata: document type, scan date, custom name, tags
- OCR-extracted text
- Keywords (date, amount, email, phone, IBAN, reference, etc.) — values marked sensitive are encrypted with AES-GCM using a key stored in the iOS Keychain
- Templates, audit logs, OCR exclusions
- User preferences (settings, expiration notifications)

### Data NOT collected
- No data is transmitted to the Publisher or any third-party server
- No advertising identifier
- No telemetry, no analytics
- No cookies

## 3. iCloud sync (optional)

If an iCloud account is active on your device, your database is automatically replicated by iOS to **your private iCloud container** (CloudKit), accessible only from your devices signed in with the same Apple ID. **The encryption key for sensitive values is never synced**; it remains in the local Keychain of each device.

The Publisher has no access to any data stored in iCloud. Sync is governed by Apple's privacy policy: https://www.apple.com/legal/privacy/

## 4. In-app purchases

When you purchase "MesJustifs Pro", the transaction is processed by **Apple via the App Store**. The app receives only a purchase status (Pro active/inactive). The Publisher receives no personal information, no payment details.

## 5. iOS permissions requested

- **Camera**: required to scan documents
- **Face ID / Touch ID**: required for optional app locking
- **Notifications**: required for expiration reminders (local only, not transmitted)

## 6. Your rights (GDPR, art. 15-22)

All data remains on your device, so you retain full control:
- **Access / portability**: CSV / JSON / PDF exports available in the app
- **Rectification**: edit directly within the app
- **Erasure**: Settings → "Erase all my data (GDPR)" destroys all documents and the encryption key
- **Disable iCloud**: from iOS Settings → your Apple account → iCloud → MesJustifs

## 7. Security

- AES-GCM encryption (Apple CryptoKit) for values marked sensitive
- Key kept in the **iOS Keychain** (accessible only when device unlocked, never synced)
- Optional Face ID / Touch ID lock
- No network communication outside private iCloud

## 8. Data retention

Your data is retained as long as you use the app. Deleting the app erases all local data. To also wipe the private iCloud container: iOS Settings → your account → iCloud → Manage Storage → MesJustifs → Delete Data.

## 9. Children

MesJustifs is not intended for children under 13 and does not collect any data from them.

## 10. Changes

Any substantial change to this policy will be signaled in the app via an update. The update date appears at the top of this document.

## 11. Contact & complaint

For any question: mmoukah@gmail.com
You also have the right to lodge a complaint with the CNIL (www.cnil.fr) or your local data protection authority.
