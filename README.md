<p align="center">
  <img src="assets/logo.svg" alt="Writing Skills" width="440">
</p>

<p align="center">
  <strong>Augmentation-only <a href="https://www.anthropic.com/news/skills">Agent Skills</a> for fiction writers — an editor, a critique group, a character bible, and a craft coach that read your manuscript and never write a word of it.</strong>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-5E8480" alt="License: MIT"></a>
  <a href="#the-catalog"><img src="https://img.shields.io/badge/skills-13-5E8480" alt="Skills: 13"></a>
  <img src="https://img.shields.io/badge/works%20with-Claude%20%7C%20ChatGPT%20%7C%20Cursor-2B2722" alt="Works with Claude, ChatGPT, Cursor">
  <img src="https://img.shields.io/badge/augmentation-only-B7355E" alt="Augmentation only">
  <a href="https://github.com/calliope-editor/writing-skills/stargazers"><img src="https://img.shields.io/github/stars/calliope-editor/writing-skills?color=5E8480" alt="Stars"></a>
</p>

Every AI writing tool wants to draft for you. **These don't.** Each skill reads your book, critiques it, simulates a room it will face, or drills you on craft — and hands back diagnosis, reaction, and ranked feedback. Never prose. The words on the page stay yours; that refusal is the whole point.

Built as [Claude](https://claude.com) Agent Skills, usable in any Claude session, and made to connect to a real manuscript over the [Calliope](https://writecalliope.ink) MCP connector.

> ## 13 skills · 4 categories · 0 that write your prose
> Fork any one, shape it to your craft, and point it at your book.

## The catalog

### ✍️ Editorial — simulated editors, from the story read to the copy pass

| Skill | What it does | Tends canon\* |
|---|---|:--:|
| [**developmental-editor**](editorial/developmental-editor) | The big-picture read: structure, pacing, arc, stakes — an edit letter, before any line edits. | ✓ |
| [**line-editor**](editorial/line-editor) | Sentence craft — rhythm, clarity, voice, overwriting. Shows the weak line and why; never rewrites it. | ✓ |
| [**copy-editor**](editorial/copy-editor) | Grammar, punctuation, consistency, house style — each flagged with the governing rule, so you decide. | ✓ |
| [**continuity-editor**](editorial/continuity-editor) | Reads the book against its own facts and timeline and flags the contradictions. Pairs with the Map. | ✓ |

### 🎭 Character — industry-standard cards

| Skill | What it does | Tends canon\* |
|---|---|:--:|
| [**reverse-character-cards**](character/reverse-character-cards) | Reverse-engineers a standard character card per major player, built only from what's on the page. | ✓ |
| [**character-card-builder**](character/character-card-builder) | Builds a card from scratch, interview-style — one sharp question at a time. | ✓ |

### 🔍 Critique simulators — the rooms your book will face

| Skill | What it does | Tends canon\* |
|---|---|:--:|
| [**beta-reader-panel**](critique/beta-reader-panel) | A panel of distinct reader personas reacting chapter by chapter — confused, bored, delighted, lost. | ✓ |
| [**agent-first-pages**](critique/agent-first-pages) | A literary agent's slush-pile read of your opening: request, or pass — and the honest why. | — |
| [**workshop-critique**](critique/workshop-critique) | A Milford/Clarion-style critique round; the group speaks while you stay in the cone of silence. | — |

### 🏋️ Craft drills — get better on purpose

*Theory framed by your intent → a targeted drill → you write it → a ranked read of how you did → the next drill.*

| Skill | What it does | Tends canon\* |
|---|---|:--:|
| [**dialogue-gym**](craft/dialogue-gym) | Subtext, beats, and distinct voices — drilled and ranked. | — |
| [**scene-architecture**](craft/scene-architecture) | Goal, conflict, disaster; scene and sequel — drilled and scored. | — |
| [**psychic-distance**](craft/psychic-distance) | The five rungs of narrative distance, and controlling them on purpose. | — |
| [**prose-rhythm**](craft/prose-rhythm) | Sentence variety, sound, and cadence — tuned and scored. | — |

\* **Tends canon** — connected to a Calliope book over MCP, these skills can write their findings back to your **Map** or **marginalia** (a character card, an edit letter, a continuity flag) — never your prose, and with a Calliope subscription. The rest return their output as text.

## Two ways to use a skill

**Universal — paste or attach, in any Claude session.**
Every skill is self-contained. Drop a skill's `SKILL.md` into any Agent-Skills-capable client, then paste your text, attach a manuscript file, or name a chapter range. No account, plugin, or subscription required. The skill works on exactly the text you hand it and returns its output as text or markdown.

**With Calliope — connect over MCP, work on your whole book.**
[Calliope](https://writecalliope.ink) is a manuscript-first writing app. Connect a skill to your Calliope book over the [MCP connector](https://writecalliope.ink/docs/mcp) and it reads the *real* manuscript — chapters in order, a search across the whole book, your **Map** (characters, arcs, timeline) and **marginalia** — instead of only the snippet you pasted. See how it fits together at **[writecalliope.ink/features/mcp](https://writecalliope.ink/features/mcp)**.

## These are seeds — fork them

Each `SKILL.md` is a **seed**, not a finished prompt: coherent and usable, but the deep work — rubrics, worked examples, drill ladders — is marked with `<!-- TODO(research): … -->` for you to develop. Fork the repo, shape a skill to your own craft and taste, and make it yours. That's what it's for.

## The one rule

Everything here is **augmentation-only**. A skill may read, analyse, critique, teach, and — over MCP — tend your canon. **No skill may write or rewrite the author's prose.** A contribution that drafts, ghostwrites, or "rewrites in your voice" is out of scope by design. What you get back is diagnosis, reaction, and ranked feedback — the things a good editor, a good beta reader, and a good workshop give you — never a draft written for you.

## Contributing

New skills are welcome — a folder, a `SKILL.md`, and a row in the catalog above. See **[CONTRIBUTING.md](CONTRIBUTING.md)** for the skill format and the one hard rule. Please also read the **[Code of Conduct](CODE_OF_CONDUCT.md)**.

## License

[MIT](LICENSE) — fork, adapt, and ship freely. Craft-method references (Gardner, Le Guin, Swain, Story Grid, the Chicago Manual of Style, and others) are named as methodology attribution only; no source text is reproduced.

## About

Maintained by the team behind [Calliope](https://writecalliope.ink) — the AI writing app that never writes your prose. If these skills are useful on their own, wonderful; if they make you want a manuscript-native home for them, that's where Calliope comes in.
