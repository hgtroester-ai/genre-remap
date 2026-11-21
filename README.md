# Genre Remap
### by HGT · Supported with AI

**Transform your drum MIDI. Explore new genres. Shape your groove.**

Genre Remap is an Ableton Live extension for transforming existing MIDI drum patterns into different musical styles.

Load a MIDI drum pattern, choose a target genre, adjust the remapping and groove settings, preview the result, and create a new MIDI clip in Ableton Live.

![Genre Remap – User Interface](GenreRemap.png)

---

## 1. Key Features

### Genre Transformation

Choose a target style for your existing MIDI drum pattern:

- Classic Rock
- Blues Rock
- Alternative Rock
- Punk
- Funk
- Hip-Hop
- Reggae
- Ska

Genre Remap adapts the drum pattern to the selected musical style while retaining the source material as the basis for the transformation.

### MIDI Import

- Load a MIDI file for transformation.
- Drag and drop a `.mid` file into the MIDI input area.
- Analyze the loaded MIDI pattern before creating the remapped version.
- Select the MIDI track and destination clip slot in Ableton Live.

### Groove and Performance Settings

Adjust the character of the transformed drum pattern using the available remapping and performance controls.

- **Remap Strength:** Set how strongly the source pattern is transformed.
- **Target Tempo:** Set the desired tempo for the remapped pattern.
- **Drummer Profile:** Select a playing character for supported genre-specific processing.
- **Fill Engine:** Add genre-aware fills and control their placement and behaviour.
- **Phrase and Variation Settings:** Shape the development and variation of generated fills.
- **MIDI Mapping:** Select the appropriate drum note layout for the destination instrument.

The available controls and options depend on the selected genre and processing mode.

### Preview Studio

Audition the source and processed drum pattern before creating the new MIDI clip.

- Preview the original pattern.
- Preview the processed pattern.
- Compare original and processed versions.
- Adjust preview volume.
- Use loop and stop controls.

### Four-Layer Velocity Audio Preview

The preview engine uses 37 embedded MP3 sound payloads derived from **Phazite Sounds** and declared under **CC0 1.0 Universal**.

- Nine instruments use four velocity layers each.
- Crash uses one dedicated long-decay one-shot.
- MIDI velocity selects the corresponding preview layer.
- Natural / Balanced / Expressive preview behaviour and Sensitivity shape the effective velocity.
- Preview processing includes level protection, stereo panning and mixer controls.

The preview sound set covers Kick, Snare, Rim / Side Stick, Floor Tom, Low Tom, High Tom, Closed Hi-Hat, Open Hi-Hat, Crash and Ride.

### MIDI Clip Creation

After previewing the result, create the transformed MIDI pattern as a new MIDI clip in Ableton Live. The generated MIDI can be edited further in Live and used as part of your own production.

---

## 2. How to Use

**Step 1 – Load a MIDI Drum Pattern**

Choose a `.mid` file or drag it into the MIDI input area.

**Step 2 – Select the Target Genre**

Choose one of the available musical styles.

**Step 3 – Adjust the Transformation**

Set Remap Strength, Target Tempo and the available groove, drummer and fill options.

**Step 4 – Choose the MIDI Destination**

Select the target MIDI track and clip slot in Ableton Live.

**Step 5 – Preview the Result**

Listen to the original and processed patterns. Compare them and adjust the settings as needed.

**Step 6 – Create the MIDI Clip**

Create the transformed MIDI clip in Ableton Live and continue editing it in your project.

---

## 3. Installation & Requirements

### System Requirements

- Ableton Live with JavaScript Extensions support.
- macOS or Windows systems supported by Ableton Live.
- Ableton Live Suite with Extensions support.

**Important:** Ableton Extensions are not available in Live Standard, Intro or Lite.

### Installation

1. Download the latest `.ablx` file from GitHub Releases.
2. Open Ableton Live.
3. Navigate to **Settings / Preferences → Extensions**.
4. Select **Install Extension** and choose the downloaded `.ablx` file. Alternatively, drag the `.ablx` file onto the Extensions settings page.
5. Restart Ableton Live if required.

### Updates

1. Visit the GitHub Releases section.
2. Download the latest `.ablx` package.
3. Install the updated extension through Live's Extensions settings.
4. Restart Live if required.

---

## 4. Compatibility & Technology

- Built with the Ableton Live JavaScript Extensions SDK.
- Available as an installable Ableton Extension (`.ablx`).
- The installable extension contains its embedded runtime bundle.
- Rebuilding from source requires the corresponding Ableton Extensions SDK runtime obtained separately from Ableton.

No separate JavaScript development environment or SDK installation is required to use the pre-built `.ablx` package.

---

## 5. Audio Assets, Sources & Licenses

### Audio Preview — Phazite Sounds

The current Genre Remap 3.3.0 preview uses **37 embedded MP3 sound assets derived from Phazite Sounds**, documented under the **CC0 1.0 Universal** dedication.

- **Sound source:** [Phazite Sounds](https://github.com/august-byrne/phazite-sounds)
- **License:** [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)

The preview set contains four velocity layers each for Kick, Snare, Rim / Side Stick, Floor Tom, Low Tom, High Tom, Closed Hi-Hat, Open Hi-Hat and Ride, plus one dedicated long-decay Crash one-shot.

MIDI velocity selects one of four recorded layers: 1–31, 32–63, 64–95 and 96–127. The MP3 preview payloads are embedded in the extension. The original WAV/FLAC recordings are not included as loose files in the release source archive.

HGT names Phazite Sounds as the source for transparency. The supplied source archive and embedded payload details are recorded in `SOUND-ASSETS.md` and `SOUND-ASSET-MANIFEST.json`.

### MIDI Mapping Compatibility

Third-party product names used for MIDI mapping identify note assignments only. They do not indicate that recordings, samples, presets or software from those manufacturers are included.

### Project and Third-Party Licenses

The HGT License 1.0 applies to the original Genre Remap software and documentation authored by HGT. It does not replace or change the separate CC0 1.0 dedication for Phazite sound assets or the license terms for the Ableton Extensions SDK runtime.

For detailed information, see the files included in the source package:

- `LICENSE.md` — HGT License 1.0
- `THIRD-PARTY-NOTICES.md` — third-party components, sound assets and trademark notices
- `SOUND-ASSETS.md` — Phazite Sounds provenance and audio asset details
- `SOUND-ASSET-MANIFEST.json` — embedded audio payload hashes and byte lengths

For the central documentation covering all three HGT Ableton Extensions:

- [Sources & Documentation](https://github.com/hgtroester-ai/hgt-ableton-extensions/tree/main/Documentation)
- [Sources — English](https://github.com/hgtroester-ai/hgt-ableton-extensions/blob/main/Documentation/SOURCES.md)
- [Quellen — Deutsch](https://github.com/hgtroester-ai/hgt-ableton-extensions/blob/main/Documentation/SOURCES_DE.md)

---

## 6. Downloads

**Latest release: Genre Remap 3.3.0**

- [Download installable Ableton Extension (.ablx)](https://github.com/hgtroester-ai/genre-remap/releases/download/v3.3.0/Genre_Remap_3.3.0.ablx)
- [Download complete source code (.zip)](https://github.com/hgtroester-ai/genre-remap/releases/download/v3.3.0/Genre_Remap_3.3.0_Source.zip)

Check [GitHub Releases](https://github.com/hgtroester-ai/genre-remap/releases) for version numbers, updates and release notes.

---

## 7. About HGT

**The only good system is a sound system.**

Music connects people.

Independent development, creative ideas and a shared passion for music.

**HGT – Developed with passion. Shared with the community.**

Free to use. Community supported.
