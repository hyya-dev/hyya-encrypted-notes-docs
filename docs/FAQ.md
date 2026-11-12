# FAQ

**→ [hyya.com/hyya-encrypted-notes.html](https://hyya.com/hyya-encrypted-notes.html)** has the overview. This page answers the questions people ask most.

## Privacy

**Can hYYa read my notes?**
No. Notes are encrypted on your device before they are saved or synced. There is no hYYa account and no hYYa server, so we have no copy to read.

**What is encrypted?**
Everything you write and attach, and also the titles, folder names, dates and the search index.

**What does Google or Apple see?**
Your iCloud Drive or Google Drive holds encrypted files only. With Google Drive, the app can see only the files it creates, in a folder named "hYYa Notes", and nothing else in your Drive.

## Sync

**iCloud or Google Drive?**
iCloud syncs between your iPhone, iPad and Mac. Google Drive syncs between all your devices, Android included, and Apple devices can use both. You can also keep your notes on one device.

**How do I add a second device with Google Drive?**
Install the app and choose **Open My Library from Google Drive** on its first screen. It asks for the passphrase you set when you connected Google Drive. Don't create a new library on the second device: two libraries never sync with each other.

**Two devices changed the same note. What happens?**
Both versions are kept. The second one opens with a banner saying it is a conflicting copy. Nothing you typed is discarded.

**Is sync free?**
Yes. iCloud and Google Drive sync need no purchase.

## Passphrase and unlocking

**What is the passphrase for?**
It lets another device open your library, and it is how you get back in if a device's own key is missing. Choose one you will remember, and write it down somewhere only you can reach.

**I forgot my passphrase. Can you reset it?**
We can't: no one but you holds the key, and that is what keeps your notes private. If the app still opens on one of your devices, set a new passphrase there.

**After my iPhone locks, Face ID doesn't appear by itself.**
That is on purpose, so the app never asks for Face ID over your Lock Screen. Tap **Unlock** in the app.

## Free and Pro

**What is free?**
Up to 2 notes, with sync and every other feature, and no time limit. Deleting a note frees its place. Encryption, the biometric lock, import and export are free for everyone.

**What does Pro add?**
Unlimited notes, as a one-time purchase. It is never a subscription. On the App Store, one purchase covers iPhone, iPad and Mac.

**Do notes in the Widget folder count?**
No. Notes in the Widget folder don't count toward your free limit. They appear on the Home Screen widget, so the app's lock does not cover them: keep private notes in other folders.

**I already had more than 2 notes.**
You keep every note and keep syncing. Only a new note past the limit asks for Pro.

## Export and import

**How do I get my notes out?**
**Settings → Export all notes** writes every note as plain Markdown, with its pictures and files in a folder beside it. It is free and always will be.

**What can I import?**
Markdown (with the pictures and files beside it), plain text, HTML, RTF and an Evernote export (`.enex`). On iPhone, iPad and Android you can also share text, Markdown or a note from another app straight into hYYa Encrypted Notes from the Share sheet; it appears the next time you unlock the app.

## Troubleshooting

**A note from another device hasn't appeared yet.**
- Check that both devices are online, and that iCloud Drive is on for the app in your device's settings, or that Google Drive is connected on both.
- With Google Drive, use **Sync Now** in Settings: it shows when the last sync happened.
- Make sure both devices opened the same library and didn't each create their own.

**Google Drive asks for a passphrase I don't recognise.**
It is the passphrase set on the device that first connected Google Drive. If that device still opens the app, go to **Settings → Google Drive → Set a New Passphrase** there.

**Something else is wrong.**
[Open an issue](https://github.com/hyya-dev/hyya-encrypted-notes-docs/issues/new/choose) with your device and the app's version, or contact us at [hyya.com/contact.html](https://hyya.com/contact.html). Please never include your notes or your passphrase.
