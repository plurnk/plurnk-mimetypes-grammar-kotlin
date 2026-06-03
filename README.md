# @plurnk/plurnk-mimetypes-grammar-kotlin

Pre-built `tree-sitter-kotlin` WASM grammar for the [@plurnk/plurnk-mimetypes](https://github.com/plurnk/plurnk-mimetypes) framework.

## install

```
npm i @plurnk/plurnk-mimetypes-grammar-kotlin
```

## what's in here

- **`kotlin.wasm`** — pre-built from the pinned upstream [tree-sitter-kotlin](https://github.com/tree-sitter-grammars/tree-sitter-kotlin) commit (SHA in `.grammar-pin`)
- `scripts/build-wasm.mjs` — reproducible rebuild from the pinned source
- `scripts/verify-wasm.mjs` — CI byte-identical reproducibility check

Declares only `web-tree-sitter` as a peer — no native `tree-sitter`, no node-gyp.

## license

MIT. The bundled `kotlin.wasm` is built from the upstream tree-sitter-kotlin grammar; see the pinned commit for that project's attribution.
