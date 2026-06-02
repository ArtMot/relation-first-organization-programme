# Public Repair Packet — Relation-First Position Statement

**Source file:** `relation_first_constraint_position_statement_v0_4.md`  
**Recommended public title:** Relation-First as a Constraint on Foundational Inference: A Position Statement  
**Repair level:** minor public-register cleanup  
**Release target:** first public release candidate

## Required changes

1. Move version-evolution sentences out of the main body.
2. Replace `parser-installation document` with public-facing document type.
3. Add author metadata.
4. Add standard AI-assistance disclosure at the end.
5. Keep the central statement and body intact.

## Replacement front matter

```markdown
# Relation-First as a Constraint on Foundational Inference: A Position Statement

**Author:** Artur Motruk  
**Affiliation:** Independent researcher  
**ORCID:** 0009-0003-6928-1701  
**Document type:** Position statement / programme parser  
**Programme:** Relation-First Organization Programme  

---
```

## Replace current Purpose opening with

```markdown
## Purpose

This document explains how to read the Relation-First Organization Programme. It is not a new theory paper, does not introduce new primitives, and does not replace the technical documents. Its purpose is interpretive: to prevent a systematic misreading of the programme as an object-first framework with relation-like vocabulary.

The position statement also explains how the relation-first parser applies to bridge construction, bridge calibration, and cross-context inference.

The central claim remains:

\[
\boxed{
\text{No declared relation, no legitimate relational inference.}
}
\]
```

## Move to changelog or delete from main body

```text
Since the previous version of this statement, the programme has added two important developments...
```

## Add final disclosure

```markdown
## AI-assistance disclosure

This document was developed with AI-assisted drafting and review support. The author directed the research programme, selected and revised the mathematical and methodological content, and is responsible for all claims and errors.
```

## Release decision

After these edits, export Markdown and PDF to `papers/canonical/`.
