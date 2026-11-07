# Repolex Knowledge Graph of allenai/rslearn_projects

RDF knowledge graph data for [allenai/rslearn_projects](https://github.com/allenai/rslearn_projects), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/rslearn_projects
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 836ac8034d9de1329bfc0d736c01448ee4dbbc67
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 836ac8034d9de1329bfc0d736c01448ee4dbbc67
│           └── chunk-001.nq.gz
└── blob
    ├── 00d9f22d72c0b337287c144509de0cf8b7799e7f.nq.gz
    ├── 013e41080b4e58f3ab9f757bb411d19567a6e7e9.nq.gz
    ├── 0196db98d9b759b3f74669ad442e1c512b116bb2.nq.gz
    ├── 01c234b99755ccdf02d8a6f6549b0f9623de94fd.nq.gz
    ├── 031ce0a2490e8282d8abc2d97ba2a64617c31b75.nq.gz
    ├── 032540e95b10e03ebbd38b8997eb805f730b8433.nq.gz
    ├── 035fa8eb7506ffdec644d9d52d45bf7f01f8d615.nq.gz
    ├── 036803a743aeb17fd0bc66e78c988b4485999343.nq.gz
    ├── 03fa6d16b4be20c3dd9c4b4c215dee01d2f47685.nq.gz
    ├── 05097e97bff9c563dde07ed4e719edf999070cc3.nq.gz
    ├── 050d6bb7bc0b5356a9431460271f298c2ad5deec.nq.gz
    ├── 054415ef6b0c46b0badcbc35cd4eff85d5fd5174.nq.gz
    ├── 05b6b9121bd23188b3528b37cfd366f9a1aa2103.nq.gz
    ├── 07545c56dc96a10099f0e105d84b374dc70f1398.nq.gz
    ├── 078b437cb8b8d8560c113d517077b9454454907d.nq.gz
    ├── 0a12fb6b4459cc2e53252035cc639e8ebef184a5.nq.gz
    ├── 0a5ae5cdb44f550baad1ed3a30926808336f0262.nq.gz
    ├── 0a6ccd6b9143c97647bc987ac3872b9b4b7a5c7b.nq.gz
    ├── 0ae380f74f95128cbd3c73fffe17e35f3cfa3940.nq.gz
    ├── 0bd3f1fe89499c871909bd0d86c94c1ebc4ef4ab.nq.gz
    ├── 0bee50672682b35b5198f17927c94026ec383e2f.nq.gz
    ├── 0c4a764d683591dd3b2be8b2b952711f75dc0ab7.nq.gz
    ├── 0cdf3612d3fe2c205ab54928ba6f5ac58943999d.nq.gz
    ├── 0e77f638f5a3c0052dbab6ea7224a52e3b840c18.nq.gz
    ├── 0ea1c5433303e822df0e591e6de930e7e6e9607d.nq.gz
    ├── 0fde7d38fdc4efe46addedc799b91d240582d028.nq.gz
    ├── 1097b48396b508920ede9310d4bbca88e4e9c8db.nq.gz
    ├── 10b53802bb0a5b7e1c64708261992ed01516f419.nq.gz
    ├── 11a58f86e90547d9de352012d2b2f1f64481304b.nq.gz
    ├── 1264f8aa6881f2726ebb757a6d91a80c4c788b4b.nq.gz
    ├── 1297b3dc8c7be21480cd546157b70f6a80488de6.nq.gz
    ├── 1340e521ad8ff5bc75816a19f7faec7d52247018.nq.gz
    ├── 138d360e3ec1d711f344334ef37cb2f4b3682b79.nq.gz
    ├── 13b34d5911d06a6cd588f91a649765de1c56f56c.nq.gz
    ├── 16f809e102f32ca60d6c12259449a4f3c0afb627.nq.gz
    ├── 170fbd540651e66167471521b24d08cd5b48c602.nq.gz
    ├── 175a9750c32e875f0a0a876e1b7c9275d0f51dd0.nq.gz
    ├── 1786a2d120118f0be20660236455c98ee490dcaa.nq.gz
    ├── 178adb952a3f8cf24ec82f75711ada2f7092e4b4.nq.gz
    ├── 182f147f4e5a8d3df5a9c315e11cc22e107276a2.nq.gz
    ├── 1bfac8bd3e27a88e90b9640b5e39e098696c5137.nq.gz
    ├── 1c71355e48fa7a5421d5107ece3baa2d26828ae9.nq.gz
    ├── 1c8fc1cd3d72435732c4d53ae529e9e0ee828fc7.nq.gz
    ├── 1ce626de9d5d8571e090ed516f19c06121fecd0e.nq.gz
    ├── 1d50a6f3dfcfe8a3c2af128fdd46d88cb885f8fe.nq.gz
    ├── 1dd3733542d13755d060c5920a366426188ec955.nq.gz
    ├── 1f0b2fffdbfe3360d8e2b54361b0e1a0b0ffd4cd.nq.gz
    ├── 1f249bc8a016f053129b70ff684a47104aeb89b1.nq.gz
    ├── 1fa0e3f8e7f0aac80ff7eb46e72a029e2a1201ae.nq.gz
    ├── 2080f4958d85a1b25c84429aca5342e26adc34e2.nq.gz
    ├── 20983b21b477b049fa62430bd19dde88211a291a.nq.gz
    ├── 222836180dac43db9e93f2acf5b6b87e18206e1a.nq.gz
    ├── 22428c049715577d5ebc60f3d487e892d9bbb500.nq.gz
    ├── 229e01b53b3b8db1965f4e0b1215a50ebe0f7304.nq.gz
    ├── 2399836901bcc7cf4082294e72eaf88d18ff3eed.nq.gz
    ├── 240ce52324aa05c40c01c5e642e75b06cc10fb9c.nq.gz
    ├── 24e056ce4b7eccdfb6844d376532bd0d66405f22.nq.gz
    ├── 24fe01203933e3a3f36dc2cf298896442112d0da.nq.gz
    ├── 25a60de9c9bf12a81ae560d0d65eda3c7825baf8.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 265f3ed46295ff217c73ff4ff83b7e45cc0741a8.nq.gz
    ├── 26906c70b453889d5b52c2f43ffd92300002feba.nq.gz
    ├── 26abb3d9b6e7dc370b4a536515e72f57b94e358d.nq.gz
    ├── 273b93165713a935a746a427a8fcb2c2e15f2406.nq.gz
    ├── 27727f7d3473109c9a334530c86f1c0ea2305998.nq.gz
    ├── 2779a90e77ed260572aa9c755059cf05c984e237.nq.gz
    ├── 27ad2097850166fe813b13f99bc4ce63a95dc289.nq.gz
    ├── 288cd9fffee5eb6fac5882157955063859470589.nq.gz
    ├── 2981ee3e7096d9dd2b3461a9f1052f6f9693d496.nq.gz
    ├── 2a1e32572b4f34e288fcc4e0678c3df29c47b6f1.nq.gz
    ├── 2a30c08ccd08bce3fd32b8e0ae50df352facfe61.nq.gz
    ├── 2a84cb005109bb7ef562b5d531b6eeded0f05789.nq.gz
    ├── 2a9c6a5a363441e4a1907c69682dede668b19b44.nq.gz
    ├── 2b13a807557580c6ae0251216d6f9567bc5b37a7.nq.gz
    ├── 2c1170b0a0df2fd9dc86b025361c7f3566e18cd2.nq.gz
    ├── 2e84b5b02c5de88af674cce2d8a94d31bf89bece.nq.gz
    ├── 2eccbd89984bf03ee8c124106bd028855291ea98.nq.gz
    ├── 30b2d05b102dac4e33273c93ae099848b6d9791a.nq.gz
    ├── 3108de14d1b6449a594007581a70a8cca310843d.nq.gz
    ├── 314780baf871735f5ce7808935c0eb933811d4ec.nq.gz
    ├── 32f0f001582f37835b34d89f8a2fb63717d0f012.nq.gz
    ├── 334ff30205b144316a35c73d595f0aa3aa35f20f.nq.gz
    ├── 3429f1a185ddaf05950c1e7ff60e155b276def34.nq.gz
    ├── 34e299f6e7d69b7a742af58fa44fcc1ab9556513.nq.gz
    ├── 35cf256c14bbbf457987dd4972efbab22ad7136d.nq.gz
    ├── 3621f37d0978435b6d2b6b702a96eee585d33f99.nq.gz
    ├── 36427ebf622063d2040f977245a19df2469a607f.nq.gz
    ├── 3680c86b7e2481578d5b818262c55c48fee02c3b.nq.gz
    ├── 36cd96ae95a085017798b7f569f41f01bb2ca185.nq.gz
    ├── 374a4bf5654241ba641b9d794b92412b0fcc102c.nq.gz
    ├── 37ac86cecd8069876a0b1c221ada84bc46755b1c.nq.gz
    ├── 37b68b888a80884dc2466f4cd747446f27905c74.nq.gz
    ├── 38711778240e7dc558c2cb6a18d9c12939712076.nq.gz
    ├── 38ed659148729157ecc72f9d0a733aeab9ea20ea.nq.gz
    ├── 395ce6c2b4514656cd20741b09aad3a8cc2da6cb.nq.gz
    ├── 39d7d862f3c366fce340ce0b0ecc2034c4c33e3f.nq.gz
    ├── 3a1f2343aaf2bba2116988d79cc1f23866e7afad.nq.gz
    ├── 3a2f65a784c19836813f6186f6631d2d33366243.nq.gz
    ├── 3a6427540aaeff4c7605ec248b89668366a9d6cf.nq.gz
    ├── 3af9adbae84381fe9be9cb55f3b80aa8ecb8f46a.nq.gz
    ├── 3b852b64878a0a08cc7f3450f10ca51a02edaa80.nq.gz
    ├── 3c34d4f2b1d4066e63699ddc3e993957f4d37612.nq.gz
    ├── 3c7235ed736f348f6f95a21ed9970acfa7b94b61.nq.gz
    ├── 3d038d295c73e4994c33fb7f27e5fe7da8cd7e9a.nq.gz
    ├── 3e50839d625dffa071aa5fbd57bcaedd1c84dcec.nq.gz
    ├── 3eb2c6e357d1066740535e7341f3763aba8e29b4.nq.gz
    ├── 3eb7ca246b079640c157a8d6056cb331dc2b87d6.nq.gz
    ├── 3ed0cbe7b632c582e9eebafceac73de0f111a227.nq.gz
    ├── 3f24c2b22e0514e0f397bea4fca3ae4861225832.nq.gz
    ├── 3faf15ea92a55698c785578524dccbb56e0a10ba.nq.gz
    ├── 3fff87139c661439acb2607f02190c8c9c997aaf.nq.gz
    ├── 40475cfc4a1a36aed5bfc17bc7bb38fcc8754c52.nq.gz
    ├── 4155a8b7b4ee54d979cca1590f47fa340e933e66.nq.gz
    ├── 4230c048ec8e6b87030bd3f3568879bedb42d1b2.nq.gz
    ├── 428afd62ca339598148630686fedadb1eec031a8.nq.gz
    ├── 436429b9a1cb5d3dbb84a2cfd8637ad5064aa1a8.nq.gz
    ├── 43b0970705fe16aff3e846291473f63095e336de.nq.gz
    ├── 43cf8c245aed39e135ac8898190b721fb586c892.nq.gz
    ├── 44f802dc872ac779158be6fff1c58c5ad7901b38.nq.gz
    ├── 45b16bfc95e02c18199d69541339f21292acbd2f.nq.gz
    ├── 4666e2585d85f142deadc81730b5ad7e2bfe48ac.nq.gz
    ├── 4684db8b3e647764d78901b9459dfe91684b2c61.nq.gz
    ├── 47330673807205ca7d6b657b918ea420f19d3819.nq.gz
    ├── 474eba0f213394d90db8c2e03f1066ad5e09cdbe.nq.gz
    ├── 478579f4ca5a96fe4c9639ae030ccd96a6cea282.nq.gz
    ├── 47a2db2b16662299c104e2ab2e140a9c13f052e9.nq.gz
    ├── 4891ccdefbd324841c29a61a3d021465fc727fe3.nq.gz
    ├── 492be59e381141a3f92a57e5dcc1f22e79590a01.nq.gz
    ├── 494e495f2d35999d2d5609c6a8552459c71bb71a.nq.gz
    ├── 49d8236dd25a127f11b0cf052a5a356561b151a3.nq.gz
    ├── 4a6706af61ef44c23428c73b47fa696e9c0f6245.nq.gz
    ├── 4c43473f07fc667e00c55641cd3bdc9d601e4813.nq.gz
    ├── 4cd234d67242d7e2f1506788729c5c18509244b1.nq.gz
    ├── 4cd7a6791e68b634c3cbfcceec2e066b7a4a5173.nq.gz
    ├── 4cfde570abde46268fb5c94e1ccea28db1810ade.nq.gz
    ├── 4d170ec2bfa9815d0ac38971d195a81150e27201.nq.gz
    ├── 4d797b630d5fca074ab2bd5be21d5508ebc3ee1a.nq.gz
    ├── 4db0a1afb2f09e6fafb558e2acb4bcc0826b9ece.nq.gz
    ├── 4dc65e04483036551ab3e33ab2c20efe03536871.nq.gz
    ├── 4dedfd3b813666524d700df03a09ff1cb8ea7f5a.nq.gz
    ├── 4ea2e49dee03e4a8dafd4794a1ccbafa3fcea646.nq.gz
    ├── 4ebfce1b17a44f7fe0409d7fcc8587ede2203438.nq.gz
    ├── 4ed6717c26b983752db1bdc68e5cab4a54bbaf23.nq.gz
    ├── 4ef2644b3e6cfc8fa1dfa1217eb554a0ad0ba023.nq.gz
    ├── 4f0438e016a37573939b35d4946e841d8eda93a0.nq.gz
    ├── 4f9969ab65a1d4c7fb80aa9ca1f9bd394bf7e5d6.nq.gz
    ├── 4fa547c66c011011d0c995b0c063266bd87eebed.nq.gz
    ├── 50319e162e5041838ae7171b4555f5b12df920b8.nq.gz
    ├── 50ddfbd97f740af11cbcde31bd7c649339b9b892.nq.gz
    ├── 528fc4b8438eb72ed0a46a7f3e47016ceb01cc43.nq.gz
    ├── 52cc8aaab0c1f5038f1c0d8a17ea1649f5559443.nq.gz
    ├── 52d03f9268a509a32cd32f37d09dba292d6538f1.nq.gz
    ├── 52ee2b0f3e65ba7427dfd4d57be7150171176345.nq.gz
    ├── 531c17c3efddb2bafa18e322849ea7ee86235738.nq.gz
    ├── 533b8d05e0eed25c1950df08f2f6408d13e14ff3.nq.gz
    ├── 53e0f8db4c6d13b9d83a269d9c9afc9edbf6b940.nq.gz
    ├── 5412ec0cd07b45cfdd169ec23468eeef3b8b687c.nq.gz
    ├── 544a7ecef62b44f7c66bb82e3c12c3e08e4ff1d8.nq.gz
    ├── 5455074cfac944d0b20d872b1dae2a72d4144392.nq.gz
    ├── 5577f8ef936ef3d0951e59b4af2f8d260bbb68ef.nq.gz
    ├── 55fb0675d92a86fb989ea6d27457d747a45c0ff8.nq.gz
    ├── 5608cbbe2a32ee9875c56b31370b3436c37d9c53.nq.gz
    ├── 562a0af7fb387885c4eb075fc86e35a908ef99f0.nq.gz
    ├── 5707159e3a1c157b2a655f5abd1a4b479e13586f.nq.gz
    ├── 57126682ddb4a7a5e2c2fcbb1830613b8d430c9f.nq.gz
    ├── 57887a2671b306050c81f16c0dc819a375e8f1d1.nq.gz
    ├── 58237dbfd19c1aac217ee9e2d20ce7f58abcc955.nq.gz
    ├── 5865fb4ecf291d802fcb98ab5f4a30a095103a76.nq.gz
    ├── 58e24568f1470aa45b81ea5fb57045a09affabde.nq.gz
    ├── 59362bad7d0fd25913de511cfe05c66a442e798f.nq.gz
    ├── 59a7bf08cd88b177e6964247274fda01f2b59abc.nq.gz
    ├── 5a233671374d0f5587c31d8074c9ca92dc034e23.nq.gz
    ├── 5a4e838cb8a8c6435ee8292b995c4186b2f69808.nq.gz
    ├── 5af07a72ee166de412c80ffa063684afeec84d79.nq.gz
    ├── 5afaed91df6dc4389354e665feb403c509f20d07.nq.gz
    ├── 5b8db7763d735af315ad152782b47c3e42eddb5a.nq.gz
    ├── 5bf47f886df616921db9876d5047a2b52f08d272.nq.gz
    ├── 5c2da2ce796734e8e2980c09e4eddd745fdf63de.nq.gz
    ├── 5c58378edd258a50e17f53ad3f4fae34ee80fe84.nq.gz
    ├── 5ca4834428182bdefbf6a74f1c3fa5f16fde5b89.nq.gz
    ├── 5d5c55041adbd7142c8b3e1bf123d4f66d4fbd95.nq.gz
    ├── 5e19fff81dbf1000dcf44992adc95e1f5f9d8cb7.nq.gz
    ├── 5eb4a81944a60e10fb6256d672ef7fbe4e911988.nq.gz
    ├── 5ed5a55b403d1949cde328e042240ab949c44faa.nq.gz
    ├── 601950a2bc1cbee5b9606bb9025db8298d29911d.nq.gz
    ├── 612156214e19e219cdd4d35077528af70643795d.nq.gz
    ├── 6173883548e3b2c4a12aa351f2eed173a14c4444.nq.gz
    ├── 631df75a845549f3b39ee46b1be02d010af34720.nq.gz
    ├── 636e100fb8c3c109cfb2065b61dea69ea05f1255.nq.gz
    ├── 637f79a3b2a5e1f1d21feb30fd0ab6945e791311.nq.gz
    ├── 63da9964919ae11037fa6e67cad3aff68b3297c7.nq.gz
    ├── 63e00217cbb8f27685f296b43b58707af7eeda0d.nq.gz
    ├── 65178f2c13f4f5975e018474114fd433309506d7.nq.gz
    ├── 65b50c9a758b691e34f32a38efbfdc7ac1bfd17d.nq.gz
    ├── 6683759b75633792523832c4cd8f60a9cd02b4d9.nq.gz
    ├── 678f7dd3ae86545e218a7afc88c7bfbfd83e1ed6.nq.gz
    ├── 67b5b1c6f9f3255f3bd61944839c83ee2bfb400f.nq.gz
    └── 67c8968812fe08e666331cdf08a91c251e5e4881.nq.gz

7 directories, 200 files
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

[allenai/rslearn_projects](https://github.com/allenai/rslearn_projects)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
