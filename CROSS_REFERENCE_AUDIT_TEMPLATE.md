# Cross-Reference Audit Template

Use this template before exporting any RFOP manuscript as public Markdown/PDF or including it in a GitHub/Zenodo release.

## Manuscript

```text
Title:
Internal filename:
Version:
Repair packet:
Suitability report:
Auditor/date:
```

## Internal RFOP references

| Referenced RFOP paper | Citation status | Load-bearing? | Needed result locally summarized? | Public location / release tag / DOI | Action needed |
|---|---|---:|---:|---|---|
|  | public release / public preprint / repository manuscript / forthcoming / internal only | yes/no | yes/no |  |  |

## External references

| External reference / literature | Role in paper | Full citation present? | Action needed |
|---|---|---:|---|
|  | prior art / analogy / imported theorem / comparison / application domain | yes/no |  |

## Load-bearing dependency check

For each internal RFOP reference marked load-bearing:

1. Is the cited paper included in the same public release?
2. If not, is the needed theorem/definition summarized locally?
3. If not, can the dependency be downgraded to orientation rather than proof support?
4. If not, the manuscript is not release-ready.

## Forthcoming-reference rule

A forthcoming RFOP paper may be mentioned for orientation, but it should not carry an essential proof obligation in a public manuscript.

## Release decision

```text
[ ] Cross-reference audit passed
[ ] Passed with local-summary additions required
[ ] Hold until referenced paper is public
[ ] Hold until citation status is resolved
```

## Notes

```text

```
