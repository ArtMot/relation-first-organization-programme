# Full Manuscript Export Queue

This repository is currently a public programme-footprint shell. Several root-level manuscript-looking files from the first upload were source-pointer placeholders rather than full manuscripts, and some of those pointers were mismatched.

The next step is **not** simply exporting PDFs. The next step is a public-suitability pass, followed by controlled Markdown/PDF export.

See:

```text
PUBLIC_SUITABILITY_AUDIT_PROTOCOL.md
```

## Gate order

For every manuscript:

```text
Drive source
-> public-suitability audit
-> content-preserving register cleanup if needed
-> Markdown export
-> PDF export
-> placement into papers/<tier>/
-> release checklist
-> GitHub release
-> Zenodo DOI
```

Do not place a manuscript into a public release merely because a PDF exists.

## Required export formats after suitability pass

For each canonical paper that passes the suitability audit, export at least:

- Markdown (`.md`)
- PDF (`.pdf`)

Optional later:

- DOCX (`.docx`)
- LaTeX source (`.tex`) where needed for arXiv/journal submission

## Canonical spine audit/export targets

Place audited full manuscripts under:

```text
papers/canonical/
```

Audit these first:

1. `relation_first_constraint_position_statement_v0_4.md`
2. `relation_first_organization_programme_guide_v0_5.md`
3. `RFOP_Public_Bibliography_Reader_Map_v2_0.md` or current reader map
4. `theory_of_organization_foundation_v0_5_1_final_clean.md`
5. `charted_organization_theory_v0_5.md`
6. `recursive_chart_learning_theory_v0_5.md`
7. `triadic_closure_recursive_residual_theory_v0_7.md`
8. `cross_closure_instantiation_theorems_v0_7.md`
9. `triadic_substitution_coupling_closure_atlases_v0_9.md`
10. `Paper A Draft 1.0 - Recoverable Dependence Is Not Causal Precedence`
11. `Paper B Draft 1.2 - Task-Visible Quotients and Minimal Sufficient Recoverability`
12. `no_undeclared_relation_bridge_completion_v1_1.md`
13. `no_undeclared_boundary_v0_5.md`
14. `no_undeclared_observer_v0_5.md`
15. `recursive_bridge_calibration_v1_7.md`
16. `bridge_valence_diagnostics_predictive_criticality_v1_12.md`
17. `generative_bridge_search_structural_unblocker_transfer_v0_16.md`

## First suitability pass priority

Start with three representative difficulty levels:

1. `relation_first_constraint_position_statement_v0_4.md` — likely low-risk register cleanup.
2. `theory_of_organization_foundation_v0_5_1_final_clean.md` — core foundation suitability check.
3. `bridge_valence_diagnostics_predictive_criticality_v1_12.md` — high-density methodology paper requiring content-preserving public-register repair.

Do **not** start with all 17 at once.

## Support/article audit/export targets

Place audited full manuscripts under:

```text
papers/support/
papers/article_candidates/
```

Priority support/article candidates:

- `charted_objecthood_contextual_gluing_v0_5.md`
- `persistence_margins_dynamic_trace_stability_v0_4.md`
- `moving_supports_trace_stability_v0_3.md`
- `rfop_bridge_valence_self_audit_v0_6_reproducibility.md`
- `bridge_valence_diagnostic_atlas_causal_set_theory_v0_8_reproducibility.md`
- `target_presentation_calibration_atlas_M0_M16_audited_synthesis_v0_2.md`
- `bridge_accessibility_target_relative_inaccessibility_v0_5_reader_facing.md`
- `no_undeclared_photon_relation_packet_v0_8.md`

## Frontier branch exports

Place under:

```text
papers/frontier/
```

Export frontier branches only after the root public footprint is stable and non-claims remain clear.

## AS / critical-rank branch

AS / critical-rank files require a separate branch reader map and provenance audit before promotion. They should not be placed into the main public reader path yet.

## Rule

Do not create a GitHub release or Zenodo DOI until the manuscripts intended for the first public release have passed the public-suitability audit and full manuscript exports have replaced the placeholder state.
