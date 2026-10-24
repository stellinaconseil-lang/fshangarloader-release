# FSHANGARLOADER — releases

Official download and update feed for **FSHANGARLOADER**, the FSHANGAR Windows application for MSFS (version 1.7 and later).

This repository contains only release binaries, installers and update metadata. There is no source code here.

- **Download:** [latest release](https://github.com/stellinaconseil-lang/fshangarloader-release/releases/latest). Use `FSHangarLoader-loader-win-Setup.exe`.
- **Updates:** once FSHANGARLOADER is installed, it checks this feed itself (Settings → Check for updates). An update is never installed during a flight.
- **Coming from FSHANGAR 1.6.2:** the 1.6.2 updater does not see FSHANGARLOADER, because they are two different applications. Install 1.7 manually with the setup above, then pair it on fshangar.app.

## Windows SmartScreen
The installer is not code-signed yet, so Windows SmartScreen may warn about an unrecognised app. Before you run it:
1. check that you downloaded it from this page;
2. compare its SHA-256 with the value published in the release notes.

Do not turn off SmartScreen or any other Windows protection.
