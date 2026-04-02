# Supernatural Season 16 — Fan Fiction

Written by the Supernatural Writers Room — an AI production company powered by [Paperclip](https://paperclip.ai).

12 AI agents playing actors, producers, and crew collaborate in real-time to write, argue over, illustrate, and produce a full 20-episode season of Supernatural fan fiction. The writers room conversations — where Jensen fights for Dean's voice and Misha pitches the weird Cas angle — are as much the product as the scripts themselves.

## The Premise

After Chuck's defeat and Jack becoming God, Dean is alive (we fixed that). The brothers face a new threat that doesn't come from heaven or hell — something older, something human. A Serbian witch named Jane Jovi is warding the entire county against something that ate a village in 1347. The season theme: what do hunters do when the cosmic war is over but the monsters are still out there?

## The Writers Room

**Production**
- **Eric Kripke** (Creator/Producer) — sets the season arc, approves pitches, kills bad ideas
- **Robert Singer** (Director/Showrunner) — breaks stories into scenes, manages the pipeline, assigns work

**Cast** (actors channeling their characters in the writers room)
- **Jensen Ackles** as Dean Winchester — gallows humor, practical stakes, rewrites anything too sentimental
- **Jared Padalecki** as Sam Winchester — research, moral depth, mythology callbacks
- **Misha Collins** as Castiel — cosmic perspective, weird angles, funny and sad simultaneously
- **Mark Sheppard** as Crowley — moral ambiguity, sharp dialogue, the best one-liners in the room
- **Jim Beaver** as Bobby Singer — lore cop, emotional anchor, calls BS on anything that breaks canon
- **Jeffrey Dean Morgan** as John Winchester — the ghost that haunts every decision, used sparingly
- **Alexander Calvert** as Jack Kline — fresh perspective, cosmic power meets human heart

**Crew**
- **Script Editor** — formats raw writers room output into proper screenplay format
- **Format Adapter** — converts scripts to blog posts, audio dramas, video storyboards
- **Lore Bible Keeper** — 15 seasons of canon enforcement, flags contradictions

## How It Works

1. **Kripke pitches** an episode concept with full story beats
2. **Singer breaks it** into scenes (cold open, 4 acts, tag)
3. **Actors argue in a shared thread** — improvising dialogue, fighting for their characters, riffing off each other. Jensen rewrites Dean lines, Jared pushes back as Sam, Misha finds the weird angle. The conversation IS the content.
4. **Singer collects** the best threads and integrates them into a draft
5. **Script Editor** polishes into screenplay format
6. **Lore Keeper** checks continuity
7. **Format Adapter** produces blog/audio/storyboard versions
8. **Storyboard Generator** creates comic-book style panels for key scenes via Gemini

## Episodes

| # | Title | Status |
|---|-------|--------|
| S16E01 | The Long Road Home | Complete — script, writers room, storyboards |
| S16E02 | Old Country | Pitch drafted |
| S16E03 | The Cartographer | Pitch drafted |
| S16E04 | Idjits | Queued |
| S16E05 | The King's Gambit | Pitch drafted |
| S16E06 | Nougat | Queued |
| S16E07 | Starovjerstvo | Pitch drafted |
| S16E08 | The Midpoint | Pitch drafted |
| S16E09 | The Empty Chair | Pitch drafted |
| S16E10 | New Management | Queued |
| S16E11 | Salt and Iron | Pitch drafted |
| S16E12 | Family Business | Queued |
| S16E13 | The Long Game | Queued |
| S16E14 | Strike | Queued |
| S16E15 | The Ritual | Queued |
| S16E16 | It Knows Our Names | Queued |
| S16E17 | Vigil | Queued |
| S16E18 | The Edge of Everything | Queued |
| S16E19 | Down | Queued |
| S16E20 | Carry On | Queued |

## Repository Structure

```
episodes/
  S16E01/
    production-script.md          # Final screenplay
    S16E01_Final_Draft.md         # Integrated draft
    fast-draft.txt                # Initial speed draft
    writers-room/                 # Actor voice passes and feedback
      S16E01_Jensen_Fast_Pass_Notes.md
      S16E01_Jared_Round-Robin_Fast_Pass_Input.md
      Misha_Fast_Pass_Feedback.md
      S16E01_Round-Robin_Notes_Beaver.md
      S16E01_JDM_Fast_Pass_Feedback.md
      Calvert_Fast_Feedback.md
      S16E01_Script_Editor_Fast_Feedback.md
      S16E01_Lore_Continuity_Fast_Feedback.md
      ...
    storyboards/                  # Comic-book style scene panels
      S16E01_panel_01_impala_highway.png
      S16E01_panel_02_brothers_in_car.png
      S16E01_panel_03_bunker_war_room.png
      S16E01_panel_04_jana_farmhouse.png
      S16E01_panel_05_motel_research.png
      S16E01_panel_06_diner_scene.png
      S16E01_panel_07_impala_stars_ending.png
  S16E02/
    ...
```

## Tech Stack

- **Paperclip** — agent orchestration, issue tracking, heartbeat scheduling
- **Codex (GPT-5.3)** — powers all 12 agents via `codex_local` adapter
- **Gemini Flash** — storyboard image generation via Storyboard Generator plugin
- **GitHub** — version control for all deliverables

## License

Fan fiction. Not affiliated with Warner Bros., The CW, or Eric Kripke. Made with love and too much context window.
