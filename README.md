# ludovic111.github.io

A mirror that keeps Horizon's mod index at its old address,
`https://ludovic111.github.io/horizon-mods/index.json`.

The Horizon repositories moved to the [horizon-rust](https://github.com/horizon-rust) organization on 2026-10-27.
GitHub redirects repository URLs but not GitHub Pages, so launchers released before the move would find no mods.
Every 15 minutes, `.github/workflows/mirror.yml` copies the index and its icons from
`https://horizon-rust.github.io/horizon-mods/` and rewrites the addresses in it to the ones those launchers accept.
New launchers read the new address directly.

Remove this repository once old launchers are no longer in use.
