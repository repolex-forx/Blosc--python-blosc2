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
│   │   └── d3bca9e53db4d47b06814e3ec055795c32f39482
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── d3bca9e53db4d47b06814e3ec055795c32f39482
│           └── chunk-001.nq.gz
└── blob
    ├── 00725cd0c60a18a347d0fbf9d8cf94b176149332.nq.gz
    ├── 008119c106f8e9a423bc6553c89af580bd4fa1cd.nq.gz
    ├── 008b95338cfd2087e095d4500bbc923788f5d724.nq.gz
    ├── 0130c0118361e7c6ae566e8a3c216fa746622e3e.nq.gz
    ├── 03ef063614cbebcf7cfa59663ea68fcc89048e18.nq.gz
    ├── 04a35fd4875e2821663a5292c71aec84ea9f6915.nq.gz
    ├── 0596ceaca42c1881f907b10ef0a643dc0509cd0b.nq.gz
    ├── 06a6e77849a7fc121734b0031b0dbd4a074e7771.nq.gz
    ├── 07354b59559f8e3f74466b2e2cde82af96853d35.nq.gz
    ├── 07969627e490f7317b402edf8abe8aa2e785273c.nq.gz
    ├── 092e0c2860f0191f2342776292d3360ec650a62d.nq.gz
    ├── 097539f22180839676ddf20001acb6df06610a23.nq.gz
    ├── 097dbeb41e1125c24ff3eb6d79b24b307f4176f8.nq.gz
    ├── 09d16fe020be1b7c999ddb5f2edbccc64217a19e.nq.gz
    ├── 0b82dce89455256b86bd364e109c10e155f6e2f3.nq.gz
    ├── 0b9281b49ca99576e2484ea08792a4258a8acc04.nq.gz
    ├── 0bb8c8ef8378a50db4079255916182a07ec7344b.nq.gz
    ├── 0be97a04433255529dba4be710fc80866e7a9a00.nq.gz
    ├── 0c4794485d4ad372c624c28ea5999dd1139acfae.nq.gz
    ├── 0d18cfa2456aff1cbcaa4a7b1fcfa1393b2ee06e.nq.gz
    ├── 0fc0afed1078cbc91e992e4cc8b35fcbeb43a0d3.nq.gz
    ├── 10bf1287dba878317008993450ca6994ce05ea6c.nq.gz
    ├── 1175edc6e066eee347f3781842b3c415bffe0792.nq.gz
    ├── 125a6c5ecd60aaf225753230137df2ec6ad6f4ca.nq.gz
    ├── 14ee04c9893a5ec1346ab5f08dc8ffcac79999af.nq.gz
    ├── 155b34085380791b8b1d1ef9d12f09e33a0b9a2d.nq.gz
    ├── 15fc9708bf3ee7c8c9ffb3b9eac5722e53df2412.nq.gz
    ├── 160d3a627503cb32fcbdc1afc4c12a5884fb1dc2.nq.gz
    ├── 16641b1e5e501f1107ce63bf5300c99f201b3027.nq.gz
    ├── 166920e131471ce85649eaef75b4d06b16e1b3b6.nq.gz
    ├── 17307b5854cbfd600aea140eab9f385ff3a70c76.nq.gz
    ├── 177ce6078a201cad2cd70607edc3d8c57ad41820.nq.gz
    ├── 18c06b15877de45655a68f6d79df7270ad02c4a4.nq.gz
    ├── 18e8c70b959a33d0c51c8e8ba3cd1a668a6e5f53.nq.gz
    ├── 19a96c67b390c2f3c685f2902a584d6aefe10343.nq.gz
    ├── 19b3889545135bbd60c2081a9aef83d0f2160b80.nq.gz
    ├── 19f90c7bc5bd43750d665be87e5c4b4dbc9befad.nq.gz
    ├── 1a94137670c89168d8080f2cad754cd026242002.nq.gz
    ├── 1ac2c812a8f2c3d20cd814f5354c32dca04d4be9.nq.gz
    ├── 1b5e05909da72f519fe93b9466af2b07ed81dc14.nq.gz
    ├── 1ba38d84e4bf911aa8035b5909a5d4f96c8b4a0d.nq.gz
    ├── 1bc39865340d73dad91db267157dc46d09c2deaf.nq.gz
    ├── 1be57adbd202a18e3b426711ac4cf523dfee6163.nq.gz
    ├── 1d56418d996d136a2f555217f450b7963692d256.nq.gz
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
    ├── 1ecbf1b44e84f288f7023451f7dc9da15545e4c3.nq.gz
    ├── 1fdb257ee57783ea99c34418a002e3a65c594a5a.nq.gz
    ├── 200b1b3e2604ad5593b602ab16507c30931c9c63.nq.gz
    ├── 2085ce11e6b5dbadaff61f9d2d92004015f216ce.nq.gz
    ├── 2193ce3d585ddcc7ea9466f444d2f77db142c1df.nq.gz
    ├── 22449fbab2be5b17a75e2c0e2fe4a041a90abf39.nq.gz
    ├── 230f7b66af5ea812c19cdc93e5083e1e6e2d4945.nq.gz
    ├── 23e24b58c07e6a2ce4e8153e78706fac1f35dd6c.nq.gz
    ├── 23e829e9f7d3f0b94a5dc9805a6956606b6c4002.nq.gz
    ├── 23e8777bfaefdad7d8aaaf6cc20411646d91627d.nq.gz
    ├── 241d027ca1dba929ffb3caa9275b2a4014c4aa51.nq.gz
    ├── 24e0f89d85d5a95edf16d90b602331bd3283e6c6.nq.gz
    ├── 2568d31712b901df768959b4f221ec8fda88d233.nq.gz
    ├── 25c35a8afe4e78988011ba91ea2a0863b6b6d040.nq.gz
    ├── 2670835c5a28c95aae7a4a5ca76e37bad1bab65b.nq.gz
    ├── 26a929b59fd2bfae3aa55a83ec26c773bf411c50.nq.gz
    ├── 272e936eb0b50966dc64a16c338a1357f36f8bb1.nq.gz
    ├── 273bc3a05bd60ca028f31c36e633efa4a51f618b.nq.gz
    ├── 28120e6816fe8b374fecc047df73d063fe748161.nq.gz
    ├── 2894757b231dbe39de65b2ac3567eb82b8478239.nq.gz
    ├── 2910c345531b7eb354d0d45e871c265deae8f8b6.nq.gz
    ├── 29f942f712c2a1030408e248d8e60207987642ba.nq.gz
    ├── 2a4ed189003c0d82677c724b63a907999590d2a7.nq.gz
    ├── 2a5cbf5069d893e8619d01cb9a533deb07625409.nq.gz
    ├── 2a5eaa4394db38fd6c9ed8ebccfe6fb2a8686971.nq.gz
    ├── 2a95e4bca622b23b65c11c1dceeb4a669b303d7b.nq.gz
    ├── 2aa5df5aa7360ad2664b9a3c1c48577e69b0abed.nq.gz
    ├── 2b6d8b7dbeba79995e9f994ca8e8736d90b3e05b.nq.gz
    ├── 2bebb9066e7e99275db1cab4a50a9d5aaabf6eff.nq.gz
    ├── 2c14d22f4cead0b23af011dc747e4e93b1d5ab5c.nq.gz
    ├── 2c5d78a0833390e4d061bb154a0f4f7bb9074cd0.nq.gz
    ├── 2c627876a940bd1f01659ae538b9fe9cb277b1cb.nq.gz
    ├── 2c6db7d658bacbb28775e22f0b75ff1eb6b43817.nq.gz
    ├── 2c7bcaaaeb82bbf8573053613681c302bb9a235c.nq.gz
    ├── 2c94025cb6ecd4cb2a01b98c7e7503dd549f3060.nq.gz
    ├── 2d04d195129d9c1acab500fc0850dc32ced40706.nq.gz
    ├── 2df9ef11e751d6c8896562fcf724b1c53baf0246.nq.gz
    ├── 2e6c9ed4d05b4eb14d0e21c148df48eaaeeef12f.nq.gz
    ├── 2e6d0a6e707943c7d43a341ca2f1763d54c7f2b8.nq.gz
    ├── 2e905df5dc597570181492f254f5cf47d3a272b9.nq.gz
    ├── 2f86142c8cd278cca033f4818b6784854a518958.nq.gz
    ├── 2f8e901369c2d7509a60fd8dacd7f9d6480bf4e9.nq.gz
    ├── 2fee6d7caee3d8182b458e4af51100b770746189.nq.gz
    ├── 2ff83bd7008ed5494f5217920773c59d9f4d835a.nq.gz
    ├── 302dc57119341d07a1c7fc661f392bfa476c68b3.nq.gz
    ├── 30490f95fe8d6efcec121424d3bbff696255abef.nq.gz
    ├── 3096b79dfb876d190ae1daa715123ac2ab3900c9.nq.gz
    ├── 3234df7180c4796c5e8e2801a9b36e0c5cbf72c1.nq.gz
    ├── 32b937041e50cead29901732dd4c1d21b6ac0e3c.nq.gz
    ├── 32c6b7b1f2d5d66a746c82e9742a1a4929621d8a.nq.gz
    ├── 33067ce50bba07af2d0c66a0b867001fad8dfb12.nq.gz
    ├── 3355068bdef2f7225bba8abc62f69b430bd76b46.nq.gz
    ├── 3495b50d4760bb653b3790a42f92b02b72e64e37.nq.gz
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
    ├── 3d6097fe0900f75c82b8eb967f65a107eb927c62.nq.gz
    ├── 3e3553a08d427b732f8dcf80fc6c2624ca9d70c4.nq.gz
    ├── 3f328f756be26d786d352c0e747f87dccc70a245.nq.gz
    ├── 403b0d31e63bb5b362627ebd025e019b09133b7e.nq.gz
    ├── 40f70288f8a8b775dcc7ae764dd4394540bdf86f.nq.gz
    ├── 41015218df78a4561e7f5e60dd85008b992074d9.nq.gz
    ├── 41afc0698a1a423f9ee14defc44191f3b831aac4.nq.gz
    ├── 41d8f6bc8e60752321abfb14f96579edd96e7908.nq.gz
    ├── 42f2c1925be633dad0df15979dc248efee6e899c.nq.gz
    ├── 438ec6b32934b161fef1a20c2520c891c2732a1d.nq.gz
    ├── 442fabb28a3b47dd823f3f99e7f8f79c17b1aea7.nq.gz
    ├── 44d272db8518173d19b7b76e351bd18f6be900f8.nq.gz
    ├── 4541da471cf5ed1c84c6b1139776f98fbd1cfe10.nq.gz
    ├── 4567e00f76ac52661b90c0648b3085704ddc286a.nq.gz
    ├── 46db8e2a6f6dd804db1d74e7469214b22b253022.nq.gz
    ├── 46ef5c94d8ee6b8bdddca8ea3d2452bd50da8e21.nq.gz
    ├── 472f483fee0dca844952be96ae9d29003c4add51.nq.gz
    ├── 47efce451b4fbcad4747296d2a68435298a84755.nq.gz
    ├── 48fed2f0b22f42a5a4358b6eeb147183c7265337.nq.gz
    ├── 490fd8a4b64b77443d8cb8583c07aab03417cf8c.nq.gz
    ├── 491c3c2afad46b76d3ef2d278819e53ac24886bb.nq.gz
    ├── 493447210aa2e6d514f8b7f0ea85d048412d1f5f.nq.gz
    ├── 4956b2e857b4cb1fc01f0e4ff8644a49dbe16194.nq.gz
    ├── 4a2427145a73c58a2cd1b773c8aea9bbebc354e1.nq.gz
    ├── 4b112bd9939f22040b0b2e60951450c411daa8d0.nq.gz
    ├── 4b1215f4a3e7b3c8c3fabc308d9a8f8894ef3125.nq.gz
    ├── 4bb5fd3c0c498f4e98ae9f12353a5ca1c6efe9ef.nq.gz
    ├── 4bbedbc1f17f2bb5848815adccb2fa7824f1fcbf.nq.gz
    ├── 4bc4e17eccb751b25a2003e75119d944cafa36de.nq.gz
    ├── 4bdf4965c31e174566d5eb1458335771cf146879.nq.gz
    ├── 4c13483e7e5f34a93a4033e270cfc0f22ee4d338.nq.gz
    ├── 4c8f938f4189ff830651af9f5298f2d22b69a303.nq.gz
    ├── 4d50dec3bc832367591e2e89a0eabd94adfca333.nq.gz
    ├── 4dd315817fbabe41c087d8decfed2d44d08ef6e7.nq.gz
    ├── 4e2a3ae20e25f83f0d972e5f81564b51ff657021.nq.gz
    ├── 4ea95c425f5ab78f319d4008ce3c26663ff4204b.nq.gz
    ├── 4ee1b06316b909ba23df0d8355c38cf3bc2f6b85.nq.gz
    ├── 4fe6428100ad10abce360f5f4359830ac8bfe0f0.nq.gz
    ├── 51bc5eac175775b165a118eba34b766e42b53f48.nq.gz
    ├── 51ff083dd574be77ac8c7b287951721fc8708b99.nq.gz
    ├── 5322c50ccab45350604a16f89f550e199b233fbc.nq.gz
    ├── 542978b4c92ddde0dd3ed0c53189de64d47ad972.nq.gz
    ├── 54477ad4ec9ab9897f9d6f8b3942d82e6c27b9da.nq.gz
    ├── 54bc57a0568bd497dc3df6552089f40ea1e31491.nq.gz
    ├── 550e48594a1484e0febfd9f80a6bc034dd7816e8.nq.gz
    ├── 5567526fdbe782507b71294d0844ef0b6116d21d.nq.gz
    ├── 55699fe2bfa93c48b7619191c680993c5459dbd0.nq.gz
    ├── 5624b6771aa8f92aca0f9da73743240f3e2e9a92.nq.gz
    ├── 564680242ee493b0508c70fe4a0529278a4caa07.nq.gz
    ├── 56e252b8188e426697ed260482a883f2c0aec5f6.nq.gz
    ├── 579ca7abe6caf2d34ec7293d8b760f8a76fcec55.nq.gz
    ├── 57cd09a4e919a6f89d66756000584b4162789d81.nq.gz
    ├── 57e10771cc3f0acb3c8d4a614a33fd9dceb9080e.nq.gz
    ├── 581e22a04cdd7bb9bdf7db0d88531d19d3ea4777.nq.gz
    ├── 58a52a25d298200b891ae2c6c17c468554067f0a.nq.gz
    ├── 5992817fb7d7b5922853a5e8d1e42f02534f8de8.nq.gz
    ├── 5a2778f6905efb0c1154941c9c11b4dc3e1f432a.nq.gz
    ├── 5a47f05effcbc404cdf9ea85269d804ae556bbb6.nq.gz
    ├── 5b8d94a614644340a136d78b1b9ebfd5a614e691.nq.gz
    ├── 5bb46c2ba4e53dc0498411a63986d29c0878e3b4.nq.gz
    ├── 5c1cb1b295ff292a0a1131463d2a5e60983e01b3.nq.gz
    ├── 5caa2c681e8e4b9517dbe76d2c43ace451626e3e.nq.gz
    ├── 5d9e25f3ad64f2bc87d9bfa27a122ee4e78085ee.nq.gz
    ├── 5e0506398b8bda3d961cf2847a4485cd999aed9b.nq.gz
    ├── 5e5cdbfe87478f605dbbe075d0b416e63079cae5.nq.gz
    ├── 5eb9e4ff2cbcc91158c1d1fbfd77f5f4cc94fecd.nq.gz
    ├── 5f6b840fa9bb08c49b5b5c3b7c9c6f0f81539f2e.nq.gz
    ├── 5fa13d125b24c655386f7dd660b1e669aeee1776.nq.gz
    ├── 6053442ec0ee115822da66eec54034b624ce7a0b.nq.gz
    ├── 60fc91517f05fc8b88e0b69e2fd27787067f67d0.nq.gz
    ├── 614494f09b430f298126c839c218dccbdec20a92.nq.gz
    ├── 627163c4e9f00d9122f613c927d059c31b3d1873.nq.gz
    ├── 62947526ef6854f96b3044070aa039cd3813a2c7.nq.gz
    └── 6349be8317a177d70704c9086911ad8d1338ee96.nq.gz

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

[Blosc/python-blosc2](https://github.com/Blosc/python-blosc2)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
