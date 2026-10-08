# Astroguru desktop application

[Download the complete Astroguru delivery ZIP](https://github.com/menababu-debug/AstroGuru/raw/refs/heads/main/Astroguru-delivery.zip)

The ZIP includes the Python/Qt desktop application source, Windows setup/build scripts, operator guide, calculation rules, licensing and limitations documentation, and clearly labeled fictional sample reports and charts.

## Run on Windows

Extract the ZIP, open the `Astroguru` folder and run `Start-Astroguru.cmd`. Install CPython 3.12 x64 first. Follow `Astroguru/README.md` for complete instructions.

To build `Astroguru.exe` and `Astroguru-Setup.exe`, install Inno Setup 6 and run `build-windows.ps1` on Windows. Windows binaries are not included and were not built or tested in the Linux development environment.

## Verification and scope

42 automated tests passed, along with a frozen Linux offline end-to-end smoke test. Live AI access requires your own API credentials. Read `LIMITATIONS.md`, `VERIFICATION.md` and `LICENSING.md` before using real client data or distributing commercially.

## License

AGPL-3.0-or-later; included third-party notices and commercial distribution requirements apply. The ZIP contains no client vault or API credentials.
