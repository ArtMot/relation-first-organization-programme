# Public Repair Packet — No Undeclared Boundary

**Source file:** `no_undeclared_boundary_v0_5.md`  
**Recommended public title:** No Undeclared Boundary: Scope, Approximation, and Admissibility in Relation-First Inference  
**Repair level:** minor public-register cleanup  
**Release target:** first public release candidate

## Required changes

1. Replace title with public title.
2. Move draft subtitle to changelog/provenance.
3. Add author metadata.
4. Keep hierarchy with No Undeclared Relation near the front.
5. Keep non-claims visible.
6. Add standard AI-assistance disclosure at the end.

## Replacement front matter

```markdown
# No Undeclared Boundary: Scope, Approximation, and Admissibility in Relation-First Inference

**Author:** Artur Motruk  
**Affiliation:** Independent researcher  
**ORCID:** 0009-0003-6928-1701  
**Programme:** Relation-First Organization Programme  
**Document role:** Boundary-face corollary of No Undeclared Relation  

---
```

## Move to changelog/provenance

```text
Draft v0.5 — global-boundary clarification, physics examples, and no-go table cleanup
```

## Keep this hierarchy visible

```markdown
The hierarchy is:

\[
\boxed{
\text{relation-first primitive}
\Rightarrow
\text{No Undeclared Relation}
\Rightarrow
\text{No Undeclared Boundary}.
}
\]
```

## Add final disclosure

```markdown
## AI-assistance disclosure

This document was developed with AI-assisted drafting and review support. The author directed the research programme, selected and revised the mathematical and methodological content, and is responsible for all claims and errors.
```

## Release decision

After these edits, export Markdown and PDF to `papers/canonical/`.
