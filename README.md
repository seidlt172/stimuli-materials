# Stimulus Materials for Evaluating Multimodal Explainable AI in Ambiguous Driving Scenarios: Effects on User Trust and Satisfaction

This repository contains the video stimuli used in the study reported in the associated paper submission.

## Repository contents

The repository includes 16 final stimulus videos in `.mp4` format:

- **Online survey stimuli**: 4 videos
- **On-site simulator stimuli**: 12 videos

All videos:
- include audio
- are encoded in MP4 format
- have a frame rate of 24 fps
- have a duration of 14 seconds and 20 frames

## Stimulus design

The stimuli are based on four scenario types:

- Ethical
- Legal
- Utility
- Moral

Three environmental variants were created:

- Daytime
- Nighttime
- Late Afternoon Winter

### Online survey condition
For the online survey, only the **Daytime** versions were used and exported.

### On-site simulator condition
For the on-site simulator study, all three environmental variants were used:

- Daytime
- Nighttime
- Late Afternoon Winter

## Technical specifications

### Online survey videos
- Resolution: 2556 × 1179 px
- Frame rate: 24 fps
- Duration: 14s 20f
- Audio: yes
- Format: MP4

### On-site simulator videos
- Resolution: 3840 × 1080 px
- Frame rate: 24 fps
- Duration: 14s 20f
- Audio: yes
- Format: MP4

## Production pipeline

The visual stimuli were created using a multi-step workflow:

1. **Scene creation in Blender**
   - Four scenario types were developed.
   - Three environmental variants were produced for the simulator study.
2. **Visual XAI adaptation**
   - Materials were adjusted.
   - The visual environment was simplified.
   - The camera perspective was changed from ego perspective to bird's-eye view.
3. **Post-production in Adobe After Effects**
   - Standard and Visual XAI video components were combined into final stimulus videos.
   - Audio and final export settings were added during post-production.

## Files not included

This repository contains the final stimulus videos only.

The original Blender and Adobe After Effects source files are not included because they contain proprietary third-party assets licensed from commercial marketplaces. These materials cannot be redistributed as part of this repository.

## Metadata

A structured overview of all stimuli is provided in:

`metadata/stimuli_manifest.csv`

## Third-party assets

The production pipeline used commercial third-party assets obtained from Superhive, including:

- Launch Control // Auto Car Rig for Vehicles
- The City Generator
- Transportation

See `docs/asset_and_production_notes.md` for a short note on asset usage and redistribution limitations.

## Intended use

This repository is intended to document and share the final video stimuli shown to participants in the study.

## Citation

Citation information is provided in `CITATION.cff`.
