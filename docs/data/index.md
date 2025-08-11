# Data

This project separates **tiny sample data** (for quick tests) from **full datasets** (hosted externally or in Releases).

## Layout
- `samples/` — small frames/clips kept under 100 MB each (use Git LFS)
- `manifests/` — CSV/JSON listing dataset items, checksums, and sources
- `external/` — pointers (URLs) to large datasets hosted elsewhere

## Integrity
Every dataset entry should have a SHA256 checksum in `manifests/`. Use the fetch script in the repo to download and verify.

> Note: GitHub limits regular files to 100 MB. For larger assets use **Git LFS** or the **Releases** page and link here.