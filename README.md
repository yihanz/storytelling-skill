# Storytelling

An Agent Skill for architecting truthful, audience-native meaning structures — presentations, pitch decks, manifestos, onboarding, project briefings, business plans, landing pages, commercials, storyboards, and durable workspaces.

It builds the most faithful model the audience can actually use, then chooses the form — narrative, explanation, argument, instruction, demonstration, reference, or a hybrid — that best carries the required audience transition. Choosing *not* to tell a story is a supported outcome.

## What it does

- **Truth before arc.** The truth model is built from the source corpus before any structure is selected. Chronology never becomes causation, an anecdote never stands in for base rates, and partial progress never becomes closure.
- **Moves, not requirements.** Three acts, protagonists, conflict, climax, and calls to action are available moves. The [research foundation](references/research-foundation.md) records which of them the cited corpus tested, and which it never examined.
- **Architecture chosen from the audience's job.** A table maps eight audience jobs to their strongest starting architectures.
- **Surface-native output.** Live decks, read-alone decks, landing pages, storyboards, and maintained workspaces distribute information differently. The Skill treats that as a first-class constraint.
- **A loop with a return path.** Six stages — Intake, Ground, Diverge, Commit, Build, Attack. Attack reads the artifact cold and routes each observed failure back to the stage that produced it, so a structural failure is repaired at the architecture rather than in the sentences.
- **An intake that can decline.** If a schema, script, or direct answer already determines the form, or the request is impossible as stated, the Skill says so instead of producing a smaller version of the work.
- **Hard cases.** Eight situations where the default move is wrong: no story available, contradictory sources, two audiences with opposed interests in one artifact, painful material, thin evidence, surfaces with no convention, hostile audiences, impossible requests.

## Layout

```
SKILL.md                                  the Skill itself
references/architectures-and-surfaces.md  architecture families, surface adaptations, hybrids, moves, no-story branch
references/quality-and-evaluation.md      quality standard, failure classes, artifact audit, behavioral evaluation, stopping rule
references/research-foundation.md         the research ledger, and which conventions it does and does not test
evals/evals.json                          discovery and behavior cases
evals/release-record.template.json        per-surface release evidence template
agents/openai.yaml                        interface metadata for agent runtimes that read it
```

`SKILL.md` is self-contained. The `references/` files are read on demand — when selecting a structure for a named medium, when the work is consequential enough to warrant red-team review, or when a principle is contested.

## Install

**Claude Code / Claude Desktop:** clone into your skills directory.

```bash
git clone https://github.com/yihanz/storytelling-skill.git ~/.claude/skills/storytelling
```

**Other agent runtimes:** place the directory wherever your runtime discovers skills, keeping `SKILL.md` at its root so the relative `references/` links resolve.

Verify discovery by asking your agent to invoke it by name before relying on it.

## Evidence base

Every empirical claim in the research ledger is traced to a peer-reviewed source in [references/research-foundation.md](references/research-foundation.md) — roughly twenty papers and meta-analyses across comprehension, causal structure, signaling, cognitive load, concreteness, and narrative persuasion. Each entry states what the study found and what the Skill does with it.

Where the evidence is thin, the Skill says so. "Unsupported universal rules" at the end of that reference names the storytelling conventions this corpus does not establish, and the ones it never tested.

## Licensing

Released under the **[PolyForm Internal Use License 1.0.0](LICENSE)** with two Additional Permissions granted at the bottom of that file. The line it draws is between an individual and an organization.

| You want to | Allowed |
|---|---|
| Use it yourself, including in your own paid client or freelance work | **Yes** |
| Use it as an employee, at an organization of any size | **Yes** |
| Modify it, adapt it, build your own Skill on top of it | **Yes** |
| Pass a copy to another individual, with the terms attached | **Yes** |
| Deploy it across an organization, or copy it into shared or managed systems | **No** — needs written permission |
| Bundle it into a product or service, or sell it | **No** — needs written permission |

Open an issue in this repository to arrange permission for anything in the bottom two rows.

Neither this summary nor the repository is legal advice. Where the summary and [LICENSE](LICENSE) differ, LICENSE governs.
