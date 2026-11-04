# Tidy for Mac: downloads

This repository holds the installer for Tidy's private beta.

**Download the latest:** https://github.com/mduong-glpeak/tidy-releases/releases/latest/download/Tidy.dmg

The tester page has the same button and the install steps: https://desktop-organizer-production.up.railway.app

Requires macOS 14 Sonoma or later. Runs on Apple silicon and Intel Macs. Signed with a Developer ID and notarized by Apple, so it opens without warnings beyond the usual "downloaded from the internet" question.

## Installing

1. Open `Tidy.dmg`.
2. Drag Tidy onto the Applications folder next to it.
3. Open Tidy from Applications. When macOS asks about an app downloaded from the internet, click Open.
4. Follow the setup. When macOS asks whether Tidy may access your Desktop, click Allow.

## Releases

Each release has one file named exactly `Tidy.dmg`. The download link above always serves it from the newest full release; pre-releases and drafts are skipped. Releases are built and published with `app/scripts/release.sh` and `app/scripts/publish.sh` in the main repository.
