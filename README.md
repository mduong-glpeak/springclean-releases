# Spring Clean for Mac: downloads

Spring Clean sorts your Mac's Desktop and Downloads into folders you describe in your own words. This repository holds its releases. More at https://springclean.io.

**Download the latest:** https://github.com/mduong-glpeak/springclean-releases/releases/latest/download/SpringClean.dmg

Requires macOS 14 Sonoma or later. Runs on Apple silicon and Intel Macs. Signed with a Developer ID and notarized by Apple, so it opens without warnings beyond the usual "downloaded from the internet" question.

## Installing

1. Open `SpringClean.dmg`.
2. Drag Spring Clean onto the Applications folder next to it.
3. Open Spring Clean from Applications. When macOS asks about an app downloaded from the internet, click Open.
4. Follow the setup. When macOS asks whether Spring Clean may access your Desktop, click Allow. If it asks for a license key, paste the one from the email you got when you bought Spring Clean.

## Updates

Spring Clean updates itself. Each copy checks the `appcast.xml` on the newest release and offers the update from its menu bar icon.

## Releases

Each release has one file named exactly `SpringClean.dmg` and an `appcast.xml` for updates. The download link above always serves the newest full release; pre-releases and drafts are skipped. Releases are built and published with `app/scripts/release.sh` and `app/scripts/publish.sh` in the main repository.
