# KMP Template iOS Installer

GitHub Pages installer repository for the OneLane Kotlin Multiplatform template. `./.ol/ol.cmd template publish kmp` in the parent repo builds the signed IPA, updates `ipa/kmp-install.ipa`, regenerates `manifest.plist` and `release.json`, pushes this repo, and verifies the exact public release.

The OTA install is valid only for UDIDs included in the package's Ad Hoc provisioning profile.
