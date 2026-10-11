# WTHz alpha releases

FT8 reception, maps and spectrum analysis in one native Mac workspace.
Public downloads and complete corresponding source for a limited receive-only alpha.
This is not a general compatibility or production-ready build.

The active application is now named WTHz, previously WTHz-D.
The last published binary remains **WTHz-D Alpha 4 build 5**; a renamed WTHz release has not been published.

![Historical development mock-up of the WTHz-D workspace, showing a blue spectrum plot, decoded FT8 messages and a map](assets/workspace-development-mockup.webp)

*Historical development mock-up created before the WTHz rename, not a screenshot of a released WTHz app.*

## Current published alpha

Latest published release: [WTHz-D Alpha 4 build 5](https://github.com/mint5auce/wthz-releases/releases/tag/v0.1.0-alpha.4), with [publication verification](releases/v0.1.0-alpha.4/VERIFICATION.md).
The verification record distinguishes completed checks from unperformed checks accepted by the owner for this limited alpha.

Requires Apple Silicon and macOS 27.0 or later.
For the historical Alpha 4 release, download the DMG from [Releases](https://github.com/mint5auce/wthz-releases/releases), drag WTHz-D into Applications and select Simulator to explore without a radio.
The app cannot tune the radio, assert PTT or transmit.
Experimental Wi-Fi audio and spectrum are included; Wi-Fi FT8 remains disabled.
Unreleased enhancements in the current WTHz source are not included in Alpha 4.

Every release includes its exact complete corresponding-source archive, release manifest and SHA-256 checksums.
The automatic GitHub source archives for this distribution repository contain only distribution metadata; download the Corresponding-Source asset for the actual application and dependency source.
The development repository remains private.
Project source is GPL-3.0-only; dependency licences and notices are retained in the installed app and corresponding-source packet.

## Future WTHz installation and updates

The first installation of the renamed WTHz app will be manual after a signed release is published.
There is no automatic upgrade bridge from the WTHz-D application identity.
The reserved future feed is `https://wthz.app/updates/appcast.xml`; it is not a published WTHz update service yet.
The historical WTHz-D feed remains unchanged.
Existing release files, tags, manifests, source archives, mock-up and verification records retain their original names and contents.

## Problem reports

Use [Issues](https://github.com/mint5auce/wthz-releases/issues) for problem reports.
Include the version, macOS version, Mac/radio models, connection type and reproduction steps.
Omit credentials, private logs, station data and recordings from public reports.
