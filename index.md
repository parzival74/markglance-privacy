# MarkGlance — Privacy Policy

*Last updated: 2026-05-10*

MarkGlance is a Markdown viewer for iPhone and iPad. **MarkGlance does not collect, transmit, sell, share, or store any personal information.** This page documents that fact in detail.

## What MarkGlance does not do

- **No accounts.** MarkGlance has no sign-in, no user profile, no account system.
- **No analytics or telemetry.** No third-party analytics SDK is bundled. We do not measure usage, send crash reports automatically, or track which files you open.
- **No advertising.** No ad networks, no ad SDKs, no ad identifiers.
- **No network calls.** MarkGlance reads `.md` files from your device and renders them entirely on-device. It does not contact any server. The bundled rendering pipeline (`marked.js`, `highlight.js`, Open Sans fonts) ships inside the app and runs locally.
- **No location.** We do not request or use your location.
- **No microphone, camera, contacts, or health data.** None of those entitlements are declared.
- **No tracking across apps or websites.** MarkGlance is fully offline; there is no mechanism to track anything off-device.

## What MarkGlance reads on your device

- **Markdown files (`.md`, `.markdown`, `.mdown`, `.mkd`, `.mkdn`)** that you explicitly open — via the Files app, an email attachment, AirDrop, the Share Sheet, or by tapping a file in the in-app file list. iOS sandboxing means MarkGlance only sees files you choose to share with it.
- **A copy of any file dropped into MarkGlance's Inbox** (the standard iOS document import flow). These files live inside the app's sandbox on your device and are never copied off the device by MarkGlance.

## Settings stored locally

MarkGlance saves the following to your device's local app preferences (iOS UserDefaults). These never leave your device:

- Your chosen text size (size slider)
- Your chosen theme (Light / Dark / Auto)

That's the entire list. Removing the app removes these preferences.

## PDF export

When you tap **Share → Export to PDF**, MarkGlance produces an A4 PDF of the currently open document on-device using Apple's native print pipeline. The resulting PDF is handed to the iOS share sheet so you can save it, AirDrop it, or send it where you choose. MarkGlance does not retain a copy or send it anywhere on its own.

## Children's privacy

MarkGlance does not knowingly collect any information from anyone, including children under 13. The app's age rating is 4+.

## Third-party content

MarkGlance bundles open-source libraries used for offline rendering:

- [marked.js](https://github.com/markedjs/marked) — MIT
- [highlight.js](https://github.com/highlightjs/highlight.js) — BSD-3-Clause
- [Open Sans](https://fonts.google.com/specimen/Open+Sans) — Apache License 2.0

These libraries operate entirely on-device and do not phone home.

## Changes to this policy

If MarkGlance ever changes its privacy practices in the future, this page will be updated and the "Last updated" date at the top will change. Material changes will be reflected in a new release of the app.

## Contact

Questions about MarkGlance's privacy: **zugzwang74@gmail.com**

— Anurag Gupta
