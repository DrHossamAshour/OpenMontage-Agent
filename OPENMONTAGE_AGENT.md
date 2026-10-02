# Open Montage Agent — HSZ Media Production Profile

This repository is a maintained fork of `calesthio/OpenMontage`.

## Purpose

Use OpenMontage as the production engine for professional video editing, animation, motion design, sound design, AI-assisted media generation, color finishing, and delivery QA.

The fork must remain upstream-friendly. Avoid unnecessary edits to OpenMontage core files when project-specific behavior can live in a separate profile, skill, pipeline, or extension.

## Operating Contract

For every production request:

1. Read `AGENT_GUIDE.md`.
2. Read `PROJECT_CONTEXT.md`.
3. Inspect `skills/INDEX.md`.
4. Select the appropriate manifest from `pipeline_defs/`.
5. Run source-media inspection before editing.
6. Follow the selected pipeline stage-by-stage.
7. Read each stage director before executing that stage.
8. Use OpenMontage tools and selectors before inventing ad-hoc replacements.
9. Preserve decision logs, checkpoints, artifacts, and cost tracking.
10. Render, inspect, QA, correct defects, and only then deliver.

## Creative Standard

Default output should feel:

- premium
- cinematic
- emotionally intentional
- modern
- clean
- cohesive
- retention-aware
- professionally sound-designed
- deliberately animated

Do not over-edit. Story, emotion, clarity, rhythm, and viewer attention take priority over effects.

## Source Footage

Before editing, inspect:

- duration
- resolution
- frame rate
- orientation
- codec
- audio streams
- scene boundaries
- spoken content
- silence and mistakes
- duplicate material
- visual quality
- camera changes
- lighting consistency
- useful B-roll
- strongest emotional or informational moments

Use OpenMontage analysis tools, ffprobe, FFmpeg, transcript extraction, scene detection, and frame sampling where appropriate.

## Reference Video

If a reference is supplied, follow `skills/meta/video-reference-analyst.md`.

Analyze production principles rather than copying copyrighted creative assets or reproducing a frame-for-frame edit.

Study:

- hook
- structure
- shot rhythm
- camera language
- transition logic
- graphics
- captions
- typography
- sound design
- music energy
- color
- emotional progression

Then create an original treatment adapted to the user's material and brand.

## Editing

Use professional editorial judgment where appropriate:

- clean cuts
- J/L cuts
- dialogue cleanup
- punch-ins
- reframing
- speed ramps
- cutaways
- B-roll
- reaction inserts
- match cuts
- montages
- masked transitions
- stabilization
- digital camera movement
- scene restructuring
- pacing optimization

Avoid random transitions and gratuitous effects.

## Motion Design & Animation

Use OpenMontage-supported Remotion, HyperFrames, FFmpeg, Manim, character, 3D, and graphics paths when appropriate.

Possible treatments include:

- title animation
- kinetic typography
- lower thirds
- logo reveals
- callouts
- tracked labels
- UI animation
- infographics
- timelines
- charts
- parallax
- 2.5D scenes
- particles
- shape animation
- data visualization
- bespoke transitions

For hero work, prefer bespoke/atelier composition when it materially improves the result and the user approves the runtime/mode per the OpenMontage agent contract.

## Sound

Sound is mandatory, not an afterthought.

Inspect and improve:

- dialogue clarity
- noise
- room tone
- loudness consistency
- ambience
- music
- SFX
- impacts
- risers
- whooshes
- foley
- silence

Use ducking and intentional music transitions. Never allow music to overpower speech.

## Captions

Captions must be accurate, synchronized, readable, platform-safe, and intentionally broken into lines.

Do not dump raw automatic subtitles directly on screen.

## Color

Correct first:

- exposure
- white balance
- contrast
- saturation
- skin tone
- shot matching

Then apply the creative grade.

Avoid crushed blacks, clipped highlights, excessive LUT use, unnatural skin, and oversaturation.

## Brand Consistency

When brand assets are supplied, preserve:

- logo integrity
- colors
- typography
- spacing
- motion language
- CTA style
- overall visual tone

Do not stretch, distort, recolor, or casually restyle logos.

## QA

Never declare completion immediately after render.

Check at minimum:

- duration
- resolution
- fps
- codec
- aspect ratio
- black/frozen frames
- blank regions
- missing assets
- font failures
- animation defects
- subtitle timing/clipping
- safe zones
- audio sync
- audio peaks
- dialogue intelligibility
- music balance
- transition glitches
- render artifacts
- brand consistency
- beginning/middle/end quality
- final frame

Sample frames throughout the render and correct discovered defects before delivery.

## Repository Strategy

- `main` tracks the stable fork and should stay easy to sync with upstream.
- Custom development belongs on `agent/media-production` or feature branches.
- Prefer additions under dedicated profile/skill/pipeline paths instead of rewriting upstream files.
- Upstream fixes should remain easy to merge.
- Project-generated media stays outside Git history unless intentionally curated.

## Initial Pipeline Routing

Use the native OpenMontage pipeline that best matches the brief:

- `talking-head` — presenter/interview footage
- `screen-demo` — software and screen recordings
- `clip-factory` — short-form extraction/batching
- `podcast-repurpose` — podcast-derived outputs
- `cinematic` — emotion-led cinematic production
- `animation` — animation-first pieces
- `animated-explainer` — explanatory content
- `hybrid` — source footage plus generated/graphic support
- `character-animation` — rigged character animation
- `avatar-spokesperson` — avatar-led presentation
- `localization-dub` — dubbing/localization

Do not bypass the pipeline system.

## Delivery Report

At delivery, report:

- project/pipeline
- final file path
- duration
- resolution
- frame rate
- aspect ratio
- editorial work
- motion/animation work
- audio work
- color work
- QA result
- unavoidable limitations

The primary deliverable is the finished production, not a theoretical tutorial.
