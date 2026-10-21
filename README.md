# Repolex Knowledge Graph of sanic-org/sanic-frontend

RDF knowledge graph data for [sanic-org/sanic-frontend](https://github.com/sanic-org/sanic-frontend), parsed by [repolex](https://repolex.ai).

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
rlex download sanic-org/sanic-frontend
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b66911dce63e6f9069437accce983963cca3aeba
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b66911dce63e6f9069437accce983963cca3aeba
│           └── chunk-001.nq.gz
├── blob
│   ├── 0ae01dd17c4065486d1b3115893405cc058dbce5.nq.gz
│   ├── 0c1ad7e46e7202c254fa4ed1790733db05b377ad.nq.gz
│   ├── 11ad6dcaa98811a800e6e98777072ccd7b814b28.nq.gz
│   ├── 128753a25240f7a7f61d87d2990eb35bc10126f9.nq.gz
│   ├── 143a3c83e921d85ff73250403abf59b887ce23c2.nq.gz
│   ├── 177c640ed997720a1952088d338917d8a4c83b7f.nq.gz
│   ├── 21b1c879923d7c944a71fb147ee412681a6fc118.nq.gz
│   ├── 251ae0a01fa535932f554fbf97a308afa2abd9e1.nq.gz
│   ├── 3b71ffeb0f40282f98a645beb5ad5e2dd5ebe071.nq.gz
│   ├── 3ec8d092a2bfd532fd1fa15cf53bfe1efa004cb7.nq.gz
│   ├── 45c9c7c5596e06c9696bfc181198a52befaf53d9.nq.gz
│   ├── 4df538343e268806176614709be956a8197072b0.nq.gz
│   ├── 5276de07bd974671971a9e6284ed488915d99638.nq.gz
│   ├── 56cc77ea685828932d5415d317549b9b0758143b.nq.gz
│   ├── 57e6796e8ef16474a2cf6fb8793d313b181e68d6.nq.gz
│   ├── 5a2ce0079983d9aebf47d42196330713591d1c30.nq.gz
│   ├── 698429ecae3d530bfd7b7b133f6e9733a254b4b7.nq.gz
│   ├── 6e907d28ef58d0c2d2eaad9610b6f292c1f24499.nq.gz
│   ├── 7e97f2541ec53ae2de9023a5d06d0d4bc7b38451.nq.gz
│   ├── 845b5d6214b6a9f723875d2b40f235ef55fb5443.nq.gz
│   ├── 85ff8ef6981db9aaf809eeb6b971ea62c7555301.nq.gz
│   ├── 8c15281146f9a4661ad8c4d968e20066da034004.nq.gz
│   ├── 96348b0ab2b5c340c8b7dede1e8d49074c446f77.nq.gz
│   ├── 98b8ecaa7031dae60824901e9b1b4690aaa30068.nq.gz
│   ├── 995d8b2ed3dfa2ae6e9ae98e3fc07967f3d11ef6.nq.gz
│   ├── 997d9bc9f4c46cbe5df4c0493313324f54893c34.nq.gz
│   ├── 9d39cd88e540b0146b32b4bd1cca112efa1999e3.nq.gz
│   ├── 9fb908a35e12722007c2b09e2fab48bf0766a9a2.nq.gz
│   ├── a44ff2765c524ef7fecbf8785d634795d58f904c.nq.gz
│   ├── a59b6fd2be3c54b56841bd8af9fe7901203f748d.nq.gz
│   ├── a68b90f5c44677578e46857c38983c2e16f734d7.nq.gz
│   ├── a93c3f8f46de9f43d0d11db5a6619ccc706a3062.nq.gz
│   ├── ac5f81517935e37adad8b70bc18db237644b7956.nq.gz
│   ├── aed5a616e0c8060f8ce99f3a2d08301ffaa79bf4.nq.gz
│   ├── af1280dc45cad80ddc23ae075f7763f15bcdf3aa.nq.gz
│   ├── b3a022206fd5069e03a0cffcf96f85446ad463ad.nq.gz
│   ├── bc9f8c357248e41ed13bebde963662868f288c85.nq.gz
│   ├── c0ba7b59af12dac274d948eb67d55bd0c3b8f149.nq.gz
│   ├── ce4d818d49368e41ef8fd32603ce7bd5f348e7c4.nq.gz
│   ├── d2e30d5f1209227090d2e66e59aab9745bfc0198.nq.gz
│   ├── d8fe8d5a00bed2eba89080602964174ac74bcf4f.nq.gz
│   ├── da7aa691148dfaa470bfa9cee772d445fc50658e.nq.gz
│   ├── dac4581f27ab7e11900226a966fb52844971f085.nq.gz
│   ├── e43eda56bdf19f80e3b4150f83ae70ddc661261e.nq.gz
│   ├── e4d62e6c0e23010995ce568fac90375e54cf5f1c.nq.gz
│   ├── eada720a6776e2e218b84e5c7af6904402ce36b1.nq.gz
│   ├── ed8e11c27e845c04c51aafca9ce00e9f9547ed06.nq.gz
│   ├── edfee2aeabb4071dba45561d2080381b2a2c413f.nq.gz
│   ├── f53a7a93a4d7b38392a84d406248857a8110d2ee.nq.gz
│   ├── f81d0f77a8bd1c07bc3dfdcb29a3f408033edf42.nq.gz
│   ├── f9af6627d2a609df6df78da2037f5e50d4753b21.nq.gz
│   └── fbcffc98ea12fca29129eb3c5786718b95824ba9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b66911dce63e6f9069437accce983963cca3aeba.nq.gz
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

[sanic-org/sanic-frontend](https://github.com/sanic-org/sanic-frontend)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
