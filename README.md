# Reel-Deal (Web Build)

Public deploy target for [Reel-Deal](https://github.com/dagron27/Reel-Deal)'s
Godot Web/HTML5 export, served via GitHub Pages.

This repo contains **only the exported build output** (`index.html`, `.wasm`, `.pck`)
— no source code, no project docs. The actual game source, design docs, and dev
tooling live in the private `Reel-Deal` repo; this one exists solely so GitHub
Pages has something public to serve from.

Updated via `scripts/deploy_web.sh` in the source repo — not meant to be hand-edited.

## Preserved snapshots
- [full-world-0.3.0](./full-world-0.3.0/) -- the last build with the old
  full region-graph world (12 regions), frozen just before the scope
  reduction to one composite Lake.
- [0.5.0](./0.5.0/) -- frozen milestone build, never overwritten. Last
  version before a major departure in fishing mechanics.
