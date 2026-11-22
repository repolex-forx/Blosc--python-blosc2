# Repolex Knowledge Graph of Blosc/python-blosc2

RDF knowledge graph data for [Blosc/python-blosc2](https://github.com/Blosc/python-blosc2), parsed by [repolex](https://repolex.ai).

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
rlex download Blosc/python-blosc2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0fc782e4c558aa181580515af6d1203d6bf3efbc
│   │   │   └── chunk-001.nq.gz
│   │   └── d3bca9e53db4d47b06814e3ec055795c32f39482
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   └── 0fc782e4c558aa181580515af6d1203d6bf3efbc.nq.gz
│   └── repolex
│       ├── 0fc782e4c558aa181580515af6d1203d6bf3efbc
│       │   └── chunk-001.nq.gz
│       └── d3bca9e53db4d47b06814e3ec055795c32f39482
│           └── chunk-001.nq.gz
└── blob
    ├── 00725cd0c60a18a347d0fbf9d8cf94b176149332.nq.gz
    ├── 008119c106f8e9a423bc6553c89af580bd4fa1cd.nq.gz
    ├── 008b95338cfd2087e095d4500bbc923788f5d724.nq.gz
    ├── 00df2fd6419874d7725262d4bd5021863d5efc14.nq.gz
    ├── 0130c0118361e7c6ae566e8a3c216fa746622e3e.nq.gz
    ├── 0134af8892114744824e0d7fae581d2ba1d8f170.nq.gz
    ├── 014519a528f13a072616411d1449e39b50f1c9ec.nq.gz
    ├── 01c0bc4836b9b89a30810be0772e63d27d3eaadb.nq.gz
    ├── 028f5ae2ca39efa2279d5a37a06c207ea4495e8d.nq.gz
    ├── 02a0a336a960885942f8c8bb75914a595a942c22.nq.gz
    ├── 032105ebd63a03c8a29bf649583ddf17483f4ba1.nq.gz
    ├── 03ef063614cbebcf7cfa59663ea68fcc89048e18.nq.gz
    ├── 04a35fd4875e2821663a5292c71aec84ea9f6915.nq.gz
    ├── 0596ceaca42c1881f907b10ef0a643dc0509cd0b.nq.gz
    ├── 064341ccd72649ffbe94a749b654eb4082fb508b.nq.gz
    ├── 06a6e77849a7fc121734b0031b0dbd4a074e7771.nq.gz
    ├── 07354b59559f8e3f74466b2e2cde82af96853d35.nq.gz
    ├── 07397fec1cfd9e3760e36f2c608cd30e49374614.nq.gz
    ├── 07969627e490f7317b402edf8abe8aa2e785273c.nq.gz
    ├── 07a78247468136593557ce2bfd8c5e370685a65d.nq.gz
    ├── 07e0f600c87c47f51e4fa7d9ae0fb44a6d7b3713.nq.gz
    ├── 08d5691119b1d1373d7d12fcb6a34e211bbf8c72.nq.gz
    ├── 092e0c2860f0191f2342776292d3360ec650a62d.nq.gz
    ├── 097539f22180839676ddf20001acb6df06610a23.nq.gz
    ├── 097dbeb41e1125c24ff3eb6d79b24b307f4176f8.nq.gz
    ├── 09c39e2f14170d555caf68209bb852e2e6003e14.nq.gz
    ├── 09d16fe020be1b7c999ddb5f2edbccc64217a19e.nq.gz
    ├── 09d8b5164acb293357ac2946c6a1222427e61370.nq.gz
    ├── 09f87e70802c3b5d7753d97cef22b0c004911acb.nq.gz
    ├── 0b82dce89455256b86bd364e109c10e155f6e2f3.nq.gz
    ├── 0b9281b49ca99576e2484ea08792a4258a8acc04.nq.gz
    ├── 0bb8c8ef8378a50db4079255916182a07ec7344b.nq.gz
    ├── 0be97a04433255529dba4be710fc80866e7a9a00.nq.gz
    ├── 0c4794485d4ad372c624c28ea5999dd1139acfae.nq.gz
    ├── 0cb58c5a89e1c1f50e765974a2f840eb6a5ff8cc.nq.gz
    ├── 0d18cfa2456aff1cbcaa4a7b1fcfa1393b2ee06e.nq.gz
    ├── 0d5f99c03a13e5001f7a8bf0bd4158532bcad59b.nq.gz
    ├── 0dbcdf820555c139ca51fed056fb2c7e2e891f8e.nq.gz
    ├── 0ef9ec753d40c2a5d0d6c936bd7954516d5d0816.nq.gz
    ├── 0f2da850bb0cba551a7328a3ee37eb47ee357b92.nq.gz
    ├── 0fc0afed1078cbc91e992e4cc8b35fcbeb43a0d3.nq.gz
    ├── 10395c3db96e68459223b454717fb6226b947cd5.nq.gz
    ├── 107981adbfbfc01a2796f317fc24b1f1cc9c9ae6.nq.gz
    ├── 10bf1287dba878317008993450ca6994ce05ea6c.nq.gz
    ├── 1175edc6e066eee347f3781842b3c415bffe0792.nq.gz
    ├── 11d3173b9dba7a945ecd3bd4ca1a46d9ab16555e.nq.gz
    ├── 125a6c5ecd60aaf225753230137df2ec6ad6f4ca.nq.gz
    ├── 133f9fec43599628d63a0f50f6d0fc8766afde66.nq.gz
    ├── 14bb6710267d3e675f542961c86d2d620a446446.nq.gz
    ├── 14ee04c9893a5ec1346ab5f08dc8ffcac79999af.nq.gz
    ├── 1525d3671f65afec2ca39fe77ddb71f59b30c833.nq.gz
    ├── 154830b8b6ce34b16f8af4f2ad34e00578c115e8.nq.gz
    ├── 155b34085380791b8b1d1ef9d12f09e33a0b9a2d.nq.gz
    ├── 15648e99585ab20563f933d88376786fd08afe61.nq.gz
    ├── 15fc9708bf3ee7c8c9ffb3b9eac5722e53df2412.nq.gz
    ├── 160d3a627503cb32fcbdc1afc4c12a5884fb1dc2.nq.gz
    ├── 1628b9f32960fb856d327862b038998a77f7cbc8.nq.gz
    ├── 1645d9f7ab4cc2823814d9be22a041086f89e3cf.nq.gz
    ├── 16641b1e5e501f1107ce63bf5300c99f201b3027.nq.gz
    ├── 166920e131471ce85649eaef75b4d06b16e1b3b6.nq.gz
    ├── 17307b5854cbfd600aea140eab9f385ff3a70c76.nq.gz
    ├── 177ce6078a201cad2cd70607edc3d8c57ad41820.nq.gz
    ├── 17a1c8b9f3475f6d903dab35061c5a850db53eec.nq.gz
    ├── 18bedc8bbf63c42c49554a4e83b89431c2751f82.nq.gz
    ├── 18c06b15877de45655a68f6d79df7270ad02c4a4.nq.gz
    ├── 18e8c70b959a33d0c51c8e8ba3cd1a668a6e5f53.nq.gz
    ├── 19a96c67b390c2f3c685f2902a584d6aefe10343.nq.gz
    ├── 19b080c5ce43107bd095360ce5ab53ffa6476d73.nq.gz
    ├── 19b3889545135bbd60c2081a9aef83d0f2160b80.nq.gz
    ├── 19f90c7bc5bd43750d665be87e5c4b4dbc9befad.nq.gz
    ├── 1a87ec867d4972a3ff5933ae82c1c215648a3871.nq.gz
    ├── 1a94137670c89168d8080f2cad754cd026242002.nq.gz
    ├── 1aa6deb00a31a867d08e24b6a61e6ced540e544f.nq.gz
    ├── 1aa7badab52cd115ee0c5f6bcc0933b54cff7b3f.nq.gz
    ├── 1ac2c812a8f2c3d20cd814f5354c32dca04d4be9.nq.gz
    ├── 1b5e05909da72f519fe93b9466af2b07ed81dc14.nq.gz
    ├── 1b7cdd3ce6fa0cfce640c4df570a0fc7a12583a7.nq.gz
    ├── 1ba38d84e4bf911aa8035b5909a5d4f96c8b4a0d.nq.gz
    ├── 1bc39865340d73dad91db267157dc46d09c2deaf.nq.gz
    ├── 1be57adbd202a18e3b426711ac4cf523dfee6163.nq.gz
    ├── 1d56418d996d136a2f555217f450b7963692d256.nq.gz
    ├── 1d5c7f7d8812713c045b29ce9dfdc0a58e1e0573.nq.gz
    ├── 1d7a632a864d93b0eccb50a026be392b7c94c168.nq.gz
    ├── 1d7bd308cc6ebd6706ec8569570380145412c710.nq.gz
    ├── 1d87029b67f3e181e2085cba9b0323ee0b32cb08.nq.gz
    ├── 1dac36566e3d3b726ec5934dc0f2d13c29400411.nq.gz
    ├── 1dd4fd14af74e408b358a413b052be7fe01e7c31.nq.gz
    ├── 1de0f19fbf898a80b3c54252d601c34942aafefc.nq.gz
    ├── 1dee30e5eb8fb401aa84090d8f984a2eb66acc67.nq.gz
    ├── 1dfee1f425cdac8507721b270c46602bbe19ce9c.nq.gz
    ├── 1e486d264c4c4180d77936da0b73c648504c57e0.nq.gz
    ├── 1e60c429fe54eec859403b56a1e02e39f9c46232.nq.gz
    ├── 1e803be85aa537f4d18167990eeebba7866d27c8.nq.gz
    ├── 1eabdfda10f0a0b10ed1c2e4c6e5d96ff401d4f0.nq.gz
    ├── 1ebfc601e63793187eebe0ce9740258bd9ecd7fc.nq.gz
    ├── 1ecbf1b44e84f288f7023451f7dc9da15545e4c3.nq.gz
    ├── 1f8b3580913048ffeb9770f74e427f5a67607596.nq.gz
    ├── 1fdb257ee57783ea99c34418a002e3a65c594a5a.nq.gz
    ├── 200b1b3e2604ad5593b602ab16507c30931c9c63.nq.gz
    ├── 2085ce11e6b5dbadaff61f9d2d92004015f216ce.nq.gz
    ├── 2193ce3d585ddcc7ea9466f444d2f77db142c1df.nq.gz
    ├── 21b4744ae166eb7bc4b89094da66f3845700b3cf.nq.gz
    ├── 21b76e07125822aa6225ae41ffba01e6d52826a1.nq.gz
    ├── 22449fbab2be5b17a75e2c0e2fe4a041a90abf39.nq.gz
    ├── 22b685f6af13a78ec20725da97f7fa572224603d.nq.gz
    ├── 22ea9ee179a5babcecac12deeeb5d06ec0098568.nq.gz
    ├── 230f7b66af5ea812c19cdc93e5083e1e6e2d4945.nq.gz
    ├── 23e24b58c07e6a2ce4e8153e78706fac1f35dd6c.nq.gz
    ├── 23e829e9f7d3f0b94a5dc9805a6956606b6c4002.nq.gz
    ├── 23e8777bfaefdad7d8aaaf6cc20411646d91627d.nq.gz
    ├── 241d027ca1dba929ffb3caa9275b2a4014c4aa51.nq.gz
    ├── 244495545574992cc0d31fcf362c3f6604bc7769.nq.gz
    ├── 24870afbd13c4782bcae2ff0a9b61c4db21b58ed.nq.gz
    ├── 24e0f89d85d5a95edf16d90b602331bd3283e6c6.nq.gz
    ├── 24f3d6033cdd1bec91b4d618248cee1ef57edfb3.nq.gz
    ├── 2568d31712b901df768959b4f221ec8fda88d233.nq.gz
    ├── 25c35a8afe4e78988011ba91ea2a0863b6b6d040.nq.gz
    ├── 2670835c5a28c95aae7a4a5ca76e37bad1bab65b.nq.gz
    ├── 26a929b59fd2bfae3aa55a83ec26c773bf411c50.nq.gz
    ├── 272e936eb0b50966dc64a16c338a1357f36f8bb1.nq.gz
    ├── 273bc3a05bd60ca028f31c36e633efa4a51f618b.nq.gz
    ├── 28120e6816fe8b374fecc047df73d063fe748161.nq.gz
    ├── 2894757b231dbe39de65b2ac3567eb82b8478239.nq.gz
    ├── 290846e2548f213493b2ee10ea0a346bc9cf709b.nq.gz
    ├── 2910c345531b7eb354d0d45e871c265deae8f8b6.nq.gz
    ├── 2942e94b448fadf62dcabfb438162c1167ea1fd8.nq.gz
    ├── 29d12c432d575a7f0aac0cf632f6fd2911e0da74.nq.gz
    ├── 29f942f712c2a1030408e248d8e60207987642ba.nq.gz
    ├── 2a4ed189003c0d82677c724b63a907999590d2a7.nq.gz
    ├── 2a5cbf5069d893e8619d01cb9a533deb07625409.nq.gz
    ├── 2a5eaa4394db38fd6c9ed8ebccfe6fb2a8686971.nq.gz
    ├── 2a95e4bca622b23b65c11c1dceeb4a669b303d7b.nq.gz
    ├── 2aa5df5aa7360ad2664b9a3c1c48577e69b0abed.nq.gz
    ├── 2b6d8b7dbeba79995e9f994ca8e8736d90b3e05b.nq.gz
    ├── 2bc22c36d8105dedcfc3d67f4fb1e23c9946acdb.nq.gz
    ├── 2bebb9066e7e99275db1cab4a50a9d5aaabf6eff.nq.gz
    ├── 2c14d22f4cead0b23af011dc747e4e93b1d5ab5c.nq.gz
    ├── 2c2adb15bb170f27abddb599be616a4b49ad4e55.nq.gz
    ├── 2c5d78a0833390e4d061bb154a0f4f7bb9074cd0.nq.gz
    ├── 2c627876a940bd1f01659ae538b9fe9cb277b1cb.nq.gz
    ├── 2c6db7d658bacbb28775e22f0b75ff1eb6b43817.nq.gz
    ├── 2c7bcaaaeb82bbf8573053613681c302bb9a235c.nq.gz
    ├── 2c8a6464d38539410805b8baf99e4cd2c14c453c.nq.gz
    ├── 2c94025cb6ecd4cb2a01b98c7e7503dd549f3060.nq.gz
    ├── 2d04d195129d9c1acab500fc0850dc32ced40706.nq.gz
    ├── 2daba1826bdef4c81a43c21c0c5f404dda538ac6.nq.gz
    ├── 2dbab4847c534a273fb30468bceb43f5301bda13.nq.gz
    ├── 2df9ef11e751d6c8896562fcf724b1c53baf0246.nq.gz
    ├── 2e42b96287f57b841c39cdae88758e9ee68caafc.nq.gz
    ├── 2e6c9ed4d05b4eb14d0e21c148df48eaaeeef12f.nq.gz
    ├── 2e6d0a6e707943c7d43a341ca2f1763d54c7f2b8.nq.gz
    ├── 2e905df5dc597570181492f254f5cf47d3a272b9.nq.gz
    ├── 2f3a8b7be3ccf80f7c5fe796e119574dc8d61600.nq.gz
    ├── 2f86142c8cd278cca033f4818b6784854a518958.nq.gz
    ├── 2f8e901369c2d7509a60fd8dacd7f9d6480bf4e9.nq.gz
    ├── 2fee6d7caee3d8182b458e4af51100b770746189.nq.gz
    ├── 2ff83bd7008ed5494f5217920773c59d9f4d835a.nq.gz
    ├── 302dc57119341d07a1c7fc661f392bfa476c68b3.nq.gz
    ├── 30490f95fe8d6efcec121424d3bbff696255abef.nq.gz
    ├── 3096b79dfb876d190ae1daa715123ac2ab3900c9.nq.gz
    ├── 31b0e2298c31b18bae9ada7a5ffc863f9692125e.nq.gz
    ├── 3234df7180c4796c5e8e2801a9b36e0c5cbf72c1.nq.gz
    ├── 32b937041e50cead29901732dd4c1d21b6ac0e3c.nq.gz
    ├── 32c6b7b1f2d5d66a746c82e9742a1a4929621d8a.nq.gz
    ├── 33067ce50bba07af2d0c66a0b867001fad8dfb12.nq.gz
    ├── 3355068bdef2f7225bba8abc62f69b430bd76b46.nq.gz
    ├── 3495b50d4760bb653b3790a42f92b02b72e64e37.nq.gz
    ├── 35ddbd9146ceb7615de8b33fbf02f5ddf6fed123.nq.gz
    ├── 35f347d40286e2b50fc45e42d2307342aaf184c4.nq.gz
    ├── 362dc52e34a34b2fdd141026cc70a56f5da6097f.nq.gz
    ├── 36dbcacb5d79a65ea6e5ef5f22fa226976e09524.nq.gz
    ├── 36f5b4ddb9002702f38199fca3037b85ad7f6600.nq.gz
    ├── 3922f49f2247395bd845a433a0be6502789939c8.nq.gz
    ├── 393b502fec128600ef67d35ac062f2a61f368f2e.nq.gz
    ├── 39e23f055a4b3235d407940831c10daf8e1b1d89.nq.gz
    ├── 3a0f16f23d50d641846257320b5ede6d1dd7dd73.nq.gz
    ├── 3aa2999e8cbd31f1a093ca0bf52c972769006d5a.nq.gz
    ├── 3ae5397a7bc11161b9758466e08aa8ce040038d3.nq.gz
    ├── 3af0769950022520af421a0b115a779eb065f0fd.nq.gz
    ├── 3af0aecee5a11f7d747c16da49d836a27aa8e4b9.nq.gz
    ├── 3b16e720b02703ab5647caa9f3641a5b658a07a4.nq.gz
    ├── 3b30bfb667c345f39231fef49d4f5f4ceb8fb1e4.nq.gz
    ├── 3bb108f91f4afd492091f0dd796da3f115952f93.nq.gz
    ├── 3c11a5858f79b585fb1723a9de1a16d292fb3227.nq.gz
    ├── 3c5344d041a5a1bbbed8ca39821b6212257f2158.nq.gz
    ├── 3c6710de325db6ff35c605e25c4dde275a3161f5.nq.gz
    ├── 3ce0f312e941ffec96263d9d2248e365217c1006.nq.gz
    ├── 3d6097fe0900f75c82b8eb967f65a107eb927c62.nq.gz
    ├── 3e3553a08d427b732f8dcf80fc6c2624ca9d70c4.nq.gz
    ├── 3e5309209e49f3eb125345273bd1c6513b5aa4f8.nq.gz
    ├── 3eee9c9911aaab2c3ea716af5849c5c7309ad49c.nq.gz
    ├── 3f328f756be26d786d352c0e747f87dccc70a245.nq.gz
    ├── 3fd26d57af5f9bd2657a7fd9ddb9b06ed0a4445d.nq.gz
    └── 403b0d31e63bb5b362627ebd025e019b09133b7e.nq.gz

10 directories, 200 files
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

[Blosc/python-blosc2](https://github.com/Blosc/python-blosc2)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
