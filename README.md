# Repolex Knowledge Graph of UKPLab/arxiv2026-hierarchical-latent-structures

RDF knowledge graph data for [UKPLab/arxiv2026-hierarchical-latent-structures](https://github.com/UKPLab/arxiv2026-hierarchical-latent-structures), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/arxiv2026-hierarchical-latent-structures
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ce7bc085f951685061b41a85fe5550c8df85dc23
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ce7bc085f951685061b41a85fe5550c8df85dc23
│           └── chunk-001.nq.gz
├── blob
│   ├── 09715c389fb85a8cb5cce6a0b5a763247251a144.nq.gz
│   ├── 0c7d87c302c0edeea57abdc8edff345f148f5951.nq.gz
│   ├── 103c89313bd5d3677289b6659c81fd0a39253bbd.nq.gz
│   ├── 1062d85b005f3c7be2a618c4699df2a5d69adb65.nq.gz
│   ├── 12a66feeea0030ddb6b99b5374922e36b27b989f.nq.gz
│   ├── 15562f03354f7da2fea0df929098217414c4b7a2.nq.gz
│   ├── 15b637097e467e64592f80474d82afa97ad33211.nq.gz
│   ├── 176ec03b8cf358afa4318b4ad18171f702ec0bdf.nq.gz
│   ├── 1d072059e0ede0b7be0fb111238d13eb777d0687.nq.gz
│   ├── 1debf4e131ba789fc490ac2701117f6435f98b01.nq.gz
│   ├── 1e7193907de3ef303a87e678702166df8316fe1d.nq.gz
│   ├── 1f4561b09228d73af4d93c6b551d220fba9976c8.nq.gz
│   ├── 2a0dfdd2e97b5af1d5b3949924237ad2b422deab.nq.gz
│   ├── 3005a86b994b130e9348803d691f5b4996cafa82.nq.gz
│   ├── 3118da81190e5df401b8deffa577d62793eb3e71.nq.gz
│   ├── 34eff7674e7ef171807877affa269d48d17e46e7.nq.gz
│   ├── 38182c615d2ebddf998849e20b829acfd4197ecf.nq.gz
│   ├── 3bd4bea3b42342f43e3db95b4f0f9efeeba8f338.nq.gz
│   ├── 425942eef20627a4c9825f6788f060c891e2421d.nq.gz
│   ├── 4494df4e3e293447567838b384a15b7932d48105.nq.gz
│   ├── 53d479589e151db68ab6e295682bf9e35e93d568.nq.gz
│   ├── 5475613fc2914a915c08206e2b60a3a59d6f1cad.nq.gz
│   ├── 569d89cd08b35e2eb3b0edb9186b6c0539e4c53b.nq.gz
│   ├── 57a5dca25ed9a27a7b255f20b06a03c5877f019e.nq.gz
│   ├── 5af90cb674613f19bd5bd4fc27544638c196329c.nq.gz
│   ├── 5c3834e59094ed9e036ac539e4b66e913ea190d6.nq.gz
│   ├── 65c3df0fc27b5afbeabc252452ecb2b6333a3363.nq.gz
│   ├── 69a4d39178802d8c9559dfbe17a0649a4033197e.nq.gz
│   ├── 72e48342c56a99c7fdc0a622dcd17fb8ee9411ec.nq.gz
│   ├── 732a11bab01b1cfae8038d1a1de059c94330b307.nq.gz
│   ├── 73f59d59c863db53dfc2a7be0d6ddf22fc161b35.nq.gz
│   ├── 744fcf2f7e407df32cae5d218ea29c24dbc7e760.nq.gz
│   ├── 78dc289ec62830fd99211242cc6e25b8bb427479.nq.gz
│   ├── 7a0b84077fcb42a5fa4284d3dacd4e1ca85699a2.nq.gz
│   ├── 84a213062dff1a83abe732ca89a1488cf295f5c4.nq.gz
│   ├── 862256dfa3e734b3d8765f5cf7c60a6adab28787.nq.gz
│   ├── 8722da8dec41da1fac4ab215486b20830da50a9d.nq.gz
│   ├── 91ae6f628e7152c8dede2cff700d4bca9d36708b.nq.gz
│   ├── 92441e5b9d9a3d13217d4fa1128fc3a8a127bb2c.nq.gz
│   ├── a25556a9b57fc2239a7ef8b03b238e59d8deb25b.nq.gz
│   ├── a275698d50c834fa930dc02c0f89d2a3a4fd1ff7.nq.gz
│   ├── a6f1d48f32b06bcba529fe9f52bdbeff9fd6f262.nq.gz
│   ├── a8b791c218fff55c0308e08e4ff4dfe8a4f31176.nq.gz
│   ├── a8d6775abfe3e3aac745cfa3e68426eefb7e2fd1.nq.gz
│   ├── b5ebef9e67c92a2e33cc2f8692334608f8151eae.nq.gz
│   ├── bad009b190f9cacae99ea7d11e6057d29d72c2e1.nq.gz
│   ├── bfabdb814095b7ec6d72131f5b1a877b524366a4.nq.gz
│   ├── c31b393654b715465a1d39990bd82473ba3a0044.nq.gz
│   ├── c6252828ed37738fed5ab9d605064a20779fda6d.nq.gz
│   ├── cda76bd6d85c537409a0d43aa629e1b0da1d54c8.nq.gz
│   ├── d29cb826c6b6c2adc5d5871462ae80fda3b3c413.nq.gz
│   ├── d41e2cc40bc12235e6bdfef655c9488463c8a06a.nq.gz
│   ├── d4f41098066c01c3ec56e079c9f69932b73cb58e.nq.gz
│   ├── d5135e984fe1d468c78f32070c26bf7f6c013e95.nq.gz
│   ├── e50a0b56c32933d368b42ddf6cc4e546e4784cde.nq.gz
│   ├── ea6d05ea8f9d193059c6b06318dbcc5229e7b33a.nq.gz
│   ├── eb7f0f6dd74a106b8fbd88970453a09fa4b43a8b.nq.gz
│   ├── ed6156e623ca3598b610b728a0a3549e4e92904f.nq.gz
│   ├── f1f87f8d29f83a48538bd9c7715c94d786bbd590.nq.gz
│   ├── f6bfb6cbe69412803e73e5ae47bd416b88020a90.nq.gz
│   ├── fa1c77de4141ff9acb30c46461f9d623870ca384.nq.gz
│   ├── fa8fe4baddaf0bff290f918e47ec61c40140d9f4.nq.gz
│   └── ff8a59548ae3a6a757d76dfc21df97a0b3449568.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ce7bc085f951685061b41a85fe5550c8df85dc23.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 70 files
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

[UKPLab/arxiv2026-hierarchical-latent-structures](https://github.com/UKPLab/arxiv2026-hierarchical-latent-structures)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
