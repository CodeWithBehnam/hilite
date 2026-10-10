# Hilite privacy policy

**Effective date:** 2026-10-10
**Applies to:** Hilite 1.0.1

Hilite keeps everything on your device. It has no servers, no accounts and no analytics, and it sends nothing to the developer or to any third party.

## What Hilite stores

- **Highlights:** the exact text you highlight, a few words either side of it, where it sits on the page, its colour, any note, and when you created or last changed it.
- **Page addresses and titles:** only for pages that have at least one highlight. Addresses are tidied before storage, with common tracking parameters such as `utm_*` removed.
- **Settings:** your colours, default colour, toolbar and hover options, and any sites where you have turned Hilite off (hostnames only).
- **Reminder state:** when Hilite was installed or updated, when you last exported a backup, and whether you dismissed the backup reminder or the review request. It is used only to decide whether to show those two prompts.

When you visit a page, Hilite reads its text on your device only so it can place your highlights. Hilite keeps no list of the pages you visit. A page is recorded only after you highlight something on it, and its record is deleted when its last highlight is removed.

## Where it is stored

Everything is kept in `chrome.storage.local`, which lives in your browser profile on your device. Hilite does not use `chrome.storage.sync`, so highlights and settings do not sync between your devices.

## What Hilite does not do

- It does not send your data to any server, and it makes no network requests of its own.
- It does not need an account or a sign-in.
- It does not use analytics, telemetry, crash reporting or advertising.
- It does not use third-party services, SDKs or remote code.
- It does not sell, rent or share your data, or use it for anything other than highlighting.
- It does not read your browsing history or list your open tabs.

## What leaves your device

Nothing, except a file you choose to export. Export creates a Markdown or JSON file that your browser saves where you tell it to. Once saved, that copy is yours and Hilite no longer controls it. Import reads a JSON file you choose, on your device.

The "Report a site" and "Write a review" buttons open a page in a new tab, and "Tell a friend" copies the Chrome Web Store link to your clipboard, only when you click them. "Report a site" opens a GitHub issue form with only the Hilite version filled in. It does not include the page you were on.

## Deleting your data

- **One highlight:** delete it from the highlight's menu, the popup or the library.
- **One page:** delete the page in the library.
- **Everything:** use the clear-all option in the Data section of the Options page.
- **Uninstall:** removing Hilite from `chrome://extensions` deletes the data it stored in your browser. Files you exported are not deleted, so remove them yourself.

## Permissions in plain words

- **Storage:** keeps your highlights and settings in your browser.
- **Unlimited storage:** lets your library grow past Chrome's default storage limit.
- **Context menus:** adds Highlight to the right-click menu.
- **Scripting:** starts Hilite on tabs that were already open when you installed it.
- **Access to web pages (http and https):** runs Hilite on the pages you visit so it can place highlights. Hilite does not ask for the tabs or history permissions.

## Changelog

- 2026-10-10: Hilite 1.0.1 stores local reminder state and adds the "Report a site", "Write a review" and "Tell a friend" buttons. Nothing is sent anywhere.
- 2026-10-08: First version, for Hilite 1.0.0.

## Contact

Questions or concerns: open an issue at https://github.com/CodeWithBehnam/hilite/issues. Do not post personal information in a public issue.
