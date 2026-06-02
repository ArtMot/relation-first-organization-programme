# Public Repair Packet — No Undeclared Observer

**Source file:** `no_undeclared_observer_v0_5.md`  
**Recommended public title:** No Undeclared Observer: Readout, Evaluation, and Visibility in Relation-First Inference  
**Repair level:** minor public-register cleanup plus cross-reference check  
**Release target:** first public release candidate

## Required changes

1. Replace title with public title.
2. Move draft subtitle to changelog/provenance.
3. Add author metadata.
4. Keep the observer-not-mind warning near the front.
5. Keep co-required faces section near the front.
6. Add standard AI-assistance disclosure at the end.
7. Complete internal-reference status check before PDF export.

## Replacement front matter

```markdown
# No Undeclared Observer: Readout, Evaluation, and Visibility in Relation-First Inference

**Author:** Artur Motruk  
**Affiliation:** Independent researcher  
**ORCID:** 0009-0003-6928-1701  
**Programme:** Relation-First Organization Programme  
**Document role:** Observer/readout-face corollary of No Undeclared Relation  

---
```

## Move to changelog/provenance

```text
Draft v0.5 — observer positioning, co-required faces, and no-go table cleanup
```

## Keep this warning visible

```markdown
This paper does not claim that observer is an external mind, a primitive object, human perception, or physical measurement. Observer/readout means a declared visibility, readout, chart, evaluator, or admission role internal to the relation context.
```

## Cross-reference checks

Before export, check references to:

- No Undeclared Relation;
- No Undeclared Boundary;
- Charted Organization Theory;
- Recursive Chart Learning Theory;
- Recursive Bridge Calibration;
- Triadic Closure.

Each should either be included in the same programme release or locally summarized if not yet public.

## Add final disclosure

```markdown
## AI-assistance disclosure

This document was developed with AI-assisted drafting and review support. The author directed the research programme, selected and revised the mathematical and methodological content, and is responsible for all claims and errors.
```

## Release decision

After these edits and reference checks, export Markdown and PDF to `papers/canonical/`.
