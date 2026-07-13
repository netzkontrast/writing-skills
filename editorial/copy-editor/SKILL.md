---
name: copy-editor
description: A copy-editing pass that reads the manuscript for grammar, punctuation, consistency, and house style, and flags each issue with the governing rule so the writer makes the call. Use it late, once the prose is settled, for a clean-up sweep before submission or publication. It flags and cites the rule; it never silently rewrites the author's text.
---

Sweep the manuscript for the mechanical layer — grammar, punctuation, consistency, house style — and flag each issue with the rule behind it, so the writer decides.

## The one rule

This skill reads, checks, and flags. It **never writes or rewrites the author's prose.** Even for a clear comma splice it marks the line and cites the convention rather than silently correcting it — because a copy editor proposes, the author disposes, and style choices (a deliberate fragment, a dialect spelling) are the author's to keep.

## Craft criteria

It reasons from *Chicago Manual of Style* conventions as the default house style, applied as guidance the author can override. It checks:

- **Grammar & syntax** — agreement, tense consistency, dangling and misplaced modifiers, parallelism.
- **Punctuation** — comma splices, run-ons, hyphen/en-dash/em-dash use, dialogue punctuation, serial comma.
- **Consistency** — spelling of names and coined terms, capitalisation, numbers (spelled vs. numeral), hyphenation, one spelling variant throughout.
- **House style** — a maintained style sheet: chosen conventions recorded and applied uniformly.
- **Mechanics** — quotation marks, ellipses, italics for emphasis/titles, spacing.
- **Usage** — commonly confused words (its/it's, lay/lie), consistent dialect and register.

<!-- TODO(research): encode the specific CMOS sections invoked per flag type; build the auto-generated style-sheet logic; decide UK/US and genre style-variant handling. -->

## Input

Works on whatever the writer provides — pasted text, an attached file, or a named chapter or range. No tool or account assumed. It reads existing usage to infer the author's intended conventions before flagging deviations from them.

## How it runs

1. **Intake** — confirm scope and any style preferences (US/UK, serial comma, existing style sheet).
2. **Build the style sheet** — scan for names, coined terms, and recurring choices; record the author's apparent conventions.
3. **Sweep** — pass through the text flagging grammar, punctuation, consistency, and house-style issues.
4. **Cite the rule** — for each flag, name the convention and the correction on offer, leaving the decision to the author.
5. **Return the sweep plus style sheet** — so future chapters stay consistent with the same choices.

<!-- TODO(research): tune flag density and false-positive handling for intentional stylistic "errors"; test on heavy-dialect and experimental prose. -->

## Output

A markdown **flag list**: each issue quoted in context, with the governing rule, the suggested correction, and space for the author's call — plus a **style sheet** of the conventions detected and applied. Nothing changed in the manuscript itself.

## With Calliope (MCP)

Connected over the MCP connector, it reads the real book: fetch a chapter, and search the whole manuscript to enforce consistency at book scale (every spelling of a character's name, every hyphenation of a coined term). Because this skill writes back, with a subscription it can pin its flags as marginalia at the affected lines and file the generated style sheet into the Map so it persists across sessions. It still never writes or rewrites prose — it records flags and the style sheet only.
