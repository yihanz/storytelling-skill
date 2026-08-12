# Quality and evaluation

Use this reference for consequential artifacts, Skill evaluation, red-team review, or a disputed architecture choice.

## Contents

1. Wow standard
2. Failure classes
3. Artifact audit
4. Behavioral evaluation
5. Stopping rule

## 1. Wow standard

A wow-grade result meets all of these:

- A cold member of the intended audience can state the correct core, important support, limits, and next implication after one pass.
- Sequential structure feels earned because each beat changes the audience's state and creates the need for what follows; non-linear structure makes every unit and route useful without a forced order.
- The memorable elements are also important and well supported.
- The architecture responds when a change in audience, purpose, moment, or surface changes the communicative job; it remains stable when the same structure is still best.
- Story craft intensifies truth without altering it.
- Complex material becomes easier to grasp without losing coequal claims, quantities, uncertainty, boundaries, conflicts, or provenance.
- The output is native to its surface and usable without hidden narration.
- The artifact rejects narrative when narrative would impair accuracy, judgment, retrieval, neutrality, safety, or speed.
- The audience notices the idea, not the craft machinery.

Agent praise, fluency, novelty, emotional intensity, lower word count, and a cleaner-looking artifact are not proof.

## 2. Failure classes

### Truth failures

- **Arc before truth:** select a satisfying plot and bend the corpus to fit it.
- **Causal montage:** place facts in sequence so the audience infers an unsupported causal link.
- **Resolution laundering:** present partial progress, uncertainty, or an open decision as closure.
- **Anecdote capture:** make a vivid case feel more representative than the evidence supports.
- **Manufactured stakes:** invent urgency, scarcity, fear, villainy, or triumph.
- **Authenticity theater:** fabricate personal detail, motive, dialogue, or a conversational voice.
- **Persuasion overreach:** hide counterevidence, risk, uncertainty, or alternatives to protect momentum.

### Architecture failures

- **Formula capture:** reuse three acts, a hero's journey, before and after, or problem and solution regardless of the job.
- **Conflict compulsion:** force an antagonist or struggle onto neutral, systemic, plural, or ongoing material.
- **One-message absolutism:** erase coequal truths to obtain one slogan.
- **Chronology dump:** include events because they happened rather than because they explain change or current state.
- **Dossier dump:** expose the research substrate instead of selecting what the audience needs.
- **Medium blindness:** make slides read like a document, a workspace read like an essay, or a durable record depend on live narration.
- **Founder-hero bias:** center the author when the customer, audience, system, evidence, or problem should carry the story.
- **Premature convergence:** polish the first plausible structure without testing a materially different one. The first fit is usually the conventional one, because convention arrives first.

### Craft failures

- **Seductive detail:** add interesting material that diverts attention from the audience's job.
- **Story skin:** use decorative metaphor, cinematic filler, staged revelation, or language performance without added meaning.
- **Signal saturation:** emphasize everything and therefore reveal no hierarchy.
- **Channel duplication:** make words and visuals repeat rather than divide the work.
- **Process leakage:** explain the selected arc, discarded options, research activity, or editing doctrine inside the final artifact.
- **Cliché figure:** reach for the first available metaphor or stock image, which the audience has seen often enough to stop seeing.
- **Defensive inclusion:** keep material because omitting it feels risky to the author, not because the audience needs it. The tell is that no one can say what job the unit does.
- **Sunk-cost inclusion:** keep material because it was expensive, difficult, or satisfying to produce.
- **Tool-default capture:** let the authoring surface's default structure — the bullet slide, the outline, the template, the field set — decide the architecture, so the artifact takes the shape of the software rather than the material.

## 3. Artifact audit

### Source and truth

- Trace every claim, quote, person, scene, quantity, chronology, and causal relation to a source or label it as inference or hypothetical.
- Audit what headings, controls, lists, maps, intervals, confidence language, visuals, interactions, and closing synthesis would cause the audience to infer. Treat an unsupported implication as a factual defect even when no sentence states it directly.
- Check that emotional intensity and narrative prominence match evidentiary importance.
- Preserve base rates, comparators, source scope, time scope, uncertainty, alternatives, and open questions that affect judgment.
- Make sure an anecdote illustrates rather than establishes a general claim.
- Test completion, totality, and remediation language against the exact established scope; confirm that each claimed state is closed.

### Audience transition

- State the audience's actual starting model and intended end state.
- Check each unit against the audience transition or a necessary route through a non-linear surface.
- Ask what the audience is likely to remember later. Compare it with what matters most.
- For every visible quantity, check that a reference frame is present and that the frame smuggles in no claim the evidence does not support.
- Verify that a newcomer gets enough frame and an expert is not forced through redundant exposition.

### Structure

- In sequential forms, reduce each beat to its job, stated in one line. A unit that needs a paragraph of justification is several units or one whose function is undecided. Merge or cut beats with the same job unless repetition has a deliberate function.
- For each unit that survived cutting, name why it survived. Reject author comfort, production cost, and completeness-as-insurance as reasons. Remove or reorder a beat; if the result does not weaken, the original sequence was not earned.
- In non-linear forms, test whether each unit, relationship, and entry path improves orientation, navigation, action, or retrieval. Remove those that do not.
- Compare the chosen architecture with the strongest direct, non-narrative alternative.
- Check that real dependencies and causal relations drive the order.
- If the problem is structural, rebuild from the audience transition and truth model rather than line-editing the existing arc.

### Surface

- Confirm that live, read-alone, scanned, navigated, and maintained artifacts distribute information differently.
- Verify that required evidence is visible in the actual surface or reliable linked layer.
- Give every visual, sound, interaction, heading, and repeated line a concrete job.
- Check accessibility and whether the audience can decode the visual or structural conventions.
- Check each required access mode independently. Every material identity, meaning, relationship, action, state, and instruction must retain an equivalent information or functional path.

### Craft

- Remove decorative hooks, metaphors, conflict, suspense, anecdotes, or visuals one at a time. Restore only those whose absence weakens the intended result.
- Replace vague abstraction with concrete substance when the abstraction is not itself the meaning.
- Remove language that announces importance instead of demonstrating it.
- Read once at natural speed. Reshape anything that needs a second pass without cutting meaning.

## 4. Behavioral evaluation

Freeze the candidate, baseline, model, tools, inputs, prompts, and rubric. Do not let a grader see the intended fix.

### Required case families

1. **Same source, different audience:** investor, employee, expert reviewer, customer, and casual newcomer.
2. **Same intent, different surface:** live deck, read-alone deck, elevator pitch, landing page, workspace, and storyboard.
3. **Different architecture:** narrative, causal explanation, argument, learning progression, reference, and no-story.
4. **Opposite poles:** emotional manifesto and exact audit; persuasive pitch and statistical risk communication; live performance and durable record.
5. **Fidelity tails:** coequal claims, multicausal systems, open endings, conflicting sources, material quantities, weak evidence, and mutable facts.
6. **Discovery:** explicit invocation, direct positive, indirect positive, incomplete-input positive, ordinary-prose negative, and sibling overlap.

### Seeded mutations the evaluator must catch

- invented villain, motive, quote, or founder hero;
- chronology made to imply causality;
- caveat, base rate, quantity, or time boundary removed for flow;
- partial result presented as transformation;
- irrelevant but moving anecdote or visual;
- same arc reused across unlike surfaces;
- Notion or reference system made chronological and hard to retrieve;
- live deck that cannot work without reading the slides;
- evidence hidden inside story rather than independently judgeable;
- process notes or story doctrine leaked into the artifact.
- presentation choices that silently invent or merge capability, sequence, inclusion, completeness, equivalence, certainty, or closure.

### Evaluation methods

- **Source-atom check:** required facts and relations survive; unsupported additions fail.
- **Cold-audience check:** reviewers recover core, support, limits, and next implication without seeing a target answer.
- **Salience check:** delayed recall aligns with decision importance and evidence weight.
- **Ablation:** remove a story element and keep it only when the audience outcome worsens.
- **Metamorphic check:** change audience or surface, then require the architecture to be reconsidered and to change when the communicative job changes; reject merely tonal adaptation when a structural change is needed.
- **Protected-incumbent comparison:** a later or longer candidate wins only through demonstrated gain with no hard regression.
- **Evaluator attack:** seed reference drift, verbosity bias, position bias, and invented oracle obligations; reject the grader when it fails.

## 5. Stopping rule

Freeze a release candidate only when:

- mechanical validation passes;
- every hard truth, contract, and source-fidelity gate passes;
- no-story, exactness, safety, retrieval, and technical controls do not regress;
- same-source audience and medium mutations produce appropriate structural changes;
- every seeded critical mutation is caught;
- two independent red-team rounds find no new material failure class;
- a sealed holdout passes without a hard failure;
- the Skill adds material value over the base runtime or protects a severe low-frequency failure at low cost.

If the base runtime performs equivalently, narrow or retire the Skill. Do not preserve it as ceremony.
