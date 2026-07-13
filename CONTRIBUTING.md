# Contributing

Thanks for wanting to add to the catalog. New skills, and improvements to the seeded ones, are welcome.

## The one hard rule

**A skill may never write or rewrite the author's prose.** It may read, analyse, critique, teach, simulate a reader/editor/agent, and — over MCP — tend canon (Map, marginalia). It may *not* draft, ghostwrite, continue, or "rewrite in your voice." A PR that does is out of scope by design. Everything here is augmentation-only; that constraint is the point of the project.

## Adding a skill

1. Pick the right category folder: `editorial/`, `character/`, `critique/`, or `craft/` (or propose a new one).
2. Create `<category>/<skill-name>/SKILL.md` where `<skill-name>` is kebab-case and matches the `name:` in the frontmatter.
3. Follow the frontmatter shape used across the repo:

   ```yaml
   ---
   name: your-skill-name
   description: >-
     Third person, one or two sentences: what it does and WHEN to use it
     (this is what triggers the skill). End with the refusal — it never writes
     or rewrites the author's prose.
   license: MIT
   metadata:
     category: editorial        # editorial | character | critique | craft
     writes_back: false         # true only if it tends canon over MCP
     status: seed               # seed | reviewed
     craft_standard: "The method / lineage it reasons from (attribution only)."
   ---
   ```

4. In the body, include: a one-line purpose; a `## The one rule` restating the refusal; `## Craft criteria` it reasons from; an `## Input` contract (pasted text / attached file / chapter range — no tool assumed); `## How it runs`; `## Output`; and a `## With Calliope (MCP)` section describing the connected path (and, if `writes_back: true`, what it writes to the Map/marginalia — never prose).
5. Add a row for it to the catalog table in the [README](README.md).
6. Keep craft-method references as **attribution only** — name the method or author; never paste or reproduce their text.

## Seeds are fine

Skills here are seeds. It's OK to leave `<!-- TODO(research): … -->` markers where deeper work belongs — a clear, honest seed is more useful than an over-claimed one.

## Pull requests

Open a PR with a short description of the skill and who it's for. Be kind and constructive — see the [Code of Conduct](CODE_OF_CONDUCT.md).
