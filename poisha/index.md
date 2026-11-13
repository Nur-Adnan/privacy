---
title: Poisha privacy policy
---

# Privacy policy

_Last updated: 2026-11-13_

Poisha organizes your income and spending on your phone. It has no server, no user
account, no advertising and no analytics.

## What the app reads

- **SMS (Android, only if you allow it):** the app reads your SMS inbox on the device to find
  transaction alerts from banks and mobile wallets. Messages that are not transactions (one-time
  passwords, promotions, personal messages) are skipped and never stored.
- **Messages you add yourself:** text you paste, or that an Apple Shortcuts automation hands to
  the app. Nothing is saved until you confirm it.
- **Email (Gmail), optional and off by default:** only if you connect Gmail. The app asks Google for read-only access and fetches only emails matching a transaction search, which Google runs on its side. Each email is read on your phone like an SMS: transaction emails are stored in the same encrypted database (their text is deleted after your retention period), and anything else is discarded without being stored. Disconnecting, or Delete everything, revokes the app's access at Google.

## What the app stores, and where

Everything stays in an encrypted database on your phone (SQLCipher, 256-bit key kept in the
Android Keystore / iOS Keychain). It contains your transactions, accounts, categories, budgets
and settings, plus the text of transaction messages for a limited time (7, 30 or 90 days, your
choice; 30 by default). After that only the transaction remains.

## What leaves your phone

Nothing, unless you do it:

- **Exports (CSV/JSON)** you share are **not encrypted**; anyone with the file can read it.
- **Backups** are encrypted with a passphrase you choose. We never see the passphrase, cannot
  recover it, and cannot open your backups.

The app sends no data to us or to any third party, and contains no tracking or crash-reporting
code. Builds without Gmail do not even request the Internet permission on Android, so the
operating system itself prevents them from sending anything. Builds with Gmail use the network
only to sign in with Google and read your matching emails, after you connect; your transactions
never leave the phone.

## Permissions

- **SMS (read only, Android):** to record transactions automatically. The app cannot send SMS.
- **Internet (only in builds with Gmail):** used solely for Google sign-in and reading your Gmail after you connect it.
- **Notifications:** budget alerts, reminders for bills you track, unusual-spending alerts and a weekly recap, all created on the phone. They never show amounts; a bill reminder shows the name you gave the bill. Weekly recap and unusual-spending alerts can be turned off in Settings.
- **Biometrics:** only if you turn on app lock; the check happens in the operating system.

## Your control

- Change how long message text is kept in Settings.
- Export your data at any time.
- **Delete everything** in Settings removes the database and its key from the phone. Backups or
  exports you saved elsewhere must be deleted by you.
- Uninstalling the app removes all its data from the phone.

## Contact

Questions or requests: email nuradnanchowdhury015@gmail.com.
