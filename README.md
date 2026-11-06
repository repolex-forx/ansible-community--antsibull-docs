# Repolex Knowledge Graph of ansible-community/antsibull-docs

RDF knowledge graph data for [ansible-community/antsibull-docs](https://github.com/ansible-community/antsibull-docs), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-community/antsibull-docs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 389734f265a8093845176afefe4fd5e6dedc1fc0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 389734f265a8093845176afefe4fd5e6dedc1fc0
│           └── chunk-001.nq.gz
└── blob
    ├── 0006187920a290c6359bc95101484811f479b288.nq.gz
    ├── 0133192574c7c2adbacbb0393133a6e7ce46425b.nq.gz
    ├── 0173bb559821f09aff2d107f3e33558114d2fcaa.nq.gz
    ├── 01779064549117e8cd9dcc498e881001531c95e2.nq.gz
    ├── 023f1555465d3f1639f9f55985eb5e7a3f233e9e.nq.gz
    ├── 02f3ebf913cb9fd7b49fa74bc8714d396d8d47d6.nq.gz
    ├── 040707c495308ffabed3a7ebf3768b247d6c02a6.nq.gz
    ├── 0499c37b1da9c1d505731d8dc83e3c5d19eed3c1.nq.gz
    ├── 054773e6151e23c15f8bd273b12d5a0c3854b698.nq.gz
    ├── 05c575e1155debf502dbd9c20c13f7a6d7fc1b4b.nq.gz
    ├── 06cf9fec431525102a9973dfb4600e4c0c8e4ab3.nq.gz
    ├── 07b847ea5a8714732769a515ad0874dfb74caea9.nq.gz
    ├── 07bb540d71b3e7e8bf0abd0fa410b56cc5e26f5f.nq.gz
    ├── 08feb99e9f0cc19cd5f784c6aa28e3caf77c4768.nq.gz
    ├── 0948cae2c621d412ba8ffbbc0e6941b3bb386021.nq.gz
    ├── 097fa837e6233044d2ff8258d9a001fef20bcfd1.nq.gz
    ├── 0ac241e50302770d747d2cf93107e149fc5ff2ea.nq.gz
    ├── 0b1a34d91856425d00d12d4ddf8f4becd1ced026.nq.gz
    ├── 0bb0d37ce743bda2fea6535b77a2954241a393c3.nq.gz
    ├── 0c78ff22f009e1519e45666635123bda2249039f.nq.gz
    ├── 0cc457319adb4e72ad2829eec4333a8a8805ce61.nq.gz
    ├── 0df650ed7af6b48cca8648e50720342de53eaa44.nq.gz
    ├── 0e82f1e29d7261a56aa1e72850f6f88ca1a48dbb.nq.gz
    ├── 0fdce495d84890ee1d57f2310281c32a0ace3a3e.nq.gz
    ├── 10908b0051d8ca5b0da18b854f0d200c158b38e0.nq.gz
    ├── 10a8e8cb25676e5199747ec7a768e1eda0053ff6.nq.gz
    ├── 10e8a4197f1758cda9dcb3e2344b48f16e56d3ab.nq.gz
    ├── 1135b1ce0a67bfd1733692aa2541e8bce0831f0b.nq.gz
    ├── 11598cd1b7671f0a9da2f91369653612e82ebe1e.nq.gz
    ├── 120b096a107b2d45b4cdedd59c6d143ca5543963.nq.gz
    ├── 1258c032406f7e2c84327c532de4753e52728afc.nq.gz
    ├── 138b35655685bbe16e2998ac04cd66b2e3ce52f8.nq.gz
    ├── 13936211dbcd5ba2654a1b989bebc286693b176e.nq.gz
    ├── 13ef4968bbfe8543c09a49bb2e825b54d1ce1f72.nq.gz
    ├── 14bb9dccfaf0fe35000a34060a63f5cc3345c85d.nq.gz
    ├── 14bce60b74c22e08cf124842a47c2e4fe982b6fa.nq.gz
    ├── 14cde9c34be30c5e5de852d4e0ebccb967aff23a.nq.gz
    ├── 150e258cbd82301ea90f6bace0ef80e12421e4c0.nq.gz
    ├── 150e3cc4c9e7c8fe61f69adb682e5af0aa1a3a4e.nq.gz
    ├── 15870447d39b6cc85626f37ec2d4be8bf8a109a9.nq.gz
    ├── 15945e7b49a1c7d18a16b0774fcd0c8379d5a819.nq.gz
    ├── 16d80cb3b3ebebf9bb0c7a90cd2920429b902b42.nq.gz
    ├── 1806f929b2f6da447409acc5de58ca11aa9ad7cc.nq.gz
    ├── 18144809e1393bda359261de3750f9e9e5c79c57.nq.gz
    ├── 188d23483cbdb833ba630d848e262a713f6a8511.nq.gz
    ├── 18ded477d8b8c3482e989063c23d9215c3a42117.nq.gz
    ├── 1988b0684db1824e9badb48451acbefe0c6110c9.nq.gz
    ├── 199dd98a7179c75fddf427b9e77959ceaabd7c39.nq.gz
    ├── 1a453e600de8dd3fdb71bcef2bae252630172e3a.nq.gz
    ├── 1a4e6e6a18d05f97a6187c067d7f43e134011233.nq.gz
    ├── 1b785bc047576bfb74cbdcbb89165864934e4321.nq.gz
    ├── 1b873f0c3b0a6d9ecddbd3ba3951fff7db867077.nq.gz
    ├── 1d2306a56c372a6645dceda2cf46402efb75ff9f.nq.gz
    ├── 1d45f43732e125027127e21f327f4cafd96627e0.nq.gz
    ├── 1d6cf8554ada641c9a963a6f986822bf4be2da9d.nq.gz
    ├── 1e90cd5db354bc7604f9bb8940a62a7a1712b7d4.nq.gz
    ├── 1eb39cc36931acb56e983b0c9c1e3c37fdbbfef6.nq.gz
    ├── 1ebbf99c2f39bbc342c592dda36f97596754f61c.nq.gz
    ├── 1fa4c9d595dd0e844718d4bb2fc0da9691ab5aee.nq.gz
    ├── 20fa3b603df0331d8f5111cf4db14e9571a106b2.nq.gz
    ├── 219eef6ec717bb57fa98d3b4f143dc52e13348bd.nq.gz
    ├── 21a8e5d0d2b88a7dea5bdfdf6aff5997a6a5d051.nq.gz
    ├── 220b13ccb9b3e4dfdf8568381a3d73e1b95d4b2d.nq.gz
    ├── 22ae396d04bc9af5231275e403b45869cc2861f8.nq.gz
    ├── 22b8135f0f5a9d9247dd8b57da40874e211a1383.nq.gz
    ├── 232f22cf0bfae5fc3a9373545bb1bfa889bf82f7.nq.gz
    ├── 24196cb1fb16725161fda175290fc809252ab70b.nq.gz
    ├── 2458aee0f64bbaa83efd10945dee616745e5c883.nq.gz
    ├── 24e9d79d255b0d6a2b69bd95ca79315e2979fc04.nq.gz
    ├── 262cb0579b8b6642503a6098212037b5f44184ff.nq.gz
    ├── 265eb95b88f87bab6e90e2b3653e7963bf83783d.nq.gz
    ├── 26a455f83b23342bca9ef5d5eb20697b07eb06f0.nq.gz
    ├── 26e05eed3c5ba281c05a726b8164a72f2fd06b66.nq.gz
    ├── 274f81d75a87c08a2f75333ab6e200a0cc5e0a4e.nq.gz
    ├── 276e173513500bb5011c8191a83a14ad93cab436.nq.gz
    ├── 27fdbd2c76cd6fb62e03a2afa5173ce51a6e9fd8.nq.gz
    ├── 2810fc4048b79e1dc9473277e00357f0521c4e30.nq.gz
    ├── 28a17749b6d2c265898cbe62f19a139dbf2cd353.nq.gz
    ├── 291c608742d763fe22c859ab2e1b6febf6c8e3c4.nq.gz
    ├── 29c2d9cb667a3775efe2bd5cf5a8a78260f5840f.nq.gz
    ├── 2b07f6631318caa2b7efb5b19b7debf0f51140b0.nq.gz
    ├── 2b4f269dbac8f5529c989a5bd3c6c0c2335de690.nq.gz
    ├── 2c4749af0dddd135f9a7dfc0c931ec5c9b999b9a.nq.gz
    ├── 2c510c5e5811c9ae8e87083c67e40d66503ddc23.nq.gz
    ├── 2cb994cc59b621630ebfffc54361eb19e05c36a5.nq.gz
    ├── 2d225aaa522c70b47c87827b3e564dd66464e86e.nq.gz
    ├── 2dbcd02987713dbebf7b027503f145663e6f2ec4.nq.gz
    ├── 2f92ca6d1e7ac3f80cf1e26c7e5415a8957af558.nq.gz
    ├── 3074e32da3dfa7b601447bf74fb5782a7300964e.nq.gz
    ├── 3110c76c7d4077ec1a733cff5f567b354276f1ed.nq.gz
    ├── 314e747fd1a8c4924be317de8fc256f33b199039.nq.gz
    ├── 3155823081fc0ddc372b8d3e63fe394b23e2cd1e.nq.gz
    ├── 317dab8759a5ea772b4332d8d47897cc547a4fe7.nq.gz
    ├── 336cb4cd8f5b0e2548d6a1adee925eaa29bdcc12.nq.gz
    ├── 338498ca419e095e84a6fd4ca152d60e6c663695.nq.gz
    ├── 343c112bd8f548a814b0a781116ba071bcbe2baf.nq.gz
    ├── 34a189811f5b9ef50a72abbc8330e3436171a205.nq.gz
    ├── 34d1e4820be0fe497cd2f36a37fbd3c28c6b9f55.nq.gz
    ├── 357d3014043b71b6ad5593c9b0af731b7833e169.nq.gz
    ├── 35badf83c744179ab4eec81a694656d806f91550.nq.gz
    ├── 35f7496f7faa42ae2bbf5b9e644ba01ea6eeb4ab.nq.gz
    ├── 364095195ead7c95fd65def50a79d28cf8782d53.nq.gz
    ├── 3642be0f9cb43e8b0433074f470ce0a3d3e3ed83.nq.gz
    ├── 369795b22e70fd9e54b42b5ef6ba5e7df873c8a2.nq.gz
    ├── 37da850c2fe91e1097970970161328fac25bfaa2.nq.gz
    ├── 37db993293478724e4cda3faf4e7e09eb8e4f70f.nq.gz
    ├── 392155a5d9699a3d5d760a361c0801f52f485f30.nq.gz
    ├── 395fe58ab3e145bb9500355051ec786dcafb8bd1.nq.gz
    ├── 398f912914831800575c70e3fc833433682a7e8a.nq.gz
    ├── 39df975a1185c3ea2122fcf865700d6ad04df57e.nq.gz
    ├── 3a2293afa45d4b60915f52ff8f08d5d7c40ccc94.nq.gz
    ├── 3a41b3c41a62f084cee8f5ef92da05ed29e05507.nq.gz
    ├── 3a90a19b2b4161d79552f1bd79051becfb54e4a1.nq.gz
    ├── 3b7e87c6e31df207fb93f3877d2efd72d35afd06.nq.gz
    ├── 3c09b1bea641225101ac0dab91b16375835b68a7.nq.gz
    ├── 3d2c99655070a14687879fd2fc2453fb088354f6.nq.gz
    ├── 3ee59b3ea772ece17441ddba33a838c6dc951f9b.nq.gz
    ├── 3fba96ce3d0f3f9c38c0f354f3041811828b3c5e.nq.gz
    ├── 3fbc07b63dfdf22c068b5fb813e34bd18998c6da.nq.gz
    ├── 407bbb3cb75598dabc8c7842aecbadd32da27cbc.nq.gz
    ├── 40a4cc40918e2be6da67fe06dea5ca45c82fd90f.nq.gz
    ├── 40eb73b04e9f81173d69cdd804e9ca3bed73ffc8.nq.gz
    ├── 40f7089dc347d9384d663d520a29f2d81f436826.nq.gz
    ├── 4301afab193e0637bded8adcc268dcce3a9067ff.nq.gz
    ├── 430dd829c481986823e0571af782f70f6f4ed7f7.nq.gz
    ├── 43711e7e4eae0af114a7657865c6cc70aaa48fbb.nq.gz
    ├── 4525811c08747c6f25b3e1632376df13a5a8166f.nq.gz
    ├── 45a509e4c131d4f01d7b6d3b558741ba49397336.nq.gz
    ├── 462069a34d220e02c84c385bc2e235b3deff53b4.nq.gz
    ├── 465b9c1530bff0476801240cba5662be9f8e733e.nq.gz
    ├── 46a564eee04457e21e5b28142fcff8e03c01ce7f.nq.gz
    ├── 473249d52f9da9e3a3509a6f9524aea0db6a4f71.nq.gz
    ├── 47339d0c9a5edc403def0c0e0451a4eb00615a7e.nq.gz
    ├── 477dc1dabab3da2b623c18cd845db957c144e3b4.nq.gz
    ├── 48a00824ec55a8117dbf6e16e930c48bf9f78d8c.nq.gz
    ├── 48ade09518c929a1c4c6948c5d94ada8171a005f.nq.gz
    ├── 48b671d0265db286b6dd9849837018df7213be58.nq.gz
    ├── 49c1edc8f3e8fdc6c397094e68e6e1c939918da5.nq.gz
    ├── 4a9372a8064172bb3473445a4cd2b88f44be2b9e.nq.gz
    ├── 4b2fac064983ca705258d42088dad9b8f28c5e98.nq.gz
    ├── 4b5768fa1468b51675aa95cb9fd4cbfc3e01fd0e.nq.gz
    ├── 4b9ecd84c4139b15157e02f0b40cfaddb9c6b999.nq.gz
    ├── 4c1016f6543fd904102762d8fdef2e92826f6d9e.nq.gz
    ├── 4c591a94cdaa4445cb53db39c234ff57d95ca5d3.nq.gz
    ├── 4d28a6355c93b62cfea50860f6d5dcb464b74ff9.nq.gz
    ├── 4d7d3f69a07b57f2dfb0a336697f0f1ebc0026fe.nq.gz
    ├── 4e2e2dd42986c248d9ec2cdf0ca608b05814e677.nq.gz
    ├── 4e5b59e0bb2ff9424ddee0370c85ab7987145de0.nq.gz
    ├── 4e947adab7b9ac798ecfc510f33c2d404b7a053e.nq.gz
    ├── 4f20baeefb9cbab7f014eb6c6648d48ec3e572b7.nq.gz
    ├── 50426a0a51af2226ad27d0d341fbfef0808f2fe1.nq.gz
    ├── 506599223d2d47ea3d4f03fcf8437d548c8548ef.nq.gz
    ├── 50804672e0269f4e8b8d20cfc9ad7a1237607c31.nq.gz
    ├── 50d35a10299d1d77bc058cf850040dbcdd67c53a.nq.gz
    ├── 529400c85b284f8ae9247fb5b34bf5b330820236.nq.gz
    ├── 53032421b20a3a74a1b7a99d56bd90dc524a8173.nq.gz
    ├── 5396c86ab67d941b4819a5f8b84ad588f49e8971.nq.gz
    ├── 53f0acd6c3b86a7847a3165e7fbea2c32318b5ea.nq.gz
    ├── 545dc22618b9c86063c82ea7023df281a09a2318.nq.gz
    ├── 55b01c5354750d0b3b9184a611d46a48d1cfd2d6.nq.gz
    ├── 564d9933c02f057fded96e33ef3ddc53c3be7e0b.nq.gz
    ├── 568c3afbc0d47f9e562f03137f078718f2c5f02a.nq.gz
    ├── 56a33873dd1a2285fcbc4f8d28d5c2bd0c0f312c.nq.gz
    ├── 56cd853766a9b9400174473f366449c9545669aa.nq.gz
    ├── 57391e1ba5bd038e2e5c8c0e09a3845c2ecd0a8f.nq.gz
    ├── 57f8afa76e5424d19fc8c9ef04220dd2b8aa5af6.nq.gz
    ├── 5866db952488c7b54980c11bd489041f45f30945.nq.gz
    ├── 587b7e014eb8ba1435c113870f839e7ae8ab38b0.nq.gz
    ├── 58c0f9f2c108734bb18c63ef068bfdbcf3b2cb80.nq.gz
    ├── 591be5b0b8ae4559b3e4768fdd66032bd29b136c.nq.gz
    ├── 59496e384392a3cbf415159d348131668a3e8b1e.nq.gz
    ├── 594caf5ba3d54f348acffe0d9e5049477e887bc1.nq.gz
    ├── 5953f99feeab1fd6c9ef72a34b4a65a17cbcbca1.nq.gz
    ├── 595e4cfbca7be3d78ae8fd2b12381986532c0315.nq.gz
    ├── 599c89a9a5a448ceb6cdb669b70b827f738810ed.nq.gz
    ├── 59b5c9dfce31379b6f8159dc8ceb23dd30305742.nq.gz
    ├── 5a0383dca94ffb6518b8011fec9dd386bfc584da.nq.gz
    ├── 5b5fc6dbbeff6cc96029034ba19f5a9d0c5eb7b5.nq.gz
    ├── 5bce5be48587451c796a27bf3f469a18093c5be6.nq.gz
    ├── 5be1fb825cf29b51ba3f384072059621397aa1df.nq.gz
    ├── 5cbcedb33b8d08f0e2b162f8b32682161a9b0b16.nq.gz
    ├── 5d2fe9e5ba4d4b60e52b9629a0b5c597d3462574.nq.gz
    ├── 5d55a04492642b511053e34a3875ae9cd2975b26.nq.gz
    ├── 5db620b6d7e588fce87348587650cd8f0a52e6b1.nq.gz
    ├── 5ec77585b474a075736e6c4ef7b5cf9d9a41f4d1.nq.gz
    ├── 5ee7812edbb236187b2434d8d01342f71c10b922.nq.gz
    ├── 601e911a86e404f85db2009d97548891837ebccf.nq.gz
    ├── 6026bcfb2245e0d022dbfd6bb7d47b6b18f79925.nq.gz
    ├── 608ee2c9151bfe3145966823846aa8124c2c5ea0.nq.gz
    ├── 61049d2202810270ae5383e05629b079f44f228d.nq.gz
    ├── 614f1e7f52d5beb4143ff646fd6b0aad4e1209fd.nq.gz
    ├── 61ca4e9973db291fb243f90853ab6b862fa3d2c2.nq.gz
    ├── 63226dd3f9a1c19148d7071fb26f2d0d91b855d3.nq.gz
    ├── 63711ca0ce5b5869d08b64d92303ec5de785ce62.nq.gz
    ├── 644c3dde0083d34b9dc61f7330227dd1d2e49047.nq.gz
    ├── 64889297d55b1b3948c2de008a7fa015e551480e.nq.gz
    ├── 6493db751e9ff8da8c96dc05f1e0921fa872d553.nq.gz
    └── 64bc6eefbdf4f23168f8a8882a4e928f2dc8b192.nq.gz

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

[ansible-community/antsibull-docs](https://github.com/ansible-community/antsibull-docs)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
