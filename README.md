# Repolex Knowledge Graph of tensorflow/ecosystem

RDF knowledge graph data for [tensorflow/ecosystem](https://github.com/tensorflow/ecosystem), parsed by [repolex](https://repolex.ai).

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
rlex download tensorflow/ecosystem
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c39378894bf080843a86edacd0176c53f70d939f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c39378894bf080843a86edacd0176c53f70d939f
│           └── chunk-001.nq.gz
├── blob
│   ├── 0536c57afed276320d8ba7c30ac368bf5b11be3a.nq.gz
│   ├── 054a7b80175eb426aa2ae436aee64db3ed786880.nq.gz
│   ├── 066acf15b9482473b0920880ad7669c82ca5dcd4.nq.gz
│   ├── 069604f204057ca72523fb5a1776141025d4c914.nq.gz
│   ├── 07c3afc2dfe74e066407299f51d766b10ba2a8f3.nq.gz
│   ├── 099e5185abd15fcb4bbe7cc8b7a6f460e852708e.nq.gz
│   ├── 0a381de2b0cb514922f4c533426aafe57b5f67d5.nq.gz
│   ├── 0ce3809e74f3f52ee5890f3deec6737f0f5f5d83.nq.gz
│   ├── 132e991abf5fd89d469c27437756ce5081aeff3f.nq.gz
│   ├── 165e8db68adafe19b779536c426fe15cd04e7340.nq.gz
│   ├── 229117329e5047b118c19d9d0abb13268282e59f.nq.gz
│   ├── 23246edc6f3d6bb4590ebfe326e1a63b63326225.nq.gz
│   ├── 23478cb038f27457e541f556cb90d244e4beb63e.nq.gz
│   ├── 2c01ad5ba5da5c438959ed51b844f5b7543e9e75.nq.gz
│   ├── 2f7c8a82191c8a941cee20c3c0ce23afae4e6b2c.nq.gz
│   ├── 32808955ab3fb8245fdba2a46fad371b45769922.nq.gz
│   ├── 353b0a1a37324cfca1651e18b328d7f4818857d5.nq.gz
│   ├── 36da27f60249774572f01405398b3635753effb8.nq.gz
│   ├── 38d75aa3dc28b0870a3d26832f4602b3d1a78976.nq.gz
│   ├── 399e51db0710c36b43cd708851893cf4375d8a83.nq.gz
│   ├── 3ee13822c7218b35b9afefa13a49aba58c6c400c.nq.gz
│   ├── 3ff88c75486470bd74d20e9561409b854e9bdd17.nq.gz
│   ├── 4007a0ec20aecac5ded7f7340d9dcbfe8f0f4c4d.nq.gz
│   ├── 48b4edb1c5bd19516d832056112ab0b38b3203fe.nq.gz
│   ├── 4adba5fe0d1420477cce1133bef95e506c03cf5b.nq.gz
│   ├── 4b198d93ccd12c5053f85c332d7c8cdf83be6ae7.nq.gz
│   ├── 4b4e1e9724ad76acb3e90cb220d09f3f536b0a67.nq.gz
│   ├── 4c1f4c88540dfb3c38943fa555db1070f23dd355.nq.gz
│   ├── 4cf93ad2decce786f59acf2eb7337ae117b8e03a.nq.gz
│   ├── 51ca6898c00c5473a6db1fc8028957f37f2b2467.nq.gz
│   ├── 5263a4a480a66e1b096fcb8da026b7e4b130b8c5.nq.gz
│   ├── 5973aac4a31db67a5c9395bd22f19a51c3beb8e4.nq.gz
│   ├── 5a69d1ffa787951c98023e6321cb6dbb24d38be4.nq.gz
│   ├── 5b3ba49b4372406387a8d5fdcd1304c8d3a9a74c.nq.gz
│   ├── 5dbd9a7c50768cddaa8aa0da985f1e6a239d0167.nq.gz
│   ├── 5edbfae4e2b36ebdb5c0bb84d2b80bd6aebb42c9.nq.gz
│   ├── 5f32afe7da80ff3f1876ed36334e40f2e6242153.nq.gz
│   ├── 658b69177938f8c453bb9ed89cc87e10d50a50c3.nq.gz
│   ├── 65d0bac4d5f647a509b93950586037ef165b0b89.nq.gz
│   ├── 661b964112174c014121dd3e6967f0f701b93ce6.nq.gz
│   ├── 68f97da1dfe298642d7ac14870972680e2c3e004.nq.gz
│   ├── 6ca6197fe295600681923aa0e2d257cae68bdf32.nq.gz
│   ├── 71649a3dbce1b390e45ee15de0879eb2f3343e41.nq.gz
│   ├── 7317b30d9ff31d4b195960c44885536a76cfea28.nq.gz
│   ├── 7886ec2b4c7a44b705e60649da2e0aff785c4b93.nq.gz
│   ├── 79a58d9b0147ef86348add9f35bded85dcfc45cd.nq.gz
│   ├── 7c5af8d5d6bfa9a33754d0a461bae7c28332d6e8.nq.gz
│   ├── 7c698b6ba1c7b5134d597ed764dd5b5a29e8ecd3.nq.gz
│   ├── 84ac9ddcf1cd049ceac1fd6544a2ddab507f4921.nq.gz
│   ├── 8b5a02fea0b062f965bc85c10d55a0f8f0fa4906.nq.gz
│   ├── 92723617d3999e8bcc9a1be2fdecd922059ba96c.nq.gz
│   ├── 98ef69e891c752c278366bc84e124cbb8aff6405.nq.gz
│   ├── 9d0479b5569302300efe202d04f23ea98d12dff4.nq.gz
│   ├── 9eac202be2fe9411d9c1a295b9f3f4d77772348d.nq.gz
│   ├── 9ef7f1dd29be155e66ec02d19a82b3975af01b29.nq.gz
│   ├── 9fb8e278b5d9961a5bd4134558e75a33c544c032.nq.gz
│   ├── a02672c59a070a852643880d014b31924881f93c.nq.gz
│   ├── a4953afb291fa5888bac072adbf4a07b08c49586.nq.gz
│   ├── a4fd6c6fca47c2c0ac767d44ee1534acc5bd0b6b.nq.gz
│   ├── a672dfd188566fe32fa2766de696ec5d0286eebe.nq.gz
│   ├── a7c9e3d39574d2688f0edebff017b37024191276.nq.gz
│   ├── a9f127f8ffab7defd8b4ac3ae6b58d0af3227b9c.nq.gz
│   ├── aea4a481900aa09c3a5734c3bce58a5b5e22f374.nq.gz
│   ├── aff8fff423580d1bc26ba37328913c981f424133.nq.gz
│   ├── b397b35c3c0fc92d539ffc5128f788a9dbdc7132.nq.gz
│   ├── b7a0d2867660176d9c8d25154b5b6bc6123d631d.nq.gz
│   ├── b7d523cfd471efea74eb17c6cf1425f20331e47c.nq.gz
│   ├── bde354f68ebed97e00aada2d3d390f6e2cf53727.nq.gz
│   ├── be7b1dc549d67f5f687919c6432fa8ff58d3d818.nq.gz
│   ├── bf70e8658898f8fb8b6d092a6174eb24d4a94beb.nq.gz
│   ├── c1b1779a191de69b5c181fcfd25d6b422c405f3b.nq.gz
│   ├── c2869067c7cc40a53f3ebe15a55bfb194f9b23f3.nq.gz
│   ├── c28ac5bd22d92da081a8f706483decd4a156d954.nq.gz
│   ├── c43d56f281abc34f92214964074c213221b1ac51.nq.gz
│   ├── cd715be5ff24782c0865938fd1c13a0ad4eb3a15.nq.gz
│   ├── ce53146d9e41221d1e1e6e79d0fa84425f167604.nq.gz
│   ├── d3da228420e973edaf4123d5eeb42210f4450b0c.nq.gz
│   ├── d45da6f5f9a4affbf71de832d661e2439dcd09b2.nq.gz
│   ├── d5a6935c0ce710fb018ad83f3a6f615696a0b114.nq.gz
│   ├── d6d877ca7ba8089c531e2c719464cdfd7f6de4cc.nq.gz
│   ├── da703a903ecbf04580fad91803f33247295c9025.nq.gz
│   ├── dba79368818aa4802a663eb3e0a11b73ac793349.nq.gz
│   ├── dcb35272a1594b34a1a5cf9ab61de06731bd80b6.nq.gz
│   ├── dcc0ff21262fdda710cd4abf8fcb7d89b32d94ae.nq.gz
│   ├── de4cea80f3feeb12fd495a1b3d5c81f01616ad1c.nq.gz
│   ├── debd74acaed83a253b6765601358054544e786a4.nq.gz
│   ├── e86cd11442cd6e97e006d202e0f3c6468391131f.nq.gz
│   ├── e87c815b6bdcd72d6670d463df90306c489e04da.nq.gz
│   ├── ef70ed8435de187d7df706f271ac957bfe2b7299.nq.gz
│   ├── f51df3619ca05d3513e5021de74c2e785a19e074.nq.gz
│   ├── f5ac6df18dfb2f87fe2d2d8e7380aaed9d639ef3.nq.gz
│   ├── f7742c1200ded87893c690c344645dfc326d289b.nq.gz
│   ├── f7f3a4e0094b9d7c5ac6b209c085f7606b7863ab.nq.gz
│   ├── faf7bca7468d80216830a880e836772ce5d9f22c.nq.gz
│   └── fd4857b91d340e977f762eb5ac7f002b73ad77e3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c39378894bf080843a86edacd0176c53f70d939f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 103 files
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

[tensorflow/ecosystem](https://github.com/tensorflow/ecosystem)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
