# jk screenshots

This repository hosts screenshot and GIF assets for
[`joshka/jk`](https://github.com/joshka/jk).

Assets in this repository are intended to be embedded from the `jk` README, crates.io page, docs,
and release notes using absolute URLs such as:

```markdown
![jk log view](https://joshka.github.io/jk-screenshots/assets/jk-log.gif)
```

## Rules

- Store generated screenshots, GIFs, and videos under `assets/`.
- Keep all image and video assets Git LFS-backed.
- Do not copy these assets into the main `jk` repository.
- After publishing an asset, verify the served URL returns real media bytes rather than a Git LFS
  pointer file.

