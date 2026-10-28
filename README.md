# Repolex Knowledge Graph of explosion/spacy-experimental

RDF knowledge graph data for [explosion/spacy-experimental](https://github.com/explosion/spacy-experimental), parsed by [repolex](https://repolex.ai).

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
rlex download explosion/spacy-experimental
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 66c4be536d4e69b8f6366ceb2c0ebb39079d2c89
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 66c4be536d4e69b8f6366ceb2c0ebb39079d2c89
│           └── chunk-001.nq.gz
├── blob
│   ├── 03a908c7d4908eddd4e3e08420ecf810fa43097e.nq.gz
│   ├── 09009cdbdad6280f7483324ed74b6f34caf7f4a2.nq.gz
│   ├── 0a319bbc65f9bcd4041401dc60c65954094505e9.nq.gz
│   ├── 0b50c79b0b87f903c65edab749ffb26aae1985eb.nq.gz
│   ├── 10621c208fd2f0c514e40e2352e0cafec8ca5eff.nq.gz
│   ├── 109c62c38c1b1c806e36de59e4a8d1787c09a610.nq.gz
│   ├── 1411a4a0b5ab886adfb744e685d150151ab10023.nq.gz
│   ├── 169a5829f47180cd97408930de337fea075c0f69.nq.gz
│   ├── 1d361abf2d1a3e1d45088a15019e4289bda16053.nq.gz
│   ├── 20c7a2fbb7babb47097e039ddcca8fc5f5f38d22.nq.gz
│   ├── 2121b583b626f0bbbb1a1873f8b6bc472112288f.nq.gz
│   ├── 2240e1b37f3452ccdfd72873281cbcb1c0c24bc8.nq.gz
│   ├── 224b0d0d079377385021f7c4c0d43cc1256fca6c.nq.gz
│   ├── 23ebfb47cd7f1390ceae39f1d91972ff76717e70.nq.gz
│   ├── 278d4dbd2edf45359da16c783289819c12dd029a.nq.gz
│   ├── 2942d1b7dbafb7492381a9061cbb127816420b9d.nq.gz
│   ├── 3039c9eddeee2a4caeabe0feeeed2d79116157b1.nq.gz
│   ├── 31caf9a13c29deacaf4b02f9c0750ae65469b135.nq.gz
│   ├── 32d60f0ff1c4def75afa176c2664381ce5954725.nq.gz
│   ├── 3c9db7c5d4abb51065278a7ab1183a7db676761d.nq.gz
│   ├── 3ccf0da4f5f72a658460616469077c4ed83004da.nq.gz
│   ├── 424fb2ca88f000b52ee1f3f9bcf86bcc0ab6c971.nq.gz
│   ├── 459bd18514835b307624f5f57db86c218d7cadd4.nq.gz
│   ├── 45b863bdc9f5a6354c18f0e0b7bb0efca9fc12af.nq.gz
│   ├── 47fe9f1a175fe08b391783d5995a12c9ba5d3cf3.nq.gz
│   ├── 4bc6c937453f536d90f8640a3940e851a5d69451.nq.gz
│   ├── 4c1d0649471deed5d94cbe37bf8c476974959df5.nq.gz
│   ├── 4cf1c0da7f6450eeef2ba98549cf21c8f626cbc6.nq.gz
│   ├── 5540d634d69b8f1781f37434dc5e4ffc461f31b0.nq.gz
│   ├── 560217377f49ce62b73dacaf66c8e35db29ea14c.nq.gz
│   ├── 5a36f827d86687f89a9326802c2c5a1d1867fff9.nq.gz
│   ├── 5a38e2f8417fddfc3e66559594bc01fe9702f030.nq.gz
│   ├── 5ef0b5f1ae46ac58e7185ec7ee5d9c88dffdea5e.nq.gz
│   ├── 60036a4756eb715c379a2af29650aa6d9932548e.nq.gz
│   ├── 662c59857d20d32d34db4efd3fc75cd74e7b1fa6.nq.gz
│   ├── 67730e40d1ebb22ed4e50590c1eb57fd4a6fbe9e.nq.gz
│   ├── 6af7ff59bf79c91dbe4ca4e3bd5ff7b560cc81b4.nq.gz
│   ├── 6bcada424a596ff8da111f69a5f97dbe57c2a9aa.nq.gz
│   ├── 706732a778f781f9c90b6a7063b8a63d95fadab2.nq.gz
│   ├── 71ac358d7b9dbedcc1ff9ad50ebaaa6657c732a3.nq.gz
│   ├── 7499726444c252a34e83719883fb45ac8792c2b2.nq.gz
│   ├── 7e02176128a2accfd121b9e4fe3282d3056b2da2.nq.gz
│   ├── 7ea8a2b034150dfb8e175b5baf4344b938d14e61.nq.gz
│   ├── 84b4b2d0d086896b4f6454f1e6594aa501f77193.nq.gz
│   ├── 86d1718432df93b27accf416f1d8ff91a78e9d9e.nq.gz
│   ├── 875fa1bce49eda91c8f368eceba052c2666a8acc.nq.gz
│   ├── 8bdf56793ae59f5380280151a6bdb962f87f4924.nq.gz
│   ├── 97196f2dcf51c81550a0cf00706d65d95ec5cdf8.nq.gz
│   ├── 9b2bc23f290c89a86e0e4a9b4ba89651e29a105a.nq.gz
│   ├── 9bda722241c132be04fd4ae8df256fda3d896ba5.nq.gz
│   ├── a276a1dcba74de3c4fe379a9a9e56266d6d7fd7e.nq.gz
│   ├── a81c8ee121952cf06bfaf9ff9988edd8cded763c.nq.gz
│   ├── ae00d82cce477a2e1a6e23e9d882c9096e7d1d8d.nq.gz
│   ├── b5be34b76e715ef599ac001f5ee5e42014a71564.nq.gz
│   ├── b6b695989b50e643e76894ac389ee5fcf89f6e76.nq.gz
│   ├── b7e03d59e2dd8d3d3657c97ef8d39a0eb6822f83.nq.gz
│   ├── baf01f5891914adeef200fd254516016e09343ba.nq.gz
│   ├── c5ba801403cf3f8d490f81706b694e7adeb5b067.nq.gz
│   ├── c81490e92765cda1af293917bd03974744f7a92c.nq.gz
│   ├── ca30ae291d9c1296fa103e3a7cb13eee5e661fcc.nq.gz
│   ├── cc2ffdbb1448b3a9b9af8c91a6fc5bc35ccc3f30.nq.gz
│   ├── ceda1469c58415f1bf079368c02cd7e34e39e5da.nq.gz
│   ├── d1a7825113dae35634c892ae070510778ae64bd6.nq.gz
│   ├── d38b7b0f0614e78a7ea09f71b2379e6ba9241714.nq.gz
│   ├── dbf4dcee9d995cd681f0aff71acb42690e21d85f.nq.gz
│   ├── def34298fdbd78fa646e60188efa3b4b97c1fc45.nq.gz
│   ├── dfaeea877a2829a6970cead7c7468f0ac972d005.nq.gz
│   ├── e3eafa84eb5dbb8998585350871848869aafde61.nq.gz
│   ├── e400399527372a4d63f0bcb5ee9488db7495223b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea0aa931eb5c6697c06682ead1cc488dbf609f7a.nq.gz
│   ├── f1cfaf5b84e52cef1f0148b9efc632b4d4ca4f5c.nq.gz
│   ├── f7d9a650e750ab69a2a702e0455623122bce47fd.nq.gz
│   └── ff395f97f8edd755ec076607187b4ff3e71ae3b5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 66c4be536d4e69b8f6366ceb2c0ebb39079d2c89.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 81 files
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

[explosion/spacy-experimental](https://github.com/explosion/spacy-experimental)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
