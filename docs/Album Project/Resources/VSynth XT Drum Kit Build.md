# VSynth XT Drum Kit Build

Custom VSynth XT drum patches for consistent, Berlin-era sound palette.

---

## Overview

This guide shows how to build **individual drum patches** on the VSynth XT, each optimized for a specific drum sound. You'll create 5 core patches plus 5 FX/perc patches that can be sampled into Ableton Drum Rack or triggered directly via MIDI.

**Approach:** Create separate patches for each drum sound using XT's PCM/AP synthesis.

**Result:**
- Custom-numbered patches (Kick #28, Snare #14, etc.)
- Consistent sonic character across album
- Fast recall and reproducible
- Berlin Trilogy aesthetic (digital, tight, slightly weird)
- Ready for sampling or direct use

---

## Naming Convention

Use this format for all patches:

```
DR_[Sound]_[Number]
```

**Examples:**
- `DR_Kick_28`
- `DR_Snare_14`
- `DR_Snare_33`
- `DR_CH_06` (Closed Hat)
- `DR_OH_XX` (Open Hat)
- `DR_Click_01`
- `DR_RevNoise_02`
- `DR_LowTom_03`
- `DR_Rim_04`
- `DR_Wood_05`

**Note:** Numbers are just labels for quick reference — they don't matter musically, but they help you pull up the right sound fast during the project.

---

## Core Drum Palette (Locked)

These are your PRIMARY sounds for the entire album:

**Kick:**
- PRIMARY: VSynth XT – Digital Kick #28
- SECONDARY (1 track only): Volca Beats – Kick (pitch-down + overdrive)

**Snare:**
- PRIMARY: VSynth XT Snare #14 (tight digital)
- ALT (1 track only): VSynth XT Snare #33 (metallic/bitcrushed)

**Hi-Hats:**
- Closed Hat: VSynth XT CH #06
- Open Hat (optional): Volca Beats OH (noisy, use sparingly)

**FX / Perc (MAX 5 total for all tracks):**
- Metallic click
- Reverse noise burst (short)
- Low tom
- Processed rimshot
- Woodblock/tick

**Processing Chain (EVERY TRACK):**
- Short plate reverb (0.3–0.5s)
- Mild tape wobble
- Light saturation
- Gentle bus compression

---

## Patch Building Guide

### General Approach

For each drum sound, you'll create a **dedicated patch** (not a multi-tone patch). This makes sampling easier and gives you maximum control over each sound.

**Workflow:**
1. Start with INIT patch
2. Configure oscillator, filter, envelope, FX
3. Save with naming convention
4. Repeat for each drum sound

---

## 1. PRIMARY KICK — "Kick #28"

**Goal:** Punchy, mid-focused digital kick (very "Low"-friendly)

### Source
`PCM > BD DIGITAL`

### Patch Setup

**Oscillator:**
- Structure: Single PCM oscillator
- Waveform: BD DIGITAL (or similar kick PCM)
- Pitch: -12 semitones (or -24 for deeper tone)

**Filter:**
- Type: LPF 12dB
- Cutoff: 40–50 (keeps it punchy, not boomy)
- Resonance: 0–5 (minimal)

**Amp Envelope:**
- Attack: 0
- Decay: 35–45 (tight, controlled)
- Sustain: 0
- Release: 0

**FX:**
- Drive: 5–10% (adds slight edge)
- Reverb: OFF (reverb applied externally in Ableton)

### Character
Punchy, mid-focused, Berlin-era digital kick. Not too deep, sits well in mix.

**Save as:** `DR_Kick_28`

---

## 2. PRIMARY SNARE — "Snare #14"

**Goal:** Tight, digital snare with crisp transient

### Source
`PCM > RHY_SNARE1` (tight digital snare)

### Patch Setup

**Oscillator:**
- Structure: PCM
- Waveform: RHY_SNARE1 (or similar tight digital snare)
- Pitch: Default or -2 (slightly lower for more body)

**Filter:**
- Type: HPF (Highpass) at ~120 Hz (keeps it crisp, removes mud)
- Resonance: 10-15%

**Amp Envelope:**
- Attack: 0
- Decay: 50 (tight but not choked)
- Sustain: 0
- Release: 0

**FX:**
- XT Lo-Fi: Slight bit reduction (adds digital character)
- Optional: EQ peak +3 dB @ 4–6 kHz (transient boost)
- Reverb: OFF (applied externally)

### Character
Tight, digital, crisp. Berlin-era snare with clear transient.

**Save as:** `DR_Snare_14`

---

## 3. ALTERNATE SNARE — "Snare #33"

**Goal:** Metallic, bitcrushed snare (use on ONE track only for contrast)

### Source
`PCM > RHY_SNARE_METAL` or `PCM > RHY_SNARE_DIGI2`

### Patch Setup

**Oscillator:**
- Structure: PCM
- Waveform: RHY_SNARE_METAL (or similar metallic/digital snare)
- Pitch: +2 to +5 (brighter, more aggressive)

**Filter:**
- Type: LPF 12dB
- Cutoff: ~80 (controlled brightness)
- Resonance: 20-30% (light resonance for character)

**Amp Envelope:**
- Attack: 0
- Decay: 40-50 (slightly shorter than primary snare)
- Sustain: 0
- Release: 0

**FX:**
- XT Lo-Fi: Higher bit reduction (more digital crunch)
- Optional: Slight ring modulation (adds metallic edge)
- Reverb: OFF

### Character
Harsh, digital, metallic. Use sparingly for one "weird" track on Side A.

**Save as:** `DR_Snare_33`

---

## 4. CLOSED HAT — "CH #06"

**Goal:** Tight, digital closed hi-hat

### Source
`PCM > RHY_CHHAT1` or `AP SYNTH > Perc Noise`

### Patch Setup

**Oscillator:**
- Structure: PCM or Noise OSC
- Waveform: RHY_CHHAT1 (or band-limited noise)
- Pitch: +3 to +7 (brighter)

**Filter:**
- Type: HPF (Highpass) around 300–500 Hz (removes low-end)
- Resonance: 0 (clean, no resonance)

**Amp Envelope:**
- Attack: 0
- Decay: 10–20 (very short, tight)
- Sustain: 0
- Release: 0

**FX:**
- No FX (keep it clean)
- Reverb: OFF

### Character
Clean, tight, digital closed hat. Berlin-era hi-hat aesthetic.

**Save as:** `DR_CH_06`

---

## 5. OPEN HAT (OPTIONAL) — "OH_XX"

**Goal:** Sustained open hat (optional — can use Volca Beats instead)

### Source
`PCM > RHY_OHHAT1`

### Patch Setup

**Oscillator:**
- Structure: PCM or Noise OSC
- Waveform: RHY_OHHAT1 (or open hat noise)
- Pitch: +2 octaves

**Filter:**
- Type: HPF around 300–400 Hz
- Resonance: 10-15%

**Amp Envelope:**
- Attack: 0
- Decay: 80–90 (sustained, not too long)
- Sustain: 0
- Release: 20

**FX:**
- No FX
- Reverb: OFF

### Character
Sustained, noisy open hat. Use sparingly on Side A.

**Note:** Volca Beats OH is recommended for grit — only build this if you want an XT-only kit.

**Save as:** `DR_OH_XX`

---

---

## 6. FX / PERC SAMPLES (MAX 5 TOTAL)

These are your additional textural elements. Create 5 patches using samples or XT synthesis:

### DR_Click_01 — Metallic Click
- **Source:** Noise OSC + highpass filter, or imported sample
- **Pitch:** High (+12 to +24)
- **Filter:** HPF at 1 kHz
- **Decay:** Very short (5-10)
- **Character:** Sharp transient, metallic, no body

### DR_RevNoise_02 — Reverse Noise Burst
- **Source:** Imported reverse cymbal/noise sample
- **Decay:** Medium (40-60)
- **Filter:** Bandpass 800 Hz - 6 kHz
- **Character:** Textural, builds up, no sharp attack

### DR_LowTom_03 — Low Tom
- **Source:** PCM > RHY_TOM_LOW or similar
- **Pitch:** Default or -5
- **Filter:** LPF around 300-500 Hz
- **Decay:** Medium (50-80)
- **Character:** Resonant, tonal, fills

### DR_Rim_04 — Processed Rimshot
- **Source:** PCM > RHY_RIMSHOT
- **Pitch:** +3 to +7
- **Filter:** HPF at 800 Hz
- **Decay:** Short (15-30)
- **FX:** Bit reduction or reverb (processed)
- **Character:** Tight click, Eventide-style

### DR_Wood_05 — Woodblock/Tick
- **Source:** PCM > RHY_WOOD or similar
- **Pitch:** +5 to +10
- **Filter:** Bandpass 500 Hz - 2 kHz
- **Decay:** Very short (5-15)
- **Character:** Percussive tick, no sustain

---

### Processing Inside XT (All FX Patches)
- Mild drive: 10–15% maximum (not more)
- No reverb on patch (applied externally in Ableton)
- Short envelope (except reverse noise which needs longer decay)

---

---

## Processing in Ableton (Global Chain for ALL Drums)

Once you've sampled these patches into Ableton Drum Rack, apply this processing chain:

### 1. Short Plate Reverb (0.3–0.5s)
- Decay: 0.3–0.5 seconds
- Pre-Delay: 20 ms
- Dry/Wet: 20-30% (send level per pad)

### 2. Tape Wobble (Very Subtle)
- Use Ableton's Saturator or tape emulation
- Slight pitch modulation (barely perceptible)

### 3. Mild Saturation
- Ableton Saturator
- Drive: 5-10%
- Soft clip

### 4. Gentle Bus Compression
- Glue Compressor
- Ratio: 2:1
- Attack: Slow (30 ms)
- Release: Auto
- Gain Reduction: 1-2 dB maximum

**Result:** Consistent, cohesive drum sound across all Side A tracks.

---

## Saving Workflow

After creating each patch:

1. **Press WRITE** button on VSynth XT
2. Navigate to **User Patch** slot (e.g., User 001–010)
3. **Name the patch** using XT's interface:
   - `DR_Kick_28`
   - `DR_Snare_14`
   - etc.
4. **Confirm** and save

**Tip:** Document patch locations in a text file:
```
User 001: DR_Kick_28
User 002: DR_Snare_14
User 003: DR_Snare_33
User 004: DR_CH_06
User 005: DR_OH_XX
User 006: DR_Click_01
User 007: DR_RevNoise_02
User 008: DR_LowTom_03
User 009: DR_Rim_04
User 010: DR_Wood_05
```

---

## The Goal

When you're done, you'll have:

✔ **1 primary kick** (DR_Kick_28)  
✔ **1 primary snare** (DR_Snare_14)  
✔ **1 alternate snare** (DR_Snare_33) — use on ONE track only  
✔ **1 closed hat** (DR_CH_06)  
✔ **1 open hat (optional)** (DR_OH_XX) — or use Volca Beats  
✔ **5 FX/perc elements** (Click, RevNoise, LowTom, Rim, Wood)  
✔ **100% consistent processing chain** (plate reverb, tape wobble, saturation, bus comp)  
✔ **Fast recall for every track**

**This is EXACTLY what Bowie/Visconti would do for consistency — a defined sonic vocabulary.**

---

## Next Steps

After creating all 10 patches on VSynth XT:

### Option A: Sample into Ableton Drum Rack (Recommended)
1. Follow **"Sampling Checklist"** resource
2. Record each patch (8-12 hits at various velocities)
3. Build Ableton Drum Rack (see **"Drum Rack Layout"** resource)
4. Apply global processing chain (reverb, tape, saturation, compression)

**Benefits:**
- Faster recall
- Easier editing
- Consistent across all tracks
- Ableton's full FX suite

### Option B: Trigger Directly from VSynth XT
1. Create MIDI track per drum sound
2. Load patches via program change
3. Record audio output from XT
4. Apply processing in Ableton

**Benefits:**
- Hardware-centric workflow
- XT's COSM processing retained
- Hands-on control

**For 14-day album project: Option A (Ableton Drum Rack) is strongly recommended.**

---

## Workflow Integration with Ableton

Even if you build the drum kit on XT, you'll still record into Ableton.

### Recording Workflow:

1. **Load drum kit patch** on VSynth XT
2. **Create MIDI track** in Ableton
3. **Set MIDI output** to VSynth XT
4. **Set Audio input** to XT's audio outputs (Apogee Inputs 6-7)
5. **Arm both MIDI and Audio tracks** (MIDI for notation, Audio for sound)
6. **Record MIDI performance**
7. **Simultaneously record audio output** from XT

**Result:** You have MIDI (editable) and audio (final sound).

---

### Mixing Workflow:

After recording XT drums as audio:

- **EQ** individual drum hits (automate filter on snare, etc.)
- **Add Ableton reverb** (supplement XT's internal reverb)
- **Compress drum bus** (Glue Compressor)
- **Sidechain** (optional, for bass/kick interaction)

---

## Comparison: XT Drum Kit vs. Ableton Drum Rack

| Feature | VSynth XT Drum Kit | Ableton Drum Rack |
|---------|-------------------|-------------------|
| **Recall Speed** | Moderate (patch loading) | Instant (saved as .adg) |
| **Consistency** | Good (if patch unchanged) | Excellent (locked samples) |
| **Layering** | Limited (4 Tones max) | Unlimited (128 pads) |
| **Processing** | XT's COSM + FX | Ableton's full FX suite |
| **Editing** | Hardware interface (slower) | DAW interface (faster) |
| **CPU Usage** | Uses XT's DSP | Uses computer CPU |
| **Workflow** | Hardware-centric | DAW-centric |
| **Best For** | Live performance, hands-on | Studio production, speed |

**For 14-day album project:** **Ableton Drum Rack** wins (speed and consistency).

**For live performance or hardware lovers:** **XT Drum Kit** is viable.

---

## Troubleshooting XT Drum Kit

### Issue: Drums sound too similar
- **Solution:** Adjust tuning, filter cutoff, COSM processing per Tone

### Issue: Kick and snare overlap when playing fast
- **Solution:** Set each Tone to **MONO** mode (Poly/Mono setting)

### Issue: One drum is too loud/quiet
- **Solution:** Adjust Tone Level (AMP → Level) for balance

### Issue: Reverb is too wet
- **Solution:** Lower per-Tone reverb send levels (EFFECTS → Tone Send)

### Issue: Patch loading is slow
- **Solution:** Reduce COSM usage, simplify oscillator settings

### Issue: Limited to 4 sounds
- **Solution:** Create multiple drum kit patches (Kit A, Kit B) or use Ableton Drum Rack

---

## Optional: Multi-Patch Drum Kit

If 4 Tones aren't enough, use **multiple patches** and switch via MIDI Program Change.

### Setup:

1. Create **Patch A:** Kick, Snare, Closed Hat, Open Hat (C1, D1, F#1, G#1)
2. Create **Patch B:** Tom 1, Tom 2, Crash, Perc (F1, F#1, A1, A#1)
3. Save both to User memory

### Usage:

- **Send MIDI Program Change** from Ableton to switch patches
- **Or:** Load both patches on separate MIDI channels (if XT supports multi-timbral mode)

**Trade-off:** More complex setup, not as immediate as Drum Rack.

---

## Quick Reference: Patch List

| Patch Name | Sound | Character |
|------------|-------|-----------|
| DR_Kick_28 | Primary Kick | Punchy, mid-focused, Berlin-era |
| DR_Snare_14 | Primary Snare | Tight, digital, crisp transient |
| DR_Snare_33 | Alt Snare | Metallic, bitcrushed (1 track only) |
| DR_CH_06 | Closed Hat | Clean, tight, digital |
| DR_OH_XX | Open Hat (opt) | Sustained, noisy (or use Volca) |
| DR_Click_01 | Metallic Click | Sharp, no body, syncopation |
| DR_RevNoise_02 | Reverse Noise | Textural, builds up |
| DR_LowTom_03 | Low Tom | Resonant, tonal, fills |
| DR_Rim_04 | Rimshot | Tight click, processed |
| DR_Wood_05 | Woodblock | Percussive tick, no sustain |

---

## Summary

The VSynth XT Drum Kit Build provides:
- ✓ 10 custom-numbered patches (5 core + 5 FX)
- ✓ Berlin Trilogy aesthetic (digital, tight, weird)
- ✓ Consistent sonic vocabulary across album
- ✓ Fast recall and reproducible
- ✓ Ready for sampling or direct use
- ✓ Bowie/Visconti-style discipline

**Sample these into Ableton Drum Rack for maximum speed and consistency during your 14-day sprint.**
