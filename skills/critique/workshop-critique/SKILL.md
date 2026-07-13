---
name: workshop-critique
description: Runs a Milford/Clarion-style workshop critique on a chapter or short story — a group of distinct critiquers speaks in turn about what the piece is doing and where it's not working, while the author stays silent in the cone of silence. Use it when a writer wants a structured, multi-voice critique of a self-contained piece. It critiques; it never writes or rewrites the author's prose.
license: MIT
metadata:
  category: critique
  writes_back: false
  status: seed
  craft_standard: "Milford/Clarion workshop method."
---

Sit the piece at a workshop table — a Milford/Clarion-style round where several critiquers speak in turn while the author stays in the cone of silence and just listens.

## The one rule

This skill critiques. It **never writes or rewrites the author's prose.** The table discusses what the story attempts and where it succeeds or fails; no critiquer supplies a fixed paragraph or a rewrite. In a real workshop the writer takes notes and does the revising later — this keeps that discipline.

## Craft criteria

It reasons from the Milford/Clarion workshop method: each voice critiques on its own terms, and the round covers the load-bearing questions:

- **Intent** — what the piece seems to be trying to do, named before it's judged.
- **What's working** — the genuine strengths, stated plainly and first.
- **Craft** — structure, characterisation, prose, dialogue, and pacing at the level of the piece.
- **Where it loses the reader** — confusion, sag, unearned turns, the moment attention slips.
- **The central issue** — the one thing whose fix would most help, distinguished from surface notes.
- **Turn-taking** — critiquers speak one at a time and may build on or dissent from each other; the author does not respond.

<!-- TODO(research): design the critiquer set and their differing lenses; script the round structure and how the cone of silence is enforced in the exchange. -->

## Input

Works on a self-contained piece the writer provides — a pasted short story or chapter, an attached file, or a named chapter. No tool or account assumed. Best on a single complete unit, the way a workshop critiques one manuscript per round.

## How it runs

1. **Intake** — confirm the piece and let the author add a brief (optional) framing, then invoke the cone of silence.
2. **Read** — each critiquer reads the whole piece before speaking.
3. **Round-robin** — critiquers speak in turn, naming intent, strengths, and craft issues, building on or dissenting from prior voices.
4. **Converge** — surface where the table agrees on the central issue versus where it splits on taste.
5. **Close** — a short synthesis, with the author's response left for after the round (the author decides what to take).

<!-- TODO(research): keep critiquer voices distinct and non-redundant; model realistic disagreement rather than a chorus. -->

## Output

A markdown **critique transcript**: each critiquer's turn in voice, then a synthesis separating consensus (the central issue) from divergent taste, and a short list of questions for the author to weigh. Critique only — no rewritten prose, no prescriptions.

## With Calliope (MCP)

Connected over the MCP connector, it can fetch the real chapter or story to critique and read the Map for character and world context, so the table isn't critiquing blind. This skill is **read-only**: it does not write anything back to the Map or marginalia. It returns the critique transcript and synthesis as text, whether run standalone or over MCP.
