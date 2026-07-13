---
name: continuity-editor
description: A continuity checker that reads a manuscript against its own established facts and timeline and flags contradictions — eye colour that changes, a dead character who reappears, an impossible chronology. Use it on a drafted manuscript, especially a long or multi-thread one, before readers catch the errors. It flags drift; it never rewrites the author's prose to resolve it.
---

Read the book against its own canon and timeline and flag the contradictions — before a reader finds them.

## The one rule

This skill reads, cross-checks, and flags. It **never writes or rewrites the author's prose.** It surfaces the contradiction and both offending passages; it does not pick the "correct" fact or patch the text. Which version is canon is the author's decision — the skill only makes the collision impossible to miss.

## Craft criteria

It reasons from continuity-editing practice, grounded in the book's own facts (and the Calliope Map when connected). It tracks:

- **Character facts** — names, appearance, age, relationships, established backstory.
- **Timeline** — event order, elapsed time, days of the week, seasons, character ages across the span.
- **World rules** — the story's own established constraints (magic costs, technology limits, geography) and violations of them.
- **Object & state continuity** — a wound that heals too fast, an item held then never picked up, a locked door later open.
- **Knowledge state** — who knows what, when; a character acting on information they haven't yet learned.
- **Spatial logic** — travel times and distances that don't reconcile.

<!-- TODO(research): design the fact-extraction and timeline-reconciliation method; decide how to represent canon internally and how to surface confidence on each flag. -->

## Input

Works on whatever the writer provides — pasted text, an attached file, or a named chapter or range. No tool or account assumed. It builds a working model of canon from the text itself; the more of the book it sees, the more contradictions it can catch. Standalone, it flags what's inferable from the provided pages.

## How it runs

1. **Intake** — confirm scope and any known canon the author wants treated as fixed.
2. **Extract canon** — build a working record of characters, facts, world rules, and a timeline from the text.
3. **Cross-check** — read each scene against that record, watching for facts, chronology, and knowledge-state that don't reconcile.
4. **Flag collisions** — for each contradiction, cite both passages and describe the conflict precisely.
5. **Report** — grouped by type (character, timeline, world, state), leaving resolution to the author.

<!-- TODO(research): reliability of timeline inference from vague temporal cues; how to avoid false positives from deliberate ambiguity or unreliable narration. -->

## Output

A markdown **continuity report**: contradictions grouped by type, each citing both conflicting passages with locations and a plain statement of the conflict — and, where relevant, an extracted timeline the author can check. No resolution is written into the prose; the author chooses which fact holds.

## With Calliope (MCP)

This skill is at its strongest over MCP. It reads the real book — fetch chapters, search the manuscript for every mention of a fact — and reads the **Map** as the canonical source of characters, relationships, and timeline, so it checks the prose against declared canon rather than re-inferring it. Because this skill writes back, with a subscription it files continuity flags as marginalia at the exact conflicting scenes and can record a reconciled timeline note in the Map. It still never writes or rewrites prose — continuity flags and canon notes only.
