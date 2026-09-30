# ArchitechVPN releases

Public macOS and Windows installers and authenticated update feeds for ArchitechVPN. Application source code is maintained in a separate private repository.

Download installers from [Releases](https://github.com/twilinger/architechvpn-releases/releases). A GitHub account is not required. The first updater-enabled version must be installed manually.

The application checks for stable updates automatically and asks before installation. Installation closes the application and disconnects its VPN. macOS uses Sparkle with Ed25519-signed archives. Windows verifies signed release metadata and the installer checksum.

Update feeds are published together with verified installers. An empty release list means no installer is available yet.

Initial packages do not yet have Apple Developer ID/notarization or Windows Authenticode certificates. Update signatures authenticate release files but do not replace operating-system publisher certificates.
