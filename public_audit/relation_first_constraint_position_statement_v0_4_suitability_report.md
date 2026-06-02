# Public Suitability Report — relation_first_constraint_position_statement_v0_4

**File audited:** `relation_first_constraint_position_statement_v0_4.md`  
**Current title:** Relation-First as a Constraint on Foundational Inference  
**Recommended public title:** Relation-First as a Constraint on Foundational Inference: A Position Statement  
**Status:** `release-ready-with-minor-edits`  

## Summary judgment

This is one of the strongest public-facing entry documents. It is already written mostly in stable public register and does not read like an internal chat transcript. It can serve as the parser/position statement once minor evolution-based language is removed.

## Strengths

- Clear central thesis: no declared relation, no legitimate relational inference.
- Good public function: explains how to read the programme without pretending to be a theorem paper.
- The tone is mostly sober and explanatory.
- Strong non-overclaim posture: it explicitly says it is not a new theory paper and does not replace technical documents.
- Current title is acceptable; it is technical but not opaque.

## Required minor edits before PDF/public release

### 1. Remove version-evolution narration from the introduction

Current issue: early text says that since the previous version the programme added developments, then says this position statement now includes those lessons.

Public-paper repair:

- Move version history to a changelog or appendix, or delete it from the main body.
- Replace with a stable sentence such as:

```text
This position statement also explains how the relation-first parser applies to bridge construction and bridge calibration.
```

### 2. Clarify document type in metadata

Current metadata says `parser-installation document`. This is internally meaningful but unusual externally.

Suggested public form:

```text
Position Statement / Programme Parser
```

### 3. Add author metadata before export

Add:

```text
Artur Motruk
Independent researcher
ORCID: 0009-0003-6928-1701
```

### 4. Add AI assistance disclosure only at the end

Do not mention AI in the body. Add a brief final disclosure if this file is included in a public release.

## Title audit

The title is usable. It has a real public-facing claim and does not sound like a private code name.

Possible variants:

1. **Relation-First as a Constraint on Foundational Inference: A Position Statement**
2. **No Undeclared Relation: A Position Statement on Foundational Inference**
3. **Relation-First Inference: Why Foundational Transfers Require Declared Relations**

Recommendation: use option 1 for public release. Option 2 overlaps with the separate No Undeclared Relation paper.

## Release decision

Do not rewrite substantially. Perform minor public-register cleanup, add metadata, then export Markdown/PDF.

**Decision:** suitable for first public release after minor edits.
