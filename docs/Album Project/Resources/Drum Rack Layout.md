# Drum Rack Layout

Complete pad-by-pad Ableton Drum Rack configuration for Side A (with optional Side B kit).

---

## Overview

This is your **fixed drum palette** for Side A.

**Sources:**
- VSynth XT (primary digital drum sounds)
- Volca Beats (grit and analog texture)
- 5 curated FX samples (processed)

**Philosophy:**
- Tight, minimal, Berlin-era Bowie aesthetic
- Consistent across all Side A tracks
- No swapping sounds mid-project
- Processed through same FX chain

---

## Pad Layout (Side A Main Kit)

Use **chromatic mapping** starting from C1 for muscle memory.

### Primary Pads:

```
C1  — Kick (XT Primary)
C#1 — Kick (Volca Overdrive) — ALT (use on 1 track only)
D1  — Snare 14 (XT Primary)
D#1 — Snare 33 (XT Metallic ALT)
E1  — Rimshot (Processed)
F1  — Low Tom
F#1 — Hat Closed (XT)
G1  — Hat Closed (Volca Noisy) — ALT
G#1 — Hat Open (XT or Volca)
A1  — Metallic Click
A#1 — Reverse Noise Hit
B1  — Noise Burst (Short)
```

**Total Pads:** 12  
**Beyond B1:** Empty (keep palette tight)

---

## Sound Descriptions

### C1 — Kick (XT Primary)

**Source:** VSynth XT Digital Kick #28  
**Character:** Punchy midrange, not too deep, Berlin feel  
**Tuning:** ~60-80 Hz fundamental  
**Decay:** Short to medium (200-400 ms)  
**Use:** Primary kick for ALL tracks

**Processing:**
- EQ: Roll off below 40 Hz, slight boost at 80 Hz
- Compression: Ratio 4:1, fast attack, medium release
- Saturation: Minimal (5%)

---

### C#1 — Kick (Volca Overdrive) — ALT

**Source:** Volca Beats Kick, pitched down, overdriven  
**Character:** Gritty, lo-fi, saturated  
**Tuning:** ~50-70 Hz fundamental  
**Decay:** Medium (300-500 ms)  
**Use:** ONE track only (for grit/contrast)

**Processing:**
- Overdrive: Built-in Volca distortion
- EQ: Roll off below 35 Hz, cut at 200 Hz
- Compression: Ratio 6:1, medium attack

---

### D1 — Snare 14 (XT Primary)

**Source:** VSynth XT Snare #14 (tight digital)  
**Character:** Tight, dry, digital transient  
**Body:** 180-250 Hz  
**Snap:** 3-5 kHz  
**Use:** Primary snare for ALL tracks

**Processing:**
- EQ: Boost at 200 Hz (+2 dB), boost at 4 kHz (+4 dB)
- Compression: Ratio 3:1, fast attack, fast release
- Reverb: Plate (short, 0.3-0.5 sec)

---

### D#1 — Snare 33 (XT Metallic ALT)

**Source:** VSynth XT Snare #33 (bit-crushed/metallic)  
**Character:** Harsh, digital, metallic  
**Body:** Less present  
**Snap:** Very bright, 5-8 kHz  
**Use:** ONE track only (for weird/experimental vibe)

**Processing:**
- EQ: Cut at 300 Hz, boost at 6 kHz (+6 dB)
- Compression: Ratio 4:1, fast attack
- Reverb: Plate (short)

---

### E1 — Rimshot (Processed)

**Source:** VSynth XT or Volca, heavily processed  
**Character:** Tight click, Eventide-style reverb  
**Use:** Transitions, accents, syncopation

**Processing:**
- EQ: Highpass at 800 Hz
- Reverb: Short plate with pre-delay
- Slight distortion (10%)

---

### F1 — Low Tom

**Source:** VSynth XT or sampled  
**Character:** Soft, resonant, tonal  
**Tuning:** ~100-150 Hz  
**Use:** Fills, transitions

**Processing:**
- EQ: Boost at 120 Hz, cut at 400 Hz
- Reverb: Plate (medium)
- No compression

---

### F#1 — Hat Closed (XT)

**Source:** VSynth XT Closed Hat #06  
**Character:** Clean, tight, digital  
**Brightness:** 8-12 kHz  
**Use:** Primary closed hat for ALL tracks

**Processing:**
- EQ: Highpass at 500 Hz, boost at 10 kHz (+2 dB)
- Compression: Ratio 2:1, fast attack/release
- Reverb: Minimal (10-15% send)

---

### G1 — Hat Closed (Volca Noisy) — ALT

**Source:** Volca Beats (slightly open setting)  
**Character:** Noisy, lo-fi, sizzling  
**Brightness:** More noise, less tone  
**Use:** Driving tracks, motorik feel (use sparingly)

**Processing:**
- EQ: Highpass at 800 Hz
- Compression: Ratio 3:1
- Reverb: Minimal

---

### G#1 — Hat Open (XT or Volca)

**Source:** VSynth XT or Volca Beats  
**Character:** Sustained, washed out, noisy  
**Decay:** 400-800 ms  
**Use:** Accents, groove variation

**Processing:**
- EQ: Highpass at 600 Hz
- Compression: Ratio 2:1, slow attack
- Reverb: Plate (20% send)

---

### A1 — Metallic Click

**Source:** Custom sample (processed)  
**Character:** Sharp transient, metallic, no body  
**Use:** Syncopation, off-beat accents

**Processing:**
- EQ: Highpass at 1 kHz
- Distortion: 5-10%
- Reverb: Short plate

---

### A#1 — Reverse Noise Hit

**Source:** Custom sample (reverse cymbal/noise)  
**Character:** Textural, builds up, no sharp attack  
**Use:** Transitions, fills, build-ups

**Processing:**
- EQ: Bandpass 800 Hz - 6 kHz
- Reverb: Medium plate
- Volume automation (swell)

---

### B1 — Noise Burst (Short)

**Source:** Custom sample (short white/pink noise)  
**Character:** Percussive noise, no pitch  
**Decay:** Very short (50-100 ms)  
**Use:** Texture, fills, experimental accents

**Processing:**
- EQ: Highpass at 2 kHz
- Reverb: Short plate
- Distortion: 5%

---

## Choke Groups

Configure in Drum Rack → I/O tab → Choke:

### Choke Group 1 (Hats):
- F#1 (Hat Closed XT)
- G1 (Hat Closed Volca)
- G#1 (Hat Open)

**Reason:** Hats should never overlap (realistic hi-hat behavior)

### Choke Group 2 (Metallic/FX):
- A1 (Metallic Click)
- A#1 (Reverse Noise)

**Reason:** Prevents metallic sounds from stacking (keeps clarity)

---

## Macros (8-Knob Universal Controls)

Map these for quick adjustments across all tracks.

### Macro 1 — Drum Saturation
**Controls:** Ableton Saturator drive on drum bus  
**Range:** 0 to +10 dB (mild saturation, no clipping)  
**Use:** Add warmth/grit globally

### Macro 2 — Plate Reverb Send
**Controls:** Send A level (routed to plate reverb)  
**Range:** 0% to 40%  
**Use:** Adjust room depth for entire kit

### Macro 3 — Hat Brightness
**Controls:** Lowpass filter on F#1, G1, G#1  
**Range:** 6 kHz to 12 kHz  
**Use:** Darken or brighten hats

### Macro 4 — Snare Body
**Controls:** EQ bell around 180-250 Hz on D1, D#1  
**Range:** +0 dB to +4 dB  
**Use:** Add/remove low-mid body in snare

### Macro 5 — Snare Snap
**Controls:** EQ shelf at 4-7 kHz on D1, D#1  
**Range:** +0 dB to +6 dB  
**Use:** Add/remove high-frequency snap

### Macro 6 — Kick Punch
**Controls:** Transient shaper or compressor attack on C1, C#1  
**Range:** Slow to fast attack  
**Use:** Shape kick transient (more/less punch)

### Macro 7 — Noise FX Level
**Controls:** Volume on A1, A#1, B1  
**Range:** -inf dB to 0 dB  
**Use:** Balance FX sounds in mix

### Macro 8 — Global Drum Bus HPF
**Controls:** 24 dB/oct highpass filter  
**Range:** 45 Hz to 80 Hz  
**Use:** Clear low-end mud without affecting bass

---

## Drum Rack FX Chain (Parent Track)

Process the entire drum bus (all pads together) through:

### 1. Tape/Console Saturation
**Device:** Ableton Saturator  
**Settings:**
- Drive: +5 to +10 dB
- Curve: Soft Clip
- Dry/Wet: 50-70%

**Purpose:** Adds warmth, glues kit together

---

### 2. Short Plate Reverb (Send A)
**Device:** Ableton Reverb  
**Settings:**
- Decay: 0.3-0.5 seconds
- Pre-Delay: 20 ms
- Size: 60%
- Damping: High 50%, Low 0%
- Highpass: 300-500 Hz (keep low-end dry)
- Dry/Wet: Controlled by sends (0-40% per pad)

**Purpose:** Creates space, Berlin studio aesthetic

---

### 3. Glue Compressor (Light)
**Device:** Ableton Glue Compressor  
**Settings:**
- Ratio: 2:1
- Attack: Slow (30 ms)
- Release: Auto or Fast
- Makeup: To taste
- Gain Reduction: 1-2 dB maximum

**Purpose:** Subtle gluing, not heavy pumping

---

### 4. EQ8 Tilt (Optional)
**Device:** Ableton EQ Eight  
**Settings:**
- Highpass: 40 Hz (24 dB/oct)
- High shelf: +1 dB at 10 kHz (subtle air)
- Low shelf: -1 dB at 100 Hz (if needed)

**Purpose:** Final tonal shaping

---

### Save As:
**SIDE_A_MAIN_KIT.adg**  
Store in Ableton User Library for instant recall.

---

## Ableton Sampling Checklist

Follow this workflow to build your kit from hardware.

### Step 1 — Prepare Audio Tracks

1. Create **two audio tracks** in Ableton:
   - Track 1: "XT Sampling"
   - Track 2: "Volca Sampling"
2. Set inputs:
   - XT: Apogee Inputs 6-7 (stereo)
   - Volca: Apogee Inputs (assign to available pair)
3. Arm both tracks
4. **Disable all FX** (record raw, dry samples)
5. Set monitoring to "Off"

---

### Step 2 — Sample Each Sound

For each sound (kick, snare, hats, etc.):

1. **Record 8-12 hits** per sound:
   - 3-4 soft hits
   - 3-4 medium hits
   - 3-4 hard hits
2. **Leave 1-2 seconds of silence** between hits
3. **Play consistently** (velocity variations are fine)
4. **Record without effects** (add FX in Drum Rack later)

**Tip:** Use MIDI velocity or manual playing — doesn't have to be perfect. Choose the best transient later.

---

### Step 3 — Edit Samples

For each recorded hit:

1. **Trim leading silence**
   - Start sample exactly at transient onset
2. **Trim tail**
   - Leave natural decay (don't cut off early)
   - For kicks: ~500-800 ms
   - For snares: ~300-600 ms
   - For hats: ~200-400 ms (closed), ~400-800 ms (open)
3. **Normalize** (optional but recommended)
   - Ensures consistent levels across kit
4. **Convert to 24-bit WAV**
5. **Rename** using naming conventions (see below)
6. **Delete messy takes** (keep only the best)

---

### Step 4 — Organize Folders

Create this folder structure:

```
/Drums
   /XT
      /Kick
      /Snare14
      /Snare33
      /Hats
      /Perc
   /Volca
      /Kick
      /Hats
   /FX
      /MetallicClick
      /Reverse
      /Noise
```

Place each sample in its appropriate folder.

---

### Step 5 — Import into Drum Rack

1. Create new **Drum Rack** on MIDI track
2. **Drag samples** onto pads:
   - C1: Kick_XT_Primary
   - C#1: Kick_Volca_OD
   - D1: Snare14_XT
   - (etc., following pad layout above)
3. **Set pad parameters:**
   - Mode: One-Shot (not Loop)
   - Choke: Assign groups (see above)
4. **Add per-pad FX** if needed:
   - Simpler (built-in sampler)
   - EQ, compression, reverb send

---

### Step 6 — Add Macros

1. Open Drum Rack Macros panel
2. Map 8 macros as specified above
3. Name each macro clearly
4. Test each macro's range

---

### Step 7 — Add FX Chain

1. Add devices to Drum Rack parent track:
   - Saturator
   - Reverb (Send A)
   - Glue Compressor
   - EQ8
2. Configure settings (see FX Chain section above)
3. Test full kit through processing chain

---

### Step 8 — Save Rack

1. **Save Drum Rack** as: `SIDE_A_MAIN_KIT.adg`
2. Store in: `Ableton User Library/Drums/`
3. **Backup samples folder** externally

---

### Step 9 — Test

1. Create simple drum pattern
2. Verify all pads trigger correctly
3. Test choke groups (hats should mute each other)
4. Test macros (adjust saturation, reverb, etc.)
5. Verify no clipping on master

---

## Naming Conventions for Drum Hits

Use this exact format:

```
Instrument_Source_Type_Note_Take.wav
```

### Examples:

```
Kick_XT_Primary_C1_01.wav
Kick_XT_Primary_C1_02.wav
Kick_Volca_OD_Cs1_01.wav
Snare14_XT_D1_01.wav
Snare14_XT_D1_02.wav
Snare33_XT_Ds1_01.wav
HatC_XT_Fs1_01.wav
HatC_Volca_Fs1_01.wav
HatO_XT_Gs1_01.wav
Click_Metallic_A1_01.wav
Noise_Reverse_As1_01.wav
Perc_LowTom_F1_01.wav
```

### Naming Rules:

1. **Instrument:** Kick, Snare14, Snare33, HatC (Closed), HatO (Open), Click, Noise, Perc
2. **Source:** XT, Volca, Custom
3. **Type:** Primary, OD (Overdrive), Metallic, Reverse, etc.
4. **Note:** C1, Cs1 (C#1), D1, Ds1, etc.
5. **Take:** 01, 02, 03 (use best take in Drum Rack)

**Benefit:** Keeps library organized, makes swapping samples easy, scalable for future projects.

---

## Side B — Minimal Percussion Kit (Optional)

Build **only if needed** for transitions or gentle punctuation in Side B.

### Pad Layout (Minimal):

```
C1  — Soft Sub Kick (XT or Moog sample, very quiet, felt-like)
D1  — Low Tom (long decay, resonant)
F1  — Brushed Click (very quiet, textural)
A1  — Reverse Texture (subtle, ambient)
```

**Total Pads:** 4  
**All other pads:** Empty

---

### Sound Descriptions:

#### C1 — Soft Sub Kick
**Source:** VSynth XT kick (low velocity) or Moog sine wave sample  
**Character:** Felt-like, deep, no transient  
**Tuning:** ~50-60 Hz  
**Use:** Extremely rare, only for gentle pulse

**Processing:**
- Reverb: Long Hall (20-40 sec decay)
- Highpass: 200 Hz (removes deep sub)
- Level: -12 to -20 dB quieter than Side A

---

#### D1 — Low Tom
**Source:** VSynth XT or sampled  
**Character:** Resonant, tonal, long decay  
**Tuning:** ~100 Hz  
**Use:** Transitions, fills (very sparse)

**Processing:**
- Reverb: Long Hall
- No compression
- Level: Very quiet

---

#### F1 — Brushed Click
**Source:** Custom sample (brush on snare or wood)  
**Character:** Soft attack, textural, no body  
**Use:** Subtle punctuation

**Processing:**
- Reverb: Long Hall
- Highpass: 500 Hz
- Level: Very quiet

---

#### A1 — Reverse Texture
**Source:** Reverse cymbal or noise  
**Character:** Ambient swell, no attack  
**Use:** Transitions between movements

**Processing:**
- Reverb: Long Hall
- Bandpass: 800 Hz - 4 kHz
- Level: Very quiet

---

### Processing Chain (Side B Kit):

1. **Long Hall Reverb**
   - Decay: 20-40 seconds
   - Dry/Wet: 70-90%
2. **Highpass Filter**
   - 200-300 Hz (removes deep low-end)
3. **No Compression**
   - Preserve ambient dynamics
4. **Optional Sidechain** (very weak)
   - Duck percussion slightly when drones/pads are present

---

### Save As:
**SIDE_B_AMBIENT_PERC.adg**  
Store separately from Side A kit.

---

## Discipline Rules

To maintain cohesion across the album:

### 1. One Main Kick for the Whole Album
No swapping mid-project. This is your anchor.

### 2. One Main Snare + One Alternate
Use the alternate on ONE track only.

### 3. Hats: Pick One, Add Volca Noise Only When Needed
If every track uses noisy hats, they lose impact.

### 4. Never Layer More Than 2 Drum Sources at Once
Clarity > density.

### 5. No New Samples After Day 1
Lock the FX/texture set and commit.

### 6. Use the Same Processing Chain Album-Wide
- Short plate reverb (0.3-0.5 sec)
- Tape saturation (5-10%)
- Light highpass filter
- Consistent bus compression

### 7. Quantization: Only Partial
Let drums be slightly humman/weird. Don't over-quantize.

### 8. Finish Tracks Before "Upgrading" Drum Sounds
Sketches first, taste-polish later.

---

## Summary

The Drum Rack Layout provides:
- ✓ Fixed 12-pad kit (Side A)
- ✓ Choke groups for realistic hat behavior
- ✓ 8 universal macros for quick adjustments
- ✓ Complete FX chain for cohesion
- ✓ Step-by-step sampling workflow
- ✓ Naming conventions for organization
- ✓ Optional minimal kit for Side B

**Build this once on Day 1, never think about drums again during creative sprints.**
