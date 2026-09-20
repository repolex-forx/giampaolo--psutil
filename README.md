# Repolex Knowledge Graph of giampaolo/psutil

RDF knowledge graph data for [giampaolo/psutil](https://github.com/giampaolo/psutil), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download giampaolo/psutil
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0d18187e79b349e577fadabd3589f8fdbf99bf5a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0d4900b073f8697ab21c47d823621bea61f39a3b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 27a1432daeacd46b287517c11bfea2af4fd95a88
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3d5522aafb6c9cbcbcf4edfa11348f755af97d96
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4650d44a9ba6ac06a8161e7778b0556cd5573b1c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 58552f6aa9f7dfb964596e28519ad77b8374defd
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5904ff94e3fd0fea3d0734a936834bef6e63369a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6130c19da2d01383befa0dfca2371a792f8881af
│   │   │   └── chunk-001.nq.gz
│   │   ├── 704e218db7da14e98a54f2aa9f93372d5900e0b4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8e21684cf34fccab5868b13fcedd69b3598be6f9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8eb2930539e8030bae94255040a6254889c0fb05
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9267775415c6464478457e9ac332f83787a7acc2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 992dfe4620bbda3316b54c53b63236f3159aa5f9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9eea97dd6f1d16ea33f5144c8925f1ce7a0688e1
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9f9a82d02c901f62512236b44edb050f84cbe5b6
│   │   │   └── chunk-001.nq.gz
│   │   ├── a07e87a1336678cbcc929116cd826137779cf654
│   │   │   └── chunk-001.nq.gz
│   │   ├── a0967043b5819b2edc61d9a12306289d5e7f98c2
│   │   │   └── chunk-001.nq.gz
│   │   ├── aa1253c92984e5be6335c024d84e7ec1072baddf
│   │   │   └── chunk-001.nq.gz
│   │   ├── aae4346a560601e0417188f55cdd2d2a0e606fa7
│   │   │   └── chunk-001.nq.gz
│   │   ├── b760f4848db4db49de57918660f6a5059666b720
│   │   │   └── chunk-001.nq.gz
│   │   ├── c6cd256da95ffe9599792759b1c2586ba24fa047
│   │   │   └── chunk-001.nq.gz
│   │   ├── c948ef07e46b114a61492c9d207c741339fceeb2
│   │   │   └── chunk-001.nq.gz
│   │   ├── ea5b55605f857affa4e65fa27eb80f4f2bfebd63
│   │   │   └── chunk-001.nq.gz
│   │   ├── f1a54ad88527e0706fb8a88ad7daae80686acc62
│   │   │   └── chunk-001.nq.gz
│   │   └── fb68f9fae3b398899d87161746884ebb2a2613c0
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0d18187e79b349e577fadabd3589f8fdbf99bf5a.nq.gz
│   │   ├── 0d4900b073f8697ab21c47d823621bea61f39a3b.nq.gz
│   │   ├── 27a1432daeacd46b287517c11bfea2af4fd95a88.nq.gz
│   │   ├── 3d5522aafb6c9cbcbcf4edfa11348f755af97d96.nq.gz
│   │   ├── 4650d44a9ba6ac06a8161e7778b0556cd5573b1c.nq.gz
│   │   ├── 58552f6aa9f7dfb964596e28519ad77b8374defd.nq.gz
│   │   ├── 5904ff94e3fd0fea3d0734a936834bef6e63369a.nq.gz
│   │   ├── 6130c19da2d01383befa0dfca2371a792f8881af.nq.gz
│   │   ├── 704e218db7da14e98a54f2aa9f93372d5900e0b4.nq.gz
│   │   ├── 8e21684cf34fccab5868b13fcedd69b3598be6f9.nq.gz
│   │   ├── 8eb2930539e8030bae94255040a6254889c0fb05.nq.gz
│   │   ├── 9267775415c6464478457e9ac332f83787a7acc2.nq.gz
│   │   ├── 992dfe4620bbda3316b54c53b63236f3159aa5f9.nq.gz
│   │   ├── 9eea97dd6f1d16ea33f5144c8925f1ce7a0688e1.nq.gz
│   │   ├── 9f9a82d02c901f62512236b44edb050f84cbe5b6.nq.gz
│   │   ├── a07e87a1336678cbcc929116cd826137779cf654.nq.gz
│   │   ├── a0967043b5819b2edc61d9a12306289d5e7f98c2.nq.gz
│   │   ├── aa1253c92984e5be6335c024d84e7ec1072baddf.nq.gz
│   │   ├── aae4346a560601e0417188f55cdd2d2a0e606fa7.nq.gz
│   │   ├── b760f4848db4db49de57918660f6a5059666b720.nq.gz
│   │   ├── c6cd256da95ffe9599792759b1c2586ba24fa047.nq.gz
│   │   ├── c948ef07e46b114a61492c9d207c741339fceeb2.nq.gz
│   │   ├── ea5b55605f857affa4e65fa27eb80f4f2bfebd63.nq.gz
│   │   ├── f1a54ad88527e0706fb8a88ad7daae80686acc62.nq.gz
│   │   └── fb68f9fae3b398899d87161746884ebb2a2613c0.nq.gz
│   └── repolex
│       ├── 0d18187e79b349e577fadabd3589f8fdbf99bf5a
│       │   └── chunk-001.nq.gz
│       ├── 0d4900b073f8697ab21c47d823621bea61f39a3b
│       │   └── chunk-001.nq.gz
│       ├── 27a1432daeacd46b287517c11bfea2af4fd95a88
│       │   └── chunk-001.nq.gz
│       ├── 3d5522aafb6c9cbcbcf4edfa11348f755af97d96
│       │   └── chunk-001.nq.gz
│       ├── 4650d44a9ba6ac06a8161e7778b0556cd5573b1c
│       │   └── chunk-001.nq.gz
│       ├── 58552f6aa9f7dfb964596e28519ad77b8374defd
│       │   └── chunk-001.nq.gz
│       ├── 5904ff94e3fd0fea3d0734a936834bef6e63369a
│       │   └── chunk-001.nq.gz
│       ├── 6130c19da2d01383befa0dfca2371a792f8881af
│       │   └── chunk-001.nq.gz
│       ├── 704e218db7da14e98a54f2aa9f93372d5900e0b4
│       │   └── chunk-001.nq.gz
│       ├── 8e21684cf34fccab5868b13fcedd69b3598be6f9
│       │   └── chunk-001.nq.gz
│       ├── 8eb2930539e8030bae94255040a6254889c0fb05
│       │   └── chunk-001.nq.gz
│       ├── 9267775415c6464478457e9ac332f83787a7acc2
│       │   └── chunk-001.nq.gz
│       ├── 992dfe4620bbda3316b54c53b63236f3159aa5f9
│       │   └── chunk-001.nq.gz
│       ├── 9eea97dd6f1d16ea33f5144c8925f1ce7a0688e1
│       │   └── chunk-001.nq.gz
│       ├── 9f9a82d02c901f62512236b44edb050f84cbe5b6
│       │   └── chunk-001.nq.gz
│       ├── a07e87a1336678cbcc929116cd826137779cf654
│       │   └── chunk-001.nq.gz
│       ├── a0967043b5819b2edc61d9a12306289d5e7f98c2
│       │   └── chunk-001.nq.gz
│       ├── aa1253c92984e5be6335c024d84e7ec1072baddf
│       │   └── chunk-001.nq.gz
│       ├── aae4346a560601e0417188f55cdd2d2a0e606fa7
│       │   └── chunk-001.nq.gz
│       ├── b760f4848db4db49de57918660f6a5059666b720
│       │   └── chunk-001.nq.gz
│       ├── c6cd256da95ffe9599792759b1c2586ba24fa047
│       │   └── chunk-001.nq.gz
│       ├── c948ef07e46b114a61492c9d207c741339fceeb2
│       │   └── chunk-001.nq.gz
│       ├── ea5b55605f857affa4e65fa27eb80f4f2bfebd63
│       │   └── chunk-001.nq.gz
│       ├── f1a54ad88527e0706fb8a88ad7daae80686acc62
│       │   └── chunk-001.nq.gz
│       └── fb68f9fae3b398899d87161746884ebb2a2613c0
│           └── chunk-001.nq.gz
└── blob
    ├── 000323c5ddcfc50bb89ea2a5b1e588a9ed72194f.nq.gz
    ├── 0005e4a18161936b992e88ddcc745927fd009b96.nq.gz
    ├── 003a7d081764adec64932104b990585f430acdfe.nq.gz
    ├── 004174561779f11f1ccb0cda72af31660a1f43b8.nq.gz
    ├── 0042adbeb810b97899ca1848fbe8f2ce2bfb9ffb.nq.gz
    ├── 00ad666517c6de1e399782a5abb27363954308b3.nq.gz
    ├── 00f57116f6e953435e0dfc49ba0b627a48aba4da.nq.gz
    ├── 016dcfaa03814120bd9517ca5494badaabb296d7.nq.gz
    ├── 01974513f035ecd46ffb47404eb0cfb2e3f87b49.nq.gz
    ├── 01ef6a425e82ff4f8e350b209040a76087551f2e.nq.gz
    ├── 0210f2d699eefb095ece9ca1e86283fe50888233.nq.gz
    ├── 02373b6cc203900998a4f9a637a2f5c0de8a6583.nq.gz
    ├── 024452630f32375794b02aa43441533ce5e6950e.nq.gz
    ├── 02c04a70c5d20fcad9516abda6e492a0648eb962.nq.gz
    ├── 02fe5a3744862d5cb850658b23a0cc2293f90cb4.nq.gz
    ├── 0308370dec85aae6766c96d27a0ae05f3d43dd31.nq.gz
    ├── 034b763faf6896171bbdabae7cc1f53478a25ecc.nq.gz
    ├── 036bf581b3cca7ba490c183657ac0af81f79479b.nq.gz
    ├── 037f1c968048e5a773e4a841ca0037dbfaf422cb.nq.gz
    ├── 03837e54eaa6aa1c164d5ff9e281d1d7ebbf2504.nq.gz
    ├── 039b8f98a22ee2e833f88795a0e7c1c29d764d39.nq.gz
    ├── 03ab738f208a70fda777f244081484b0b7eb64ca.nq.gz
    ├── 03b85777d01515440126e257cfc055de96fcb664.nq.gz
    ├── 03c7c77c170891c8861bb1b0bd8bf1035cd366f4.nq.gz
    ├── 040f948195d04273863f996e807319a69f848bdc.nq.gz
    ├── 044e6042d44220ac42a4da649daa376d5f095a3e.nq.gz
    ├── 045366145a0112761b501dcdfaea3b7685b22f99.nq.gz
    ├── 0468367347a2163f30558d19f5cbce4d32be2811.nq.gz
    ├── 0482ef72df5550303644a4bfaeefd22b76a7bcb9.nq.gz
    ├── 04b4470124da22b81a3d7a5fa8d012ec817114f9.nq.gz
    ├── 04ba3ee4c591753938d2b98527e48d1e4932b35e.nq.gz
    ├── 04d553cf99a4b62cb408b7baef8b75f9ddd404d9.nq.gz
    ├── 04e7a8481e15406f7eddfb0f21a93116cd0175de.nq.gz
    ├── 050418c5f9f107243cef4403d05cc27f9406b339.nq.gz
    ├── 051d00360b3f8fb4934cd9a2b53d22dc2b95b195.nq.gz
    ├── 051eb66b87be4ea02af3be80cb4fc589deb503bd.nq.gz
    ├── 052d19996b355a037dbb3be9816a91e437e25209.nq.gz
    ├── 053ee01bce075121bf16a2aff991d06f68dd7806.nq.gz
    ├── 05694fbe85bbc4f34917789cca3a4f6252458db5.nq.gz
    ├── 056fecc6e236c3a9cc78b9dbc6e189647cb55466.nq.gz
    ├── 05849aa1d8eab56178731da1f59f18a539d993a7.nq.gz
    ├── 058838de96368071694cccc122b90f6c84b8e8d7.nq.gz
    ├── 0595d1ad10379dfbd0526d177a0e0cfae414c3ec.nq.gz
    ├── 05ca5655004c8bda7f0efb61ad2b1a53d1ea4a58.nq.gz
    ├── 05fb5025579c27d5a9fb2abff4b33c8837907a42.nq.gz
    ├── 0691fd1ff0b4f63f0c5bc63bbf5e6052a699d71f.nq.gz
    ├── 06a65087a43d3768a94cdb97acfa36145c024d35.nq.gz
    ├── 0752e610c9a40fa7cf19923bf0ec1a0135a8348c.nq.gz
    ├── 07578edaa27776c8e46a9f84346a99e1fc97e8dc.nq.gz
    ├── 0777f5e74d2474bffac55300f935e79992110ea9.nq.gz
    ├── 07ab909a84fdd90c88665c776e6f3ab62cf81a7b.nq.gz
    ├── 07ae2fa3d454093f2d049fae24f27ac25df44977.nq.gz
    ├── 07bf95fd826df01a437e0a4607d031e8966bd8ef.nq.gz
    ├── 07c10398bb28d9b527389dcc8031cce9f7ae2dc0.nq.gz
    ├── 07d239984986a66e02f205165feead89add5c212.nq.gz
    ├── 07ea0caf7939dd37d33a87f7320670648513b1fa.nq.gz
    ├── 084ba0a718af613dae02d225c341a17a2d76a809.nq.gz
    ├── 08574ae46a10d24c99a8b8b695f9690fe56a4216.nq.gz
    ├── 08997797c3d07437640ace3970a810e8e938bd14.nq.gz
    ├── 08a882dd9331e523668c25242139eaa648ca5a22.nq.gz
    ├── 08b0b7e672042409500d0a310e79f4c29328adc5.nq.gz
    ├── 08c2e747fb3864843829f34b59bf7aa2d4f18349.nq.gz
    ├── 08e9618822e5259f2eff02a2993fc9939be291ad.nq.gz
    ├── 090324a93e003c44c13b43534e440ea87e521a3d.nq.gz
    ├── 09169984d8e1af2b8bc036cc68e188b03f84166e.nq.gz
    ├── 0953a9b99a06c0c1d8f825ea595882ac5ab577c0.nq.gz
    ├── 096033db8d377f8af0e24b680fd27a5e4151c607.nq.gz
    ├── 096e2f373f430c3fbda24e71fe589d571dd69954.nq.gz
    ├── 097bff10842f72e726c6b216da3880828f02f035.nq.gz
    ├── 09bee6820b3bf72599b7fcdd7b79d33beb37a276.nq.gz
    ├── 09f3055eda3b3d3f2d0efb85233d577cf3032c34.nq.gz
    ├── 09fa267a983800a7505043dc1ce06ef8d8567f6a.nq.gz
    ├── 0a1cbb77ef5e2f4b3b23801ed875c60b4c06efa6.nq.gz
    ├── 0a1fb8913dd9792ca62759fbc9db7e36ceb79946.nq.gz
    ├── 0aa04f12146db99988810fe951ab2579a4bd0b74.nq.gz
    ├── 0aa0b5a0d3289f320ca12271db7cc4fe4534f904.nq.gz
    ├── 0ab1ea06ea903cc604105ea4dad079d7ce0a17e0.nq.gz
    ├── 0af18f3e2634c91f9ef8940bc749ea59d7c7a15e.nq.gz
    ├── 0b15ff2b75eaaa9291025926c7c6ed551a3ac2fe.nq.gz
    ├── 0b17471d55fdb20c3b834b9d808314effcade0da.nq.gz
    ├── 0b3ed44849e767b00b663c888f854b79155ffd6e.nq.gz
    ├── 0b5f5c1fc82777beaf3197e5f3c33271c49c5ce3.nq.gz
    ├── 0b69ada78f48925fe9887486f9a3a8766aefa2a6.nq.gz
    ├── 0ba511b9016b5bc49f69fcfac3af545c422716eb.nq.gz
    ├── 0bacb2048aaaf8ab3584e881d36d6a372f16e523.nq.gz
    ├── 0bc62f5a15099a654eb3d8406a4b8a5f03680932.nq.gz
    ├── 0bde5e3c8b28afb5ccf69e32b14a3b4749806391.nq.gz
    ├── 0bf4a7fc04a1b7a913868a299680be3a040012ef.nq.gz
    ├── 0c221bdc236acd67d8b008a9d78e95f8423ee4e5.nq.gz
    ├── 0c2c46734d65cfa26edc7fac8c6f8c6bf1c42b55.nq.gz
    ├── 0c4bdf48a2f1803fe117c186e46d3c87801c2b40.nq.gz
    ├── 0c4fade50971f09428cbdade2c9c0b924c301d3f.nq.gz
    ├── 0c702fc762d794cae4387365b25331eb5f075a46.nq.gz
    ├── 0cade49ccef5a6a5495603f249e2e715b87520e8.nq.gz
    ├── 0ccd2c609a1b7039d4014e7bc0f548e515822cec.nq.gz
    ├── 0cd56422c03731f42ae7c1ba201109a3540dcf52.nq.gz
    ├── 0d16eb42761aa5565efb97ce935073195211fdef.nq.gz
    ├── 0d63979bfab9da1dd34c48f3cb7ac0ffc4c680bb.nq.gz
    ├── 0d900669a46510e10219bc883327ef7a502a7496.nq.gz
    ├── 0da2b9588900a691cdf8bc5089531362266dec9c.nq.gz
    ├── 0dc77f2d9ded001db16d8e701edfe9c660839648.nq.gz
    ├── 0e0a29afde02836d7f36113b553300c44587a6b9.nq.gz
    ├── 0e6490b395602fe5e97f87933102d19ad3b4142a.nq.gz
    ├── 0e782ebc7b44ca6a12655a8be388c1562394de42.nq.gz
    ├── 0e7aaca0b145721f316c02176d8551f0b0b302c7.nq.gz
    ├── 0ea7355eb3ccc848629b46cb76775387ba6de899.nq.gz
    ├── 0ec2ead8e299368d94273c42752bbd85ee386cb4.nq.gz
    ├── 0ecae2f3b7350d3e7276e3a901151e66c1eab522.nq.gz
    ├── 0f6716b3b50917a8d6948526aa21e39baba51c28.nq.gz
    ├── 0f8bd08d48ac521efa19e5fdb0e98aa3f84922ef.nq.gz
    ├── 10157cc9c1f0f4db7de1fd4a3c814359e1052b8a.nq.gz
    ├── 101a64ef71a99775b148e6c305968e43164b8760.nq.gz
    ├── 1074c4c20f17d2490f03f9a935aaed9e30718610.nq.gz
    ├── 1075efddfd1bcccc3a0616bef405e1d04d33ab4e.nq.gz
    ├── 1079293de96e53305f27454d57a97acedb14bb9d.nq.gz
    ├── 10934c12d41ee19b641fca103bee992b9336fc16.nq.gz
    ├── 10ae640595d9df287ffa2cfd8c9b8e729432c6c8.nq.gz
    ├── 10e45d23f5f223f27f24f154c6cdb261523272a5.nq.gz
    ├── 11176de7388ef3e0576c60bb767d9bdf758d8e0a.nq.gz
    ├── 11335993f64468c4b8230c918f3826e3cdfdb51f.nq.gz
    ├── 1161268d4623a873bf2461ce4f07beca8a3e79cb.nq.gz
    ├── 116809cac1845fa9a4e0c2d3542f7342e7ed6e8b.nq.gz
    ├── 118ebc2652e9a8776fd33ba3083956c7eab1a50d.nq.gz
    ├── 11b8c1dd2557cfca7e45e5d186298607f4d93a7a.nq.gz
    └── 11f47276558c3054b00e0622741ca75f82599a50.nq.gz

56 directories, 200 files
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

## Source repository

[giampaolo/psutil](https://github.com/giampaolo/psutil)

---
*Parsed on 2026-09-20 by [repolex](https://repolex.ai)*
