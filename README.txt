FINORA V5.2 — PUBLIC BETA

WHAT'S NEW
- Wallet and transfer storage writes now roll back together if a later write fails.
- Transaction dates are checked as real calendar dates; impossible dates such as February 31 are rejected.
- Updated service worker cache to V5.2.
- Edit saved transactions without deleting and recreating them.
- Set or correct the transaction date.
- Search transaction history by description, category, or account.
- Export transaction history to CSV (Excel-compatible UTF-8 with BOM).
- Main balance now reflects the sum of all account balances, including opening balances and transfers.
- Backup format is branded FINORA; legacy BRIGADIR_FINANCE V1 backups remain importable.
- Backup restore maps transactions with missing account IDs to the default cash account.
- Added clear privacy notice: data is stored locally in this browser/device and is not cloud-synced.
- Added online/offline connection status.
- Updated service worker cache version.
- Four interface languages: Ukrainian, Russian, English, German.

IMPORTANT PRODUCT LIMITATIONS — PUBLIC BETA
- This release is a local-first PWA. There is no user registration, cloud database, cross-device sync, or server-side recovery.
- Data may be lost if browser/site data is cleared or the device is lost. Users should export backups regularly.
- Currency is currently UAH only. No foreign exchange or multi-currency accounting is provided.
- Financial goals are a separate progress tracker; adding to a goal does not move money from an account.
- The app does not connect to banks, payment cards, or payment systems.
- Do not store passwords, full card numbers, or other sensitive secrets in the app.

DEPLOYMENT
1. Download and extract FINORA_V5_2.zip.
2. Replace the files in the root of the existing GitHub Pages repository with all files from this archive.
3. Commit the changes.
4. Open the published app, refresh it, and test with small sample transactions.
5. Before public promotion, complete the release test checklist below.

RELEASE TEST CHECKLIST
- Add income and expense to each account; verify only the selected account changes.
- Add opening balances; verify the total balance includes them.
- Transfer money between accounts; verify the combined balance does not change.
- Edit and delete transactions; verify balances and history recalculate.
- Change transaction dates; verify monthly statistics use the selected date.
- Search history and export CSV.
- Export a backup, clear test data in a separate browser profile, then restore the backup.
- Test all four languages and install/offline behavior on Android and desktop.
- Keep a backup of the previous deployed files before replacing them.

This is a public beta, not a certified accounting, banking, or tax product.
