# Astroguru 1.1.0 desktop application

[Download the complete Astroguru 1.1.0 ZIP](https://github.com/menababu-debug/AstroGuru/raw/refs/heads/main/Astroguru-1.1.0.zip)

## What changed

- Modern consultation studio dashboard, dark sidebar, spacious cards and lavender/ivory styling.
- Ten-step reading workflow: five client-information pages, right palm, left palm, calculation settings, review and generation.
- Explicit client-right/client-left hand labels; rectangular palm alignment instead of hand silhouettes. Photographs are not manually mirrored or stretched.
- Optional local Clear background control with tolerance, preview and Restore original background. Plain-background removal requires manual checking; originals are preserved.
- Offline birthplace suggestions automatically fill country, coordinates and a suggested timezone. Ambiguous city names require selection, and country can be corrected manually. Historical timezone verification remains required.

The ZIP includes complete Python/Qt desktop source, Windows setup/build scripts, an operator guide, calculation rules, licensing and limitations documentation, and fictional sample reports, charts and updated screenshots.

## Update or run on Windows

1. Close Astroguru and save an encrypted backup through Settings if you already have records.
2. Extract this ZIP into a new folder.
3. Open its Astroguru folder and double-click Start-Astroguru.cmd. CPython 3.12 x64 is required; the first launch installs dependencies.
4. Use your existing vault password. The default data folder and vault format are unchanged, so existing records remain available. Keep the same ASTROGURU_DATA_DIR if you use a custom data location.

Do not delete or overwrite your client vault folder. Follow Astroguru/README.md for complete instructions.

To build Astroguru.exe and Astroguru-Setup.exe, install Inno Setup 6 and run build-windows.ps1 on Windows. Windows binaries are not included and were not built or tested in the Linux development environment.

## Verification and scope

51 automated tests passed, along with source and frozen Linux offline end-to-end smoke checks. Tests cover the new navigation, hand labels, rectangular clipping, country lookup, background preview/restoration and preserved originals, alongside existing calculations, storage and PDF tests. Live AI access requires your own API credentials. Read LIMITATIONS.md, VERIFICATION.md and LICENSING.md before using real client data or distributing commercially.

## License

AGPL-3.0-or-later; included third-party notices and commercial distribution requirements apply. Offline GeoNames data is CC BY 4.0. The ZIP contains no client vault or API credentials.
