# zene-genre-timeline — moved

Merged into **[zene-collection](https://github.com/abobabo91/zene-collection)** on 2026-08-12.

The artist graph, the genre timeline and the combined dashboard were never independent —
the dashboard reads the other two's output directly, and every collection change rebuilds
all three in order. Keeping them apart meant three commits and three pushes per change, and
two rebuild scripts that drifted into near-copies of each other.

- live site: <https://abobabo91.github.io/zene-collection/timeline/>
- source: <https://github.com/abobabo91/zene-collection>

This repository is a redirect stub so the old Pages URL keeps working. Nothing here is
maintained; the full history came along with the merge.
