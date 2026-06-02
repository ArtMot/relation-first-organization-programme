# Version Lineage Notes

This repository distinguishes between the **public reader path** and the **version/provenance layer**.

## Core rule

```text
Latest version wins only after provenance audit.
```

A file with a higher version number, `_self_contained`, `_submission_integrated`, or `FULL_PRESERVATION_REPAIR` suffix is not automatically canonical. It must be checked for:

1. self-containedness;
2. carry-forward of prior content;
3. preservation of relevant definitions, claims, non-claims, and proof obligations;
4. avoidance of overclaim;
5. placement in the correct public/support/frontier/internal tier.

## Public reader path

The public reader path should contain only:

- root navigation and policy files;
- canonical public corpus list;
- full exported manuscripts intended for public release;
- support/article candidate papers where appropriate;
- frontier branch index with clear non-claims.

Prior versions should not be mixed into the main reader path.

## Provenance layer

Prior versions, self-contained variants, preservation-repair versions, and construction traces belong in a lineage/provenance archive, not in the main public corpus.

Suggested private/archive structure:

```text
internal_archive/
  prior_versions/
  self_contained_candidates/
  full_preservation_repairs/
  construction_traces/
  superseded/
```

## AS / critical-rank branch

The AS / critical-rank branch has multiple version lines and repair variants. It should receive a dedicated branch reader map and carry-forward audit before files are promoted into the public release.

## Why prior versions are preserved

Prior versions are useful because they help establish:

- inter-version provenance;
- carry-forward of relevant content;
- repair of lost material;
- proof that the programme evolved through traceable stages rather than isolated post hoc files.

They should be preserved, but not confused with the current public canonical corpus.
