# Repolex Knowledge Graph of google-deepmind/spriteworld

RDF knowledge graph data for [google-deepmind/spriteworld](https://github.com/google-deepmind/spriteworld), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/spriteworld
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ace9e186ee9a819e8f4de070bd11cf27e2265b63
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ace9e186ee9a819e8f4de070bd11cf27e2265b63
│           └── chunk-001.nq.gz
├── blob
│   ├── 199f9d51ed53076a8240a43ab8a5ce6736d71ea6.nq.gz
│   ├── 1a88f697047fd96b5b494eefdeb7b50873e39278.nq.gz
│   ├── 1e65f5154125fdca84d93a545ab9d3667d62181b.nq.gz
│   ├── 20cb483d3ce7457df228d8ad3fdb26712e671e6d.nq.gz
│   ├── 22fb425ee3f0e07d1e40f74ea55777ea8b2e06ad.nq.gz
│   ├── 29757bf938c83dfc25dbb5e72a9cd541cfe20be3.nq.gz
│   ├── 29a29e68df72b66956665e4cea8395245298fb5e.nq.gz
│   ├── 38d4cb23e2004f99d27153e674b122c610bcb464.nq.gz
│   ├── 3b5c12523d1a47e5408c85e57e14a7ed33671f51.nq.gz
│   ├── 490fe21cb0ee496dcd09673bfe6f4bf88e4bd31f.nq.gz
│   ├── 4cc3e5cc5771339871dba51a06cd61f62073082e.nq.gz
│   ├── 584ce631c4fe34f6ea624ae15bd8ae76c69cb8bb.nq.gz
│   ├── 5e5ede71ea1b3988c4c64c6d0922132b6792b861.nq.gz
│   ├── 5fd320567535195a8beaceaa2859f80bc5e21a53.nq.gz
│   ├── 618ef95ac109bb98319f081f84b42b6ec011414f.nq.gz
│   ├── 68fa33b08b3b5bfadd99e0bcfaf3c56539b1bd36.nq.gz
│   ├── 6a2551e27d039170bcfdb2cf81ce515e3906daa5.nq.gz
│   ├── 856dc8147d108144f25b35f2da0ad0bd1ff67e85.nq.gz
│   ├── 8df55c265cc14acb4c11093e6f6fa4e3513dbea1.nq.gz
│   ├── 8f9b348f90c578606ccf8d2e579b9864714b7f13.nq.gz
│   ├── 973bf34b814d32d2770a70edf076cbd397a8a58b.nq.gz
│   ├── 9d8206ee659268b257c65b883df084280058fe11.nq.gz
│   ├── a3c30a21b9322e0692e513b5286225273d62baf1.nq.gz
│   ├── aa91485898f2516078f010ae2d88d1895c9e216a.nq.gz
│   ├── abf67a7cff6cbbd8e1e033d8cc992aba1e7e5391.nq.gz
│   ├── af6d720ff5d92c1ce37c16373cf91dba5c9f235b.nq.gz
│   ├── b10d565acb6780d5fe0b472544e0cf2d9fe6e981.nq.gz
│   ├── b942bd97a5455d83552e85eadffc1e43975c87b2.nq.gz
│   ├── bab7fb67a02d7ddb4c077bc6243a78a770d0a35b.nq.gz
│   ├── bc1f6120fbc19ab9eb2e2e98b08034189e28c69c.nq.gz
│   ├── bdfcbcf91632c3541f06d952c2b400a3c327f689.nq.gz
│   ├── c0061ceb35e3e195b9d718321d421baa671ed709.nq.gz
│   ├── c825ec4ddf6419f483f186f57b236f494af1e9d9.nq.gz
│   ├── cc67921fec087bef8762d005b704ce17ee8c9714.nq.gz
│   ├── d0cfdb96ce34268581d5290a2b267215a7bcccfa.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d716ea5575e69ec0f0333f54659e01dbf247f9d9.nq.gz
│   ├── db177d4ac70f76c2172ce65ca33c830d6cbd3ac5.nq.gz
│   ├── db66c95e57e311d3a9a578d327bc210d46c0a13c.nq.gz
│   ├── dd0a01c3531d43b51f7b87b3db4697847c749fab.nq.gz
│   ├── dd2004bac4c663183ebe8166bb96d09748ca3af0.nq.gz
│   ├── e08c9474ffb414f933def2b94d953e7b87605880.nq.gz
│   ├── e0c1dbf06c9eb199513e314744732824dc04d469.nq.gz
│   ├── e2970108c5653fb7a88ca4ffffb2119f25f1f5d2.nq.gz
│   ├── f04b42343d3846d623a185057bbb251651f5e421.nq.gz
│   ├── f255832d2c0effed18e3aa107d41e03b15f0dc74.nq.gz
│   ├── f6b80380be548ba104b9933d24520745a41b8584.nq.gz
│   └── f86250e1f99584e7cd6d63a04897a18c809f282a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ace9e186ee9a819e8f4de070bd11cf27e2265b63.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 56 files
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

[google-deepmind/spriteworld](https://github.com/google-deepmind/spriteworld)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
