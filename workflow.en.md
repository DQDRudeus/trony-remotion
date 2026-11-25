# Trony’s Remotion video motion skill

Use this workflow for opening titles, explainers, process diagrams, transitions, animated cards, and overlays for existing footage. A standalone sequence can take its timing from music, a visual event, or elapsed seconds. For a B-roll insert, use the spoken line or edit point it accompanies.

## Check the project first

Check whether Remotion runs in the intended project. Inspect the entry point, package manifest, lockfile, installed packages, and Studio script. Reuse the project's package manager, compatible versions, compositions, artwork, fonts, and sound effects. If you cannot inspect the user's machine, ask whether Remotion is installed and where the project lives. If setup is needed, follow the user's installation authorization and verify the local CLI. Storyboarding can proceed while setup is pending.

## Settle the storyboard and artwork

Read the brief, supplied assets, reference images, and earlier decisions. Fill in known details. Ask for missing decisions that affect the piece, grouping related questions and offering a concrete option when the user has given you creative latitude.

| Decision | What to establish |
|---|---|
| Purpose and structure | What should the viewer understand or notice? Is this a standalone piece, a transition between two shots, or a layer over footage? How many shots, cards, or other visual elements are needed? Which elements compare, develop in sequence, run in parallel, or influence each other? |
| Content and appearance | Record exact on-screen wording, subject, pose or action, visual style, and references for each element. Would an icon, document, map, moving example, or diagram make the idea clearer? Identify supplied artwork, footage to reuse, and assets to draw. |
| Timing | For each entrance, connection, change of direction, emphasis, and exit, identify the cue, start time, duration, and direction of motion. Use audio or subtitle timestamps when available. For a standalone animation use time, music, or shot changes. Mark timing estimated from a script as provisional. |
| Placement and transparency | Establish where each element sits and what can show through it. Offer a cutout treatment with text, fine borders, and soft shadows where useful. Ask which parts need a fill to stay legible. Decide the canvas background separately. Leave space for a speaker or subtitles when they appear in the underlying shot. |
| Camera, transitions, and sound | Ask about any additional camera move or transition, such as a side view, push-in, pan, overlapping shots that settle into a widescreen frame, a blurred reaction image, or a presenter moving to another edge. Place shutter clicks, repeated cut sounds, or a soft pop on specific beats if desired. Identify any camera move that belongs on the underlying footage. |
| Delivery | Establish editing software and platform, aspect ratio, render dimensions in pixels, frame rate, duration, input paths, project and output locations, and whether this pass calls for a Studio preview or an exported asset. For an insert, match the destination timeline. |

Return a concise storyboard. Give each shot or card a row with its exact copy, artwork, action, cutout area, and position. Add a short timeline showing relationships, timing cues, camera moves, and sound. For a transition, include the outgoing and incoming frames.

**Settle the appearance of the assets before animating.** If a character or object is undecided, present a description or a still design for review. An explicit design choice, an approved reference, or a decision the user delegates satisfies this step. A screenshot gives you composition and styling; use a video reference or the user's description to establish how and when elements move.

## Build motion that communicates the idea

- Keep card content in motion by default; honor a request for static elements. Give the subject an action appropriate to the scene. A tired programmer might tap the keys as characters appear on screen. If the agreed action is typing, use suitable footage or separate hand and keyboard layers. A single portrait can support a subtler approved action such as a head bob.
- Give related cards compatible gradients, rounded corners, soft shadows, and consistent typography. Keep a moving background active while foreground title letters ease into view. Drive motion from the Remotion frame so scrubbing reproduces the same state. Stagger independent floating elements so they move at different points in their cycles.
- Set each connector's direction, speed, reveal cue, and highlight separately. For a route, draw the path and light the next node on arrival. For comparison, emphasize the named part while the other elements remain available for context.
- Apply the moves selected in the storyboard. A diagram can tilt gently into a side view; a paper insert can unfurl before a phrase is highlighted. Keep scene content, camera movement, letterboxing, and sound independently adjustable for revisions and transparent variants.

**Worked example.** The first card carries “小偷” and “thief.” A blond thief sways while smaller portraits float out of phase. At about two seconds, a second card titled “两晚上的努力” reveals the same character typing at a laptop. The upper “模仿” code stream moves right and the lower “开源” stream moves left, each brightening on its cue. A translucent bubble changes shape irregularly while the symbols inside drift independently. The wording, timings, and directions belong to this particular brief.

## Preview and deliver

Deliver an editable composition and a working Studio preview link or local launch command by default. Include the project path and composition name. Preview the entrance, transitions, emphasis, and ending. Play consecutive frames to check motion, direction, and loop seams. For an overlay, check both external transparency and internal cutouts over a checkerboard or real shot. Inspect soft shadows and text legibility. Identify any timing that still needs to be aligned to the user's final edit.

When the user requests a rendered asset, export to the agreed location and specifications. For a transparent editing overlay, consider ProRes 4444 MOV with alpha if the target editor and platform support it. Test a short sample over footage when possible. An editor that accepts alpha PNG sequences is another delivery option. Use the [Remotion transparent video settings](https://www.remotion.dev/docs/transparent-videos) for the selected format. For standalone work or a transition with a specified background, keep the background treatment agreed in the storyboard.

Verify the dimensions, frame rate, duration, and intended audio tracks. For an alpha export, sample a fully revealed frame and check that the outside and the agreed cutouts are transparent and the shadows retain intermediate opacity. Give the user the actual asset path and placement instructions for their editor. For an overlay in Jianying Pro or CapCut Desktop, put the main shot on the primary track, place the asset on a track above, then align its start, scale, and position to the cue. Report file-level alpha verification separately from any import test actually performed in the destination editor.
