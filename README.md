# Repolex Knowledge Graph of NousResearch/Hermes-Bot-Mode

RDF knowledge graph data for [NousResearch/Hermes-Bot-Mode](https://github.com/NousResearch/Hermes-Bot-Mode), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/Hermes-Bot-Mode
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 80fee22582b871b9765a65e2992b8b5a8211c9f8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 80fee22582b871b9765a65e2992b8b5a8211c9f8
│           └── chunk-001.nq.gz
├── blob
│   ├── 0311240c8b8abc43837e4c58a2b33a7af313c4a4.nq.gz
│   ├── 05cc64ea2e057bcc5d203e2c3e63877419d107fe.nq.gz
│   ├── 082738d3ad0983b96f10eecf916d4492bfa5f61e.nq.gz
│   ├── 0a4441fb48f593febc0816081c49653d90906090.nq.gz
│   ├── 159c7bf5afd79f82e2f91047a207f955422b6738.nq.gz
│   ├── 1d818ba93643e49e31ccfeb6d68c521695e76c68.nq.gz
│   ├── 20c002ea33b444ade582c7091bd54af12fa699c4.nq.gz
│   ├── 2b943e0d3f6548b8218b775f2a020b4033e2bb52.nq.gz
│   ├── 3200676dbc68bcb7b6f1b02ea542c6f088c931a9.nq.gz
│   ├── 3558677f299843271d26c5af8fbc80b860898f94.nq.gz
│   ├── 37bf5118bcd1107c84ef099fd0a5f56f2e0273fa.nq.gz
│   ├── 4301ad53e9f31db0b906c4eb73b98401bdd8c0cc.nq.gz
│   ├── 490d27f159bb5a887e45527c8603c330ae36914f.nq.gz
│   ├── 4bf4c46dcb9a705233b785ccc6eabf3b878bdcdb.nq.gz
│   ├── 4ed295b854fce8da448629ce4809bfa4d80a11e9.nq.gz
│   ├── 4f5a2c41b6a9bcc0411b80da930e56ae03bc0dd5.nq.gz
│   ├── 5700b997827973cb0eb6d84a2782bb08a5872434.nq.gz
│   ├── 5aca6dd7f1065b4778663f73a542c5cf07ac0e41.nq.gz
│   ├── 63b30b3cc028d531583a5b93f21ee080520e1520.nq.gz
│   ├── 71fa4202fb39e8df40f31b7525c5f2a8f73870d5.nq.gz
│   ├── 78921eb9e2232bae3ed1efd080b93760d724e678.nq.gz
│   ├── 79e094d81fe52244acfcd1e2c1aa21ad69f8d064.nq.gz
│   ├── 8510c557d87b04ff9f88495b5c0b30a2cd8d4e66.nq.gz
│   ├── 8d6d8d399727c7a688f127956a3ed5de06572eed.nq.gz
│   ├── 8ee211ab021f8da1a78147eede1859addf7054aa.nq.gz
│   ├── 934f5292f3ff2c7c65bb737d8436778f62f86803.nq.gz
│   ├── 9415860328b76e2127db3a494315e3dde91ae00f.nq.gz
│   ├── 984db4ef85679185387004c9f39e824d5a2992d3.nq.gz
│   ├── 9be4b6e885455c9f08913908b235e6723aebd798.nq.gz
│   ├── 9dbb8e1ba291e6d0bcfd648c2dc2ba64f99b0368.nq.gz
│   ├── a0d89bbdf2b7653f955c6bc8b78104c91df1e5d2.nq.gz
│   ├── b729520095061e166a43ccc80e667da7a67d6984.nq.gz
│   ├── b81fa7cee3a394b4a3fafdb03562c94e1a69614d.nq.gz
│   ├── bac16adc8c311ac826e1c0f80023ce9bb10eb4b7.nq.gz
│   ├── be07ef5d435826df1277ee58e4744e4fb80e7850.nq.gz
│   ├── bf9ec0459a732373824e071ad4bbe23b88f4c5ab.nq.gz
│   ├── c0ae2c07dd9746a04a613ff011c121decea923b0.nq.gz
│   ├── c27b42741032f3f385fb4df6e512526cd008e0fa.nq.gz
│   ├── c514f97ffa6e77013f55c11fc6ea2e8ae0da0dbf.nq.gz
│   ├── c6483824c82b541698e2cca7852c7071eff0608d.nq.gz
│   ├── cd89ff4942d2a384b499ca149a61050bbd77d849.nq.gz
│   ├── d521cf456e473ec0d4147dd2c8126dd26fc92e64.nq.gz
│   ├── de484a1d080949944f44a439821a5361318d1486.nq.gz
│   ├── e42ba5973eba9a32d22844c821e6223d99f75664.nq.gz
│   ├── eba9fa347604c2318d5def58f0d3f69c76a81291.nq.gz
│   ├── f9c2fc7034571d7da72d8f510f30067522d02e8b.nq.gz
│   └── f9f6c162c5e338ea1848ceab47236b5be475f2f4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 80fee22582b871b9765a65e2992b8b5a8211c9f8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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

[NousResearch/Hermes-Bot-Mode](https://github.com/NousResearch/Hermes-Bot-Mode)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
