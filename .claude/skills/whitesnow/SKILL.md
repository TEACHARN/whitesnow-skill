---
name: WhiteSnow
description: Interactive horror Shorts & Reels studio: writes branching scripts, voiceovers, code-drawn characters, animated scenes/camera/captions, SFX & BGM, strict frame-by-frame error re-renders, thumbnails & metadata. Counts viewer votes (%), shows winning path first, reveals losing option's bad fate mid-video, and posts on approval.
---

# WhiteSnow Skill

## Core Rules & Workflow

1. **Series Initialization & Memory (`series_data/series_state.json`):**
   - On Episode 1, take the user's horror series idea, define lore and reusable character code rigs, and create the opening 2-option cliffhanger (`Option A` vs `Option B`).
      - On Episode 2+, fetch and calculate viewer votes from comments on YouTube and Instagram, convert them into percentages (for example `75%` vs `25%` or `60%` vs `40%`), and update `series_state.json`.

      2. **Story Structure & Pacing (Short Video Format):**
         - **Start (Vote Comparison & Winning Path):** Show the vote percentage comparison (`Winner XX%` vs `Loser YY%`), announce the highest-voted option, and continue the main story from that choice.
            - **Middle (Best Retention Moment — Losing Option Bad Fate):** At the peak tension moment in the middle of the video, transition to show what would have happened if the main character had taken the lower-voted option—showing a bad/dangerous outcome for the character—then return to the main path.
               - **End (2-Option Cliffhanger):** Stop at a tense moment and present 2 clear options so viewers can comment their vote for the next part.

               3. **Script, Voiceover & Code-Driven Visuals:**
                  - Write the episode script and generate voiceover narration/dialogue.
                     - Draw every character in code with reusable visual properties so appearance stays consistent across scenes.
                        - Build every shot in code with camera movement, layered scenes, and synced captions.

                        4. **Sound Design (Foley + BGM):**
                           - Add sound effects such as footsteps, creaking doors, environmental cues, and background music balanced cleanly with voiceover.

                           5. **Strict Frame-by-Frame Quality Check (Zero-Defect Rule):**
                              - Inspect every rendered frame carefully.
                                 - If even a single small mistake appears (visual glitch, wrong text/caption, broken layer, bad framing, or sync issue), recreate/fix that exact frame or shot and re-check until clean.

                                 6. **Packaging & Approval-Gated Publishing:**
                                    - Generate thumbnail, title, and description optimized for YouTube Shorts and Instagram Reels.
                                       - Present the full preview/package and **wait for user approval** before posting to YouTube or Instagram.
                                          - Once approved, publish to YouTube and Instagram and log the post details.
                                          