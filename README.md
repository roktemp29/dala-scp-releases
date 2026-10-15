# DALA·AEP SCP — Public Releases

This repository contains **public release information and compiled installers only**. The application's source code is maintained in a separate private repository.

## Publishing a release

1. Build and test the Windows installer from the private source repository.
2. Create a GitHub Release in this repository with a version tag such as `v1.3`.
3. Upload the installer using the exact filename `DALA-AEP-SCP-Setup.exe`.
4. Update `latest.json` with the new version, minimum supported version, release notes, and SHA-256 checksum of the installer.
5. Test the public download link and in-app update flow before announcing the release.

## Important

- Never upload source code, access tokens, signing keys, or secrets here.
- Users should not need a GitHub account to download public releases.
- The installer must be tested on Windows before release.
- The app updater should verify the installer SHA-256 against `latest.json` before launching it.

The current manifest is a placeholder for version 1.2; no newer installer is published yet.
