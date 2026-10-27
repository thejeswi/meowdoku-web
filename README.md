# meowdoku-web

The playable build of **Meowdoku** — a cat-themed Star-Battle puzzle: an N×N grid, N colour
regions, one cat per row, per column and per region, and cats never adjacent (not even
diagonally). Tap = ✕, drag = paint a run of ✕, double-tap = cat.

**Play it:** https://thejeswi.github.io/meowdoku-web/

This repository holds **generated output only** — Rust/egui compiled to wasm32 via `trunk`, the
same code that also runs as a desktop binary. The source repository is private; nothing here is
hand-edited, and everything is replaced wholesale on the next build.

- `index.html` — entry page (canvas + loader shim)
- `meowdoku-app-*.js` / `meowdoku-app-*_bg.wasm` — the wasm-bindgen glue and the app

Built from source commit `e3276ca`.
