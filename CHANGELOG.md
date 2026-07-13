# Changelog

All notable changes to this catalog are documented here. The format loosely follows
[Keep a Changelog](https://keepachangelog.com/).

## [Unreleased]

### Changed

- **Catalog moved under `skills/`** — `skills/<category>/<skill-name>/SKILL.md`,
  the [Agent Skills](https://agentskills.io) catalog layout, so
  `npx skills add calliope-editor/writing-skills` resolves via the standard
  path instead of the CLI's recursive fallback. All repo links updated.

### Added

- README **"Get the skills"** section — one-command install via the skills CLI
  (`npx skills add calliope-editor/writing-skills`), alongside the paste-anywhere
  and Calliope-MCP paths.

- **PRINCIPLES.md** — the design law for every skill: simulate the service,
  read the book it's trying to be, declared lens (applied / re-scoped / set
  aside), location + evidence + stakes, root causes over symptoms, confidence
  marking, professional content in an accessible register.
- README **"Who these are for"** section — audience declared: ambitious
  beginners and self-published authors.
- CONTRIBUTING **"Improving a seeded skill"** section — how to fill
  `TODO(research)` markers, keep the protocol and frontmatter intact, test
  against a real manuscript, and graduate a seed to `reviewed`.

## [0.1.0] — 2026-07-13

### Added

- Initial catalog: **13 augmentation-only skills** across four categories.
  - **Editorial** — `developmental-editor`, `line-editor`, `copy-editor`, `continuity-editor`
  - **Character** — `reverse-character-cards`, `character-card-builder`
  - **Critique** — `beta-reader-panel`, `agent-first-pages`, `workshop-critique`
  - **Craft drills** — `dialogue-gym`, `scene-architecture`, `psychic-distance`, `prose-rhythm`
- Per-skill frontmatter (`category`, `writes_back`, `status`, `craft_standard`) and an
  `llms.txt` machine index.
- README catalog, Contributing guide, Code of Conduct, Security policy, and MIT license.

> Skills are **seeds** — coherent and usable, with `TODO(research)` markers where deeper
> prompt engineering belongs. Fork and shape them.
