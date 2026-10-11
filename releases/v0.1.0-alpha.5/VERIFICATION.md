# WTHz Alpha 5 build 6 verification

The [Alpha 5 prerelease](https://github.com/mint5auce/wthz-releases/releases/tag/v0.1.0-alpha.5) is published with all five immutable assets.
GitHub upload digests and lengths match every frozen artifact.
All five anonymous downloads match, including the 922,627,312-byte complete corresponding-source archive.
The downloaded installer passes its Sparkle archive signature, checksum, Gatekeeper and stapled-ticket checks.
Its read-only mounted app matches the exact release manifest inventory and passes strict nested signatures, its stapled ticket and Gatekeeper.
The Applications shortcut and build 6 identity verify, and the volume is detached.
These checks do not constitute installation.

Cloudflare Pages successfully deploys `mint5auce/wthz-signal-lab` commit `2afd49e1f19ce2cbd418e8b5d35795df880c0fe0` in project `wthz-app`.
The [live feed](https://wthz.app/updates/appcast.xml) and signed notes return HTTP 200 and match the prepared bytes exactly.
Both signatures verify with the retained Sparkle signing identity.
The feed SHA-256 is `af4cbed39f3db48fee1c7f099bc7721cc11b785f58cbf2e87c2f17a11956d160`.
The signed-note SHA-256 is `3304b08b899d136f13eae9f60d5a506e40ab2f39ee6d8ede883f691aa614a87c`.
The feed contains only alpha-channel WTHz build 6, the exact installer URL and length, macOS 27.0 minimum and no deltas.
Its XML content type and cache revalidation headers verify; notes use Markdown with immutable caching.
Missing update paths return HTTP 404 with the verification and WTHz/Sparkle user agents.
The default Python user agent receives HTTP 403 from Cloudflare, including for the real feed; no firewall or hosting configuration is changed to bypass this response.
The existing educational homepage and historical WTHz-D feed remain byte-identical.
The first WTHz installation is manual; this feed does not bridge the former application identity.
The future landing-page host must retain these update URLs and all signed published notes.

Critical validation passes 641 core and 234 app tests in both SwiftPM and arm64 Xcode, with three core and six native skips and zero failures.
The final Developer ID packaged decoder passes all sixteen paced synthetic intervals with identical functional repetitions, zero failures or drops, and complete cleanup.
The licence review includes all 1,768 installed licence files and the exact source packet.
The runtime closure contains sixteen thin arm64 entries.
The [owner disposition](PUBLICATION.md#owner-disposition) accepts the unperformed clean-install, physical USB and independent-install checks for this exact artifact.
Manual accessibility and actual client update installation remain unverified.
No owner installation, data transfer, physical qualification, phase advancement or transmit authority follows.

Companion JSON records contain upload, anonymous-download, downloaded-installer, Cloudflare deployment and hosted verification results.
The [release manifest](https://github.com/mint5auce/wthz-releases/releases/download/v0.1.0-alpha.5/release-manifest.json) binds the final artifacts.
