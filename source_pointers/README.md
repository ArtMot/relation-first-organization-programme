# Source Pointers and Placeholder Cleanup

The first repository upload included several root-level files whose filenames looked like full manuscripts but whose contents were only short source-pointer placeholders.

Some of those placeholders were mismatched: the filename did not match the paper named inside the pointer. To avoid misleading readers, those root-level placeholder files were removed from the public reader path.

The authoritative current lists are now:

- `MAIN_PUBLIC_CORPUS.md`
- `PUBLIC_SUPPORT_AND_ARTICLE_CANDIDATES.md`
- `FRONTIER_BRANCH_INDEX.md`
- `FULL_MANUSCRIPT_EXPORT_QUEUE.md`
- `RELEASE_MANIFEST_v2_1.csv`

Full manuscript Markdown/PDF exports should be added later under:

```text
papers/canonical/
papers/support/
papers/article_candidates/
papers/frontier/
```

Until then, this repository should be treated as a public programme-footprint shell, not as a complete manuscript archive.
