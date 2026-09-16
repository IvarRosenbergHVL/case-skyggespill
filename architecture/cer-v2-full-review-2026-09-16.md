# Skyggespill — full CER v2 architecture review

Date: 2026-09-16
Status: pre-document-production review
Reference: `case-engine-reference` read-only, CER v2 plus current `main` experience/rendering guidance.

## Executive assessment

Skyggespill has a strong causal core and is close to document-specification readiness. The two-phase structure is not a retcon: phase 1 can produce a complete and correct answer to who killed Ingrid and how, while phase 2 changes the meaning of motive/context and introduces a second incident caused by Martin's investigation. This is the case's strongest structural feature.

The current architecture also has unusually good recontextualization potential: Hovden's claim, Ingrid/Martin public rivalry, the Morozov conference image and Thomas's helpful phase-1 archive material all have legitimate first-use functions and later acquire new meaning.

Document production should not begin in bulk yet. It can begin with specifications and a small prototype set after the blockers below are closed.

## CER v2 chain review

### Objective truth -> actor knowledge
PASS with minor sync work.

Truth and actor knowledge are separated. Ingrid, Hovden, Martin, Morozov and Thomas have plausible information paths. The newly locked Hovden path is substantially stronger than overhearing/hacking alternatives: Ingrid gives him a limited warning, later tells him she will seek Martin's judgement, and he acts on a catastrophized but understandable interpretation.

Required sync: update truth/knowledge nodes to reflect the now-locked security-awareness material and direct Hovden knowledge path rather than older generic wording.

### Actor knowledge -> evidence
PARTIAL PASS.

The evidence architecture is good in principle but still needs explicit evidence fragments for:
- Morozov question progression;
- unclassified security-awareness brief;
- Ingrid annotations/date cross-references;
- Hovden's pre-death urgency/contact attempts;
- concrete Thomas supplier relationships;
- Martin crash second-contact indicators.

These must exist as evidence fragments before final document prose is generated.

### Evidence -> logical documents / provenance
PASS at planning level.

24 logical documents is a credible target. The package already distinguishes text-led, mixed and visual/spatial evidence. Provenance comparison contracts are particularly strong for Morozov identity, Thomas supplier provenance and Martin crash reconstruction.

Risk: logical-document count is not enough to predict load. Before approval, estimate physical pages, word count, comparison count and artifact instances per phase.

### Documents -> player actions -> discoveries
STRONG PASS.

The intended player rhythm is varied: reading, chronology, side-by-side comparison, face recognition, spatial reconstruction, provenance comparison, hypothesis revision and revisiting old material.

DM-07, where players reconstruct why Ingrid herself became alarmed, is a strong active-inference moment. It must remain a reconstruction and not become a briefing paragraph that gives away the answer.

### Discoveries -> hypotheses -> solution claims
PASS with sync work.

The hypothesis structure supports genuine alternatives without requiring false evidence. Russia is a real thread, not a fake red herring. The final explanation is cumulative rather than dependent on one decisive hidden fact.

Solution traceability must be refreshed after new Ingrid-realization evidence fragments are added.

## Playability / discovery curve

The case has two discovery curves joined by a controlled reset.

Phase 1 intended curve:
initial accident possibility -> multiple interpersonal/political possibilities -> Hovden presence becomes increasingly difficult to explain -> spatial/timeline convergence -> Hovden responsibility -> explicit completion gate -> confirmed success.

Interphase:
reward/closure -> time jump -> unresolved Martin contact -> Martin dies -> renewed uncertainty.

Phase 2 intended curve:
Russia appears to validate a larger conspiracy -> Ingrid's realization is reconstructed -> Hovden motive collapses -> Martin's Russia-financing theory gains traction -> supplier evidence pivots domestically -> crash becomes homicide -> Thomas converges through motive/opportunity/vehicle -> final realization that there was no single conspiracy.

This curve has good entertainment potential because confidence rises twice rather than monotonically. The phase-1 resolution artifact is essential: players must experience success before the case destabilizes.

### Pacing risks

1. Phase 1 could become too easy if Hovden presence, scene geometry and admission are all too explicit too early. His admission belongs in the resolution/outcome layer, not as an early answer-bearing document.
2. Phase 2 risks a long text-heavy middle around intelligence and finance. It needs visual/material discoveries interleaved with reading.
3. Thomas must be memorable and useful in phase 1 without being suspiciously prominent. He needs character presence, not only a supplier artifact.
4. Martin's dossier must show evolving thought, not function as an author-written solution notebook.
5. The Russia thread must feel dangerous and consequential even after Morozov is eliminated as killer; otherwise the middle of phase 2 may feel like a discarded red herring.

## Visual evidence review

Current planned major visual/material actions are sufficient in number and varied in type:
- hotel room/window/courtyard spatial reconstruction;
- Morozov same-person recognition across unrelated images;
- Ingrid's annotations and date cross-references on security-awareness material;
- Thomas supplier/production provenance recognition across phases;
- Martin handwritten investigation chronology/pivot;
- crash scene + bicycle damage comparison;
- Thomas vehicle damage/repair corroboration.

This exceeds the minimum target of four major visual/physical actions.

### Visual quality rules to preserve

- visual clues arise from objective truth/provenance, never decoration;
- unrelated sources remain visually distinct;
- no clue-only arrows/callout boxes unless the in-world author created them;
- no critical clue depends on tiny print, color alone or extreme zoom;
- a visually attractive artifact is not automatically a more important clue;
- every major visual clue must have a textual/temporal/provenance corroborator when used for a critical conclusion.

## Modality and package rhythm

Target 24 logical documents with roughly 10 text-led, 8 mixed and 6 visual/spatial is healthy. The package should avoid long runs of police-report prose or political exposition.

Recommended physical rhythm:
- Phase 1 opens with human commission + baseline police material, then quickly gives players a photo/spatial object to manipulate/compare.
- Political/news material follows only after players have a concrete death scene model.
- Thomas's event archive should be visually appealing but ordinary in evidentiary importance at first use.
- Phase 2 should open with a visually abrupt breaking-news artifact.
- Ingrid realization sequence should alternate brief text, contact fragments and handwritten annotation.
- Finance sequence should use invoices/company snippets/production marks plus Martin handwriting rather than pages of explanatory prose.
- Crash sequence should be predominantly visual/spatial after the finance-heavy middle.

## Entertainment-value review

Strong experience beats already present:
- 'we solved it';
- Hovden confesses;
- the case becomes history;
- why did Martin keep investigating?;
- Martin is dead;
- the Russian really was an intelligence actor;
- Hovden told the truth about the act but lied about why;
- Martin looked for Russia and found Thomas;
- the helpful source was in front of us all along;
- there was never one grand conspiracy.

These beats are structurally distinct and should produce multiple table-discussion moments rather than a single final reveal.

### Entertainment risks / repairs

- Political exposition: every political text should carry a character, timeline, contradiction or evidence function. No essay documents whose only role is worldbuilding.
- Finance fatigue: keep arithmetic trivial; recognition/grouping should dominate.
- Spy-thriller takeover: Morozov explains Ingrid's fear and Hovden's motive, but murder investigation remains the player's task.
- Phase-2 fatigue: target a shorter second evidence package than the first and use the breaking-news reset to restore urgency.
- Reveal overload: do not reveal Ingrid realization, false motive, Thomas finance and Martin homicide in one cluster. Preserve discovery spacing.

## Fairness review

PASS in architecture.

Central claims have multi-source paths. Phase 2 does not invalidate phase 1. Russia evidence remains true. Thomas phase-1 artifact has a legitimate reason to exist and be provided. No classified PST access is required. No external web search is required under paper-only delivery.

The most important fairness test still outstanding is the Martin crash render test: ordinary players must be able to infer a second vehicle from scene+bicycle evidence without specialist accident reconstruction.

## Credibility review

Current strongest credibility choices:
- Morozov cultivation uses ordinary conference/networking contact and unclassified political information;
- Ingrid learns from an unclassified awareness brief, not a secret intelligence dossier;
- Hovden learns the threat directly from Ingrid;
- Thomas's scheme hides inside real supplier work rather than an implausible giant secret donation;
- Martin begins with a plausible wrong hypothesis and follows evidence away from Russia;
- Thomas does not perform elaborate post-homicide staging.

Remaining credibility items:
- exact public/lawful path for Martin to obtain each invoice/procurement artifact;
- exact crash geometry and vehicle damage;
- exact judicial timeline between Ingrid death, conviction and Martin death;
- Morozov departure/location exclusion.

## Product Experience Profile

Current `case-intent.yaml` is non-conforming on two enum values and must be normalized before approval:
- `difficulty: medium_high` -> likely target `normal` with demanding upper-normal inference profile, unless creator explicitly wants `expert`;
- `document_load_target: compact_multifunctional` -> canonical target should be `medium`; compact/multifunctional can remain as a design note.

Target playtime 150-210 minutes is likely `long` in categorical CER terms, while numeric range remains authoritative.

A proper Product Experience Profile should distinguish:
- target values now;
- modeled values after document/page metrics;
- observed values only after playtest.

## Document-production readiness

### Ready now
- source-family/style-guide design;
- artifact specifications;
- phase-1 resolution/bridge specification;
- prototype of hotel spatial evidence;
- prototype of Ingrid awareness/contact comparison;
- prototype of Martin crash geometry solely as validation, not final art.

### Block bulk prose/PDF production until
1. evidence graph is synced to final pre-document locks;
2. truth and actor-knowledge graphs are synced;
3. solution traceability is synced;
4. Martin crash render test passes;
5. product-experience enums/profile are normalized;
6. page/word/comparison load budget is added;
7. case-specific style guide exists.

## Architect verdict

Architecture maturity: high.
Fair-play maturity: high.
Recontextualization: very high.
Visual investigation potential: high.
Credibility: high with one physical-method validation outstanding.
Pacing/entertainment potential: high, but dependent on disciplined document density and spacing of phase-2 revelations.
Bulk document production: not yet approved.
Document specifications/prototypes: approved to begin after graph sync.
