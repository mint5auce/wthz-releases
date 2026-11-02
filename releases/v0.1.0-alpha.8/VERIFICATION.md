# WTHz Alpha 8 build 9 verification

Source commit: `fe6514049075a98fa8023a2e7b7b387aa4a230d6` (see exact commit in the release manifest).
The release introduces the approved family waterfall icon, compact small-size representations and retained vector artwork.
Product behaviour is unchanged from Alpha 7.

The critical SwiftPM and arm64 Xcode gate passes with zero test failures and the documented optional skips.
The signed packaged decoder passes all sixteen paced synthetic intervals with zero failures or drops and identical functional repetitions.
The final notarised helper closure matches the tested closure byte-for-byte.
The complete corresponding-source verifier passes, and all 1,768 installed licence files match Alpha 7.
No new third-party runtime is packaged.
Developer ID signatures, app and DMG notarisation, stapled tickets, DMG checksum and Gatekeeper checks pass.
The read-only mounted application inventory matches the exact release manifest, including build 9 and the Applications shortcut.
The volume was detached without installation.
The appcast, archive and immutable release note signatures verify.
Sparkle's standard feed retention keeps builds 9, 8 and 7; historical release assets and notes are preserved.

Exact clean-install, physical USB, independent-install and full manual accessibility observations remain unperformed.
Actual client update installation remains unperformed.
The owner accepted these exact-artifact gaps and authorised publication on 2 November 2026.
The unperformed tests remain separately recorded and are not represented as passed.

## Completed publication

The Alpha 8 prerelease is public with five immutable assets.
All server-side upload hashes and lengths and all anonymous download hashes match.
The downloaded installer passes its Sparkle signature, checksum, stapled tickets, Gatekeeper and read-only mounted inventory checks.
Cloudflare Pages successfully deployed feed-only commit `f747619410a061663dccff300ae8da2d34e7737e` in project `wthz-app`.
The live signed feed and note match staging bytes and pass MIME, cache and missing-path checks.
Sparkle user agents for builds 8 and 9 receive the expected feed and HTTP 404 for a missing update path.
The feed retains builds 9, 8 and 7 without deltas, and the retained old entries are unchanged.
All historical hosted release notes are unchanged.
The homepage differs only in generated Astro island identifiers, and the frozen historical WTHz-D feed is byte-identical.
The accepted test gaps remain unperformed.
