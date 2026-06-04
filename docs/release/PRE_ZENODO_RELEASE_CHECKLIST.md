# Pre-Zenodo Release Checklist

Use this checklist before creating the first GitHub release and Zenodo DOI.

## Repository landing state

- [ ] `README.md` describes the current manuscript footprint accurately.
- [ ] `PUBLIC_MANUSCRIPT_INDEX.md` is present at root and lists all public manuscript paths.
- [ ] `CITATION.cff` has current title, author, ORCID, version, repository URL, and license.
- [ ] Root contains only landing/citation/index essentials and a small number of unavoidable controls.
- [ ] Detailed controls live under `docs/`.

## Manuscript paths

- [ ] `papers/canonical/` contains the canonical repository manuscripts.
- [ ] `papers/canonical_working/` contains BVD, GBS, and DWA working manuscripts.
- [ ] Each public manuscript has both `.md` and `.pdf` versions.
- [ ] The working manuscripts are labelled as working manuscripts.

## Release controls

- [ ] Release manifest exists under `docs/release/`.
- [ ] Non-claims are visible in README and release manifest.
- [ ] AI-assistance disclosure is visible in README/release materials and manuscript footers.
- [ ] Cross-reference policy is under `docs/protocols/`.
- [ ] Suitability audit protocol is under `docs/protocols/`.

## License and citation

- [ ] License choice is confirmed.
- [ ] `CITATION.cff` uses the confirmed license.
- [ ] Zenodo metadata will use the same license.
- [ ] No DOI is inserted until Zenodo generates one.

## GitHub release

- [ ] Create release tag: `v0.1-public-manuscript-footprint`.
- [ ] Release title: `Relation-First Organization Programme: Public Manuscript Footprint Release v0.1`.
- [ ] Release notes summarize the manuscript corpus and working-manuscript status.
- [ ] Confirm release assets / source archive are complete.

## Zenodo

- [ ] Upload the GitHub release archive or connect the repo to Zenodo.
- [ ] Use title: `Relation-First Organization Programme: Public Manuscript Footprint Release v0.1`.
- [ ] Creator: `Motruk, Artur`, ORCID `0009-0003-6928-1701`.
- [ ] Resource type: `Other` or `Report`.
- [ ] License: `CC BY 4.0`, unless changed before release.
- [ ] Description includes non-claims and working-manuscript status.
- [ ] Publish and record DOI.

## After Zenodo

- [ ] Add DOI to `README.md`.
- [ ] Add DOI to `CITATION.cff`.
- [ ] Add DOI to release manifest.
- [ ] Add release to ORCID.
