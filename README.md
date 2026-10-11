# WTHz alpha releases

FT8 reception, maps and spectrum analysis in one native Mac workspace.
Public downloads and complete corresponding source for a limited receive-only alpha.
This is not a general compatibility or production-ready build.

The active application is now named WTHz, previously WTHz-D.
The current published binary is **WTHz Alpha 5 build 6**, with the renamed application identity and overnight receive enhancements.

![Historical development mock-up of the WTHz-D workspace, showing a blue spectrum plot, decoded FT8 messages and a map](assets/workspace-development-mockup.webp)

*Historical development mock-up created before the WTHz rename, not a screenshot of a released WTHz app.*

## Current published alpha

Latest published release: [WTHz Alpha 5 build 6](https://github.com/mint5auce/wthz-releases/releases/tag/v0.1.0-alpha.5), with [publication verification](releases/v0.1.0-alpha.5/VERIFICATION.md).
The verification record distinguishes completed checks from unperformed checks accepted by the owner for this limited alpha.

Requires Apple Silicon and macOS 27.0 or later.
Download the Alpha 5 DMG from [Releases](https://github.com/mint5auce/wthz-releases/releases/tag/v0.1.0-alpha.5), retain your previous app and data backups, drag WTHz into Applications and select Simulator to explore without a radio.
The app cannot tune the radio, assert PTT or transmit.
Experimental Wi-Fi audio and spectrum are included; Wi-Fi FT8 remains disabled.
Alpha 5 includes Activity filters and wanted alerts, spectrum averaging and traces, a generic receive-audio foundation, and optional PSK Reporter and WSJT-X UDP output.
External reporting defaults to off; generic input and external-service compatibility retain their documented acceptance limits.
Production FT8 remains at Normal depth; Fast and Deep are debug experiments.

Every release includes its exact complete corresponding-source archive, release manifest and SHA-256 checksums.
The automatic GitHub source archives for this distribution repository contain only distribution metadata; download the Corresponding-Source asset for the actual application and dependency source.
The development repository remains private.
Project source is GPL-3.0-only; dependency licences and notices are retained in the installed app and corresponding-source packet.

## WTHz installation and updates

The first installation of the renamed WTHz app is manual.
Keep previous data and private backups for the controlled transfer; re-enter radio credentials and reselect the audio input.
There is no automatic upgrade bridge from the WTHz-D application identity.
The signed WTHz feed is live at [wthz.app/updates/appcast.xml](https://wthz.app/updates/appcast.xml).
The historical WTHz-D feed remains unchanged.
Existing release files, tags, manifests, source archives, mock-up and verification records retain their original names and contents.

## Problem reports

Use [Issues](https://github.com/mint5auce/wthz-releases/issues) for problem reports.
Include the version, macOS version, Mac/radio models, connection type and reproduction steps.
Omit credentials, private logs, station data and recordings from public reports.
