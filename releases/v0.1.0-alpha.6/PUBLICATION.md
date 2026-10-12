# WTHz Alpha 6 build 7 publication

The owner requests committing, pushing and deploying the new waterfall W icon through Sparkle.
The source is `ceb5885fd21069873f35005b14afe3382d313925`.
The exact release manifest is `25f877088a6a186dbea46477298642bf2cc693f0bf2338902a99613bf7a2ab9d`.
Alpha 6 changes the icon; receive behaviour, decoder and data locations are unchanged.
The application requires Apple Silicon and macOS 27.0 or later and remains receive-only.
The matching complete corresponding-source archive is supplied with the release.

Critical validation passes 641 core and 234 app tests in both SwiftPM and arm64 Xcode, with three core and six native skips and zero failures.
The final signed packaged decoder passes all sixteen synthetic intervals, identical functional repetitions, zero failures or drops and complete cleanup.
Source, licence inventory, Developer ID signing, notarisation, stapled tickets, Gatekeeper, mounted-installer inventory and signed feed preparation pass.
Clean-install, physical USB, independent-install and actual client update installation are not performed.
On 12 October 2026, the owner selects "Accept these test gaps and publish" for this exact release manifest.
The three missing checks remain `notPerformed`, with separate `ownerAcceptedRisk` dispositions.
The passed-only preflight requirement is superseded only for this exact limited alpha; all technical verification remains required.
Manual accessibility and actual client update installation remain unverified.
The GitHub prerelease is published with all five immutable assets.
All anonymous downloads and downloaded-installer checks pass.
Cloudflare Pages successfully deploys the signed feed and notes.
HTTPS bytes, signatures, headers and WTHz/Sparkle user-agent checks pass.
The feed offers build 7 followed by build 6, without deltas.
The existing homepage, old WTHz-D feed and build 6 notes remain unchanged.
See [VERIFICATION.md](VERIFICATION.md) and the companion JSON records.
