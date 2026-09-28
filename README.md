# Repolex Knowledge Graph of pydantic/jiter

RDF knowledge graph data for [pydantic/jiter](https://github.com/pydantic/jiter), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/jiter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dcdc93df6b9c6eb53facb0fff725069d9528d735
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── dcdc93df6b9c6eb53facb0fff725069d9528d735.nq.gz
│   └── repolex
│       └── dcdc93df6b9c6eb53facb0fff725069d9528d735
│           └── chunk-001.nq.gz
├── blob
│   ├── 08b83993d29543881b16a75634fc66d963f9f540.nq.gz
│   ├── 09116e2b28a4f89cc3252f73a2fbd79a1a6db12d.nq.gz
│   ├── 0a41adc92ee12507557875cc59cf8ac9399c8605.nq.gz
│   ├── 0b34a57ea741a1a7a8f50ee46585f0a3a8606644.nq.gz
│   ├── 0b7c9fef6b636180bc56cac19e8836058e860b18.nq.gz
│   ├── 116bda1ab52ad0751a234300a962e7e3004ba66f.nq.gz
│   ├── 1189a6b54ff6ce457ac50937468e3fb1adf26762.nq.gz
│   ├── 155d819f5b226b9b6af133230acfee1bcfd49e3a.nq.gz
│   ├── 17dfd4a2f32d35efdc89db1544ce7b6bdf204d05.nq.gz
│   ├── 18575b0c87be734e59f8e3251d11cda9b6ebe3dc.nq.gz
│   ├── 191590daecfaf86a80ac84efcd0e72aaad9059b0.nq.gz
│   ├── 1e953c85f8c5f953ea1df8285a7b239919a763be.nq.gz
│   ├── 21065413cae83aae13fbd8ab18148e23afc9b02e.nq.gz
│   ├── 27d58f94c8214140229866c207c4ca4560baa093.nq.gz
│   ├── 2b330431893a7db98a48bf7710a3930c96a8a8e0.nq.gz
│   ├── 305be8014e4a8f93b0bf41cd1e2aaf42dc11e399.nq.gz
│   ├── 30cff7403da04711c46979a06f6bf8eb10ee088a.nq.gz
│   ├── 332bb2f0ee8b8e7394ed3ff6d7f6b228daefa975.nq.gz
│   ├── 364263a5e21506ecb015980c0dca335895f102f8.nq.gz
│   ├── 3cd180c84474ba6154c0b4ca2b00de5bd257fe66.nq.gz
│   ├── 3f8873e578d6450bca66461b42a9e0bbfa70344b.nq.gz
│   ├── 41053a75291986dd9bfd4094a5055981fe4c3394.nq.gz
│   ├── 421c625f7b6466d7a9d6fe1fae6a0f2be7a21ef0.nq.gz
│   ├── 434099e5b65ed5fe6521761d43a5f35d45db76f5.nq.gz
│   ├── 455963f41782c79a8b56535770d474fc3decb00c.nq.gz
│   ├── 47de40dc06ba673d480a12ef728ce62fe43e3151.nq.gz
│   ├── 4a199567521d304275a1b0935eb5ca85d3295817.nq.gz
│   ├── 4ec565b01e412801ba55bc43771bf28db68362e8.nq.gz
│   ├── 56d127d975d316c1afd3d6a381d0841fc2a019ae.nq.gz
│   ├── 5a8d9911ccd55e85ed4c6a5b0f311f40240ff733.nq.gz
│   ├── 6550b665ca3f7f1411f34b65cb2f2e99e729c4bf.nq.gz
│   ├── 658e7d8281412d605e0c874b637e48f0dd3a2a68.nq.gz
│   ├── 692316a3f5c6e2823b52ef3cf6e5d3d33f3c5edd.nq.gz
│   ├── 6cb615529ab2339eb7c91a8700ee4616ad6140cc.nq.gz
│   ├── 6cdb2450ca3e8bdb724e68bdbb1b9f156dc1d98a.nq.gz
│   ├── 6f2603b78efdd225047cddebc6e9bc626ce1bf2c.nq.gz
│   ├── 70e26854369282e625e75b302782f581e610f2b3.nq.gz
│   ├── 75306517965a54731b94dca8bace640e856af115.nq.gz
│   ├── 79c77f73bd37c62a342affdd0aabd941e2293267.nq.gz
│   ├── 82bd5725608f630991f7f9033e1e92e64a5605a1.nq.gz
│   ├── 86c8cd58205683ba960fdb48a5484f872c8373b0.nq.gz
│   ├── 8b065bcd1abac303145a0420c2674598d2688ea4.nq.gz
│   ├── 8be37fd3bd644a6bc3b39df5cfe3f41072299216.nq.gz
│   ├── 95dbc7ae8190517ce8e22ef99d3b06ad325cd4a4.nq.gz
│   ├── 9c38ec092dc75ea2c429ccc01c2d1b201f3a7c66.nq.gz
│   ├── 9fe31fb6c4b8fa2e028c5f26e6b0ea44e9a896b8.nq.gz
│   ├── a14151e77c1912f0e98e3864da6ec31f55c9c597.nq.gz
│   ├── a7fa5b23f8b706f6f1d4d4a82376c93c3bdd856d.nq.gz
│   ├── aead3046d12dc4796dd65a1433acaccc93f70f95.nq.gz
│   ├── bfd6465982388b1abc2cb77b357ac1e5638121cf.nq.gz
│   ├── cb427c97c0e58b4be43486e9f1b5102e2da6f979.nq.gz
│   ├── d3c63c7ad845e4cedd0c70d13102b38c51ec197a.nq.gz
│   ├── d564a4e4d7a8c6bfc8264c249bfdbfe1bd643ba6.nq.gz
│   ├── d6afc2da8de50958bbb75ed4cc78b18ea6f7ae53.nq.gz
│   ├── dbae8093a3957a015282435212ed79c735890a77.nq.gz
│   ├── e0f22ef9a50e02ab3926a0ef32c4c0bf64a8c616.nq.gz
│   ├── e39d1f00a488e2de445ad582ad4b0977ae89aa4c.nq.gz
│   ├── ec3e830b6c5fd7e2edd8f9e05f003f4f021c6547.nq.gz
│   ├── ecb58d79ce0cda4f7b4557e66fd9200752dcd2a6.nq.gz
│   ├── ef3b3aa0015bb8a27f8b42ea170804655846cddf.nq.gz
│   ├── f785c8cb9c0d7b4d2126cf1ee7bfc424a5e6515f.nq.gz
│   └── fc698fc34bf89a6f10594e6f4f39c59611741a98.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── dcdc93df6b9c6eb53facb0fff725069d9528d735.nq.gz
├── filetree
│   └── dcdc93df6b9c6eb53facb0fff725069d9528d735.nq.gz
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

[pydantic/jiter](https://github.com/pydantic/jiter)

---
*Parsed on 2026-09-28 by [repolex](https://repolex.ai)*
