# Filmic Fade Releases

This repository hosts public installer downloads for Filmic Fade, a
photochemical-style fade transition for Adobe Premiere Pro 2026.

The source repository is private. Public downloads are attached to GitHub
Releases here.

## Install

1. Fully quit Adobe Premiere Pro.
2. Open the latest release.
3. Download `FilmicFade-0.5.6.pkg`.
4. Double-click the package and follow the macOS installer.
5. Reopen Premiere Pro.
6. Find Filmic Fade under `Effects > Video Transitions > Dissolve`.

If macOS blocks the unsigned package, right-click it and choose `Open`.

## Zip Fallback

If the package installer does not work:

1. Download `FilmicFade-0.5.6-macOS.zip`.
2. Unzip it.
3. Keep `FilmicFade.plugin` beside `Install Filmic Fade.command`.
4. Double-click `Install Filmic Fade.command`.
5. Enter your macOS password when prompted.
6. Fully quit and relaunch Premiere Pro.

## Uninstall

Run `Uninstall Filmic Fade.command` from the zip download, or remove:

```text
/Library/Application Support/Adobe/Common/Plug-ins/7.0/MediaCore/FilmicFade.plugin
```

## Checksums

Each release includes `SHA256SUMS.txt`.
