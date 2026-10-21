# Repolex Knowledge Graph of pandas-dev/pandas-msgpack

RDF knowledge graph data for [pandas-dev/pandas-msgpack](https://github.com/pandas-dev/pandas-msgpack), parsed by [repolex](https://repolex.ai).

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
rlex download pandas-dev/pandas-msgpack
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 51e9ef0ace8bc38630c9f3809b1909caba1d789d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 51e9ef0ace8bc38630c9f3809b1909caba1d789d
│           └── chunk-001.nq.gz
├── blob
│   ├── 02379c9188424bb05682d980135fa15f9c771895.nq.gz
│   ├── 07522535841fc29c4e808e7462fb926293d058bc.nq.gz
│   ├── 08fafe8c8b0e9988d3a4642fd1381d20704a8fe7.nq.gz
│   ├── 0942b2372e19f31719d084825649e9a902c2d75c.nq.gz
│   ├── 0a0534530ae24f09867d5ceb098705ba59d4927e.nq.gz
│   ├── 13ed35359dba1cf651ff85012a50c9f9ea43b838.nq.gz
│   ├── 146d272adf7d36bcf1d61d09af8d8390f9fe20f0.nq.gz
│   ├── 156b06acde4219360526ddfca01ee6ee06d90ac6.nq.gz
│   ├── 21025139976a9d4a6432295d9d9b1aa564d678cb.nq.gz
│   ├── 2c1c96c0759a15622f74df59c99ef53614facb69.nq.gz
│   ├── 2d135f988df3d73f945bc59a6833fc2570881780.nq.gz
│   ├── 2ee47b4152ff169520e15819775f94e5a90541af.nq.gz
│   ├── 3bc556cb28e894f184b91a3df36b144e1d2fb0da.nq.gz
│   ├── 3d78fa32ea3598a444cbf5a9e17d3da1329c33ca.nq.gz
│   ├── 4ed8cd776aed7a543b993aa90ad8db1dfd8c0f78.nq.gz
│   ├── 557ba011ad403cc6b2b2a21128aaa2c4fa9a2e32.nq.gz
│   ├── 57c08b640f19c79e844d8f2910e63680065119d2.nq.gz
│   ├── 591fad1ae46616e2b9f3e1713a8c156a60907f78.nq.gz
│   ├── 5c83bb6c9d601c0e93bfdde1ddcd1decffdebc7a.nq.gz
│   ├── 5d1088f4b7d78b25619aab1a8be7c793c20d2f40.nq.gz
│   ├── 631cfb9f60798caf27bbfa68259fd414d6ed17db.nq.gz
│   ├── 64ec7f81884cd1185051dd84b680d3d53d819e78.nq.gz
│   ├── 64fea1c892723b9db5bda7d302168b6128e14bf5.nq.gz
│   ├── 796076c1675efcc5fea4e15a8747411ad9e03593.nq.gz
│   ├── 7dc153b77bcc192767da60eb6a16b8eb3a94b652.nq.gz
│   ├── 7f69caf30b486ac45a15b7e1329a441de0ceed69.nq.gz
│   ├── 82eb580532af13dd26d6dc8a8ea427093369b7de.nq.gz
│   ├── 843a8af86d0b91434d878c8b4324cebe88a0ab9e.nq.gz
│   ├── 848f4608c8627dd20ccbdf07be2bbf4290824300.nq.gz
│   ├── 8b8259fc01349dbced4ac955a0227f3fa5b88ab3.nq.gz
│   ├── 9576544b7884a89b7caafe25c053a20dfd10dd5d.nq.gz
│   ├── 9afa48862e7244594dbbdac9b380a74c59f4a714.nq.gz
│   ├── ae0f74a6700bda58e71fb516d733112f413ac36b.nq.gz
│   ├── b07050aac11cfef124b579d2e88affb164971688.nq.gz
│   ├── b796e46398d460c8b81b326e76f2c5633f625195.nq.gz
│   ├── c0c09fdff2595a7afe21fa9f0e4d653f63fdf381.nq.gz
│   ├── c267af908c918197ed6f1c74d216c49fd4224bb4.nq.gz
│   ├── cd87dd5ef7a6e6eebd9d7575c244b0df4bb506da.nq.gz
│   ├── d000c2d11245ca63d868d15389dba47c86ce4656.nq.gz
│   ├── d681277bb89607bbfc7d0386847598ebe15c2aaf.nq.gz
│   ├── dabc771f2f2166bbc8b0fe4e2acf3c8817e35034.nq.gz
│   ├── e3eb8d6e26cb801b793a9fbeba5351518278d3c3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e97acea7d26ded431a76fa0f954697ba26abe0e9.nq.gz
│   ├── ea9fd11b91d75097369ab7e32469de1cc30536be.nq.gz
│   ├── eb19ab7b2a1e386c02aac8caa1bda66b251a7d46.nq.gz
│   ├── ee0c2620c69b8bbce68f218d345d8f767cd02b9e.nq.gz
│   ├── ef4f541f73b25cecdfddbdb90d42f6a952f7d5e3.nq.gz
│   ├── f6ff470bc52e576edc96782c5868d2bb1d9bbe7b.nq.gz
│   └── fba372ddcb3e4e658a47f3f95c6b3d383b42f70d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 51e9ef0ace8bc38630c9f3809b1909caba1d789d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 58 files
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

[pandas-dev/pandas-msgpack](https://github.com/pandas-dev/pandas-msgpack)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
