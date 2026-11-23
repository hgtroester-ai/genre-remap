# Sound asset record — Genre Remap 3.3.0

## Source and license

The selected sound recordings are attributed to **Phazite Sounds**. The official Phazite Sounds project declares its sound assets dedicated to the public domain under **CC0 1.0 Universal**. CC0 permits copying, modification, commercial use, and redistribution without requiring attribution, subject to rights that cannot be waived under applicable law.

- Official project: https://github.com/august-byrne/phazite-sounds
- CC0 1.0 deed: https://creativecommons.org/publicdomain/zero/1.0/
- Supplied source archive: `Phazite_sounds.zip`
- SHA-256: `b4fb636a688ff3e88ca368f837c303744c31fcf722eedb15b722d01ccb52c60f`

The uploaded archive contains the nine instrument source WAV recordings plus `Crash.wav`. The separately supplied `Crash.flac` is the long-decay Crash one-shot used in the build. The archive itself does not contain the upstream repository's `pack/sources.json`; therefore this release records the upstream project's blanket CC0 declaration and the hashes of the actual supplied source files, but does not claim to have a per-file upstream provenance manifest.

## Instrument and layer map

| Preview role | Source recording | Embedded layers |
|---|---|---:|
| Kick | `Kick.wav` | 4 |
| Snare | `Snare Acoustic.wav` | 4 |
| Rim / Side Stick | `Rim Side Stick.wav` | 4 |
| Floor Tom | `Tom Floor.wav` | 4 |
| Low Tom | `Tom Low.wav` | 4 |
| High Tom | `Tom High.wav` | 4 |
| Closed Hi-Hat | `Hat Closed.wav` | 4 |
| Open Hi-Hat | `Hat Open acoustic.wav` | 4 |
| Ride | `Ride.wav` | 4 |
| Crash | separately supplied `Crash.flac` | 1 long-decay one-shot |

## Processing and embedding

Each of the nine one-bar recordings contains four strikes at approximately 0.606-second intervals (about 99 BPM). The strikes are separated into four velocity layers. MIDI velocity selects the corresponding performance layer: 1–31, 32–63, 64–95, and 96–127. The Crash uses one long-decay one-shot because the crash tails overlap in the multi-hit recording.

The preview payloads are encoded as MP3 at 320 kbit/s, 44.1 kHz and embedded in the UI source. The extension contains 37 payloads in total: 9 instruments × 4 layers plus one Crash one-shot. The original WAV/FLAC recordings are not included as loose files in the `.ablx` or source ZIP.

## Distribution boundary

The underlying Phazite source recordings remain subject to CC0 1.0; the HGT software license does not attempt to revoke or narrow those CC0 permissions. The embedded, processed preview payloads are distributed as part of Genre Remap. Anyone reusing those processed payloads separately should retain this provenance record and assess any rights in the particular processing or arrangement in addition to the CC0 status of the source recordings.
