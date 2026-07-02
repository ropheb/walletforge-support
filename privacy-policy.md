# WalletForge — Privacy Policy

*Last updated: 2 July 2026*

---

## The short version

WalletForge stores your card data on your device and, if you are signed into iCloud, syncs it via Apple's iCloud. When you add a card to Apple Wallet, your card data is sent to a signing server operated by the developer. No analytics are collected. No data is sold or shared with third parties for advertising purposes.

---

## Data stored on your device

WalletForge stores the following on your device:

- Card details you enter: name, organisation, member number, barcode format, colours, and any custom fields
- Images you add: card icons, logos, and strip images
- Location coordinates you save against cards
- Group names and group assignments

This data is stored using Apple's SwiftData framework. If you are signed into iCloud on your device, it syncs automatically to your other Apple devices via Apple's CloudKit infrastructure. Apple's privacy policy governs that sync.

---

## Location data

WalletForge requests location permission when you choose to save a location against a card.

- **When In Use permission** is used to record your current position when saving a location, and to determine whether you are near a card's saved location so the nearby indicator can be shown in the card list.
- **Always permission** (optional) enables background geofencing: WalletForge registers your saved card locations with iOS so that a local notification can be delivered when you enter the area. This processing happens entirely on your device using iOS's region monitoring APIs.

Location data is stored locally on your device as part of the card record. It is not transmitted to any server except as described below.

---

## Data sent to the signing server

When you tap **Add to Wallet**, WalletForge sends the following to a signing server operated by the developer and hosted on Render (render.com):

- Your card's member number and pass metadata (organisation name, colours, field values)
- Your card's logo and icon images, if present
- The saved locations associated with the card, if any

This data is used solely to generate and sign the Apple Wallet pass file (`.pkpass`). It is not logged, stored persistently, or used for any other purpose. The signed pass is returned to your device and the data is not retained on the server.

The signing server is hosted in the United States.

---

## Camera and photos

If you use the barcode scanner, WalletForge requests camera or photo library access to read a barcode from a photo. Images selected for this purpose are processed on-device and are not transmitted anywhere.

---

## What we do not collect

- No analytics or usage data
- No advertising identifiers
- No crash reporting transmitted off-device
- No user accounts or registration

---

## Backups

The `.cardie` export file you create contains all your card data including images and locations. You control where this file is stored and shared. WalletForge does not have access to files you save to iCloud Drive, Files, or share via AirDrop.

---

## Children

WalletForge does not knowingly collect data from children under 13.

---

## Changes

If this policy changes in a material way, the updated policy will be distributed with the next app update and the "last updated" date above will reflect the change.

---

## Contact

For questions about this policy, contact: pc9r4vntb2@privaterelay.appleid.com
