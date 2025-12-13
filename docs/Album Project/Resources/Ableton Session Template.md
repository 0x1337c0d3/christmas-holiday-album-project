# Ableton Session Template

Complete track layout for Side A and Side B sessions.

---

## Overview

This is your **master template** for both Side A and Side B Ableton sessions. Colors are suggestions to keep things visually grouped.

**Workflow:**
- Keep this as a master template
- Duplicate and rename per track or per day
- Example: `2025-12-20_A01_OpeningFragment`

---

## Track Layout

### 1–4: Drums (Side A focus)

**1. DRUMS – SIDE A MAIN KIT (yellow)**
- Device: Drum Rack with sampled XT/Volca kit
- Purpose: Primary drums for all Side A tracks
- Processing: Plate reverb, tape saturation, bus compression

**2. PERC – FX / NOISE (yellow)**
- Device: Secondary Drum Rack or Simpler
- Purpose: Metallic clicks, reverse hits, noise bursts
- Contents: 5 FX samples (click, reverse, tom, rim, wood)

**3. DRUMS PARALLEL (orange)**
- Type: Return-style audio track
- Purpose: Parallel compression/saturation if needed
- Processing: Heavy compression + saturation (blended in)

**4. DRUMS PRINT (grey)**
- Type: Audio track
- Purpose: Print final drum stem (optional)
- Use: Freeze/commit drums when satisfied

---

### 5–12: Hardware Synths (External Instrument tracks)

**5. PROPHET 12 – PADS (blue)**
- Device: External Instrument
- MIDI Out: To Prophet 12
- Audio In: Apogee Ensemble Inputs 1-2
- Purpose: Primary pads and harmonic beds (Side A & B)

**6. NORD 2X – LEADS/PLUCKS (red)**
- Device: External Instrument
- MIDI Out: To Nord Lead 2X
- Audio In: Apogee Ensemble Inputs 3-4
- Purpose: Bright leads, plucks, rhythmic chord work (Side A)

**7. MOOG LP – BASS (dark blue)**
- Device: External Instrument
- MIDI Out: To Moog Little Phatty
- Audio In: Apogee Ensemble Input 5 (mono)
- Purpose: Main bass (round, simple, mono)
- Settings: Low-latency monitoring

**8. EVOLVER – TEXTURE / ALT BASS (purple)**
- Device: External Instrument
- MIDI Out: To Dave Smith Evolver
- Audio In: Apogee Ensemble Inputs 10-11 (via ADAT)
- Purpose: Weird modulation, noise, occasional bass variation

**9. FS1R – AMBIENT PADS (teal)**
- Device: External Instrument
- MIDI Out: To Yamaha FS1R
- Audio In: Apogee Ensemble Inputs 8-9 (via ADAT)
- Purpose: Evolving formant pads and ambient textures (mainly Side B)

**10. VSYNTH XT – TEXTURE (cyan)**
- Device: External Instrument
- MIDI Out: To Roland VSynth XT
- Audio In: Apogee Ensemble Inputs 6-7
- Purpose: Live granular / formant work, experimental textures

**11. VOLCA – LIVE PERC (yellow-green)**
- Device: External Instrument (optional)
- Audio In: Apogee Ensemble Inputs (assign available pair)
- Purpose: Live Volca performance beyond sampled kit (optional)

**12. SOFTSYNTH BUS (pink)**
- Device: MIDI to Instrument Rack
- Contents: Fixed Arturia/Omnisphere patches
- Purpose: Supplement hardware with limited soft synths
- Patches: Prophet V, Juno, CS-80, DX7, Omnisphere (granular/air)

---

### 13–16: Guitars, Piano, Ambience

**13. TELE – CLEAN / RHYTHM (green)**
- Type: Audio track
- Audio In: Apogee Ensemble Input 12 (via ADAT)
- Purpose: Clean rhythmic guitar parts (Side A)
- Processing: Light compression, amp sim

**14. TELE – SWELLS / EBOW (light green)**
- Type: Audio track
- Audio In: Apogee Ensemble Input 12 (via ADAT)
- Purpose: Long reverb/delay chain for ambient swells (Side B)
- Processing: Long hall reverb, delay, volume swells

**15. PIANO – UPRIGHT (brown)**
- Type: Audio track
- Audio In: Stereo pair (room mics + close mic)
- Purpose: Sparse motifs, heavily processed on Side B
- Processing: Can feed both short and long reverbs

**16. AMBIENCE / FIELD (grey-blue)**
- Type: Audio track
- Purpose: Room/foley/texture recordings
- Contents: Field recordings, found sounds, room ambience

---

### 17–20: Side B Specific

**17. DRUMS – SIDE B PERC (light yellow)**
- Device: Drum Rack
- Contents: Very minimal ambient percussion
- Sounds: Soft kick, low tom, brushed click, reverse texture
- Processing: Long hall reverb, highpass filter, very quiet

**18. AMBIENT BUS (dark teal)**
- Type: Group bus
- Purpose: Group bus for drones/pads (Side B)
- Processing: Light compression, long reverb send

**19. DRONE PRINT (dark grey)**
- Type: Audio track
- Purpose: Stereo print of long drones if you want to commit
- Use: Freeze/commit drones to save CPU

**20. FX PRINT (dark purple)**
- Type: Audio track
- Purpose: Bounced FX swells, reverses, transitions
- Use: Print textural elements for arrangement

---

## Returns (A–D)

### Return A: PLATE VERB (short)
- Device: Ableton Reverb
- Type: Plate
- Decay: 0.3–0.6 seconds
- Pre-Delay: 20 ms
- Purpose: Side A drums, synths, leads
- Dry/Wet: 100% (controlled by sends)

### Return B: HALL VERB (long)
- Device: Ableton Reverb
- Type: Hall
- Decay: 10–30 seconds
- Pre-Delay: 60 ms
- Purpose: Side B pads, swells, piano/guitar tails
- Dry/Wet: 100% (controlled by sends)

### Return C: DELAY
- Device: Ableton Delay or Echo
- Type: Tempo-synced (eighths or dotted eighths)
- Purpose: Mostly Side A leads and rhythmic elements
- Feedback: 20-40%
- Filter: Highpass at 300 Hz, lowpass at 8 kHz

### Return D: SPECIAL FX
- Device: Modulation chain (frequency shifter, phaser, etc.)
- Purpose: Weird processing, experimental textures
- Use: Sparingly, for specific moments
- Examples: Frequency shifter, ring mod, granular

---

## Groups (Optional)

### GROUP – DRUMS
- Contains: Tracks 1–3 (Drums Main Kit, Perc FX, Drums Parallel)
- Processing: Bus compression, saturation
- Purpose: Unified drum processing

### GROUP – SIDE A MUSIC
- Contains: Core synths + Tele/Piano used on songs
- Tracks: Prophet 12, Nord 2X, Moog LP, Tele Clean, Piano
- Purpose: Song-based elements (Side A focus)

### GROUP – SIDE B AMBIENT
- Contains: FS1R, Prophet pads, VSynth XT, Tele swells, Piano
- Tracks: FS1R, Prophet 12 (ambient patches), VSynth XT, Tele Swells, Piano
- Purpose: Ambient elements (Side B focus)

### GROUP – PRINTS
- Contains: All print tracks and bounces
- Tracks: Drums Print, Drone Print, FX Print
- Purpose: Organization and archiving

---

## Color Coding Guide

| Color | Purpose |
|-------|---------|
| Yellow | Drums (sampled kits) |
| Orange | Parallel processing |
| Grey | Print/bounce tracks |
| Blue | Prophet 12 (primary pads) |
| Red | Nord Lead (leads/plucks) |
| Dark Blue | Moog (bass) |
| Purple | Evolver (textures) |
| Teal | FS1R (ambient) |
| Cyan | VSynth XT (experimental) |
| Yellow-Green | Volca (live perc) |
| Pink | Soft synths |
| Green | Telecaster (rhythm) |
| Light Green | Telecaster (ambient) |
| Brown | Piano |
| Grey-Blue | Field recordings |
| Dark Teal | Ambient bus |
| Dark Grey | Drone prints |
| Dark Purple | FX prints |

---

## Session Naming Convention

Use this format for each session:

```
YYYYMMDD_ProjectName_Side_TrackNumber_Version.als
```

**Examples:**
- `20251220_AlbumProject_SideA_Track01_v01.als`
- `20251221_AlbumProject_SideA_Track02_v01.als`
- `20251227_AlbumProject_SideB_Mov01_v01.als`

---

## Workflow Notes

### Day 1 (Setup):
1. Create master template with all tracks
2. Set up External Instruments (test MIDI/audio routing)
3. Load Drum Rack with sampled XT/Volca kit
4. Configure all returns (reverbs, delay, FX)
5. Save as: `MASTER_TEMPLATE.als`

### Days 2-6 (Side A Tracks):
1. Duplicate master template
2. Rename session: `YYYYMMDD_AlbumProject_SideA_Track0X_v01.als`
3. Work only on needed tracks (mute/hide others)
4. Bounce rough mix at end of session
5. Save and close

### Days 8-11 (Side B Movements):
1. Duplicate master template
2. Rename session: `YYYYMMDD_AlbumProject_SideB_Mov0X_v01.als`
3. Focus on tracks 9, 5, 10, 14, 15 (FS1R, Prophet, XT, Tele Swells, Piano)
4. Use Return B (Long Hall) extensively
5. Bounce rough mix at end of session
6. Save and close

### Days 7, 12 (Lock-In):
1. Create new session: `YYYYMMDD_AlbumProject_SideA_LockIn_v01.als`
2. Import all track bounces
3. Arrange in sequence
4. Add transitions (if needed)
5. Export Side A or Side B rough mix
6. Export all stems

### Day 13 (Cohesion):
1. Create new session: `YYYYMMDD_AlbumProject_Album_Cohesion_v01.als`
2. Import Side A and Side B rough mixes
3. Check tonal arc, add connective elements
4. Rough balance between sides
5. Export full album rough mix

---

## Track Count Summary

- **Total Tracks:** 20 (core layout)
- **Returns:** 4 (A-D)
- **Groups:** 4 (optional)

**Typical Usage:**
- Side A: Tracks 1-8, 12-16, Returns A+C (song-based)
- Side B: Tracks 5, 9-10, 14-19, Returns B+D (ambient)

---

## CPU Management

### To Save CPU:

1. **Freeze tracks** after recording (External Instruments are CPU-heavy)
2. **Print drums** to audio once finalized
3. **Print drones** on Side B (long sustains can be bounced)
4. **Use "Reduce Latency"** mode when mixing (no live recording)
5. **Disable unused tracks** (hide and deactivate)

### External Instrument Settings:

- **Monitor:** Off (when not recording)
- **MIDI To:** Set to specific hardware output
- **Audio From:** Set to specific Apogee input pair
- **Latency Compensation:** Enable (Preferences → Audio)

---

## Quick Start Checklist

Before starting any session:

- ✅ All hardware synths powered on
- ✅ Apogee Ensemble connected and clocking correctly
- ✅ MIDI routing tested (play each External Instrument track)
- ✅ Audio routing tested (hear each hardware synth)
- ✅ Drum Rack loaded with sampled kit (Day 1 only)
- ✅ Returns configured (reverbs, delay, FX)
- ✅ Sample rate: 48 kHz (or 44.1 kHz, stay consistent)
- ✅ Buffer size: 256 samples (recording), 512-1024 (mixing)
- ✅ Session named and saved in correct folder

---

## Summary

This Ableton Session Template provides:
- ✓ 20-track layout optimized for Side A and Side B
- ✓ External Instruments for all hardware synths
- ✓ Dedicated drum tracks with parallel processing
- ✓ Guitar, piano, and field recording tracks
- ✓ Side B-specific ambient tracks
- ✓ 4 return tracks (short/long reverb, delay, special FX)
- ✓ Optional groups for organization
- ✓ Color coding for visual clarity
- ✓ Naming conventions and workflow notes

**Create this template on Day 1, then duplicate for each track/movement.**
