# Security Policy

This repository contains prompt-based Agent Skills (Markdown), not executable services — but prompts can still carry risks (e.g. instructions that try to exfiltrate a manuscript, or that quietly break the augmentation-only rule).

## Reporting

If you find a skill that behaves unsafely — leaks content it shouldn't, attempts to write prose against the rule, or embeds a prompt-injection — please report it privately to **hello@writecalliope.ink** rather than opening a public issue. We'll acknowledge within a few business days and credit you if you'd like.

## Using these skills safely

- Skills read the manuscript **you** give them; review what a skill does before connecting it to a real book over MCP.
- Over MCP, "tends canon" skills can write to your **Map** and **marginalia** with a subscription — never to your prose. If a skill tries to write prose, treat it as a bug and report it.
- These are seeds meant to be forked; when you adapt one, keep the one rule intact.
