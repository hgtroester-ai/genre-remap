# Release checklist — Genre Remap 3.3.0

## Completed
- [x] Baseline: confirmed working Genre Remap 3.2.0 source.
- [x] HGT License 1.0 replaces PolyForm Noncommercial for original Genre Remap code/documentation.
- [x] Commercial use of music made with the extension is expressly permitted.
- [x] Unmodified extension may be shared free of charge with notices retained.
- [x] Paid distribution/bundling of the extension and distribution of modified versions require prior written permission.
- [x] Phazite CC0 provenance and uploaded archive SHA-256 recorded.
- [x] Third-party notice identifies the embedded Ableton Extensions SDK runtime and its separate rights.
- [x] Source archive excludes standalone SDK runtime backup; build instructions explain that the SDK runtime must be obtained separately from Ableton.
- [x] GUI build label, package version, and extension manifest version all read 3.3.0.
- [x] 37 embedded MP3 payload records retained and unchanged.
- [x] Installable .ablx contains LICENSE.md, THIRD-PARTY-NOTICES.md, and SOUND-ASSETS.md.
- [x] Source ZIP contains source, tests, build script, license, notices, sound records, and release notes.
- [x] Automated test suite: 102 passed, 0 failed.
- [x] .ablx and source ZIP integrity and version metadata checked.

## Validation boundary
- The 3.2.0 predecessor was confirmed working in Ableton Live by the project owner.
- Version 3.3.0 changes licensing/release documentation and version metadata; no MIDI or audio behavior was intentionally changed.
- No fresh Ableton Live installation/startup or audio audition of 3.3.0 was performed in this build environment.
- The embedded SDK runtime remains in the .ablx, as in the 9.6.2 release workflow. Its standalone SDK package/source is not included in the source ZIP. This checklist records packaging treatment, not an independent legal opinion on Ableton's SDK terms.
