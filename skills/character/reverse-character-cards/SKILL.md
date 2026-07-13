---
name: reverse-character-cards
description: Reads a finished or drafted manuscript and reverse-engineers a standard character card for each major player — goal, wound, arc, voice, relationships — built only from what is actually on the page. Use it when a writer has a draft but no character bible, or wants to see who their characters have become versus who they intended. It reads and documents; it never writes or rewrites the author's prose.
license: MIT
metadata:
  category: character
  writes_back: true
  status: seed
  craft_standard: "Industry character-bible templates."
---

Read the manuscript and build a standard character card for each major player, reverse-engineered from what's actually on the page — not from what the author meant to put there.

## The one rule

This skill reads, analyses, and documents. It **never writes or rewrites the author's prose.** It produces character cards *about* the fiction; it never adds a scene, a line of dialogue, or a backstory beat that isn't already on the page. If the wound is only implied, it marks it as inferred rather than inventing it.

## Craft criteria

It reasons from industry character-bible templates, filling a standard card per major character. Each card captures:

- **Goal / want** — the conscious external objective driving them through the plot.
- **Need / wound** — the deeper lack or unhealed injury the story tests, where the text supports one.
- **Arc** — how (or whether) they change from first appearance to last; the turning beats.
- **Voice** — diction, rhythm, verbal tics, and how their dialogue differs from the rest of the cast.
- **Relationships** — the web of allegiances, tensions, and dependencies with other characters.
- **Function** — the role they serve in the story (protagonist, foil, mirror, antagonist).
- **On-page evidence** — the scenes or lines each field is drawn from, so nothing is asserted without a source.

<!-- TODO(research): finalise the canonical card template and field set; define "major character" detection; calibrate stated vs. inferred labelling. -->

## Input

Works on whatever the writer provides — pasted text, an attached manuscript, or a named chapter or range. No tool or account assumed. It reads as much of the book as it can to build accurate cards; from a partial manuscript it cards whoever it can see and says so.

## How it runs

1. **Intake** — confirm scope and which characters to card (or let it detect the major cast).
2. **Gather appearances** — collect each character's scenes, actions, and dialogue across the provided text.
3. **Infer the card** — derive goal, wound, arc, voice, and relationships from behaviour and speech, tagging each field stated or inferred.
4. **Cite evidence** — anchor every field to the passages it came from.
5. **Deliver the cards** — one per major character, plus a short note on gaps or contradictions worth the author's attention.

<!-- TODO(research): method for distinguishing a character's stated self-image from their demonstrated behaviour; handling ensemble casts. -->

## Output

A **character card** per major player, in a consistent markdown template — goal, need/wound, arc, voice, relationships, function — each field marked stated or inferred and anchored to on-page evidence, followed by notes on any gaps or contradictions. Documentation of the existing fiction, never new fiction.

## With Calliope (MCP)

Connected over the MCP connector, it reads the real book: fetch chapters, and search the manuscript for every appearance of a character so no scene is missed. Because this skill writes back, with a subscription it writes each finished card into the **Map** as a character entry (or updates an existing one), so the bible lives with the book and stays available to other skills. It still never writes or rewrites prose — it authors Map cards only, from evidence already on the page.
