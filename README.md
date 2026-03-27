# Stimulus Materials for Anonymous Paper Submission

This repository contains the final video stimuli used in the associated study submission.

## Repository contents

This repository includes a total of **30 final stimulus videos** in `.mp4` format.

### Online survey stimuli
The online survey includes:
- **4 scenario types**: Ethical, Legal, Utility, Moral
- **1 environmental variant**: Daytime
- **3 XAI modality combinations**:
  - visual-auditory (`va`)
  - visual-textual (`vt`)
  - visual-textual-auditory (`vta`)

This results in **12 online-survey videos**.

### On-site simulator stimuli
The on-site simulator study includes:
- **2 scenario types**: Legal, Moral
- **3 environmental variants**:
  - Daytime
  - Nighttime
  - Late Afternoon Winter
- **3 XAI modality combinations**:
  - visual-auditory (`va`)
  - visual-textual (`vt`)
  - visual-textual-auditory (`vta`)

This results in **18 on-site simulator videos**.

## Technical specifications

All videos:
- are provided in `.mp4` format
- include audio
- have a frame rate of **24 fps**
- have a duration of **14 seconds and 20 frames**

### Online survey videos
- Resolution: **2556 × 1179 px**
- Frame rate: **24 fps**
- Duration: **14s 20f**
- Audio: **yes**
- Format: **MP4**

### On-site simulator videos
- Resolution: **3440 × 1440 px**
- Frame rate: **24 fps**
- Duration: **14s 20f**
- Audio: **yes**
- Format: **MP4**

## Stimulus design

The stimuli are based on scenario-driven traffic situations developed for two study contexts.

For the online survey, four scenario types were used:
- Ethical
- Legal
- Utility
- Moral

For the on-site simulator study, two scenario types were used:
- Legal
- Moral

The simulator study includes three environmental variants:
- Daytime
- Nighttime
- Late Afternoon Winter

The online survey includes only the Daytime variant.

## XAI modality combinations

Each final stimulus video contains one of the following XAI modality combinations:

- `va` = visual-auditory
- `vt` = visual-textual
- `vta` = visual-textual-auditory

These modality codes are used in the file names and metadata.

## File naming convention

Files follow a structured naming scheme:

`[study]_[scenario]_[environment]_[modality].mp4`

Examples:
- `online_ethical_daytime_va.mp4`
- `online_moral_daytime_vta.mp4`
- `sim_legal_nighttime_vt.mp4`
- `sim_moral_late-afternoon-winter_vta.mp4`

## Production pipeline

The stimulus materials were created using a multi-step workflow:

1. **Scene creation in Blender**
   - Scenario-based traffic scenes were built in Blender.
   - Environmental variants were created for relevant study conditions.

2. **Visual XAI adaptation**
   - Materials were adjusted.
   - The visual environment was simplified.
   - The camera perspective was changed from ego perspective to bird’s-eye view.

3. **Post-production in Adobe After Effects**
   - Final video stimuli were assembled in Adobe After Effects.
   - Audio and modality-specific components were integrated during post-production.
   - Final exports were rendered as participant-facing study materials.

## Files not included

This repository contains the **final participant-facing video stimuli only**.

The original Blender and Adobe After Effects production files are not included because they contain proprietary third-party assets licensed from commercial marketplaces. These source materials are therefore not redistributed as part of this repository.

## Metadata

A structured overview of all video stimuli is provided in:

`metadata/stimuli_manifest.csv`

## Third-party assets

The production workflow used commercial third-party assets obtained from Superhive, including:

- **Launch Control // Auto Car Rig for Vehicles**
- **The City Generator**
- **Transportation**

Further information is provided in:

`docs/asset_and_production_notes.md`

## Intended use

This repository is intended to document and share the final video stimuli shown to participants in the study.

## Citation

Citation metadata is provided in `CITATION.cff`.
