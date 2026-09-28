# BreakThePage — releases

Signed downloads and the update feed for **BreakThePage**, an offline script-breakdown
tool for macOS. The script never leaves your Mac: the model runs locally and the app
is sandboxed with no network permission at all.

### [Read the walkthrough →](https://kunkles.github.io/BreakThePage-releases/)

## Download

The newest build is on the [releases page](https://github.com/Kunkles/BreakThePage-releases/releases/latest).
Unzip it and drag it to Applications. After that the app checks for new versions
itself, once, each time it opens.

Needs macOS 14 or later on Apple silicon.

## What's in here

- `index.html` — the walkthrough, served at the link above.
- `appcast.xml` — the update feed the app reads.
- Each version's `.zip`, attached to the matching release.

Every archive is signed with Developer ID, notarized by Apple, and signed again with
a separate update key the app checks before it installs anything — so a tampered
download is refused even if this page is taken over. The app's source lives in a
separate repository.
