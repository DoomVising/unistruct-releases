# UniStruct Releases

This repository contains public UniStruct Android release metadata and signed APK files only.

The application source code, credentials, environment files, signing keys and backend configuration are intentionally not stored here. APK files are accepted only after the private source repository's release verifier confirms their SHA-256 digest and the release catalog contents.

## Files

- `release-catalog.json`: machine-readable release notes and verified APK metadata.
- GitHub Releases: signed APK assets named `unistruct-VERSION.apk`.

The UniStruct app verifies the downloaded APK digest, Android package name, version code and signing certificate before opening the Android installer.
