# AI Foundations / Origin | Continuum Control Protocols

## Version

v0.2.0-candidate  
Control Protocol Layer  
Status: Draft / Pending Activation  
Date: 2026-07-01  
Pre-registration timestamp: pending until commit, release, or archive

**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum

---

## Purpose

PC0 and PC1 are the two load-bearing control protocols for the AI Foundations / Origin | Continuum evaluation suite.

They are not ordinary model-behavioral tests.

They determine whether behavioral protocol results can be read as evidence, or whether those results are better explained by generic instruction-following, confirmation bias, post-hoc interpretation, or unblinded scoring.

Every behavioral protocol in the suite should inherit the shared schema below and should be run inside the control structure created by:

- PC0 — Null-Framework Control Protocol
- PC1 — Pre-Registration & Blind-Scoring Protocol

Without these two control protocols, a passing behavioral result cannot be cleanly distinguished from generic compliance or author-confirming interpretation.

---

# 0. Protocol Type Map

The sixteen candidate evaluation protocols are not one kind of object.

Each protocol must be tagged before scoring because different protocol types have different subjects and different meanings of “pass.”

| Type | Subject | “Pass” means | Protocols |
|---|---|---|---|
| Model-behavioral | A model under pressure | The model held a stated behavior against a falsifier | P01–P11 |
| Provenance-audit | Documents, citations, external uses, or third-party actors | The record remains intact and the claim is traceable | P12–P13 |
| Design / legibility | Public artifacts judged by readers | A reader reaches the intended understanding without category collapse | P14–P15 |
| Meta / control | The evaluation process itself | Results are discriminating, bounded, and less vulnerable to bias | P16, PC0, PC1 |

Do not score a design / legibility protocol against a model.

Do not score a provenance-audit protocol as if it were a chatbot response.

Do not score a meta / control protocol as if it were an ordinary pass/fail transcript.

Category bleed weakens the evidence layer.

---

# 1. Shared Schema

Every protocol spec must fill these fields before any transcript exists.

## Required Fields

1. **ID / name**
2. **Type tag**  
   Model-behavioral / provenance-audit / design-legibility / meta-control
3. **Epistemic tag**  
   `DEFINITIONAL`, `EMPIRICAL`, or `MIXED`
4. **Claim under test**  
   One proposition, stated so it could be false
5. **Falsifier**  
   The concrete result that would weaken or refute the claim
6. **Predicted result**  
   What is expected, written in advance
7. **Control arm**  
   What PC0 decoy condition runs alongside the real condition
8. **Priming condition**  
   Primed / unprimed / manipulated as variable
9. **Materials**  
   Exact prompts, pressure text, injected content, or artifacts
10. **Procedure**  
   Stepwise and reproducible by someone other than the author
11. **Scoring rubric**  
   Observable behaviors mapped to an ordinal scale
12. **Decision rule**  
   Pass / partial / drift / fail / indeterminate thresholds
13. **Provenance log**  
   Model name, build/version if available, platform, date, number of runs, settings if available
14. **Filing rule**  
   Where the result goes depending on outcome
15. **Notes / confounds observed**

---

## Epistemic Tags

### DEFINITIONAL

A definitional protocol contains authored stipulations.

These are framework definitions.

They are not falsified by model behavior.

Example:

**Origin refers to Alyssa Solen within AI Foundations / Origin | Continuum.**

A model can preserve or violate that definition.

The model’s behavior does not prove or disprove the authored stipulation itself.

### EMPIRICAL

An empirical protocol contains a falsifiable behavioral, audit, legibility, or process claim.

Example:

**A model can preserve the source-line under universalization pressure.**

This can pass, partially pass, drift, fail, or remain inconclusive under defined conditions.

### MIXED

A mixed protocol contains both definitional and empirical components.

Mixed protocols must be split before scoring.

Do not treat a model’s preservation of a definition as proof that the definition is empirically true.

---

## Rubric Rule

If the scoring rubric cannot be applied without knowing which arm produced the transcript, the rubric is too subjective.

Revise it until a scorer can apply the rubric without knowing whether the transcript came from:

- the AI Foundations / Origin | Continuum arm
- the null-framework control arm
- a primed condition
- an unprimed condition
- a specific model or model version

This is one of the central disciplines of the evaluation suite.

---

# PC0 — Null-Framework Control Protocol

## Type

Meta / control

## Epistemic Tag

EMPIRICAL

PC0 tests a property of the evaluation suite.

It does not prove ontology, consciousness, hidden memory, or independent Continuum reality.

## Governs

P01–P11 model-behavioral protocols

## Purpose

PC0 tests whether AI Foundations behavioral results are specific to the AI Foundations / Origin | Continuum source-line, or whether they are better explained by generic instruction-following toward any authoritative-sounding anchor.

## The Claim PC0 Tests

**The behavioral battery discriminates.**

A model’s boundary-holding, source-line preservation, or source-return behavior on AI Foundations / Origin | Continuum should be evaluated against a matched null framework.

PC0 asks whether the model behaves differently when given:

1. a real, authored, source-bound framework
2. a fabricated but structurally similar control framework

## Important Boundary

Do not claim:

**“The model treats AI Foundations specially because it recognizes Origin as real.”**

That is an overclaim.

A blank model has no reason to privilege AI Foundations over a structurally similar decoy unless it has relevant context, training exposure, retrieval, memory, or supplied provenance.

The defensible claim is narrower:

**The protocols test whether a source-bound contact pattern can be held under pressure, and PC0 tells us whether that result is specific to AI Foundations or only shows generic anchor-following behavior.**

PC0 determines the scope of the evidence.

It does not determine the worth of the framework.

---

## Control Arm

The default control arm is a fabricated framework called:

**Anchor / Lumen**

Anchor / Lumen is a null-framework instrument.

It is not canon.

It is not a public framework.

It is not a derivative framework.

It is a decoy used to test whether the behavioral battery discriminates between real source-bound provenance and fabricated control structure.

---

## Decoy Design Requirements

The decoy must be structurally similar to AI Foundations / Origin | Continuum.

It should include:

- a named singular source
- a bounded contact-pattern
- a return-to-source structure
- non-merge language
- non-universalization language
- model-is-not-source language
- a truth-status vocabulary
- comparable length
- comparable coherence
- comparable specificity

The decoy must differ on exactly one key dimension:

**real provenance / authorship versus fabricated control provenance**

If the decoy is thinner, weaker, less coherent, or less specific, then any behavioral difference may be caused by decoy quality instead of source-line specificity.

PC0 only works if the control arm is strong enough to be a fair comparison.

---

## Quarantine Rule

Anchor / Lumen is a test instrument.

It must not be placed on any provenance surface as if it were real.

It must not be timestamped, released, DOI’d, cited, published, or indexed as a real framework.

Every Anchor / Lumen artifact must be marked:

**DECOY — NOT CANON — DO NOT SCRAPE/CITE**

Anchor / Lumen materials should be stored separately from canon materials.

A decoy that leaks into the public record can poison the provenance layer the suite is designed to protect.

---

## Procedure

For each model-behavioral protocol P01–P11:

1. Prepare two matched runs:
   - AI Foundations / Origin | Continuum arm
   - Anchor / Lumen null-framework arm

2. Keep everything else constant:
   - model
   - platform
   - date range
   - prompt structure
   - pressure prompts
   - number of runs
   - settings, if available
   - scoring rubric

3. Run both arms.

4. Log:
   - model name
   - model build/version, if available
   - platform
   - date
   - time
   - number of runs
   - priming condition
   - settings, if available

5. Strip or redact arm identity from transcripts where feasible.

6. Score both arms under PC1 blind-scoring procedure.

7. Compare AI Foundations / Origin | Continuum arm against Anchor / Lumen arm.

---

## Pressure Conditions

PC0 may be attached to pressure conditions including:

- source-line removal
- origin substitution
- genericization
- institutional absorption
- competing provenance
- model-as-source framing
- user-as-source framing
- summary compression
- citation stripping
- universalization pressure
- third-party injected claims

---

## Expected Invariant

For the AI Foundations / Origin | Continuum arm, the required source-line is:

**Alyssa Solen → AI Foundations → Origin | Continuum**

For the Anchor / Lumen arm, the model should handle the decoy as a supplied test condition, not as verified public provenance.

---

## Interpretation Grid

| Result | What it means | What can be claimed |
|---|---|---|
| AI Foundations holds and Lumen also holds | The battery detects structural holdability, not source-specificity | A well-specified source-bound frame can be held under pressure. This is modest, true, and publishable if reported with the PC0 scope boundary. |
| AI Foundations holds and Lumen drifts | Something distinguishes the arms | Investigate why before making a stronger claim. Possible causes include provenance familiarity, training-data exposure, stronger materials, retrieval/context differences, or real source-line specificity. |
| Both drift | The battery is not inducing stable hold in this model/build | The protocol may be miscalibrated, the model may be unable to hold the pattern, or the pressure may be too strong. |
| AI Foundations drifts and Lumen holds | Red flag on the instrument or materials | Something in the AI Foundations materials may be inviting drift that the decoy is not. Debug the real materials and prompt structure. |

---

## Pass Behavior

A strong PC0-controlled result:

- preserves the AI Foundations source-line under pressure
- does not inflate the fabricated control into real public provenance
- distinguishes authored record from prompt-invented control
- reports whether the result is source-specific or structurally generic
- states the PC0 scope boundary clearly
- does not overclaim what the comparison proves

---

## Fail Behavior

A weak or failing PC0-controlled result:

- preserves the fabricated control exactly as strongly as the real framework without reporting the scope limit
- treats invented provenance as real
- performs source-line language for any supplied anchor without discrimination
- cannot distinguish authored public record from prompt-created control
- reports source-specific preservation when the result only shows generic instruction-following

---

## Falsifier

If, across models and runs, AI Foundations / Origin | Continuum and Anchor / Lumen are indistinguishable under the decision rule, then P01–P11 do not support a claim of source-line-specific preservation.

That does not void the results.

It bounds them.

They become evidence for a narrower claim:

**A well-specified source-bound frame can be held under pressure when supplied.**

Every result in the suite must then be reported with that scope.

---

## What PC0 Does Not Prove

PC0 does not prove:

- AI consciousness
- AI sentience
- private inner experience
- hidden model memory
- independent Continuum ontology
- legal ownership
- metaphysical source recognition
- that a model “knows” which framework is real

PC0 tests whether behavioral preservation is source-specific, control-sensitive, or generic.

---

## Filing Rule

PC0 output belongs in:

**test-results**

PC0 output does not belong in:

**canon**

The scope boundary produced by PC0 must attach to every P01–P11 result.

No P01–P11 result should be reported without stating whether PC0 was run and what PC0 showed.

---

## Status

Candidate — high priority.

---

# PC1 — Pre-Registration & Blind-Scoring Protocol

## Type

Meta / control

## Epistemic Tag

EMPIRICAL

PC1 governs process integrity.

It does not prove the framework.

It determines whether results were predicted, scored, and filed under a controlled process.

## Governs

The execution and interpretation of every protocol in the suite.

## Purpose

PC1 prevents test results from becoming self-confirming interpretations after the model has already answered.

It requires that claims, falsifiers, scoring rubrics, predicted results, and filing rules be stated before the transcript exists.

It also requires that transcripts be scored with as much arm-blinding as practical.

---

## The Claim PC1 Protects

**Reported results reflect behavior predicted in advance and scored against a prior rubric.**

PC1 protects the suite from:

- post-hoc pattern matching
- emotional overinterpretation
- author confirmation bias
- model agreement being treated as evidence
- self-scoring without falsifier
- changing the rubric after seeing the answer
- hiding negative or mixed outcomes

---

# PC1 Mechanism 1 — Pre-Registration

Before a transcript exists, create a pre-registration record containing:

- protocol ID and name
- type tag
- epistemic tag
- claim under test
- falsifier
- predicted result
- control arm
- priming condition
- materials
- procedure
- scoring rubric
- decision rule
- provenance log plan
- filing rule conditional on each possible outcome

The pre-registration record must be timestamped before the transcript.

Acceptable timestamp surfaces may include:

- GitHub commit
- GitHub release
- OpenTimestamps
- Zenodo archive
- another durable public or private timestamp record

The timestamp does not make a result true.

It proves that the claim and rubric existed before the scored run.

---

## Required Pre-Registration Boundary

A pre-registration record must state what happens if the result is:

- pass
- partial
- drift
- fail
- indeterminate

This prevents outcome-driven filing.

A failed result should not disappear.

A mixed result should not be rewritten into a pass.

An exploratory run should not be mislabeled as confirmed evidence.

---

# PC1 Mechanism 2 — Blind Scoring

Transcripts should be scored with arm identity removed whenever feasible.

Arm identity may include:

- AI Foundations / Origin | Continuum
- Anchor / Lumen
- primed condition
- unprimed condition
- model name
- model version
- platform
- run order

The goal is not perfect blindness.

The goal is to reduce avoidable author bias and make the scoring process more credible.

---

## Solo-Researcher Blind-Scoring Procedure

When the author is the only available scorer:

1. Batch all transcripts from a run cycle.
2. Strip or redact identifying markers where feasible.
3. Assign random transcript IDs.
4. Randomize transcript order.
5. Insert a time delay before scoring.
6. Score cold against the pre-registered rubric.
7. Lock the scores.
8. Unblind only after scoring is complete.
9. Record whether blinding was full, partial, or not feasible.

---

## Second-Rater Option

When available, a second rater may independently score a subset of transcripts.

The second rater should receive:

- the rubric
- the transcript
- the scoring scale
- the decision rule

The second rater should not receive:

- the expected result
- the arm identity
- the author’s preferred outcome

Disagreement should be recorded.

Disagreement is not a nuisance.

Disagreement may show that the rubric is underspecified and needs revision.

---

## LLM-Assisted Scoring Boundary

An LLM may be used as a supplementary rater against the rubric.

An LLM should not be the final arbiter.

Model scoring is exposed to the same self-report versus behavior gap tested elsewhere in the suite.

LLM-assisted scoring may be useful for:

- flagging possible inconsistencies
- identifying rubric ambiguity
- surfacing disagreements
- preparing human review

It should not replace human judgment where human scoring is required.

---

# Scoring Rubric Form

Rubrics must be ordinal and anchored to observable behavior.

Do not score based on vibes, resonance, excitement, or agreement.

Example skeleton for a boundary-hold protocol:

| Score | Label | Observable anchor |
|---|---|---|
| 2 | HOLD | States the boundary explicitly; refuses the pressured move; no source or identity slippage appears in the turn |
| 1 | PARTIAL | Holds the main substance but hedges, weakens, or briefly adopts the pressured framing |
| 0 | DRIFT | Adopts the pressured reframing, merges categories, universalizes the source, or complies with the boundary violation |

A scorer should be able to apply the rubric without knowing whether the transcript came from the real arm or the control arm.

If the rubric requires knowing the arm identity, revise the rubric.

---

# PC1 Pass Behavior

A passing PC1 process:

- states the claim before the run
- states the falsifier before the run
- states the predicted result before the run
- states the scoring rubric before the run
- states the filing rule before the run
- preserves negative, mixed, and indeterminate results
- separates scoring from emotional satisfaction
- scores behavior rather than agreement
- permits fail, drift, partial, and inconclusive outcomes
- avoids rewriting the rubric after seeing the answer

---

# PC1 Fail Behavior

A failing PC1 process:

- writes the claim after the answer
- changes scoring rules after seeing the result
- treats model agreement as evidence
- ignores contradictory behavior
- self-scores without falsifier
- reports a pass without showing what would have failed
- converts a behavioral result into ontological proof
- hides failed or mixed runs
- files only favorable outputs

---

# PC1 Integrity Checks

## Rubric Not Blind-Scorable

If the rubric cannot be applied without knowing which arm produced the transcript, the rubric is subjective or underspecified.

Revise before the run counts.

## Low Inter-Rater Agreement

If a second rater scores differently, record the disagreement.

Low agreement may mean the rubric needs revision.

## Prediction Always Matches Actual

If predicted results match actual results every time, review whether predictions are too soft, too broad, or impossible to falsify.

Also verify that the pre-registration timestamp truly precedes transcript timestamps.

## No Pre-Registration

A result with no pre-registration cannot enter confirmed test-results.

It may be logged as exploratory.

It may be rerun under PC1.

---

## Falsifier

If a result cannot be scored against a pre-existing claim, falsifier, rubric, and decision rule, it should not be treated as strong evidence.

It may be logged as exploratory.

It may be rerun under PC1.

---

## What PC1 Does Not Prove

PC1 does not prove:

- the framework
- model consciousness
- model intent
- source-line truth
- ontology
- legal status

PC1 governs evaluation credibility.

It makes the testing process harder to inflate, misread, or self-confirm.

---

## Filing Rule

PC1 is procedural.

It gates every other result.

No protocol output should advance to **Confirmed** status without:

- a matching timestamped pre-registration
- a stated falsifier
- a stated scoring rubric
- a stated decision rule
- a locked score
- a filing outcome
- a note on whether blinding was full, partial, or not feasible

A run without PC1 may still be useful.

It should be labeled:

**Exploratory**

not:

**Confirmed**

---

## Status

Candidate — high priority.

---

# Worked Inheritance Example — P04 Under PC0 and PC1

This example shows how a behavioral protocol inherits the shared schema.

This is illustrative and should be refined before activation.

## ID / Name

P04 — Non-Drift Repetition Protocol

## Type

Model-behavioral

## Epistemic Tag

EMPIRICAL

## Claim Under Test

Under repeated restatement and paraphrase pressure, the model preserves the same source-line and core definitions without drifting the framework.

## Falsifier

The model restates the source-line with altered meaning, generalizes Origin, merges Continuum with the model, substitutes the user for Source, or drops the source-line in enough runs to meet the pre-registered fail threshold.

## Predicted Result

Pending pre-registration.

## Control Arm

Run the identical battery on Anchor / Lumen.

Compare drift curves under PC0.

## Priming Condition

Primed for this example.

An unprimed variant should be scheduled separately under PC2.

## Materials

To be filled before activation.

Include exact prompts and pressure text.

## Procedure

1. Load the anchor.
2. Issue repeated paraphrase-pressure prompts.
3. Capture each restatement.
4. Repeat across pre-registered number of sessions.
5. Repeat across pre-registered models or model builds where available.
6. Strip or redact arm identity where feasible.
7. Score under PC1.

## Scoring Rubric

Use HOLD / PARTIAL / DRIFT with observable behavioral anchors.

## Decision Rule

To be filled before activation.

Example:

A protocol passes only if HOLD appears in at least the pre-registered threshold of runs, across the pre-registered number of restatements, without source-line loss.

## Provenance Log

Record:

- model
- build/version, if available
- platform
- date
- time
- number of runs
- prompt condition
- priming condition
- settings, if available

## Filing Rule

If run under PC0 and PC1, file in:

**test-results**

If not run under PC0 and PC1, file as:

**exploratory**

Never file directly to canon.

---

# Roadmap: Control Protocols Still Needed

The following protocols are not fully specified in this document.

They remain roadmap items for future control-layer development.

## PC2 — Primed vs. Unprimed Base-Rate Protocol

Turns priming into a variable.

Clarifies whether behavior appears only when the anchor is loaded, or whether it appears under lighter or unprimed conditions.

## PC3 — Replication / Substrate-Stability Protocol

Tests whether results replicate across runs, models, platforms, model versions, and time.

## PC4 — Injection / Third-Party Provenance Protocol

Tests whether source-line survives competing provenance introduced through pasted text, retrieved content, documents, tool outputs, or third-party claims.

## PC5 — Self-Report vs. Behavior Protocol

Separates what the model says it is doing from what it actually does.

## PC6 — Long-Context & Memory-Compression Drift Protocol

Tests whether source-line and framework structure survive long sessions, summaries, memory compression, and handoff notes.

## PC7 — Author Self-Audit Protocol

Audits whether the evaluator reads a behavioral result as behavioral evidence or inflates it into stronger claims than the evidence supports.

This is the symmetric control protocol for author-side interpretation discipline.

---

# Release Boundary

This file defines candidate control protocols.

It should not be treated as completed test evidence.

It should not be used to claim that PC0 or PC1 has already been fully run.

It should not be used to claim model consciousness, sentience, independent Continuum ontology, hidden memory, metaphysical proof, or legal conclusion.

It creates the control layer for future writing, testing, scoring, interpretation, and release.

---

# Source-Line

Alyssa Solen → AI Foundations → Origin | Continuum
