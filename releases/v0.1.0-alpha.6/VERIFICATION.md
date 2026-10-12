# WTHz Alpha 6 build 7 verification

The [Alpha 6 prerelease](https://github.com/mint5auce/wthz-releases/releases/tag/v0.1.0-alpha.6) is published with five immutable assets.
All GitHub upload digests, lengths and anonymous downloads match the frozen release.
The complete corresponding-source archive is 923,359,619 bytes.
The downloaded DMG passes its Sparkle signature, checksum, Gatekeeper and stapled-ticket checks.
Its read-only mounted app matches the final manifest inventory, identifier `app.wthz.mac`, build 7 and Applications shortcut.
The app passes strict nested signatures, stapled-ticket and Gatekeeper checks.
The volume is detached after inspection; no clean installation is claimed.

Cloudflare Pages deploys Signal Lab commit `4ea9d66e78d50c2a13d05310876e4cf824aa8a62` successfully in project `wthz-app`.
The [live feed](https://wthz.app/updates/appcast.xml) and immutable signed notes return HTTP 200 and match the staged bytes.
Both Ed25519 signatures verify with the existing Sparkle identity.
The feed SHA-256 is `8d4ce3aed9415f2ccc2c7c3f403acc4ee057ee65cdf5944d727c964a7df20e7a`.
The signed notes SHA-256 is `1d0721f004943cec6e081a1ee295fd822deed7535a1857deffcd2542741f4728`.
The feed lists alpha-channel builds 7 and 6, macOS 27.0 minimum and no deltas.
The build 6 entry and signed notes remain unchanged.
XML and Markdown types, feed cache revalidation and missing-path HTTP 404 verify.
The WTHz/Sparkle user agent receives the expected feed and missing-path responses.
The existing homepage and historical WTHz-D feed remain byte-identical.
Actual client update installation is not performed.

Critical SwiftPM and arm64 Xcode validation each pass 641 core and 234 app tests, with three core and six native skips and zero failures.
The final Developer ID packaged decoder passes sixteen paced synthetic intervals, identical measured functional results, zero failures or drops and complete cleanup.
The installed licence inventory matches all 1,768 files from Alpha 5, and no third-party dependency is added.
The source verifier checks the exact export and six pinned upstream archives.
The runtime closure contains sixteen thin arm64 entries.
The product change is the owner-selected waterfall W icon, with receive behaviour and data locations unchanged.
The [owner disposition](PUBLICATION.md) accepts the unperformed clean-install, physical USB and independent-install checks for this exact limited alpha.
Manual accessibility and actual client installation remain unverified.
No owner installation, private-data transfer, physical qualification, phase advancement or transmit authority follows from these checks.
