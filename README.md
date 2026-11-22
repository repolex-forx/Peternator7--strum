# Repolex Knowledge Graph of Peternator7/strum

RDF knowledge graph data for [Peternator7/strum](https://github.com/Peternator7/strum), parsed by [repolex](https://repolex.ai).

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
rlex download Peternator7/strum
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7376771128834d28bb9beba5c39846cba62e71ec
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7376771128834d28bb9beba5c39846cba62e71ec.nq.gz
│   └── repolex
│       └── 7376771128834d28bb9beba5c39846cba62e71ec
│           └── chunk-001.nq.gz
├── blob
│   ├── 0304a019a960a2f6e32f79a3c1fee3a4f4706e43.nq.gz
│   ├── 044a1c5ef4bd022ba7ef203653a7de9ce84c24a9.nq.gz
│   ├── 0d593a9010038d0dc158b0970a19c30dcc3613b7.nq.gz
│   ├── 0fe42db1f1cec8440404a043e5bc3fce60e5cdaa.nq.gz
│   ├── 1243e58e39f724890ea43eba43482dda81bf9255.nq.gz
│   ├── 13a7f89b83b3c8a72a4fce83719f730a06ef1914.nq.gz
│   ├── 14d482b7c0044119f2b8edc6430dd2e4274f7809.nq.gz
│   ├── 1661cadfea9fed81ce8d580bdecb2961579efbc4.nq.gz
│   ├── 1ab2da85d967071ffecc22868bfa944f31506887.nq.gz
│   ├── 1f5e30882cdd7fd327b94cb0fa3884630df2aebd.nq.gz
│   ├── 21737441e11de82ced14c245c8a8d4087af1aa3a.nq.gz
│   ├── 22844952f44fee016c98ef647defc4ee5f753205.nq.gz
│   ├── 233e6343c8fc5f34ed3e925b7cd6f9e750d408c2.nq.gz
│   ├── 29c32b489435973e1939795718dd99f33605ec0c.nq.gz
│   ├── 2e1073e96fc9f1bc9ceb660aa4c460c51819eb8f.nq.gz
│   ├── 32b191734eaeabdb15913e7c632c4485c0dc26a8.nq.gz
│   ├── 3a2ed32e799ce74d7a0d309025fc64d042ab9b30.nq.gz
│   ├── 3e24d6336c4aefaed924d23e20931b5d3179ec12.nq.gz
│   ├── 475746a3f2004ce305fdeaebf2f5cfc4a5bb5678.nq.gz
│   ├── 4925fc722da1a72df6d212b7d40f6ba85a5c2c56.nq.gz
│   ├── 4daf3e109550c2434bb6955309a972ca1fa3a7ea.nq.gz
│   ├── 4e07e96043280c6f19d8b6ea29ce0adfba4ea9d8.nq.gz
│   ├── 52f5e054a3945a9fc937197ecd5a0a17bda8bc2d.nq.gz
│   ├── 53ddd5a1d0fcc2cffb6efdcccbf03e8204e5b063.nq.gz
│   ├── 588b4a7da7161c2b81628344c25c7815e30f7102.nq.gz
│   ├── 5be9c5c29b7034c6e4c354445dc80ec51b42c8ee.nq.gz
│   ├── 5c912164bef40ee522b87515d33d0d1a79a60b07.nq.gz
│   ├── 60ffa22c314ded35c626a9d964ba3069067462bb.nq.gz
│   ├── 62262e13a7cf80c7fed5d8a2bc672e92e9f23a66.nq.gz
│   ├── 65e44375610e9229db96d2f00e130332fc4ae154.nq.gz
│   ├── 6788e4cb3699b34cfd9eee8b8d8c6f43b7ddf32b.nq.gz
│   ├── 71173234e6024a57c973a233a211fbb901cc89d1.nq.gz
│   ├── 757dbe01f5c39faae5317613c5117a247be73a72.nq.gz
│   ├── 84895d173bdc76a443dec744bc1b45a77d2459a2.nq.gz
│   ├── 860f55724d7269c62499cbcc66c6970c1656d620.nq.gz
│   ├── 8d9607d2f8902f73b5dd1395c014781427e23dc1.nq.gz
│   ├── 9019a7212b11f613d47be4a7bd9d73ebe76f20bc.nq.gz
│   ├── 97e348a1e04c24abe1da4e78a801d6a77067320d.nq.gz
│   ├── 9d1ea15933aa04ffa0cd3c78d083a4587480268d.nq.gz
│   ├── 9e4e79799add2de63da6a6dc8ee40781aa1af7a1.nq.gz
│   ├── a2af7826f2ca86233e319051cca1fffa8f7d7fa8.nq.gz
│   ├── a4b0ee102f1e292e793144f3ec86b77c169697df.nq.gz
│   ├── a9d37c560c6ab8d4afbf47eda643e8c42e857716.nq.gz
│   ├── aac6284d4b8a0d741add10b2d0d50d5dcc581641.nq.gz
│   ├── acf011331bd6a2cf8fc1e948d07aee2fb396c6dc.nq.gz
│   ├── ae3c7fd9f32b0020ba04117180df1393ef5ad7bf.nq.gz
│   ├── af3f7d8dcf84e00533f9b1f4cfcd90584c81c39d.nq.gz
│   ├── b36c1399cee409dfda213ab7ac00db96b87418b2.nq.gz
│   ├── bbd6c9ed679e7e038e43fecf41007118a84f6b3d.nq.gz
│   ├── dabcecd3612656c70343d2b49e020f1afa099928.nq.gz
│   ├── dc7ba4230a93bd6ed2a359377462c75d47afb79b.nq.gz
│   ├── dcc83852f198bf6b65e32be1a3172291dd0088bd.nq.gz
│   ├── e20c39b3f7e4bcc9edd8a76e65c631b0132c383b.nq.gz
│   ├── e3cd711b5bd88597a937db6177ab93e8213c59c8.nq.gz
│   ├── e670aaacd89858d173e56c90bd8eacd76733d611.nq.gz
│   ├── e6a937805163fde3fd49e3bb86b9202379abcff4.nq.gz
│   ├── e7ff3033a53107c35917cf6b1c6802da719a6d9d.nq.gz
│   ├── e8a805412f61622ed58ff1771c0b55d91df6be87.nq.gz
│   ├── f37bac99d54dc1fbaf47454a7896b1d931bd664a.nq.gz
│   ├── f8f4f575c2266159446005b71255ed723f29f9df.nq.gz
│   ├── fafc048bbaa6f539957f01f9e580883dfdd46f22.nq.gz
│   └── ff2bd98a108b04be55af16e85062b8eadf1776ff.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 7376771128834d28bb9beba5c39846cba62e71ec.nq.gz
├── filetree
│   └── 7376771128834d28bb9beba5c39846cba62e71ec.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 72 files
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

[Peternator7/strum](https://github.com/Peternator7/strum)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
