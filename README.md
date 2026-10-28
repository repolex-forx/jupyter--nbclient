# Repolex Knowledge Graph of jupyter/nbclient

RDF knowledge graph data for [jupyter/nbclient](https://github.com/jupyter/nbclient), parsed by [repolex](https://repolex.ai).

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
rlex download jupyter/nbclient
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0811ff44c63c9853c4d6ba7265d7042ca7f8742a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0811ff44c63c9853c4d6ba7265d7042ca7f8742a
│           └── chunk-001.nq.gz
├── blob
│   ├── 0325f52deee4ed4da5a0af0b786ab51660ff232c.nq.gz
│   ├── 0cd1236bca6ade79663fb2598be8d193744916d2.nq.gz
│   ├── 11e7a8ee0755e6b98c36c4edfd5280ec6bd50aca.nq.gz
│   ├── 1350f38806a4623902a0e7bd10d10aeacb4bee83.nq.gz
│   ├── 14b35c5dbaec73e5066d20471b588151aea3340b.nq.gz
│   ├── 15763af239f40472583927158aff7bb5cfd080a2.nq.gz
│   ├── 18104e0eb4bf1feb7aceba12276f40f4bd3a2fe5.nq.gz
│   ├── 1ad0da5ba1d619c071547397203909ad6dee9332.nq.gz
│   ├── 202dc194c8850182abd6b9245f3babddbe25609f.nq.gz
│   ├── 21bfa792861eebb8d8c54c61a6c48ed7b52c1fd1.nq.gz
│   ├── 21df7db603324d1e66214ff6b708f0d05dd94cce.nq.gz
│   ├── 30c13d78450feebfb71d164fdf2966446848e94f.nq.gz
│   ├── 31cd808b6eb4c5fa8f45891d4665074bb05d1270.nq.gz
│   ├── 342acfb3c823a13bb82c4b95bc023499a87a0f13.nq.gz
│   ├── 3a31cf3c45e1d852c0003a310e0f9c5fdd3e2333.nq.gz
│   ├── 3c4b489395eb6d5f5d200650c4bfb04338b6c27a.nq.gz
│   ├── 4054c4d46a2d67555ade73c4c3a6535f7120ea5f.nq.gz
│   ├── 48c91ebc2b603f050361bb9508f0c2d7c009c24e.nq.gz
│   ├── 4cb2edf76f794feefc34748376501a8f3d58a909.nq.gz
│   ├── 53738716bdaec9fda691f3a63ac3ff73c56cd459.nq.gz
│   ├── 5b015bb39435183a353844f28e4aabe6182fb11b.nq.gz
│   ├── 6424ee4517a2ad6eca41940bfe6b7ff272f08713.nq.gz
│   ├── 6464da1e7989a5cae08b15d989143544974eeb39.nq.gz
│   ├── 64f77d90d130f9f76e2ed130fc9df8a925b3c539.nq.gz
│   ├── 66856e39004a3e98dbff8366fe62796167b53021.nq.gz
│   ├── 68390073f8762d80ada83fe7f7c327039f8649c2.nq.gz
│   ├── 6e5d7867e51ac28fcd9d6e74e97bb546d8dacab0.nq.gz
│   ├── 6f7b722d515a2439f0de794df1325a1fbc9019e4.nq.gz
│   ├── 703ae1494ac66a10d56839cfd3cf442976ba4846.nq.gz
│   ├── 7706b98eb4ce5b0f5952fdbd6b5ee45785bdd67f.nq.gz
│   ├── 796572e857827226e7dc7ca0ad72ecdb75565a0a.nq.gz
│   ├── 7bfd7e965b83bf79f70bb1d8e70e06859c546447.nq.gz
│   ├── 7ea558987b489220c0d8189e845809a79e365013.nq.gz
│   ├── 8dbf29f256922fe53960d6c13badf05142ebae3f.nq.gz
│   ├── 92212540ce7672ad420f8468c857626e1ac5c452.nq.gz
│   ├── 935630785fdc8b27dd54a7c42a270e39f0896bff.nq.gz
│   ├── 9b5543d3c791d7e2d203b9ae48d4643ecbdd4a0a.nq.gz
│   ├── 9b9f7eb7125285d0bf953840c682541b31625bb3.nq.gz
│   ├── 9fa56fea29e319fc7b39eaae5333f6786d0d8f52.nq.gz
│   ├── aaa4ab1402e7f83efc4dd73ca50767940555c29e.nq.gz
│   ├── ab4f8a5ecc48497a1ac754c6196375a58654e0e0.nq.gz
│   ├── ad2f3383bb8bbc714c0fc89e5ca6a3e33bea42ec.nq.gz
│   ├── adab3887b6e3f19fea99c69f4496e9cb7d38bb34.nq.gz
│   ├── afff18e1c89cce105539ee364e11fc7066fdf172.nq.gz
│   ├── b17da6a3a7be521ceba9b16338070e9841f4bf1d.nq.gz
│   ├── b1e6afded2d595fe330ecff9b4810c6e09b0a00b.nq.gz
│   ├── b26e49e4a9d893e1abd84813a78959883eab82d5.nq.gz
│   ├── b45391089f521ea6213817afa3b0a5d1bed79a95.nq.gz
│   ├── b9506b085d3408dbc67612bde82e66fc5de1fa6a.nq.gz
│   ├── c35447c00189988b3001a21a922cb20ff9397ca5.nq.gz
│   ├── c56d4c022a7130beed2ee67d7fff7274aff5de1e.nq.gz
│   ├── c63883c94245ef2f7aa3b5fa0a8e91cb54da68b1.nq.gz
│   ├── c8f46d25e000e9049388f363c713f2c8841aa6b3.nq.gz
│   ├── cbc374a5e159fe30532d815f595bf9f858c7c712.nq.gz
│   ├── cc896b87842287b0535fd49027aa0871d58d943d.nq.gz
│   ├── cf32f498ae3495e22d7430387c430284a9eace2b.nq.gz
│   ├── dda2e28053a6df485823f0860b86a990c21e66b4.nq.gz
│   ├── dfbb4c24a3e0204a47244e141f3ec7547f270991.nq.gz
│   ├── e19695a0f06c72493678e9dafa977b3429ac8832.nq.gz
│   ├── e393f939d2607f19437fba9fb1b25c7d74ebfa94.nq.gz
│   ├── e57440871dfb0ae4f2150b0152f002ba2db7304e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ebe2144297d05a83cc410341edfea3174f58c7d4.nq.gz
│   ├── f19854548dcf34915c6a9a75b5d7ed418d8db3b4.nq.gz
│   ├── f5173b982dc2402b9485873424f247f125d1dd9e.nq.gz
│   ├── f52bffc538d6e26bfff74f6d4e73b1883303e725.nq.gz
│   ├── f60361c03a22c0695071f62e674f938cd8ce6fa9.nq.gz
│   ├── fbc9ce38e7fdc53acfcc489ea9eec82417d06d99.nq.gz
│   ├── fdb44d10cca25b8c33a5f66633be7cb6e96bb9cf.nq.gz
│   └── ff5a7779d318c1803b3aa430ff195d2c93d86755.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0811ff44c63c9853c4d6ba7265d7042ca7f8742a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 78 files
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

[jupyter/nbclient](https://github.com/jupyter/nbclient)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
