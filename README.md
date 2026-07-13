# Writer skills — augmentation-only Agent Skills for writers

A public, forkable collection of [Anthropic Agent Skills](https://www.anthropic.com/news/skills) for fiction writers. Every skill here is built on one stance:

> **AI as editor, critic, and coach — never ghostwriter.**

These skills read your manuscript, analyse it, critique it, simulate the rooms it will face, and drill you on craft. **None of them write or rewrite your prose.** That refusal is the point: the words on the page stay yours. What you get back is diagnosis, reaction, and ranked feedback — the things a good editor, a good beta reader, and a good workshop give you — not a draft written for you.

## Two ways to use a skill

**Universal — paste or attach, in any Claude session.**
Every skill is self-contained. Copy a skill into your Claude setup (or drop the `SKILL.md` into any Agent-Skills-capable client), then paste your text, attach a manuscript file, or name a chapter range. No account, plugin, or subscription is required. The skill works on exactly the text you hand it and returns its output as text or markdown.

**With Calliope — connect over MCP, work on your whole book.**
[Calliope](https://writecalliope.ink) is a manuscript-first writing app. Connect a skill to your Calliope manuscript over the MCP connector and it can read the *real* book — fetch chapters in order, search the whole manuscript, and read the **Map** (your characters, arcs, and timeline) and **marginalia** — instead of only the snippet you pasted. Skills marked *writes back* can also tend canon: file an edit letter or continuity flag as marginalia at the exact scene, or write a character card into the Map. Writing back needs a Calliope subscription. Even then, **no skill ever writes or rewrites your prose** — only editorial notes, flags, and canon.

## Fork them — these are seeds

Each `SKILL.md` here is a **seed**, not a finished prompt. It is coherent and usable, but the deep prompt engineering — rubrics, worked examples, drill ladders — is marked with `<!-- TODO(research): ... -->` comments for you to research and deepen. Fork this repo, shape a skill to your own craft and taste, and make it yours. That's what it's for.

## The skills

### Editorial
Simulated editors and editing guidelines — from the big-picture story read down to the copy-editing sweep.

- **[Developmental editor](editorial/developmental-editor/)** — The big-picture read.
- **[Line editor](editorial/line-editor/)** — Sentence by sentence.
- **[Copy editor](editorial/copy-editor/)** — The clean-up pass.
- **[Continuity editor](editorial/continuity-editor/)** — Canon & timeline drift.

### Character
Industry-standard character work — reverse-engineered from your pages, or built from scratch.

- **[Reverse character cards](character/reverse-character-cards/)** — Reverse-engineer your cast.
- **[Character card builder](character/character-card-builder/)** — Build one from scratch.

### Critique simulators
The rooms your book will face — beta readers, an agent's slush pile, a workshop table — before it faces them for real.

- **[Beta-reader panel](critique/beta-reader-panel/)** — A room full of readers.
- **[Agent first-pages read](critique/agent-first-pages/)** — The slush-pile read.
- **[Workshop critique](critique/workshop-critique/)** — The workshop table.

### Craft drills
Get better on purpose: theory framed by your intent, an exercise to write, and a ranked read of how you did.

- **[Dialogue gym](craft/dialogue-gym/)** — Train your dialogue.
- **[Scene architecture](craft/scene-architecture/)** — Build stronger scenes.
- **[Psychic distance](craft/psychic-distance/)** — Master POV distance.
- **[Prose rhythm](craft/prose-rhythm/)** — Tune your prose.

## A note on craft lineage

Several skills reference established craft methods and authors — Gardner, Le Guin, Swain, Bickham, Egri, Browne & King, Story Grid, the *Chicago Manual of Style*, the Milford/Clarion workshop tradition. These are cited as **methodology attribution only**. The skills reason *from* these approaches; they do not reproduce the authors' text.

## License

MIT — see [LICENSE](LICENSE). Fork it, change it, ship it.
