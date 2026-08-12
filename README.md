# Storytelling

An Agent Skill for architecting truthful, audience-native meaning structures — presentations, pitch decks, manifestos, onboarding, project briefings, business plans, landing pages, commercials, storyboards, and durable workspaces.

Most storytelling guidance optimizes for engagement and treats narrative as the default. This Skill inverts that. It builds the most faithful model the audience can actually use, then chooses the form — narrative, explanation, argument, instruction, demonstration, reference, or a hybrid — that best carries the required audience transition. Choosing *not* to tell a story is a supported outcome, not a failure.

## What it does differently

- **Truth before arc.** The truth model is built from the source corpus before any structure is selected. Chronology never becomes causation, an anecdote never stands in for base rates, and partial progress never becomes closure.
- **No mandatory hooks or hero's journeys.** Three acts, protagonists, conflict, climax, and calls to action are available moves, not requirements. The [research foundation](references/research-foundation.md) documents where the evidence is silent, mixed, or actively against them.
- **Architecture chosen from the audience's job.** A table maps eight audience jobs to their strongest starting architectures.
- **Surface-native output.** Live decks, read-alone decks, landing pages, storyboards, and maintained workspaces distribute information differently. The Skill treats that as a first-class constraint.
- **An audience-side audit.** The finished artifact is read cold, as a member of the intended audience, and rebuilt rather than patched when the structure fails.

## Layout

```
SKILL.md                                  the Skill itself
references/architectures-and-surfaces.md  architecture families, surface adaptations, hybrids, no-story branch
references/quality-and-evaluation.md      wow standard, failure classes, artifact audit, behavioral evaluation
references/research-foundation.md         source corpus, research ledger, unsupported universal rules
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

Verify discovery by asking your agent to invoke it by name before relying on it — installed is not the same as reachable.

## Evidence base

Every empirical claim in the research ledger is traced to a peer-reviewed source in [references/research-foundation.md](references/research-foundation.md) — roughly twenty papers and meta-analyses across comprehension, causal structure, signaling, cognitive load, concreteness, and narrative persuasion. Each entry states what the study found and what the Skill does with it. Nothing is reproduced from any source; all prose is original.

Where the evidence is thin, the Skill says so. "Unsupported universal rules" at the end of that reference names the storytelling conventions this corpus does not establish, and the ones it never tested.

## Licensing

Released under the **[PolyForm Small Business License 1.0.0](LICENSE)**, plus an Individual Use permission granted at the bottom of that file. In plain language:

| You want to | Allowed |
|---|---|
| Use it yourself, including in your own paid client or freelance work | **Yes** — Individual Use |
| Use it inside a company with fewer than 100 people and under $1M revenue | **Yes** — Small Business |
| Modify it, adapt it, build your own Skill on top of it | **Yes**, for any permitted purpose |
| Share your modified version, carrying these same terms forward | **Yes** |
| Roll it out across a company that does not meet the Small Business threshold | **No** — needs a separate licence |
| Sell it, or sell a product whose substantial value is this work | **No** — needs a separate licence |

Two things worth being precise about. First, the base license defines a permitted purpose through *your company*, which it defines as any organization you work for — so the Individual Use permission is what makes freelance and client work unambiguously fine. Second, the license grants no right to sublicense or relicense, so these terms travel with every copy and each recipient must independently qualify.

**Beyond those grants** — enterprise or organization-wide deployment, or redistribution as part of a commercial offering — open an issue in this repository to arrange a commercial licence.

Neither this summary nor the repository is legal advice. Where the summary and [LICENSE](LICENSE) differ, LICENSE governs.
