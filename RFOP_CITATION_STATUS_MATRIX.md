# RFOP Citation Status Matrix

This matrix tracks the public citation status of RFOP manuscripts for staged release and later arXiv/journal submission.

See also:

```text
PUBLIC_MANUSCRIPT_INDEX.md
```

## Citation status legend

| Status | Meaning |
|---|---|
| `repository manuscript` | Public manuscript with stable path in `papers/canonical/` |
| `public canonical working manuscript` | Public canonical manuscript with stable path in `papers/canonical_working/`, but not yet final article-ready |
| `carry-forward audit` | Must be compared against a later paper before release/supersession decision |
| `application candidate` | Not a foundation driver; may be released/submitted as application/exemplar |
| `case study` | Public as case study after scope cleanup |
| `frontier branch` | Branch-specific paper; do not mix into core foundation release without branch map |
| `internal/provenance` | Not public proof source |

## Foundation and methodology papers

| Paper / family | Current public status | Can be cited as public now? | Stable path / notes |
|---|---|---:|---|
| Relation-First Position Statement | repository manuscript | yes | `papers/canonical/relation_first_constraint_position_statement_v0_4_public.*` |
| Programme Guide / Reader Map | repository manuscript | yes | `papers/canonical/relation_first_organization_programme_guide_v0_6_public.*` |
| Theory of Organization | repository manuscript | yes | `papers/canonical/relation_first_organization_theory_v0_5_1_public.*` |
| Charted Organization Theory | repository manuscript | yes | `papers/canonical/charted_organization_theory_v0_5_public.*` |
| Recursive Chart Learning Theory | repository manuscript | yes | `papers/canonical/recursive_chart_learning_v0_5_public.*` |
| Triadic Closure / Recursive Residual Theory | repository manuscript | yes | `papers/canonical/triadic_closure_recursive_residuals_v0_7_public.*` |
| Cross-Closure Instantiation Theorems | repository manuscript | yes | `papers/canonical/cross_closure_instantiation_theorems_v0_7_public.*` |
| Charted Objecthood and Contextual Gluing | repository manuscript | yes | `papers/canonical/charted_objecthood_contextual_gluing_v0_5_public.*` |
| Triadic Substitution / Coupling / Closure Atlases | repository manuscript | yes | `papers/canonical/triadic_closure_atlases_v0_9_public.*` |
| No-Free-Transfer and Bridge Completion | carry-forward audit | not yet | Verify carry-forward into NUR before standalone release/supersession |
| No Undeclared Relation | repository manuscript | yes | `papers/canonical/no_undeclared_relation_bridge_completion_v1_1_public.*` |
| No Undeclared Boundary | repository manuscript | yes | `papers/canonical/no_undeclared_boundary_v0_5_public.*` |
| No Undeclared Observer | repository manuscript | yes | `papers/canonical/no_undeclared_observer_v0_5_public.*` |
| Recursive Bridge Calibration | repository manuscript | yes | `papers/canonical/recursive_bridge_calibration_v1_7_public.*` |
| Bridge-Valence Diagnostics | public canonical working manuscript | yes, as working manuscript | `papers/canonical_working/bridge_valence_diagnostics_v1_12_working.*` |
| Generative Bridge Search | public canonical working manuscript | yes, as working manuscript | `papers/canonical_working/generative_bridge_search_v0_16_working.*` |
| Face Requirement Kernels | repository manuscript | yes | `papers/canonical/face_requirement_kernels_v0_6_public.*` |
| Declared Witness Assembly | public canonical working manuscript | yes, as working manuscript | `papers/canonical_working/declared_witness_assembly_v0_4_working.*` |

## External exemplars, applications, and case studies

| Paper / family | Current public status | Can be cited as public now? | Notes |
|---|---|---:|---|
| Paper A | application candidate | not yet | Strong publishable foundations-of-physics exemplar |
| Paper B | application candidate | not yet | Strong quotient/minimality exemplar |
| No Undeclared Photon | case study / public-repair needed | not yet | NUR/NUB/NUO photon relation-packet case |
| Persistence Margins | application candidate / release-ready | not yet | TDA-adjacent theorem note; pending application batch |
| Moving Supports | application candidate / minor repair | not yet | TDA-adjacent theorem extension; notation check needed |

## First release public manuscript corpus

The current public corpus has stable paths for fourteen canonical repository manuscripts and three canonical working manuscripts. It is now suitable to support a first programme-footprint release once the root README, CITATION metadata, manifest, non-claims, and Zenodo metadata are aligned.

## Rule

A paper may cite an RFOP paper as public only when that paper is included in the same release, has its own public preprint/DOI, or has a stable public repository manuscript path listed in `PUBLIC_MANUSCRIPT_INDEX.md`. Otherwise the dependency must be summarized locally or marked as forthcoming without bearing proof weight.
