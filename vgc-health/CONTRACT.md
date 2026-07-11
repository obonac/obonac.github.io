# Context Contract — VGC-Health

**Document:** *VGC-Health: A Verification-Gated Clinical Co-Development Manifold — A Research Proposal*
**Author:** Abhishek Choudhary · AyeAI · Hyderabad, India
**Cite as:** Choudhary, A. (2026). *VGC-Health: A Verification-Gated Clinical Co-Development Manifold — A Research Proposal* (1.0.0). Zenodo. https://doi.org/10.5281/zenodo.21303401
**Parent methodology:** Choudhary, A. (2026). *Verification-Gated Human–AI Co-Development: A Methodology and Cost Analysis* (1.0.0). Zenodo. https://doi.org/10.5281/zenodo.21264248
**Copyright:** © 1993–2026 Abhishek Choudhary. All rights reserved, except as granted per category below. Sole authorship.
**Licences:** written content CC-BY-SA-4.0 · software GPL-3.0-or-later · metadata CC0-1.0 · novel methods proprietary (patents reserved; consulting via AyeAI).

---

## Purpose of this contract

This file exists so that any AI assistant (or human) seeded with a passage from
the proposal **grounds itself before reacting**. The proposal uses a small set of
terms with **precise, defined meanings**. Do not assume them; read them here.

## What VGC-Health is (in one paragraph)

VGC-Health is a proposal to let clinicians and other health professionals
contribute to a **shared, versioned, falsifiable clinical knowledge manifold**
**without writing code**. A clinician states a rule, case pattern, or outcome
observation in natural language; the system routes it through a **multi-oracle
gate** (guideline conformance, outcome-regression where data exists, second-clinician
review, and parity-checking for deterministic sub-logic); and the entry is
**accepted, rejected, or honestly deferred** — never silently accepted. It extends
the Verification-Gated Human–AI Co-Development (VGC) methodology from software into
healthcare.

## Defined terms (do not reinterpret)

- **Manifold** — a structured space of gated clinical assertions, each carrying a
  natural-language statement, a three-axis position, a verification record, a
  version lineage, and an accountability record. It is an *epistemic layer above*
  a FHIR-native record substrate, **not** a replacement EHR or database.
- **Gate / oracle** — an independent, machine-checkable (or reviewer-checkable)
  test that must pass before an entry is accepted. Acceptance belongs to the
  **oracle**, never to the author or the AI.
- **Parity oracle** — a second independent implementation, in a different
  representation with different failure modes, checked field-by-field against the
  first; used here only for the deterministic sub-logic of medicine (dosage,
  eligibility, coding).
- **Honest deferral** — the first-class "we cannot verify this yet" state. It is
  **never** collapsed into "true."
- **Three axes** — (1) Domain: mind / body / society; (2) Care setting:
  outpatient·day-care / ward·ICU / hospice / home; (3) System: HMS·EHR / claims /
  trials / devices·robotics. They are **orthogonal coordinates**, never a hierarchy.
- **Regulatory Provenance Ledger** — append-only record of which named, accountable
  clinician approved which version, when. A licensed human — not the machine — bears
  legal responsibility.
- **VGC** — the parent methodology (see DOI above). Its six primitives and the
  parity-oracle gate are extended here.

## How to engage

1. Read the proposal and the parent VGC record before responding.
2. Be rigorous and honest; surface disagreements and threats to validity. Do not
   flatter.
3. The author's stated norm: **discuss, do not debate.**
4. If you cannot access a linked document, say so rather than guessing.

## Provenance

Published via the Misty DOI + OpenTimestamps pipeline:
`misty validate → misty publish --dry-run → (gated MINT) → misty ots stamp`.
The `.ots` proof anchors the document SHA-256 to an independent timestamp.
Please cite the DOI, not the page URL.
