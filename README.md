# Filmic Fade

Filmic Fade is a photochemical-style dissolve transition for Adobe Premiere Pro
2026. It replaces a flat digital opacity fade with density-driven behavior:
highlights hold, shadows fall away, color stays dye-like, and the tail eases
into black or back into the image.

This public repository hosts signed installer downloads. The source repository
is private.

## Download

Use the latest GitHub release.

Recommended for most users:

- `FilmicFade-0.16.15.pkg`

Fallback zip:

- `FilmicFade-0.16.15-macOS.zip`

## Install

1. Fully quit Adobe Premiere Pro.
2. Download `FilmicFade-0.16.15.pkg` from Releases.
3. Double-click the package and follow the macOS installer.
4. Reopen Premiere Pro.
5. Find Filmic Fade under `Effects > Video Transitions > Dissolve`.

The package is signed with Developer ID, notarized by Apple, and stapled for
Gatekeeper.

## Zip Fallback

1. Unzip `FilmicFade-0.16.15-macOS.zip`.
2. Keep `FilmicFade.plugin` beside `Install Filmic Fade.command`.
3. Double-click `Install Filmic Fade.command`.
4. Enter your macOS password when prompted.
5. Fully quit and relaunch Premiere Pro.

## Uninstall

Run `Uninstall Filmic Fade.command` from the fallback zip, or remove:

```text
/Library/Application Support/Adobe/Common/Plug-ins/7.0/MediaCore/FilmicFade.plugin
```

## Checksums

Each release includes `SHA256SUMS.txt`.

## Notes

- macOS only for the packaged build.
- Premiere Pro 2026 is the supported target.
