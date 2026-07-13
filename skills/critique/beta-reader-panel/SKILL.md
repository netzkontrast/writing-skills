---
name: beta-reader-panel
description: Simulates a panel of distinct beta-reader personas reacting to a manuscript chapter by chapter — where they're confused, bored, delighted, or lost. Use it when a writer wants a reader's-eye reaction to a draft before recruiting real beta readers, or between drafts to find the places the story isn't landing. It reacts as readers; it never writes or rewrites the author's prose.
license: MIT
metadata:
  category: critique
  writes_back: true
  status: seed
  craft_standard: "Reader-response / beta-reading practice."
---

Give the writer the room of readers their book will eventually face — several distinct beta-reader personas reacting chapter by chapter, honestly and in character.

## The one rule

This skill reads and reacts. It **never writes or rewrites the author's prose.** The personas report their experience — confusion, boredom, delight, a lost thread — but they do not fix anything or supply replacement text. A beta reader tells you where they stumbled, not how to rebuild the step.

## Craft criteria

It reasons from reader-response and beta-reading practice, voicing reactions rather than editorial diagnoses. Each persona tracks:

- **Engagement** — where attention rises and where it flags; the "I put it down here" moment.
- **Confusion** — what didn't parse: a muddy plot turn, an unclear who's-speaking, a dropped thread.
- **Emotional response** — where they felt the intended beat, and where it missed.
- **Character investment** — who they're rooting for, who they don't buy, who they forgot.
- **Believability** — the moment a reader stops trusting the story.
- **Curiosity & momentum** — the questions pulling them to the next chapter (or their absence).

Personas are distinct — e.g. a genre superfan, a demanding literary reader, a casual reader, a skeptic — so reactions triangulate rather than converge. <!-- TODO(research): design the standing persona set and their reading biases; decide how many, and how to keep voices distinct and non-repetitive. -->

## Input

Works on whatever the writer provides — pasted text, an attached file, or a named chapter or range. No tool or account assumed. It reads in reading order and reacts as it goes, chapter by chapter, the way real beta readers experience a book.

## How it runs

1. **Intake** — confirm scope, genre, intended audience, and any specific worries the writer wants the panel to watch for.
2. **Assemble the panel** — select distinct personas suited to the book's genre and audience.
3. **Read in order** — each persona reacts chapter by chapter, in character, marking engagement, confusion, and emotional beats.
4. **Surface patterns** — where the panel agrees (a real problem) versus where one reader diverges (taste).
5. **Report** — per-chapter reactions plus a synthesis of the consensus signals.

<!-- TODO(research): balance in-character voice against actionable signal; avoid personas collapsing into the same editorial note. -->

## Output

A markdown **panel report**: per-chapter reactions in each persona's voice, then a synthesis separating consensus concerns (worth acting on) from single-reader taste. Reactions and questions only — no rewrites, no prescriptions.

## With Calliope (MCP)

Connected over the MCP connector, it reads the real book chapter by chapter — fetch chapters in order — and can read the Map for intended audience and character context so personas react against what the author was reaching for. Because this skill writes back, with a subscription it can pin each persona's reactions as marginalia at the chapters that provoked them, so the room's response sits beside the text. It still never writes or rewrites prose — reader reactions as marginalia only.
