# Public Suitability Audit Protocol

This repository must not treat a file as public-release-ready merely because it has been exported as Markdown or PDF.

Every manuscript must pass a public-suitability audit before it is added to a GitHub release, Zenodo archive, arXiv submission, or journal submission packet.

## 1. Purpose

The purpose of this audit is to convert internally developed manuscripts into public research artifacts without losing mathematical or methodological content.

The audit is especially important for dense methodology papers such as:

- `bridge_valence_diagnostics_predictive_criticality_v1_12.md`
- `generative_bridge_search_structural_unblocker_transfer_v0_16.md`

These papers contain critical machinery and must not be compressed casually. They need register repair, not conceptual simplification.

## 2. Public suitability statuses

Each manuscript receives one status:

| Status | Meaning |
|---|---|
| `release-ready` | Suitable for public PDF/Markdown release after final metadata check. |
| `release-ready-with-minor-edits` | Only small title/metadata/register edits remain. |
| `content-preserving-public-revision-needed` | Core content is strong but internal/evolutionary/process language must be revised. |
| `hold-for-carry-forward-audit` | Risk of lost inter-version content or unresolved version provenance. |
| `internal-only-for-now` | Useful internally but not suitable for public reader path. |

## 3. Audit checklist

Before public export, check:

### 3.1 Metadata and title page

- Author line is present and correct: Artur Motruk, Independent researcher.
- ORCID is present: `0009-0003-6928-1701`.
- Version number is clear.
- Date/status are clear.
- The file does not claim to be final if it is a preprint or programme release.

### 3.2 Register and tone

Remove or rewrite internal process narration such as:

- `v0.4 adds...`
- `we now repair...`
- `the previous pass...`
- `this patch fixes...`
- `the assistant noticed...`
- `the user asked...`
- `after internal review...`
- `workflow note...`

Replace with paper-style language:

- `This paper introduces...`
- `The diagnostic consists of...`
- `The method requires...`
- `The construction proceeds by...`
- `The result is...`

### 3.3 AI/process leakage

The manuscript should not contain live-chat artifacts, assistant/user references, or process commentary in the main body.

AI assistance belongs only in a disclosure section, for example:

> This manuscript/programme was developed with AI-assisted drafting and review support. The author directed the research programme, selected and revised the mathematical content, and is responsible for all claims and errors.

### 3.4 Evolutionary writing

Internal development history should not dominate the abstract or introduction.

Bad public form:

> v0.3 added the missing bridge, v0.4 strengthened examples, and v0.5 repaired reproducibility.

Better public form:

> The paper develops a reproducible diagnostic in three layers: a pre-solution target-demand diagnostic, a post-diagnostic residual-persistence check, and an error-bounded admission status.

Version history may be moved to an appendix or changelog only if it is genuinely useful.

### 3.5 Claims and non-claims

Every manuscript must include claims and non-claims appropriate to its target.

Especially block:

- no GR derivation unless actually proved;
- no Standard Model derivation;
- no QED derivation;
- no `candidate = solution` claim;
- no `formal skeleton = physical spacetime` claim;
- no `diagnostic = proof of external domain` claim;
- no `GBS = automatic solver` claim.

### 3.6 Definitions and theorem status

- Definitions must be stable and not introduced as temporary chat artifacts.
- Theorems/propositions must have proof status.
- Imported external results must be distinguished from programme-derived results.
- Candidate results must be labelled as candidate, conditional, admitted, blocked, or residualized.

### 3.7 BVD / GBS special standard

For Bridge-Valence Diagnostics and Generative Bridge Search:

- Do not compress away tables, coordinates, calibrators, guardrails, or reconstruction cards.
- Preserve the derived/imported ledgers.
- Preserve the status/error-bounded classification machinery.
- Convert version-evolution paragraphs into stable paper sections.
- Move detailed version patch notes to an appendix if needed.
- Keep the distinction between diagnostic classification, candidate generation, and verification/admission absolutely explicit.

## 4. Output artifacts after audit

For each audited manuscript, produce:

```text
public_audit/<paper_slug>_suitability_report.md
papers/<tier>/<paper_slug>.md
papers/<tier>/<paper_slug>.pdf
```

The suitability report should include:

- status;
- edits required;
- high-risk phrases found;
- claim/non-claim check;
- AI/process leakage check;
- decision: release now / revise / hold.

## 5. Release rule

No manuscript enters a GitHub release, Zenodo archive, arXiv packet, or journal packet until it has passed this suitability audit.
