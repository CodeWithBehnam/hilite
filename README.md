<p align="center"><img src="assets/icon-128.png" width="96" alt="Hilite icon"></p>

# Hilite: Web Highlighter & Notes

Hilite is a free Chrome extension for highlighting text on any web page and finding it again. Select text, pick a colour, done. Your highlights come back on every visit, you can add notes, see each page's highlights in the popup, and search everything you have saved in the library. There is no account, no sign-in and no server: everything stays in your browser.

Chrome Web Store: link coming soon.

![Select text, pick a colour, done](assets/screenshots/01-select-and-highlight.png)

## What you get

- One step to highlight: select text and click a colour, or press the shortcut.
- Six colours, changeable after the fact, readable on light and dark sites.
- Highlights come back on every visit, including on single-page apps and pages that load content late.
- Notes on any highlight.
- A popup listing this page's highlights; click one to jump to it.
- A library of every highlight you have made, with search.
- Export to Markdown or JSON, import JSON back. Undo with Ctrl/Cmd+Z.
- Never breaks a page: Hilite paints highlights without changing the page's own markup.
- Free. No account, no ads, no premium tier, no tracking.

![Notes and a list for every page](assets/screenshots/03-popup-page-highlights.png)

![Search every highlight you have made](assets/screenshots/04-library.png)

## How to use it

1. Select any text on a page. A small toolbar appears above it.
2. Click a colour to highlight, or the note button to highlight and add a note straight away.
3. Click a highlight to change its colour, edit its note, copy the text or delete it.
4. Open the popup from the toolbar icon to see this page's highlights, or open the library for everything.

Keyboard shortcuts (Option instead of Alt on macOS; change them at `chrome://extensions/shortcuts`):

| Shortcut | Action |
| --- | --- |
| Alt+Shift+H | Highlight the selection with the last used colour |
| Alt+Shift+V | Show or hide highlights on this page |
| Alt+Shift+K | Open the popup |
| Ctrl/Cmd+Z | Undo the last highlight action |

## Install

From the Chrome Web Store: link coming soon.

Manual install of a release build:

1. Download `hilite-<version>.zip` from the [Releases](https://github.com/CodeWithBehnam/hilite/releases) page and unzip it.
2. Open `chrome://extensions`, turn on Developer mode, click "Load unpacked" and choose the unzipped folder.

## Privacy

Hilite stores your highlights, notes, page addresses and settings only in your own browser. It makes no network requests, has no account and no analytics. The full policy is in [PRIVACY.md](PRIVACY.md).

## Permissions and why

- Storage and unlimited storage: keep your highlights in the browser without a small size cap.
- Context menus: the right-click "Highlight" entry.
- Scripting: start working on tabs that were already open when you installed it.
- Access to http and https sites: highlights have to be painted on the pages you read. Nothing is sent anywhere.

## Support

Bug reports and feature requests: [issues](https://github.com/CodeWithBehnam/hilite/issues). Please do not include personal information in a public issue.

## Changelog

- 1.0.0 (2026-10-08): first release.
