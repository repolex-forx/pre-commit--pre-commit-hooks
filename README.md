# Repolex Knowledge Graph of pre-commit/pre-commit-hooks

RDF knowledge graph data for [pre-commit/pre-commit-hooks](https://github.com/pre-commit/pre-commit-hooks), parsed by [repolex](https://repolex.ai).

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
rlex download pre-commit/pre-commit-hooks
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2ee68084ed80421ef5a6d062cf1637825adfcb22
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2ee68084ed80421ef5a6d062cf1637825adfcb22
│           └── chunk-001.nq.gz
├── blob
│   ├── 038868d86288b5a003b8f3a8d20536e868c3eebf.nq.gz
│   ├── 058a3294830993685481feeb48bed71a1700f9ba.nq.gz
│   ├── 05d0d004cd062116ab4eee9b18dcb54be0a92131.nq.gz
│   ├── 07af277dfd8be0c7d0f04c76b5b9bc7ca01377e6.nq.gz
│   ├── 0a1c124c3a61b88e85215c060346ecee5ab5428b.nq.gz
│   ├── 0c5a37eb0adeb312718e533d0a4fbcbea6880056.nq.gz
│   ├── 100ffeac338e71c8c8e59ec001e4abe5997e85ac.nq.gz
│   ├── 108656aad58b84386efe84ce13da2e527a0c6da8.nq.gz
│   ├── 11340f4d99b77c960b85fcf2576c61139056ca5a.nq.gz
│   ├── 134f37c70bd615919dffe0eb0b95f8918fffa067.nq.gz
│   ├── 150ca8df7ca83d61c70fb8ac709f255769096fd2.nq.gz
│   ├── 1679c64058f581f92664697781807629fce109e5.nq.gz
│   ├── 2053b9a8425e6ae732fcff7d65b931a60b59e437.nq.gz
│   ├── 26d1692a4430e898fa2f084f9abb0da84f4ea6b8.nq.gz
│   ├── 2b5a0deaaf6512ca82a00265a34c9fc917edfc1e.nq.gz
│   ├── 2bbbe644f4f922388376eca631fbf656d15ad98a.nq.gz
│   ├── 2f978b76ab31f304c981cfe594087913d28aead5.nq.gz
│   ├── 2fbf067fc96bd11623a9d69b33af652e7c1031d9.nq.gz
│   ├── 324b70ce1cd20c72b68de2d8f098d3b8c0f954c2.nq.gz
│   ├── 3767076960f276e21e2b12089f87bd14ef49c02d.nq.gz
│   ├── 39c474a10fa85212c19b7665348381c29ed8f464.nq.gz
│   ├── 3b3947350d2f4f57a6dcf446e1e68197f3117416.nq.gz
│   ├── 3d93aefb2da505dba9c0114404cfaaeee5ad0d3f.nq.gz
│   ├── 3f97109be3a512da33163a0cc97533ba4a0f895f.nq.gz
│   ├── 3fdffa121e3b0e62264cdf10bc360c93537670b7.nq.gz
│   ├── 41f8bae5ea6ffcf29afdd91ad024cecd3e4470b4.nq.gz
│   ├── 42fbd15b71d227c5d7f31fc9a136c9307d97341f.nq.gz
│   ├── 4496765760fc1d9c44fc67b36533c0b2db45a225.nq.gz
│   ├── 475c91c4308e5c22f108f2280fb66d83f2a48863.nq.gz
│   ├── 4a071fc533d4fd07dbe81e1e8f0f0998b17220be.nq.gz
│   ├── 4f6c5b7ce8fe1591a3f46f2ceff0c251a1d07155.nq.gz
│   ├── 501f37f7f7a6d9384b1d81f55295d28d5d0a6c29.nq.gz
│   ├── 522925ee3ef558c3a38ebabd36f195bf94daa44b.nq.gz
│   ├── 53e1f52d8fe32198ee04fc33733eaf721dc146f6.nq.gz
│   ├── 54a083ee5e45af91a43f23f642ccece4dda7c0d4.nq.gz
│   ├── 54c4e6890c3741566dbfb11d95adf0a93538fa50.nq.gz
│   ├── 54eb16e874b6d5f69eb0ca8a1b7c8d1bf17284c8.nq.gz
│   ├── 58b1d02dcb30ed0fa48b00457499133ce1a2213b.nq.gz
│   ├── 5a8e0bb2b99871e3a0f75fe176760d677df02893.nq.gz
│   ├── 612111c531d9a1413cdc4d62def2a8fb915092c2.nq.gz
│   ├── 62083e723727a9851534966351e1e5b0ea9e1e37.nq.gz
│   ├── 624396615903b64bb6717e820de30c7b8464c4f3.nq.gz
│   ├── 64112d790dc0b583a5763895536f3084c2e52cd5.nq.gz
│   ├── 65e6b7a635b570d6c91227a41774b19e8bb78d1c.nq.gz
│   ├── 66f111152dbea964d49955f6972e97f5defb589a.nq.gz
│   ├── 68b6d7a1c8de4d40b888b9b0cfcd787188e20038.nq.gz
│   ├── 6c7fe8356658a59e175cf15f707ce01ea0374606.nq.gz
│   ├── 6cbda8577f03aaff4e1f5aae6dea9df3420fa28e.nq.gz
│   ├── 707863b32f401cc50a112f003955fcad2082b034.nq.gz
│   ├── 767619f17e642375309971cc693e75d7a3e7f533.nq.gz
│   ├── 76eb35265a74369a9e8f5572e59ea4d1ddf263b3.nq.gz
│   ├── 7d37e4907137e275c6d61829a5d43fb5e153dc6c.nq.gz
│   ├── 7e6be95ecdb05ab1bdb4a7c869f446982d7464c0.nq.gz
│   ├── 807f15b86bb939ebb40f565d264d9ae6b0ef3979.nq.gz
│   ├── 82d03e3df386f13d3942f5696a8eafdc98f84d17.nq.gz
│   ├── 82d753224e4c5d3fb5a2f4516721438bdcb146b6.nq.gz
│   ├── 8432455f62cdf03258f08570c73b523511be9838.nq.gz
│   ├── 85822886e2bdfef344d77de3cc716a4011c582af.nq.gz
│   ├── 8a4326234fd2683bbdfa57aa9a5949a04d977f9d.nq.gz
│   ├── 8a5d889ef813b3e5a2958a21f73914cc55b5dd7a.nq.gz
│   ├── 8bafae8287d3112b0dd0904ef9e75a62cef92c8f.nq.gz
│   ├── 8ce8ec643a233bffb209e3eb2c384314adb23a9a.nq.gz
│   ├── 8eb164c534235db344a1a57fa5055c2f7318f737.nq.gz
│   ├── 92473e59bf1c87fffcf4b50550baf641af7d2140.nq.gz
│   ├── 937425b0843e5f42a2d4a8dfc751470e1f6850c4.nq.gz
│   ├── 9ad703ae6a714a3f09322a270303b1d0950ff891.nq.gz
│   ├── 9bc25898aaba42f1e15bac73c3efecd74fa47824.nq.gz
│   ├── a7e797194ec3140b686c93149436215ff33e5a6c.nq.gz
│   ├── a88425c6815d0e876ed3168ca93bd1f630b531b9.nq.gz
│   ├── a914f452794be919956b5e26c18eac6362216ce0.nq.gz
│   ├── abda648a24b647803e480c06eb30b00aa31597e2.nq.gz
│   ├── ae9b1b287bfb7b81494efbcbb80911b1fc10b29c.nq.gz
│   ├── afda47a91a4a12c2bd789efd83fd58d08ac78034.nq.gz
│   ├── b03f127970884a9dfd61d67a7cabe3057560a4f0.nq.gz
│   ├── b0b8b23803222c68abbc1ea28474fe58aba73c64.nq.gz
│   ├── b16995202bb7e5881ffea27e60682cf3e0d2d2f4.nq.gz
│   ├── b7a63cd25df4a9295fa6835e2b8833fd0d0e16df.nq.gz
│   ├── bb55017f45d6305dd662b60132aa46c7ea671bf4.nq.gz
│   ├── be8a800e84969dce1e7cf3eb8cf45809f9174532.nq.gz
│   ├── c07497a2215886873b6b68dfd0e84062960d637c.nq.gz
│   ├── c0d2c65db29b1b9251b14994ddb54edb3da3d462.nq.gz
│   ├── c1f165b8d7eaead8dbd179a19045a38e4ab7abe6.nq.gz
│   ├── c94ea7168082d4e6f4e85464d48fdaa84a2fbe30.nq.gz
│   ├── cd66957831ff9b961759a5f9a513cf67db1612cf.nq.gz
│   ├── d594f81525ae7dfe4984029d2c34896864494856.nq.gz
│   ├── d6c90ae02f7b07f10232fb6d00fb6d2bf9e8784f.nq.gz
│   ├── d70eabe1773556133ff417ca268ee0f2b79f16ea.nq.gz
│   ├── d7a6599028e0a8d497fb77699947456513083677.nq.gz
│   ├── dab8b14a83b50a0d6e327d95aa84e1e4fcc9a72e.nq.gz
│   ├── de29063f2eec68565173b8ac1e6a4b237b384173.nq.gz
│   ├── dea42627ad9f5eb8061bf5068117faa3ba22591c.nq.gz
│   ├── e128eeaac65d71d13517fa0ebcff0a85fb9b3f5d.nq.gz
│   ├── e2c2c78f1fa69556b5dec9c93f59e27a674cf655.nq.gz
│   ├── e4bd07ca75c2ca4e5e4356a1ab3c561154ad9bbf.nq.gz
│   ├── e67416238d28bd20be4a0d0406a6ca87ded486da.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6edcc715ebd4d58a0b048e701b4144de734e2e1.nq.gz
│   ├── ea50c5dcf87ffe7ed87bfb27b5658fdb06647779.nq.gz
│   ├── ee26d926400f953038e0571c1c1b5cabc8e5c5d0.nq.gz
│   ├── f178ae6efda4dbdb50464de73c2a35b98a1b8708.nq.gz
│   ├── fb2b6d98c6c0823b7b03b69dfa52ee23b8bb6088.nq.gz
│   ├── fe8bf5e51d081b1a608d8ae9cf49480880a5458e.nq.gz
│   └── ff5536b5857a17cc290c40fbc7bb017ed6112d3c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2ee68084ed80421ef5a6d062cf1637825adfcb22.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 111 files
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

[pre-commit/pre-commit-hooks](https://github.com/pre-commit/pre-commit-hooks)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
