# BreakThePage — releases

Signed downloads and the update feed for BreakThePage, an offline script-breakdown
tool for macOS.

- `appcast.xml` is the update feed the app reads.
- Each version's `.zip` is attached to the matching release.

Every archive is signed with Developer ID, notarized by Apple, and signed again with
the update key the app checks before it installs anything. The app's source lives in
a separate repository.
