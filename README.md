# Relation-First Organization Programme

**Author:** Artur Motruk  
**Affiliation:** Independent researcher  
**ORCID:** 0009-0003-6928-1701  
**Repository status:** public programme-footprint shell, not yet an archival DOI release  

This repository is the public programme-footprint repository for the **Relation-First Organization Programme**. It establishes the programme architecture, reader path, public corpus list, non-claims, AI-assistance disclosure, version-lineage policy, and current export queue before individual papers are submitted as preprints or journal articles.

## What this repository currently is

This repository is currently a **release shell / public footprint**. It is intended to show the programme structure and canonical manuscript families while the full manuscript exports are being prepared.

The full paper manuscripts should be exported from the Google Drive source folder and placed into the appropriate `papers/` folders before a GitHub release or Zenodo DOI is created.

## Core programme spine

The current public spine is:

```text
Relation-first constraint
-> Theory of Organization
-> Charted Organization Theory
-> Recursive Chart Learning Theory
-> Triadic Closure / Cross-Closure / Closure Atlases
-> No Undeclared Relation / Boundary / Observer
-> Recursive Bridge Calibration
-> Bridge-Valence Diagnostics
-> Generative Bridge Search
-> controlled frontier bridge construction
```

The important v2.x correction is that **Bridge-Valence Diagnostics** and **Generative Bridge Search** are not internal scratch material. They are core discovery-methodology papers: Bridge Valence classifies bridge-problem types, and Generative Bridge Search generates candidate-answer shapes through typed blocker-unblocker matching, adaptation, guardrails, and verification obligations.

## What the programme does not claim

RFOP does **not** currently claim to derive General Relativity, the Standard Model, QED, physical constants, quantum mechanics, empirical dark-sector corrections, or a completed theory of nature.

It also does not claim that recoverability implies causality, that positive information geometry alone supplies Lorentzian signature, that local charted success implies global objecthood, that generated candidates are verified solutions, or that bridge calibration guarantees truth.

The current claim is narrower: foundational transfer claims become inspectable only when source, bridge, target distinction, boundary, readout, task, calibrator, and remaining residual are declared.

## Repository layout

| Path | Purpose |
|---|---|
| `AUTHOR_METADATA.md` | Author identity and ORCID information. |
| `NON_CLAIMS_AND_SCOPE.md` | Public scope and non-claims statement. |
| `AI_ASSISTANCE_DISCLOSURE.md` | AI-assistance disclosure language. |
| `MAIN_PUBLIC_CORPUS.md` | Canonical public corpus list. |
| `PUBLIC_SUPPORT_AND_ARTICLE_CANDIDATES.md` | Support papers and first article candidates. |
| `FRONTIER_BRANCH_INDEX.md` | Frontier branch index, not a completed-proof claim. |
| `FULL_MANUSCRIPT_EXPORT_QUEUE.md` | What still needs to be exported from Drive into this repository. |
| `VERSION_LINEAGE_NOTES.md` | Version-control and provenance rules. |
| `papers/` | Destination for full manuscript exports. |
| `source_pointers/` | Notes about initial placeholder files and why they were removed from the root reader path. |

## Before GitHub Release / Zenodo

Do **not** create the Zenodo DOI yet. First:

1. Export the full manuscripts from Google Drive as Markdown and PDF.
2. Place them in the appropriate `papers/` subfolders.
3. Confirm the root-level files are navigation and policy files only.
4. Create a GitHub release tag such as `v2.1-public-footprint`.
5. Archive that release on Zenodo and then add the DOI back into `CITATION.cff` and this README.

## Citation

A provisional `CITATION.cff` is included. After the Zenodo DOI is created, the DOI should be added to `CITATION.cff`, this README, and `AUTHOR_METADATA.md`.
