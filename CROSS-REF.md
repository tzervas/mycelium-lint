# CROSS-REF — mycelium-lint

Mycelium-internal dependencies only (steer handoff §6.1; external crates stay in Cargo
metadata). Pinned revs are the fixed (buildable) tips recorded by the Phase-B wave;
content hash = git tree hash of the pinned rev.

| Interface consumed | Repo | Pinned rev | Content hash | Notes |
|---|---|---|---|---|
| mycelium-cli-common | https://github.com/tzervas/mycelium-cli-common | `c673fafdd1bcecb713e3560689af6ab152033867` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-cli-common` (see monorepo `docs/api-index/INDEX.md#mycelium-cli-common`) |
| mycelium-doc | https://github.com/tzervas/mycelium-doc | `85c48010fb054dc80d8a86a854564c7cab5f7942` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-doc` (see monorepo `docs/api-index/INDEX.md#mycelium-doc`) |
| mycelium-l1 | https://github.com/tzervas/mycelium-l1 | `cd32a1ed7ab7d2be38c9c3047da7318d182b7a1c` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-l1` (see monorepo `docs/api-index/INDEX.md#mycelium-l1`) |
| mycelium-lsp | https://github.com/tzervas/mycelium-lsp | `7a3cfad66a3cd8a9002d885b70fd5291e6919723` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-lsp` (see monorepo `docs/api-index/INDEX.md#mycelium-lsp`) |

**Owning docs:** see monorepo `docs/Doc-Index.md`.
**Source provenance:** extracted from `tzervas/mycelium` archive `aad96b7a…`; fixed by
the course-correction Phase B (workspace root, git pins, toolchain + supply-chain
replicas, CI v2). Full program record: monorepo
`docs/planning/course-correction-2026-07-18/PROGRAM.md`.
