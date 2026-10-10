# Repolex Knowledge Graph of litestar-org/litestar-saq

RDF knowledge graph data for [litestar-org/litestar-saq](https://github.com/litestar-org/litestar-saq), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download litestar-org/litestar-saq
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 95619b5f748e2a7dba2aa8de7659b99ac361aea3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 95619b5f748e2a7dba2aa8de7659b99ac361aea3
│           └── chunk-001.nq.gz
├── blob
│   ├── 048a587ec673ce6c07ff94ed5fd090f911be58b0.nq.gz
│   ├── 0a719f90732acd7d2337d9ae624c6cfe293d6c78.nq.gz
│   ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
│   ├── 19db051bdc778c300f5a40971a39d087fd64b835.nq.gz
│   ├── 21226091f52ee6a68d9b6459297d88a8854c1fb6.nq.gz
│   ├── 2547f592f49c6fb774f075a95440b283fa29df37.nq.gz
│   ├── 2af7d6896a1069d080c376307ea5f1782709c40c.nq.gz
│   ├── 31095c944f33acd87a3ca1e9aa0c49e0702f515f.nq.gz
│   ├── 31a182fdfc96cc7c02cbc2ff0f07b46ff2a2c09c.nq.gz
│   ├── 33dbdc03f8d608aa91bf269d00441298589fac3a.nq.gz
│   ├── 34ec8d108db9cb281a6584a57c4f4a4e040db660.nq.gz
│   ├── 3c2cfda7de767ae59c479b59bdbe622156c11b2c.nq.gz
│   ├── 3db79bf128da64e9924cad8ed431d9442971f8b8.nq.gz
│   ├── 3f6b47a4ad9bf676b6a84acb6bce648801f31f44.nq.gz
│   ├── 43967886291a23dae1200eb5378fbd2f937ce665.nq.gz
│   ├── 44d9c32a93beb4662529708ae5e954de97e834e5.nq.gz
│   ├── 47ac38e5c04251d6c672b32dc7266bffeb86f501.nq.gz
│   ├── 4e2b9847740d1d3287a9cc2a339a461906294e8d.nq.gz
│   ├── 4ea846828a9bf817f3c72528ce28242dbcc5a822.nq.gz
│   ├── 5b298458fdc7b3e1506d486e47d37e3eae415329.nq.gz
│   ├── 61c8757d61d719c324f6e377a77cf9fb4de0865f.nq.gz
│   ├── 6b2c07f670fc470be95506b57e4aeb7dc2ecae11.nq.gz
│   ├── 6c07f2a80a73b23d44c1537c9112a855819f6ffc.nq.gz
│   ├── 6e6691fd67343cb3bb81d3855044a1069d5d4b6f.nq.gz
│   ├── 71182200da0eda385925f823569c7bfca1e21568.nq.gz
│   ├── 79f808a39b9e3aa36a25c40cbdb4f57a615f3ab6.nq.gz
│   ├── 7c503d04da7486fd759cf75e04f6c2ea416c827d.nq.gz
│   ├── 888fc77519be3cdc46a7d7cb4b8164d055048748.nq.gz
│   ├── 8c609367533d1496439d0a70bc03dafc4f9ab4de.nq.gz
│   ├── a60456d347c5201d10cb8715a7eb6f7ee310034a.nq.gz
│   ├── b3a2f7354e7ccb0fedb9ab8f301fd18f0538d31d.nq.gz
│   ├── b4491ff3676ad4ddab44598029f3dfdec778ffb6.nq.gz
│   ├── bb5184c3c79744733c9492dd6bc5b2720862f219.nq.gz
│   ├── bbb6ae86a18e0267bb43791b865c8f8970dadb42.nq.gz
│   ├── c49a88a9e0056e25eb2ace4aff09d8f32c23d79c.nq.gz
│   ├── c6d381ffd5e61382da06f4ec248fd0753f26d3d0.nq.gz
│   ├── c950653f1ddab5af8e134fbd101b50eb77432225.nq.gz
│   ├── cc8af743a32d3dde69c53dcf67773cae0b4b70d0.nq.gz
│   ├── ce40f53acf4e8096fbe84680995b0d3a17167773.nq.gz
│   ├── d14a557396c9fbdcc424e9c787876dffc53d35c9.nq.gz
│   ├── e226ecc3befb91fbf1f629aa2a6b6cebdf577a5e.nq.gz
│   ├── e34721e827db2e9b58f76780690a18932b0e92e5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f25ce3f4fb7b4e442c1cf90884c6abc542d92951.nq.gz
│   └── fa975f93ff16f1a3916d950f8828a166446b1eba.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 95619b5f748e2a7dba2aa8de7659b99ac361aea3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 53 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[litestar-org/litestar-saq](https://github.com/litestar-org/litestar-saq)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
