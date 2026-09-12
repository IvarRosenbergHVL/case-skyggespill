# Document design rules

These rules are mandatory for all player-facing finished PDF documents in **Skyggespill**.

## Visual differentiation is a hard requirement

Every finished PDF must have a **substantially distinct visual identity and design** appropriate to its in-world source, document type, author, institution, time, and purpose.

Documents must not look as if they were generated from the same template, and players must not reasonably be able to mistake two unrelated documents for versions of the same document merely because of repeated layout, typography, header structure, spacing, iconography, color treatment, tables, margins, or visual hierarchy.

This applies across the entire case package, including police material, newspaper clippings, political material, emails, letters, invoices, notes, photographs, reports, screenshots, internal party documents, business records, and other artifact types.

### Required design variation

Where appropriate, documents should vary materially in several of the following dimensions:

- page composition and information density
- typography and typographic hierarchy
- margins, column structure and alignment
- mastheads, logos, letterheads and institutional identity
- table and form design
- use of photographs, captions and image crops
- paper/background treatment where relevant
- signatures, handwriting, stamps, annotations and markings
- date/address/reference placement
- color treatment and print characteristics
- pagination and footer/header conventions
- document age, wear, scanning, copying or screenshot characteristics when justified in-world

Variation must be **source-driven and realistic**, not decorative randomness.

## Same-document and version exception

Visual similarity is permitted only when the case intentionally represents:

- multiple pages of the same logical document;
- authentic copies of the same artifact;
- versions of the same document;
- documents from the same real in-world template or issuing system.

When similarity is intentional, CER v2 provenance/version relationships must explicitly model it. If differences between versions are clue-bearing, those differences must be deliberate, observable, and protected through rendering.

## Forensic safety

Unintentional template reuse must never create a false inference that two documents share an author, institution, system, provenance, or relationship.

Likewise, accidental visual differences between documents that are supposed to be versions of the same source must not create false clues.

## Production gate

No player-facing PDF is considered production-ready until a visual differentiation review confirms that:

1. unrelated artifacts are clearly distinguishable at a glance;
2. each document's design plausibly matches its in-world provenance;
3. repeated layout conventions are justified by a shared source or system;
4. no accidental design similarity creates a false relationship;
5. no accidental design difference creates a false forensic clue.

This rule is a case-level production constraint and must be considered during document specification, generation, rendering, QA, and final package review.