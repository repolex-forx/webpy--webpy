# Repolex Knowledge Graph of webpy/webpy

RDF knowledge graph data for [webpy/webpy](https://github.com/webpy/webpy), parsed by [repolex](https://repolex.ai).

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
rlex download webpy/webpy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 470d1f512f02c9f6728271e7693eedfa4ee61def
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 470d1f512f02c9f6728271e7693eedfa4ee61def
│           └── chunk-001.nq.gz
├── blob
│   ├── 00eb8f1f6817869c8083c701ec4797325267c17a.nq.gz
│   ├── 09fbfd25ceb21a1a5f3ff14079e18611b02ffa04.nq.gz
│   ├── 131e7a59deaab6c0488e1a3015c662dc53641d35.nq.gz
│   ├── 15e494ec867ee8f53798bf062eca0e9bf9d8edd4.nq.gz
│   ├── 19574cf251e0c691e7207d131b22bcab451b9c0d.nq.gz
│   ├── 1e9d58399e00ae2a7a9996c40eed67f51e995005.nq.gz
│   ├── 225261d73103f36e87607e9c6e4fcae6ea9294b6.nq.gz
│   ├── 26716c515fdc84e881149bafbf09022d7b047bf5.nq.gz
│   ├── 2c49378ea360752c9cc0dc3dd1c1fc88cec4310e.nq.gz
│   ├── 394a7444a9e8b58b73f9afaf2cfe385387f37e92.nq.gz
│   ├── 3d59c424b83bbbe83e7a45e99fd025d425eb55f0.nq.gz
│   ├── 44b2cf921c761fc2748ef2b87c40f941a330b4fa.nq.gz
│   ├── 4616e43d6f7db2e045bce1f5d01a04aeb25458f5.nq.gz
│   ├── 46d6ca675167c3f625d48cdc3f3f1121291a227f.nq.gz
│   ├── 49e3496c739c00912c4e3e12d3f1ede679eda6fc.nq.gz
│   ├── 4cfe27738c60a025ca38ac96c5df6c0615932360.nq.gz
│   ├── 4f734acd8b1bd4d86b70ff278c2005f7afeb6807.nq.gz
│   ├── 54cabdc33157db8c1882fe9578a8d09d728b7162.nq.gz
│   ├── 5905ccde04194b3d74a1c5c5c75814f7933768ce.nq.gz
│   ├── 6cf20cea00334fc940637762a68bda755029cd30.nq.gz
│   ├── 6f10c32609fec09cfaeb4057ce8a102f63499eef.nq.gz
│   ├── 700d2df061f1fef8a0ec262c775da2ef96a6d8c6.nq.gz
│   ├── 7587646ebcedbf84d0b6343821996f40dc416a16.nq.gz
│   ├── 79737c70dbeaff4a481ecdd688bdf25548f0bb7c.nq.gz
│   ├── 79f9ec1beaafdd2b2c02e19e8177d3958c0e1a71.nq.gz
│   ├── 7e6f74d43135a1fbb653d31039c81748b21f959d.nq.gz
│   ├── 7ffb3cfbe673d531cc7d1340007f4f4235582aff.nq.gz
│   ├── 8248d21f1760d225849401f25d634e3a49d16769.nq.gz
│   ├── 8d4fc0c724019bd86acf872a7ceaea6d5c8e8baf.nq.gz
│   ├── 9a5b8575ddeebc1c7521e9f295ff55766352def5.nq.gz
│   ├── a1f61c03c81eff636f68d6808fb763fb009852ce.nq.gz
│   ├── ad99a88959bb078c978ef78ac2ba9488dcef29dd.nq.gz
│   ├── b0826490505e64905f6984a4448504d6c7383abf.nq.gz
│   ├── b1505e6a61a869a4166168f7249369e345daa335.nq.gz
│   ├── b7cbb94f57256db1b3bcaba38330ebf66f7c8138.nq.gz
│   ├── ba2fa501c73911b47ebc60dff8fa147b0150a395.nq.gz
│   ├── bc7892a431129e298204b4c3d987d1d781bc1c77.nq.gz
│   ├── bde525a3092b6e0b32e582d4aa12613c08086a21.nq.gz
│   ├── be33a9dc4ab94695224f2b24927cd8ac2c0d2901.nq.gz
│   ├── bfc8259bcc886fd12ad3aa6a172e91102a6c03c6.nq.gz
│   ├── c301092bf8710632acd4b4ee2680eebdaf5bb9b8.nq.gz
│   ├── c9bf88bc090ce6c25d37f1f3197c25465cdfe15d.nq.gz
│   ├── ce6c7cc969bab7504bdf6af706dfd50683550d95.nq.gz
│   ├── d27ba837e201328e7dc39767476b396e54dd710b.nq.gz
│   ├── d465c699f8498ce1e9fe760c7b9d054e9b66cda5.nq.gz
│   ├── df1cff0babb00bad6a3607c258f493788f4b1d5f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e869bb919ba92844800a2d34d567aa533d87684b.nq.gz
│   ├── ef42b5bea166c7fd36deb65bed0755ee37383df2.nq.gz
│   ├── efb352ddd772b3c0d921c2c2c65e4fc3840485ad.nq.gz
│   ├── f23ec02e87d78061b6590ec30049731ca922f670.nq.gz
│   └── f8f9c342180a028549f6d6c3a1980d736c07dadc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 470d1f512f02c9f6728271e7693eedfa4ee61def.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 60 files
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

[webpy/webpy](https://github.com/webpy/webpy)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
