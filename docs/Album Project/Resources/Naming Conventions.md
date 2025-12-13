# Naming Conventions

File naming standards for tracks, stems, samples, and exports.

---

## Overview

Consistent naming conventions are essential for:
- **Speed:** Find files instantly
- **Organization:** No confusion during mixing or archiving
- **Scalability:** Works for future projects
- **Clarity:** Anyone (including future you) can understand the structure

This document covers naming for:
1. Track names (song titles)
2. Ableton session files
3. Audio stems/exports
4. Drum samples
5. Synth patches

---

## 1. Track Names (Song Titles)

### Side A — Song-Based Tracks

**Style:** Fragmented, character-driven, Berlin-leaning (Bowie "Low" aesthetic)

**Naming Pattern:**
- 2-3 words maximum
- Abstract but evocative
- Avoid "The" unless essential
- No numbers in titles (use internally only)

**Examples:**

```
Glass Corridor
Motor Error
Static Companion
Red Logic
Corridor No. 5
Faultline Waltz
Human Index
Blue Artery
Minor Transit
Paper Satellites
The Uncertain Engine
Metallic Sleep
2AM Geometry
The Blind Frequency
A Smile in Code
```

**Internal Reference:**
```
Track 1 — [Your Title]
Track 2 — [Your Title]
Track 3 — [Your Title]
Track 4 — [Your Title]
Track 5 — [Your Title]
```

Use "Track 1", "Track 2", etc. during production. Finalize song titles on **Day 14**.

---

### Side B — Ambient Movements

**Style:** Abstract, cosmic, watery (Eno/Jarre aesthetic)

**Naming Pattern:**
- 2-4 words
- Descriptive of mood/texture
- Can reference time, space, light, structure

**Examples:**

```
Arrival in Stillness
Soft Machinery
Night Structures
Breathing Constellation
The Long Shimmer
Stationary Horizon
Cobalt Bloom
Slow Wave Chamber
Light After Memory
The Quiet Particle
Dissolve Into Air
Margins of the Sky
Cloud of Small Voices
Formant Tide
Infinite Blue Circuit
```

**Internal Reference:**
```
Movement I — [Your Title]
Movement II — [Your Title]
Movement III — [Your Title]
Movement IV (optional) — [Your Title]
```

Use "Movement I", "Movement II", etc. during production. Finalize titles on **Day 14**.

---

## 2. Ableton Session Files

### Session Naming Format:

```
YYYYMMDD_ProjectName_Side_TrackNumber_Version.als
```

**Fields:**
- **YYYYMMDD:** Date (makes chronological sorting easy)
- **ProjectName:** Album project name (short, no spaces)
- **Side:** "SideA" or "SideB"
- **TrackNumber:** Track01, Track02, etc. (Side A) or Mov01, Mov02, etc. (Side B)
- **Version:** v01, v02, etc. (optional, for iterations)

**Examples:**

```
20250601_AlbumProject_SideA_Track01_v01.als
20250602_AlbumProject_SideA_Track02_v01.als
20250608_AlbumProject_SideB_Mov01_v01.als
20250609_AlbumProject_SideB_Mov02_v01.als
```

**Benefits:**
- Chronological order (sorted by date)
- Clear side/track identification
- Version control built-in

---

### Session Folder Structure:

```
/Album Project Sessions/
   /Side A/
      20250601_AlbumProject_SideA_Track01_v01.als
      20250602_AlbumProject_SideA_Track02_v01.als
      (etc.)
   /Side B/
      20250608_AlbumProject_SideB_Mov01_v01.als
      20250609_AlbumProject_SideB_Mov02_v01.als
      (etc.)
   /Master/
      20250614_AlbumProject_Master_v01.als
```

---

## 3. Audio Stems / Exports

### Stem Naming Format:

```
TrackNumber_InstrumentName_ProcessingState.wav
```

**Fields:**
- **TrackNumber:** Track01, Track02, etc. (Side A) or Mov01, Mov02, etc. (Side B)
- **InstrumentName:** Drums, Bass, Pad, Lead, Guitar, etc.
- **ProcessingState:** Raw, Wet, Dry, Bus, FX (optional but useful)

**Examples:**

```
Track01_Drums_Wet.wav
Track01_Bass_Dry.wav
Track01_PadProphet_Wet.wav
Track01_LeadNord_Dry.wav
Track01_Guitar_FX.wav
Track02_Drums_Wet.wav
Track02_Bass_Dry.wav
Mov01_DroneMoog_Wet.wav
Mov01_PadFS1R_Wet.wav
```

**Benefits:**
- Clear instrument identification
- Processing state (for recall or mixing elsewhere)
- Sortable by track number

---

### Export Folder Structure:

```
/Album Project Stems/
   /Side A/
      /Track01/
         Track01_Drums_Wet.wav
         Track01_Bass_Dry.wav
         Track01_PadProphet_Wet.wav
         Track01_LeadNord_Dry.wav
      /Track02/
         (etc.)
   /Side B/
      /Mov01/
         Mov01_DroneMoog_Wet.wav
         Mov01_PadFS1R_Wet.wav
      /Mov02/
         (etc.)
   /Master Mixes/
      SideA_RoughMix_20250607.wav
      SideB_RoughMix_20250612.wav
      Album_RoughMix_20250614.wav
```

---

## 4. Drum Sample Naming

### Drum Sample Format:

```
Instrument_Source_Type_Note_Take.wav
```

**Fields:**
- **Instrument:** Kick, Snare14, Snare33, HatC, HatO, Click, Noise, Perc, Tom
- **Source:** XT, Volca, Custom
- **Type:** Primary, OD (Overdrive), Metallic, Reverse, Soft, Hard, etc.
- **Note:** C1, Cs1 (C#1), D1, Ds1 (D#1), etc.
- **Take:** 01, 02, 03 (use best take in Drum Rack)

**Examples:**

```
Kick_XT_Primary_C1_01.wav
Kick_XT_Primary_C1_02.wav
Kick_Volca_OD_Cs1_01.wav
Snare14_XT_D1_01.wav
Snare33_XT_Ds1_01.wav
HatC_XT_Fs1_01.wav
HatC_Volca_Fs1_01.wav
HatO_XT_Gs1_01.wav
Click_Metallic_A1_01.wav
Noise_Reverse_As1_01.wav
Perc_LowTom_F1_01.wav
```

**Benefits:**
- Instantly searchable
- Clear source/type identification
- Easy to swap/update samples

See **"Sampling Checklist"** resource for full workflow.

---

## 5. Synth Patch Naming

### Synth Patch Format:

```
[SYNTH]_[TYPE]_[NAME]
```

**Fields:**
- **SYNTH:** PROPH12, NORD, MOOG, VSYNTH, FS1R, EVOLVER
- **TYPE:** PAD, LEAD, BASS, DRONE, TEXTURE, BELL
- **NAME:** Descriptive name (no spaces, use camelCase or underscores)

**Examples:**

```
PROPH12_PAD_WarmStrings
PROPH12_PAD_DarkEvolving
PROPH12_BASS_SubDeep
PROPH12_DRONE_SubBass
NORD_LEAD_BerlinMelody
NORD_LEAD_SoftJarre
NORD_DRONE_MidLayer
MOOG_BASS_SubDeep
MOOG_LEAD_MoogLead
VSYNTH_TEXTURE_Granular01
VSYNTH_TEXTURE_MetallicShimmer
FS1R_PAD_FormantDrone
FS1R_BELL_FMBell
EVOLVER_PAD_DarkFeedback
EVOLVER_TEXTURE_NoiseTexture
```

**Benefits:**
- Synth identification at a glance
- Type/role clarity (pad vs. lead vs. bass)
- Easy to recall across sessions

**Save all patches on hardware and document in text file (for backup).**

---

## 6. Master Mix Naming

### Master Mix Format:

```
ProjectName_Side_MixType_Date.wav
```

**Fields:**
- **ProjectName:** Album name or short identifier
- **Side:** SideA, SideB, or Album
- **MixType:** RoughMix, FinalMix, Mastered
- **Date:** YYYYMMDD

**Examples:**

```
AlbumProject_SideA_RoughMix_20250607.wav
AlbumProject_SideB_RoughMix_20250612.wav
AlbumProject_Album_RoughMix_20250614.wav
AlbumProject_SideA_FinalMix_20250620.wav
AlbumProject_Album_Mastered_20250625.wav
```

**Benefits:**
- Clear version tracking
- Side identification (if exporting A and B separately)
- Date for chronological sorting

---

## 7. Field Recording / Misc Audio

### Format:

```
Type_Location_Date_Description.wav
```

**Examples:**

```
Field_Room_20250608_Ambience.wav
Field_Street_20250610_Traffic.wav
Sample_Guitar_20250605_FeedbackDrone.wav
Sample_Piano_20250603_PreparedStrings.wav
```

---

## Quick Reference Tables

### Side A Tracks (Internal)

| Internal Name | Suggested Title (finalize Day 14) |
|---------------|-----------------------------------|
| Track 1 | Glass Corridor / Motor Error |
| Track 2 | Static Companion / Red Logic |
| Track 3 | Blue Artery / Metallic Sleep |
| Track 4 | The Uncertain Engine / Faultline Waltz |
| Track 5 | Minor Transit / A Smile in Code |

### Side B Movements (Internal)

| Internal Name | Suggested Title (finalize Day 14) |
|---------------|-----------------------------------|
| Movement I | Arrival in Stillness |
| Movement II | Soft Machinery |
| Movement III | Night Structures |
| Movement IV (opt) | Dissolve Into Air |

---

## Naming Discipline Rules

### DO:
- ✅ Use consistent formats (don't mix styles)
- ✅ Include dates in session and mix files
- ✅ Use descriptive names (avoid "Untitled" or "Test")
- ✅ Backup all files with clear labels
- ✅ Document synth patch names in text file

### DON'T:
- ❌ Use spaces in file names (use underscores or camelCase)
- ❌ Use special characters (avoid !, ?, /, \, etc.)
- ❌ Mix upper/lowercase inconsistently (pick one style)
- ❌ Use vague names ("Track", "Audio 1", "Pad 01")
- ❌ Skip version numbers (always track iterations)

---

## Naming Workflow

### Day 1 (Setup Day):
- Create folder structure
- Name Ableton session: `20250601_AlbumProject_SideA_Track01_v01.als`
- Sample drums and name files using format (see "Sampling Checklist")
- Save synth patches with naming convention

### Days 2-6 (Side A Sketching):
- Name each session: `20250602_AlbumProject_SideA_Track02_v01.als`
- Use internal names: Track01, Track02, etc.
- Export stems with format: `Track01_Drums_Wet.wav`

### Day 7 (Side A Lock-In):
- Export all Side A stems with consistent naming
- Export Side A rough mix: `AlbumProject_SideA_RoughMix_20250607.wav`

### Days 8-11 (Side B Sketching):
- Name sessions: `20250608_AlbumProject_SideB_Mov01_v01.als`
- Use internal names: Mov01, Mov02, etc.
- Export stems with format: `Mov01_DroneMoog_Wet.wav`

### Day 12 (Side B Lock-In):
- Export all Side B stems with consistent naming
- Export Side B rough mix: `AlbumProject_SideB_RoughMix_20250612.wav`

### Day 13 (Cohesion Day):
- Ensure all files follow naming convention
- Organize stems into folders

### Day 14 (Album Wrap):
- **Finalize track titles** (replace "Track 1" with actual song name)
- Export album rough mix: `AlbumProject_Album_RoughMix_20250614.wav`
- Update all file names with final track titles (if desired)
- Backup entire project with clear labels

---

## File Organization Summary

```
/Album Project/
   /Sessions/
      /Side A/
         (Ableton session files)
      /Side B/
         (Ableton session files)
      /Master/
         (Master session for sequencing)
   /Stems/
      /Side A/
         /Track01/
         /Track02/
         (etc.)
      /Side B/
         /Mov01/
         /Mov02/
         (etc.)
   /Drums/
      /XT/
         /Kick/
         /Snare14/
         /Hats/
         (etc.)
      /Volca/
         (etc.)
      /FX/
         (etc.)
   /Synth Patches/
      Prophet12_Patches.txt
      NordLead_Patches.txt
      (etc.)
   /Master Mixes/
      AlbumProject_SideA_RoughMix_20250607.wav
      AlbumProject_SideB_RoughMix_20250612.wav
      AlbumProject_Album_RoughMix_20250614.wav
   /Field Recordings/ (if used)
      (audio files)
   /Docs/
      Cheat Cards, Resources, etc.
```

---

## Summary

This Naming Conventions resource provides:
- ✓ Track name ideas (Bowie/Eno style)
- ✓ Ableton session naming format
- ✓ Stem export naming format
- ✓ Drum sample naming format
- ✓ Synth patch naming format
- ✓ Master mix naming format
- ✓ File organization structure
- ✓ Workflow integration (Days 1-14)

**Consistent naming = faster workflow, less confusion, easier archiving.**

Use these conventions from Day 1 and never lose track of your files again.
