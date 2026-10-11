# Repolex Knowledge Graph of agronholm/modoboa-dmarc

RDF knowledge graph data for [agronholm/modoboa-dmarc](https://github.com/agronholm/modoboa-dmarc), parsed by [repolex](https://repolex.ai).

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
rlex download agronholm/modoboa-dmarc
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 47572ed820f16203670d0f8c2881e10ecc1d53a7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 47572ed820f16203670d0f8c2881e10ecc1d53a7
│           └── chunk-001.nq.gz
├── blob
│   ├── 03a2b80bba9e24f6cc7e70b8deb6430f33e90f45.nq.gz
│   ├── 0cf12c8bc035e8e6d7a06849589f378ed45a7e9d.nq.gz
│   ├── 1369c8316403c40319261c44cbe40dc02a57935d.nq.gz
│   ├── 136bd8a16d6c2572ef5ee7490e33b0e5a1e45aff.nq.gz
│   ├── 13cffae8e084a1e66de0ec0464e63be2ec49055e.nq.gz
│   ├── 2104c695ff9c76f63708d7f641c85d66530b12e5.nq.gz
│   ├── 21812ef7e2246836cfb32be787848cd05b6c95b5.nq.gz
│   ├── 28d211ee934f7a0fd07e3b14c5619a694376223f.nq.gz
│   ├── 2c3802b5e20ca0864d4129b1bd0ddb47ddb3b994.nq.gz
│   ├── 31924fcb1121ec13b06bdc9d836c8c349d413635.nq.gz
│   ├── 383cb153039dc4e205e8f36d3426e3d9b5df3ca2.nq.gz
│   ├── 4591feb41b1ae867ae0ba76af36106eea9a59c87.nq.gz
│   ├── 491deae0af2cae800a8fd1bc1ffb5ecd09221266.nq.gz
│   ├── 492a0ec485b6eaeeb54a8569f5bb4a0b3fd91a72.nq.gz
│   ├── 4b777ac39581deafac4c80bda14b81113cdca888.nq.gz
│   ├── 54265047a3051b290ed3c28320f654d50d133324.nq.gz
│   ├── 56cfdf7f71921f66b8297eb20643dee53fba5186.nq.gz
│   ├── 58166112587f3c7983aaf9ad5780f0ffb59c9f34.nq.gz
│   ├── 5b07aa1a1d480720904e02a02deac09a934b857f.nq.gz
│   ├── 638b0a00a63883a2bb04ae6a08d45cf3e222d715.nq.gz
│   ├── 65706193334c9ff953ddb73eb3cb53d5919d7e0c.nq.gz
│   ├── 6c3ab6db15a37f9518e62d6c403d74b97087a1ec.nq.gz
│   ├── 6c90f8a63cea9f0a82c563ff147f63c0019982b1.nq.gz
│   ├── 70151f31aa1b7a335487f91d7683702f01de0120.nq.gz
│   ├── 711ccdafa39be32734b112294e5c206e9c07f954.nq.gz
│   ├── 7c2b2874c477c0a0d7ee2245b5d776da35f61de1.nq.gz
│   ├── 7fda38ca66e54e212aff8e9231064974b441c579.nq.gz
│   ├── 82ee1ed6767e3a9a5e5b689dbd9ef4d785d3200e.nq.gz
│   ├── 8c38f3f3dad51e4585f3984282c2a4bec5349c1e.nq.gz
│   ├── 8c674ac0d25fae4fe01673bca6bbce6ed2e4b16f.nq.gz
│   ├── 8ef6bb59792346dcf9d100f1ff13db6838c90295.nq.gz
│   ├── 934962a38b74c2e7c16ddfd9d00bd5aa1053eee6.nq.gz
│   ├── 9b94041b76519650037b141f70e10e144f17c8ba.nq.gz
│   ├── 9d7c3588b721a68cb3ced0b388050b9bd2b34e8b.nq.gz
│   ├── b1b3469752ca0a3785c1eabfa9e4ee4d8f6710b8.nq.gz
│   ├── b29adcff302cf1f8917ffb57d346de6d4614892e.nq.gz
│   ├── b303ee0d7c0ecbda61fa846a0bdfe15af95d1934.nq.gz
│   ├── b6718f9da83a5ff89246825a615e6bbdb83fad5b.nq.gz
│   ├── ba4bba75cfab6fc9c4a89c429676ce3cc1a83b79.nq.gz
│   ├── ba74660506d90c514ee1d32bf4eb5ecb0af14075.nq.gz
│   ├── c313b67ae99e0c1e1260f8c4b454d0b0ccb91091.nq.gz
│   ├── c70f8a4e3e2847361ccead97cffe351fc76ff632.nq.gz
│   ├── cd26188994dc5108d5f49303900288a58090756b.nq.gz
│   ├── d041c9c9683363e27b69e35827634435558c1518.nq.gz
│   ├── d44a7a6a11b4c1d30ae03357ecc4b47fa76e394f.nq.gz
│   ├── daf4611a26187a6e04845bcb311af2159b23d9e1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e71e50fb1aa99dca2df5366c95509100bd54b3b9.nq.gz
│   ├── ec97c0337811bf7f828044aabd2027a0b4a179d1.nq.gz
│   ├── ed0d30d1cbf5609ff1d317d746c2599ecfcdda92.nq.gz
│   ├── ef23f7abdd141661ceed67eeb411f16dfbb2ebfc.nq.gz
│   ├── ef3a68f7bc17d94a462833b53d2abdf78cbd8804.nq.gz
│   ├── f05aba4c43d9acd7e28c115114090df0c22c96e1.nq.gz
│   ├── f167aaccaa45767f5ca7ab5f2473a79ef9243352.nq.gz
│   ├── fc35ea19edf6a68b2e59d32544821f496c4866e5.nq.gz
│   └── fce40e0632f6f0f53760973362cacb32b6f5245e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 47572ed820f16203670d0f8c2881e10ecc1d53a7.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 62 files
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

[agronholm/modoboa-dmarc](https://github.com/agronholm/modoboa-dmarc)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
