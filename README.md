# Repolex Knowledge Graph of tortoise/django-tortoise-objects

RDF knowledge graph data for [tortoise/django-tortoise-objects](https://github.com/tortoise/django-tortoise-objects), parsed by [repolex](https://repolex.ai).

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
rlex download tortoise/django-tortoise-objects
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8d47497fed442ad01c3d4cb85e681f88fb740b87
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8d47497fed442ad01c3d4cb85e681f88fb740b87
│           └── chunk-001.nq.gz
├── blob
│   ├── 082b69e639800acbd0287fb8438a706bff6a6d60.nq.gz
│   ├── 085b003937301e2024c2980439e1391e9febcb61.nq.gz
│   ├── 0a41077e0df0ff5372fca35a6d7f53b55cbaec29.nq.gz
│   ├── 0a5c92897bbdfa60d842cbc4509c14526e914c6e.nq.gz
│   ├── 0c1877f7a500c574689d53dfcaa703d985b96666.nq.gz
│   ├── 0ea3b49ab94e91bc770091204f6566f8fd3050e9.nq.gz
│   ├── 0f38dcfda9c06a777783106bc849e519db4c3ee3.nq.gz
│   ├── 13fdea5baa8df01f2a5eb2a8ed0c5c4124d5ff7c.nq.gz
│   ├── 1b6e9611f64c63d70e9c5190fcb2e077a92dc65e.nq.gz
│   ├── 1c3eedd93d34575663bdaa8bc7c706144a570013.nq.gz
│   ├── 1fcffb46fc998a992bc6c1a59454f45c01a41002.nq.gz
│   ├── 2817546543a8e843cb1a6b3527e464e0e3a00b3d.nq.gz
│   ├── 28f789906a0d0abb491664b57dc6e786550452cd.nq.gz
│   ├── 29314c263f0c1793adfb52d586dbd0d1426b8441.nq.gz
│   ├── 2b19b3a46f65bd9ceb0147e22530b18cdf50bb42.nq.gz
│   ├── 3586192b069d649ffc0744b5c1240c14e28f216e.nq.gz
│   ├── 43bcfd826362edb3a915be71e4bba65d6f03066c.nq.gz
│   ├── 46554d4e839e4772d7594412358f87f484f14192.nq.gz
│   ├── 4670e9bcc1ec65c470b4d9e3fdb309655787eab9.nq.gz
│   ├── 46f30515f57a306d7cf3ba20ce2b531e94f38eb9.nq.gz
│   ├── 4a0981e66dc411eae101ca62c27fc7a738cf2b75.nq.gz
│   ├── 4beb16c2a535e5b985fd26723b8e19ee5f6ac5b1.nq.gz
│   ├── 4d5f092c8e8d735d708af1e4e8c1c851d1ab2208.nq.gz
│   ├── 4f4966a580c2ca654e84f897739bfe024e13903a.nq.gz
│   ├── 4fc12bd5028ca2002a3bf65d56f15aa859fe46ac.nq.gz
│   ├── 52481073faab847065f25d2ea0efd010e63683d1.nq.gz
│   ├── 5367d6183d283010b5c44317484b5a5abce3b071.nq.gz
│   ├── 538beefe72b9a3b0532c45e6e06d32a2cfeabc76.nq.gz
│   ├── 5826f326a6c1c93db523f004901c5769deefcf98.nq.gz
│   ├── 5d35e49ade575b7916bf4c53dc821fa5dc8b75d9.nq.gz
│   ├── 6063c3b21ae25439d7423250de119ad324749570.nq.gz
│   ├── 6294c36cef9bea3b179599ee28d1e0351ff0bff0.nq.gz
│   ├── 6d60516d12397466be6b8a4f8d72e7a21f617453.nq.gz
│   ├── 6de004f1a743ed179b31a2a940c5958a2c2d1990.nq.gz
│   ├── 71d5c8e946acfd42d50db2ff7216db1649d69699.nq.gz
│   ├── 7669e0cd53bb8f4c5056473012ad6ebc2432f819.nq.gz
│   ├── 81f550dc19b44a765dd9d07af601c280643fdfcc.nq.gz
│   ├── 87fcd2458b03f9d5887a965ed23a025ab830e6bc.nq.gz
│   ├── 88ee9f4fb40accb21b8b27ab37cbfa7dbddc39d9.nq.gz
│   ├── 895b4d993e7e923c0edabb9b28919ffa1ad31113.nq.gz
│   ├── 905b60d445f9e67f051920eb07763435d19c42f6.nq.gz
│   ├── 91e35ec2be9b652fb3fee747ace67069a618f08e.nq.gz
│   ├── 94f897c83bce16172be250f36bb389bed8802d31.nq.gz
│   ├── 99a13a5cb2ac81cef28025e67fe1535d92c29a1e.nq.gz
│   ├── a26790d68b517cf32009147703ed8daa7a5b2932.nq.gz
│   ├── a495b2fb6c6839898aa55027f63f1c9d37be4d3c.nq.gz
│   ├── a5d787d2e5c2fc65cf8adab9c8f73b7e44abf8a9.nq.gz
│   ├── a741dcd73ce6dd6531425663f4c2486c6d524380.nq.gz
│   ├── a7872a78cbfce2e48bda2bb67a54809a92c5b956.nq.gz
│   ├── acaca085ae8a3b2822b5b86ee6bf67c9c0ff1e6a.nq.gz
│   ├── ad2f68860def53ebd746efc6e5a5596f1e76cfb2.nq.gz
│   ├── b42db607e9aa63440a8ff37a20930a2ebe2fbed2.nq.gz
│   ├── bb44a35bbcf366f21fa271626c35fff340370306.nq.gz
│   ├── c46f82fcb28c72ae9830b6c2b6c617ca74c8e5b9.nq.gz
│   ├── c9b03d739d9c7297d4f42170fda88f935bafcdc1.nq.gz
│   ├── ce5ce850210f9de03d74bbcaab60356335b04780.nq.gz
│   ├── cf7eaadae20320457a7de66cfff785ac532904f1.nq.gz
│   ├── d09e84bc8ac20a51862d94afd6564fcc553bf3d3.nq.gz
│   ├── d494bf9bc41141b5ce3fac855d5f405c7359cfb7.nq.gz
│   ├── d59819c23592afb791733f661007e350f67d5fcb.nq.gz
│   ├── d5ce0114037ecdcdf4239f5a027cab24a7f73169.nq.gz
│   ├── d7645feac64439f3c355b1a12a1280fb706047ad.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f0c53abc448a9dbc91b8c33fc964001a7df1a258.nq.gz
│   ├── f150dcbe2866fa71ec9c73b23a4bc76fcba39fe8.nq.gz
│   ├── f5aae22fe06edd183346348cc61b3227feb98fee.nq.gz
│   ├── f622d54d3bfd2052ecc87c6cae8ccd64af3d6889.nq.gz
│   ├── f7e315ec4d14c8f957a171c9d8c8353b75d28136.nq.gz
│   ├── f8f453b095c64cc81a0dc2e84034260c816901b3.nq.gz
│   └── feb4564d83853c0dcc28dd8717bfa439b300fad9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8d47497fed442ad01c3d4cb85e681f88fb740b87.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 77 files
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

[tortoise/django-tortoise-objects](https://github.com/tortoise/django-tortoise-objects)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
