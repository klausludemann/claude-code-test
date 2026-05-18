# Pirate Test — docs/context/

Strategy lives here, one folder over from the product, so agents read growth
context and product code from the same repo. Built with **The Codebase
Strategy Setup** (Pirate Skills, *Why Growth Strategy Belongs in Your
Codebase*).

A sunny little test run of the workflow. One topic per file. Each file
cross-references the others inline with relative links — the strategy *is*
the index.

## Files

| File | Owns | Source prompt |
|------|------|---------------|
| [business.md](./business.md) | identity, value prop, segments, pricing | Prompt 1 (Q1+Q2) |
| [team.md](./team.md) | founders, decisions, bandwidth constraint | Prompt 1 (Q3) |
| [goals-and-targets.md](./goals-and-targets.md) | north-star metric, doubling cadence | Prompt 1 (Q4) |
| [bottlenecks.md](./bottlenecks.md) | binding constraint, top 3 to fix | Prompt 1 (Q5) |
| [vision-and-strategy.md](./vision-and-strategy.md) | long-term vision, operating principles | Prompt 2 |
| [acquisition-strategy.md](./acquisition-strategy.md) | channel hypotheses, prioritization | Prompt 2 |
| [okrs.md](./okrs.md) | current cycle: objectives + KRs | Prompt 2 |
| [projects.md](./projects.md) | execution layer derived from okrs.md | Prompt 3 (local, no Linear) |

## Status

- [ ] Prompt 1 — The Founding Interview (`business.md`, `team.md`, `goals-and-targets.md`, `bottlenecks.md`)
- [ ] Prompt 2 — Derive the Strategy Layer (`vision-and-strategy.md`, `acquisition-strategy.md`, `okrs.md`)
- [ ] Prompt 3 — Stand Up the execution layer (`projects.md` — local substitute for Linear)

> These files are **empty templates**: section headers + `TODO` prompts, no
> invented content. Fill them by running the interview, or by hand.

## Note on Prompt 3

The original Prompt 3 stands up a Linear workspace via the Linear MCP server
(a third-party tool). This setup keeps everything inside Claude Code with no
third-party tools, so the execution layer is a local
[projects.md](./projects.md) that mirrors what Linear would hold — one
"project" per Objective, issues per Key Result, bidirectional links back to
`okrs.md`.
