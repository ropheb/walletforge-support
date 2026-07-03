# WalletForge — Support

## Contact

For help with WalletForge, questions, or bug reports, contact:
**pc9r4vntb2@privaterelay.appleid.com**

Please include your iOS version and, if possible, a screenshot or brief description of what you were doing when you ran into a problem.

---

## Common Questions

### "Add to Wallet" is stuck or times out

The signing server that generates passes runs on a free tier that goes to sleep after a period of inactivity. The first request after it's been idle can take up to 80 seconds while the server wakes up — WalletForge shows a progress message and retries automatically during this time. If it eventually times out, wait about 30 seconds and try again; the server will already be warm.

### Export asks for Face ID / passcode

Exporting a `.cardie` backup requires you to confirm with Face ID, Touch ID, or your device passcode, since the exported file contains your card numbers in plain text. If your device has no biometrics or passcode set up, export proceeds without a prompt.

### A card's logo or header looks wrong after importing a `.pkpass`

Open the card, tap **Edit**, and look for **Remove Imported Logo** or **Remove Strip Image** near the bottom of the Identity/Colours section. Removing an imported logo lets WalletForge regenerate the header from your icon and organisation name instead.

### Editing a card doesn't update the version already in Apple Wallet

Apple Wallet passes are static once added. After editing a card in WalletForge, remove the old pass from Wallet and tap **Add to Wallet** again to get the updated version.

### Lock screen / nearby notifications aren't showing up

Background notifications require **Always** location permission (Settings → WalletForge → Location → Always). WalletForge monitors up to 20 saved locations at a time across all cards, keeping the 20 closest to you active.

---

## Full User Guide

WalletForge includes a complete in-app User Guide. From the card list, tap **⊞** (Groups) in the toolbar, then the book icon in the top-left of the Groups screen. It covers card creation, backups, colours, locations, Wallet groups, and more, with a built-in search.

---

## Privacy

See the [Privacy Policy](privacy-policy.md) for details on what data WalletForge stores and how it's used.
