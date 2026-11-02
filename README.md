# Pilot Start — signed Android updates

This public repository distributes only verified, signed Pilot Start Android APKs. Private source code, HondaLink credentials, passwords, signing keys, and cloud configuration are not published here.

**[Download the latest Pilot Start release](https://github.com/unclebooch/pilotstart-updates/releases/latest)**

## Update from your Android phone

Open **Pilot Start → Settings → App updates → Check for updates**. If a newer version is available, tap **Download & install**, then approve Android's installation prompt. **Do not uninstall** the existing app: in-place updates preserve the saved credentials and schedules when signed with the established certificate.

## Publishing

Signed APKs staged in `release-packages/` are checked by the release workflow for package identity `com.pilotstart.app`, APK version, and the established signing certificate. GitHub Releases publishes the APK with a SHA-256 digest used by Pilot Start to verify the download. Signing keys and passwords must never be uploaded here.

This is an independent app using an unofficial HondaLink interface. Use remote start only when the vehicle is safely parked outdoors.
