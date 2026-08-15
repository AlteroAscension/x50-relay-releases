# X50 Relay releases

This repository is the public binary update channel for X50 Relay. It contains
only release metadata and signed APK artifacts, not Relay source code.

`relay/update.json` is read by the Relay application's **Updates** screen.
The application accepts a download only after it verifies the manifest's
SHA-256, its own package name and the signing certificate of the installed
Relay.
