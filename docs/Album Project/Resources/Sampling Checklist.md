# Sampling Checklist

Step-by-step guide for sampling hardware synths into Ableton drum samples.

---

## Why Sample Into Ableton Drum Rack?

For this 14-day album project, sampling into Ableton Drum Rack is the **right choice** because:

- **Instant recall** — No menu-diving on hardware synths
- **Consistency** — Same sounds across all Side A tracks
- **Speed** — Saves 10-15 minutes per track
- **Layering** — Mix XT + Volca sounds easily
- **Integration** — Tight workflow with Ableton template
- **CPU** — Frees hardware synth voices for pads/leads

**Bottom line:** Sampling removes friction and lets you focus on composition, not sound design.

---

## Overview

This checklist covers:
1. Preparing Ableton session
2. Recording samples from hardware
3. Editing and organizing samples
4. Building Drum Rack
5. Adding processing and macros
6. Saving and testing

**Time Required:** 2-3 hours (Day 1 only)  
**Do This Once:** Never rebuild during the 14-day sprint

---

## Pre-Sampling Setup

### Hardware Connections:

Verify audio routing before starting:

- **VSynth XT:** Stereo out → Apogee Ensemble Inputs 6-7
- **Volca Beats:** Stereo out → Apogee Ensemble Inputs (assign available pair)
- **Apogee Ensemble:** Connected to computer via USB/Thunderbolt
- **Apogee → RME BabyFace:** ADAT connection stable (for additional inputs if needed)

### Ableton Session Preparation:

1. Open new Ableton session
2. Set sample rate: 48 kHz (or 44.1 kHz)
3. Set bit depth: 24-bit
4. Create folder structure on hard drive (see below)

---

## Step 1 — Prepare Audio Tracks in Ableton

### Create Recording Tracks:

1. **Track 1:** "XT Sampling"
   - Input: Apogee Inputs 6-7 (Ext. In, Stereo)
   - Monitor: Off
   - Arm: Ready to arm
   - Color: Red

2. **Track 2:** "Volca Sampling"
   - Input: Apogee Inputs (assign available stereo pair)
   - Monitor: Off
   - Arm: Ready to arm
   - Color: Orange

### Critical Settings:

- **Disable ALL FX** on both tracks (record dry)
- **Disable warping** (audio will be one-shots)
- **Disable Ableton Reverb/Delay returns** (mute or disable)
- **Set input monitoring to "Off"** (prevents feedback)

---

## Step 2 — Record Samples from Hardware

### General Recording Rules:

- **8-12 hits per sound** (gives you choices for best transient)
- **Vary velocity:** 3-4 soft, 3-4 medium, 3-4 hard
- **Leave 1-2 seconds of silence** between each hit
- **Record dry** (no reverb, no FX on hardware)
- **Record at consistent levels** (-12 to -6 dB peak, no clipping)

---

### VSynth XT — Kick Samples:

**Sound:** VSynth XT Digital Kick #28 (or your chosen kick)

1. Load kick patch on VSynth XT
2. Disable all FX (COSM, reverb, chorus)
3. Arm "XT Sampling" track in Ableton
4. Hit Record in Ableton
5. **Play 10-12 kick hits** on MIDI keyboard (C1 recommended)
   - Vary velocity (soft, medium, hard)
   - Space hits 1-2 seconds apart
6. Stop recording
7. Label clip: "XT Kick Primary Raw"

**Repeat for:**
- Snare 14 (D1 on keyboard)
- Snare 33 (D1 on keyboard)
- Closed Hat (F#1 on keyboard)
- Open Hat (G#1 on keyboard)
- Any toms, cymbals, percs you want

---

### Volca Beats — Kick (Overdrive):

**Sound:** Volca Beats Kick with overdrive, pitched down

1. Set Volca Beats kick parameters:
   - Pitch: Slightly lower
   - Overdrive: ON (for grit)
   - Level: Consistent
2. Arm "Volca Sampling" track in Ableton
3. Hit Record in Ableton
4. **Play 10-12 kick hits** by triggering Volca
   - Use Volca's button or MIDI input
   - Vary intensity (if possible)
5. Stop recording
6. Label clip: "Volca Kick OD Raw"

**Repeat for:**
- Volca noisy closed hat
- Volca open hat
- Any other Volca sounds you want

---

### FX Samples (Custom/Processed):

For the 5 FX sounds (metallic click, reverse noise, noise burst, rimshot, low tom):

**Option A:** Record from VSynth XT or Volca  
**Option B:** Use existing samples and process heavily

If recording:
1. Create short, unique sounds on hardware
2. Record 6-8 hits each
3. Label clearly: "XT Metallic Click Raw", "XT Reverse Noise Raw", etc.

---

## Step 3 — Edit Samples

For **each recorded audio clip**:

### A. Consolidate and Export Individual Hits:

1. Select clip in Ableton
2. Use **Cmd+E (Mac) / Ctrl+E (Win)** to split at playhead
3. Isolate each hit into its own clip
4. For each hit:
   - **Trim leading silence** (start exactly at transient onset)
   - **Trim tail** (leave natural decay, don't cut off early)
     - Kicks: ~500-800 ms
     - Snares: ~300-600 ms
     - Hats (closed): ~200-400 ms
     - Hats (open): ~400-800 ms
     - FX: As needed
   - **Right-click → Consolidate** (Cmd+J / Ctrl+J)

---

### B. Normalize (Optional but Recommended):

Normalizing ensures consistent levels across kit.

1. Select clip
2. Right-click → **Normalize**
3. Ableton adjusts gain to maximize level without clipping

**Alternative:** Leave dynamic range intact if you prefer manual leveling later.

---

### C. Export as WAV:

1. Select each trimmed, normalized clip
2. Right-click → **Export Audio/Video**
3. **Settings:**
   - Format: WAV
   - Bit Depth: 24-bit
   - Sample Rate: Match project (48 kHz or 44.1 kHz)
   - Dither: None (since staying at 24-bit)
   - Normalize: Off (already normalized)
4. **Name file** using naming convention (see below)
5. Save to organized folder structure (see below)

**Repeat for all samples.**

---

### D. Choose Best Takes:

Out of 8-12 hits per sound, choose **1-3 best takes**:
- Best transient (clean, sharp attack)
- Natural decay (no artifacts)
- Consistent tone

Delete the rest to keep library clean.

---

## Step 4 — Organize Folder Structure

Create this exact folder structure on your hard drive:

```
/Album Project Drums/
   /XT/
      /Kick/
         Kick_XT_Primary_C1_01.wav
         Kick_XT_Primary_C1_02.wav
      /Snare14/
         Snare14_XT_D1_01.wav
      /Snare33/
         Snare33_XT_Ds1_01.wav
      /Hats/
         HatC_XT_Fs1_01.wav
         HatO_XT_Gs1_01.wav
      /Perc/
         Perc_LowTom_F1_01.wav
   /Volca/
      /Kick/
         Kick_Volca_OD_Cs1_01.wav
      /Hats/
         HatC_Volca_Fs1_01.wav
         HatO_Volca_Gs1_01.wav
   /FX/
      Click_Metallic_A1_01.wav
      Noise_Reverse_As1_01.wav
      Noise_Burst_B1_01.wav
```

**Why This Matters:**
- Fast navigation
- Easy to swap samples later
- Scalable for future projects

---

## Step 5 — Build Drum Rack

### A. Create Drum Rack:

1. Create new **MIDI track** in Ableton
2. Drag **Drum Rack** device onto track
3. Name track: "Side A Drums"

---

### B. Load Samples onto Pads:

Drag samples from folder onto Drum Rack pads following this layout:

```
C1  — Kick_XT_Primary_C1_01.wav
C#1 — Kick_Volca_OD_Cs1_01.wav
D1  — Snare14_XT_D1_01.wav
D#1 — Snare33_XT_Ds1_01.wav
E1  — Rimshot sample
F1  — Perc_LowTom_F1_01.wav
F#1 — HatC_XT_Fs1_01.wav
G1  — HatC_Volca_Fs1_01.wav
G#1 — HatO_XT_Gs1_01.wav
A1  — Click_Metallic_A1_01.wav
A#1 — Noise_Reverse_As1_01.wav
B1  — Noise_Burst_B1_01.wav
```

---

### C. Configure Each Pad:

For each pad (click pad → open chain):

1. **Simpler device** (automatically loaded):
   - Mode: **One-Shot** (not Loop)
   - Trigger: Gate
   - Start: 0.00
   - End: Natural decay
   - Fade: Minimal (5-10 ms)
   - Voices: 1 (mono, no overlap)

2. **Add per-pad FX** (if needed):
   - Insert EQ Eight (for tone shaping)
   - Insert Compressor (for dynamics)
   - Reverb send: Controlled by Send A

**Pad-Specific Settings:**

- **Kicks (C1, C#1):**
  - EQ: Roll off below 40 Hz, boost at 80 Hz (+2 dB)
  - Compression: Ratio 4:1, fast attack, medium release
  
- **Snares (D1, D#1):**
  - EQ: Boost at 200 Hz (+2 dB), boost at 4-6 kHz (+4 dB)
  - Compression: Ratio 3:1, fast attack/release
  - Reverb send: 20-30%

- **Hats (F#1, G1, G#1):**
  - EQ: Highpass at 500 Hz, boost at 10 kHz (+2 dB)
  - Compression: Ratio 2:1, fast attack/release
  - Reverb send: 10-15%

- **FX (A1, A#1, B1):**
  - EQ: Shape to taste (highpass recommended)
  - Reverb send: 15-25%

---

### D. Set Choke Groups:

In Drum Rack → I/O tab → Choke column:

- **F#1 (Hat Closed XT):** Choke Group **1**
- **G1 (Hat Closed Volca):** Choke Group **1**
- **G#1 (Hat Open):** Choke Group **1**

This prevents hats from overlapping (realistic behavior).

**Optional:**
- **A1 (Metallic Click):** Choke Group **2**
- **A#1 (Reverse Noise):** Choke Group **2**

---

## Step 6 — Add Processing Chain

On the **Drum Rack parent track** (above individual pads):

### 1. Tape/Console Saturation:

- **Device:** Ableton Saturator
- **Settings:**
  - Drive: +5 to +10 dB
  - Type: Analog Clip or Soft Clip
  - Dry/Wet: 50-70%
- **Purpose:** Adds warmth, glues kit together

---

### 2. Short Plate Reverb (Send A):

- **Create Audio Return Track** (Send A)
- **Device:** Ableton Reverb
- **Settings:**
  - Type: Plate
  - Decay: 0.3-0.5 seconds
  - Pre-Delay: 20 ms
  - Size: 60%
  - Damping: High 50%, Low 0%
  - EQ: Highpass at 300-500 Hz (keeps low-end dry)
  - Dry/Wet: 100% (controlled by send amount per pad)
- **Purpose:** Creates space, Berlin studio aesthetic

---

### 3. Glue Compressor (Light):

- **Device:** Ableton Glue Compressor
- **Settings:**
  - Ratio: 2:1
  - Attack: Slow (30 ms)
  - Release: Auto or Fast
  - Makeup: To taste
  - Gain Reduction: 1-2 dB maximum (subtle gluing)
- **Purpose:** Subtle cohesion, not heavy pumping

---

### 4. EQ Eight (Optional Tonal Shaping):

- **Device:** Ableton EQ Eight
- **Settings:**
  - Highpass: 40 Hz (24 dB/oct) — removes sub rumble
  - High shelf: +1 dB at 10 kHz (subtle air)
  - Low shelf: -1 dB at 100 Hz (if muddy)
- **Purpose:** Final tonal refinement

---

## Step 7 — Add Macros

Open Drum Rack Macros panel and map these 8 controls:

1. **Drum Saturation** → Saturator Drive (0 to +10 dB)
2. **Plate Reverb Send** → Send A level (0% to 40%)
3. **Hat Brightness** → Lowpass filter on hats (6-12 kHz)
4. **Snare Body** → EQ bell at 180-250 Hz on snares (+0 to +4 dB)
5. **Snare Snap** → EQ shelf at 4-7 kHz on snares (+0 to +6 dB)
6. **Kick Punch** → Compressor attack on kicks (slow to fast)
7. **Noise FX Level** → Volume on A1, A#1, B1 (-inf to 0 dB)
8. **Global Drum Bus HPF** → Highpass filter (45-80 Hz)

**Name each macro clearly** in the Macro panel.

---

## Step 8 — Save Drum Rack

1. Click on **Drum Rack title bar**
2. Right-click → **Save As**
3. **Name:** `SIDE_A_MAIN_KIT.adg`
4. **Location:** Ableton User Library → Drums folder
5. **Backup:** Copy `.adg` file and samples folder to external drive

---

## Step 9 — Test the Kit

### A. Create Simple Test Pattern:

1. Create new MIDI clip on drum track
2. Program basic pattern:
   - Kick on beats 1 and 3
   - Snare on beats 2 and 4
   - Closed hat on all 8th notes
3. Play clip

### B. Verify:

- ✅ All pads trigger correctly
- ✅ No clipping on master (peaks below -6 dB)
- ✅ Choke groups work (hats mute each other)
- ✅ Reverb sounds good (not too wet)
- ✅ Saturation adds warmth (not distortion)
- ✅ Macros adjust as expected

### C. Adjust if Needed:

- Rebalance pad levels
- Adjust reverb send amounts
- Fine-tune EQ on individual pads

---

## Step 10 — Lock the Palette

After testing, **DO NOT CHANGE SAMPLES** for the rest of the project.

**Rules:**
- ✅ Commit to this kit for all Side A tracks
- ✅ Use alternate snare (D#1) or kick (C#1) on only ONE track
- ✅ No new samples after Day 1
- ✅ Trust the constraints

**Exception:** If a sample is fundamentally broken (clipping, noise), you may replace it. But re-test immediately.

---

## Naming Conventions (Detailed)

Use this exact format for all samples:

```
Instrument_Source_Type_Note_Take.wav
```

### Field Definitions:

1. **Instrument:** Kick, Snare14, Snare33, HatC (Closed), HatO (Open), Click, Noise, Perc, Tom
2. **Source:** XT, Volca, Custom
3. **Type:** Primary, OD (Overdrive), Metallic, Reverse, Soft, Hard, etc.
4. **Note:** C1, Cs1 (C#1), D1, Ds1 (D#1), E1, F1, Fs1 (F#1), Gs1 (G#1), A1, As1 (A#1), B1
5. **Take:** 01, 02, 03, etc.

### Examples:

```
Kick_XT_Primary_C1_01.wav
Kick_XT_Primary_C1_02.wav
Kick_Volca_OD_Cs1_01.wav
Snare14_XT_D1_01.wav
Snare14_XT_D1_02.wav
Snare33_XT_Ds1_01.wav
HatC_XT_Fs1_01.wav
HatC_XT_Fs1_02.wav
HatC_Volca_Fs1_01.wav
HatO_XT_Gs1_01.wav
HatO_Volca_Gs1_01.wav
Click_Metallic_A1_01.wav
Noise_Reverse_As1_01.wav
Noise_Burst_B1_01.wav
Perc_LowTom_F1_01.wav
Perc_Rimshot_E1_01.wav
```

---

## Optional: Side B Minimal Kit

If you need gentle percussion for Side B ambient suite:

### Quick Sampling:

1. Sample 4 sounds only:
   - Soft sub kick (XT or Moog sine wave)
   - Low tom (resonant, long decay)
   - Brushed click (quiet, textural)
   - Reverse texture (ambient swell)

2. Load onto pads: C1, D1, F1, A1

3. Process with:
   - Long Hall Reverb (20-40 sec decay)
   - Highpass filter (200-300 Hz)
   - Level: -12 to -20 dB quieter than Side A

4. Save as: `SIDE_B_AMBIENT_PERC.adg`

**Use extremely sparingly** on Side B (if at all).

---

## Troubleshooting

### Samples sound thin or weak:
- Check recording levels (should peak at -12 to -6 dB)
- Normalize samples
- Add EQ boost in Drum Rack

### Samples clip or distort:
- Lower Saturator drive
- Check for multiple gain stages adding up
- Verify sample wasn't clipped during recording

### Reverb is too wet:
- Lower Send A amount per pad (15-25% max for most sounds)
- Reduce reverb Dry/Wet on return track

### Choke groups not working:
- Verify all hats are assigned to same choke group number
- Check that Simpler is set to "One-Shot" mode

### Samples don't trigger:
- Verify MIDI note matches pad assignment
- Check that Simpler "Start" is at 0.00
- Ensure sample file isn't corrupted

---

## Summary

This Sampling Checklist provides:
- ✓ Step-by-step workflow for hardware-to-Ableton sampling
- ✓ Editing and organization best practices
- ✓ Complete Drum Rack build instructions
- ✓ Processing chain for cohesion
- ✓ Macro setup for quick adjustments
- ✓ Naming conventions for scalability
- ✓ Testing and troubleshooting guide

**Complete this workflow on Day 1, then never think about drum sound design again during the 14-day sprint.**
