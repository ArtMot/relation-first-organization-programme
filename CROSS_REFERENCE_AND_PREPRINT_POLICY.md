# Cross-Reference and Preprint Policy

RFOP papers reference one another heavily. Later papers contain more internal references because the programme becomes more integrative over time. This must be handled deliberately before public release, preprint upload, or journal submission.

## 1. Problem

If a paper cites many RFOP manuscripts that are not yet public, the citation layer can look circular, unavailable, or unstable.

If every paper is delayed until every referenced paper is public, the programme never releases.

The solution is staged release with explicit citation status.

## 2. Citation statuses

Each internal RFOP reference should be placed in one of these statuses:

| Status | Meaning | Public citation form |
|---|---|---|
| Public release | Included in the GitHub/Zenodo programme release | Cite the programme release and the paper filename/title |
| Public preprint | Individual paper has arXiv/OSF/Zenodo/preprint DOI | Cite the preprint normally |
| Repository manuscript | Full manuscript is public in the repository but not individually archived | Cite repository path and release tag |
| Forthcoming / in preparation | Not yet public or not yet release-ready | Use sparingly; avoid relying on it for essential proof obligations |
| Internal provenance only | Not public-facing | Do not cite in public manuscripts except as internal development history if appropriate |

## 3. Minimum safe public strategy

Before individual papers are sent to arXiv or journals, create a citable programme release containing:

1. public README;
2. foundation corpus status table;
3. public reader map;
4. non-claims and scope statement;
5. AI-assistance disclosure;
6. release manifest;
7. public suitability audit protocol;
8. full manuscripts for the release-ready foundation papers;
9. placeholders only where clearly marked as not full manuscripts.

This lets later individual papers cite the RFOP programme release instead of citing unavailable private drafts.

## 4. Handling cross-references inside public manuscripts

### 4.1 If the referenced paper is in the same public release

Use a reference such as:

```text
Motruk, A. Relation-First Organization Programme, Public Footprint Release vX.Y, paper: [Title], [repository path / release DOI].
```

### 4.2 If the referenced paper has its own preprint

Cite the individual preprint normally.

### 4.3 If the referenced paper is not yet public

Do not make it a load-bearing reference unless unavoidable. Instead:

- summarize the needed result locally;
- cite the programme release if the result is listed there;
- mark the detailed paper as forthcoming only if it is genuinely close to public release.

### 4.4 If the referenced document is internal only

Do not use it as a public proof source. Convert the needed result into the public manuscript, a public appendix, or a public release note.

## 5. Regular research procedure analogue

In a conventional research programme, papers often evolve in overlapping stages:

1. internal notes establish definitions and lemmas;
2. workshop/preprint versions make the programme visible;
3. individual papers are submitted to journals;
4. later papers cite earlier preprints or accepted papers;
5. survey/review papers later unify the programme.

RFOP is unusual because many papers were drafted before any public preprint existed. Therefore the programme needs a first public corpus release to serve the role that earlier preprints, seminar notes, and technical reports would normally have played.

## 6. Release sequencing rule

Do not require every paper to be journal-ready before public release.

Do require every publicly cited paper to have one of:

- public manuscript in repository release;
- individual preprint;
- clear local summary of the needed result;
- explicit `forthcoming` status with no essential proof dependency.

## 7. Bibliography repair rule

Every paper needs a bibliography pass before public PDF export.

For each internal RFOP citation, record:

```text
Referenced paper
Citation status
Is the reference load-bearing?
If load-bearing, is the cited result locally summarized?
Public location / release tag / DOI
Action needed
```

## 8. Practical rule for first release

The first GitHub/Zenodo release should not try to make all cross-references perfect. It should make them honest.

A first public release may contain:

- public-ready full manuscripts;
- audited-but-not-yet-repaired papers as listed corpus entries;
- unreleased foundation papers marked as pending public-register repair;
- a clear statement that the programme is being released in staged form.

## 9. Do not hide dependency structure

The fact that later RFOP papers cite many earlier RFOP papers is not a defect. It is evidence of programme integration. The defect would be pretending those dependencies are already public, stable, or independently validated when they are not.

Therefore the repository should expose dependency status rather than flatten it.
