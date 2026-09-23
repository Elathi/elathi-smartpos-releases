# Elathi SmartPOS releases

This public repository is the distribution channel for signed Windows installers and updater manifests for [Elathi SmartPOS](https://elathi.xyz/).

<!-- SMARTPOS_RELEASES_MANAGED_START -->
## Stable signed releases

Stable SmartPOS releases will appear on the [release history page](https://github.com/Elathi/elathi-smartpos-releases/releases). Each published release includes the signed Windows installer, its signature, and the updater manifest.

At the moment, no stable release has been published in this repository yet.

### Download and update

- When a release is available, use [Latest release](https://github.com/Elathi/elathi-smartpos-releases/releases/latest) to download the signed Windows installer.
- Existing installations can use **Settings → Updates** or the global update control to check the signed update manifest.
- The stable updater manifest is published at [latest.json](https://github.com/Elathi/elathi-smartpos-releases/releases/latest/download/latest.json).
- SmartPOS upgrades preserve the local store database and business data. Keep the application closed during a manual installer run.

### Security and support

- Use only installer, signature, and manifest assets published in this repository. SmartPOS verifies the updater signature before installation.
- Updates wait for a safe idle state and do not interrupt an active sale.
- Check each release description for its **What’s new**, compatibility, and migration notes.
- For product help, use the in-app Guide or contact the Elathi SmartPOS support team.

The release publisher maintains this managed section. Future releases will replace the availability message with the current version and release-specific download guidance.
<!-- SMARTPOS_RELEASES_MANAGED_END -->

## Links

- [Release history](https://github.com/Elathi/elathi-smartpos-releases/releases)
- [Latest release](https://github.com/Elathi/elathi-smartpos-releases/releases/latest)
- [Elathi SmartPOS product site](https://elathi.xyz/)
