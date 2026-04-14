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
│   │   └── 9eea97dd6f1d16ea33f5144c8925f1ce7a0688e1
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 9eea97dd6f1d16ea33f5144c8925f1ce7a0688e1.nq.gz
│   └── repolex
│       └── 9eea97dd6f1d16ea33f5144c8925f1ce7a0688e1
│           └── chunk-001.nq.gz
└── blob
    ├── 016dcfaa03814120bd9517ca5494badaabb296d7.nq.gz
    ├── 039b8f98a22ee2e833f88795a0e7c1c29d764d39.nq.gz
    ├── 03ab738f208a70fda777f244081484b0b7eb64ca.nq.gz
    ├── 03c7c77c170891c8861bb1b0bd8bf1035cd366f4.nq.gz
    ├── 044e6042d44220ac42a4da649daa376d5f095a3e.nq.gz
    ├── 051eb66b87be4ea02af3be80cb4fc589deb503bd.nq.gz
    ├── 056fecc6e236c3a9cc78b9dbc6e189647cb55466.nq.gz
    ├── 058838de96368071694cccc122b90f6c84b8e8d7.nq.gz
    ├── 08574ae46a10d24c99a8b8b695f9690fe56a4216.nq.gz
    ├── 090324a93e003c44c13b43534e440ea87e521a3d.nq.gz
    ├── 09f3055eda3b3d3f2d0efb85233d577cf3032c34.nq.gz
    ├── 0bc62f5a15099a654eb3d8406a4b8a5f03680932.nq.gz
    ├── 0c2c46734d65cfa26edc7fac8c6f8c6bf1c42b55.nq.gz
    ├── 1161268d4623a873bf2461ce4f07beca8a3e79cb.nq.gz
    ├── 11f47276558c3054b00e0622741ca75f82599a50.nq.gz
    ├── 120143dd6daae918e459cd17a60feaca5941bdcf.nq.gz
    ├── 12353d4c75d47116be87f62d1a2f12e3fd900e75.nq.gz
    ├── 12847320fc2e25870387384a6fe732cdccc44290.nq.gz
    ├── 12c2fb153bde076eb1a7953b07e5ad87b3a7313d.nq.gz
    ├── 13e1cda0bab545fae036e95a6e3cf79e6527a8f7.nq.gz
    ├── 14338588ef8b024d974980a8cb3e68acb768a1f3.nq.gz
    ├── 1619b7d34186d89d20fd3ae915fca586e1965120.nq.gz
    ├── 1623ff5effe0f121ffc75b500e623e1b9fc20b05.nq.gz
    ├── 1653c017dcb4a55ac87ba9fd71b1154d00a37cb3.nq.gz
    ├── 16673e4dbbf7fda069907df4799abfb8ffd28e50.nq.gz
    ├── 1f4aab463f61116d89cad1917d9cce3c00b6fbf4.nq.gz
    ├── 1f628ad93c1b1464b16d63daee79fe161204730e.nq.gz
    ├── 246c9c050f9a8781dbc2486e34229935d3965ee8.nq.gz
    ├── 25395870c06d1095e2b9c905097a6bba2beb2a52.nq.gz
    ├── 2561e457a8cb4c72e4ed41e368bfcea3a5ead0e5.nq.gz
    ├── 274541dc6d9798f8aca6653409489aed6aad501b.nq.gz
    ├── 276ed72ddae9b810d53c8142c2454b20b1aca183.nq.gz
    ├── 283542c6ca2bbeb82c37b9012326dd2017305bcb.nq.gz
    ├── 2a5c5535e977f2b8c76df93bd88bdf4561366d88.nq.gz
    ├── 2ab139b600ac12eebfd5c6db57d5109dc8249e44.nq.gz
    ├── 2c3b7de5b4b5b8f58773e671063a701a8044c6e9.nq.gz
    ├── 31f9800ff4294d0623c828cb3fdb1ccdbce2bb50.nq.gz
    ├── 32b20a93fe7761ba8cfd3cf16fbd0553905ac75f.nq.gz
    ├── 33417e5062b9f80b1f7b6b9b61cd64e552b3d68b.nq.gz
    ├── 3376963911e51dd452d3fa6853bc4b00795c5568.nq.gz
    ├── 33b6282253ac3321193fdd882aaf38185dee9d49.nq.gz
    ├── 349493b237358d678902e3a77df90940b3051f28.nq.gz
    ├── 34bda5775d96522c78fa2860630a9c41768e5095.nq.gz
    ├── 3689b22f2ccc4fb55529403e62105efec31a86d1.nq.gz
    ├── 368c53c91a803b0551a86560dbfa67fb864e77a5.nq.gz
    ├── 36d980d70fb470263e1ae94d5979df6529422071.nq.gz
    ├── 3834b0f18705392c0ef8c6065d860a9aacc25542.nq.gz
    ├── 3867ab07fad1f224c8685eb9d9a7d1e5fa0a15f1.nq.gz
    ├── 38ae74f8217a0baed950c18529bf3d4b6c2d000b.nq.gz
    ├── 39be8cc7d5227083b5bfdda693c30df464fb28f1.nq.gz
    ├── 39dc113f1a0e7af2e2a053bd6bab69f4e5474102.nq.gz
    ├── 39dd15b23bb96546d278395448ae358a69b34b04.nq.gz
    ├── 39e43fc318ceee172a5694b02f5446793658c789.nq.gz
    ├── 3bc00d3fe78d89abe2d9da77b636c165cbef1695.nq.gz
    ├── 3c1acb58de253a65edba64b0c29d5c3e483fdc94.nq.gz
    ├── 3ce6b4957e592d82d286cb881389f8cb2c389092.nq.gz
    ├── 3ee1eafce0bb08f86df6d08d30a66bb2058c6f7c.nq.gz
    ├── 3f3afeeedebfb200ed61429d607477f817afdf6f.nq.gz
    ├── 3fafcac2b52ec7bbec3b876fe739307ebfc60747.nq.gz
    ├── 3ff399e22cd0d1da065f9cb4f1df16a786b10082.nq.gz
    ├── 41b28490462f2de4a707468f579345a4c1a43af8.nq.gz
    ├── 421be47f7a9b0c676ee4199fd7f7e1b7902ccad9.nq.gz
    ├── 4271a1a16840bb3ff7d3539536dafdbe6ce90e4e.nq.gz
    ├── 43ad7b6531a7ae040bc92a57681c44ae6a008ae5.nq.gz
    ├── 44d37972c5cc5adac0425458ed139d60eb938dc4.nq.gz
    ├── 4520683b6922e708aebbeafd801696bfa5b1e3e5.nq.gz
    ├── 49da69dfb847eb7e665cf3353e36e102d4ffa4e0.nq.gz
    ├── 4b1023d0b478b856c09a5de20011731fa5bc555c.nq.gz
    ├── 4b39bddc2dcce21a2759530663e2bfd4518bacf8.nq.gz
    ├── 4cced2d9c93eecd0b5174658caf4f286b9d2ed89.nq.gz
    ├── 4d9bc00a768f7f1f8e167ffbc51284cfeec4637d.nq.gz
    ├── 503ae49659113f6b59d40956d686905ac0522362.nq.gz
    ├── 52644a8d3b451b3103eb90cf6991425e88125e11.nq.gz
    ├── 5310a92de0fc0c8a5e4e18cf72a9eca1455ef90d.nq.gz
    ├── 532e8b15cecf13e82a3ad17425962686a99ddca1.nq.gz
    ├── 538d4c3229a981af76112bf7ff8216833df41b77.nq.gz
    ├── 544b9110e0962ab36bd18dd6de0dbd42f6e7e14b.nq.gz
    ├── 54bfefe1d493d041e2073b9905e850470e91d0a1.nq.gz
    ├── 54d53bebd7bbcf0a6f9e1cd49899cdc42ba91555.nq.gz
    ├── 56457a28d039f8a90868f0e6ef6dd049fe12354f.nq.gz
    ├── 56accf167c2f9ef833678aa7884ffe392bfbaeb8.nq.gz
    ├── 585eca2f4680f827e2e29a73bd34132dae82326a.nq.gz
    ├── 589a3296310985fdd791efadd08edacfe63fabbe.nq.gz
    ├── 59178c5363a025636dad106a2070275fea0a1881.nq.gz
    ├── 5a0787d2452edcc325fa9af02d362fe7e36d9660.nq.gz
    ├── 5b87ecf364065f7b89738af7e7b422054fa113c3.nq.gz
    ├── 5d41f23057ebc96b4dfd6c1556acb6c8dc9c3c4b.nq.gz
    ├── 5d82c672beefcc7b2b03720e94a897518f55d11c.nq.gz
    ├── 5e68c723cfd03160dcc6d95d489e4c17c2ca697d.nq.gz
    ├── 5e8615f2616f98d00153e6815ffa9eb22cd69839.nq.gz
    ├── 5f8ed673177043e0a8e7026d9d6f1576bab0b385.nq.gz
    ├── 60035014ad53f68af58dd041695ae9a15e739343.nq.gz
    ├── 601355aa8deec977de26cd2a1733e8875b59583d.nq.gz
    ├── 62f19f7d4860b2eb8b1cb4f68b5a7fafed951cf2.nq.gz
    ├── 67c446b2b6faef4c8245a3502c06d9ce15a6aff8.nq.gz
    ├── 694c815e72c0903a50bc94144d179ce5779dea22.nq.gz
    ├── 69570bd21655416500d82a47fe54ca7c8a7c356f.nq.gz
    ├── 69a4c386f29a7276451cd22c6e1c5319211ea3d9.nq.gz
    ├── 6b599659f0ea36b22607b8bf099d59f8a093e2d9.nq.gz
    ├── 6bee96998a8ac6dfde52f184845155f66c5e62e5.nq.gz
    ├── 6ce2573870ca94fad6c8f3e1bf38974031ffa57e.nq.gz
    ├── 6d7f56b53cf8588a26ef927bbb5396bffa07661e.nq.gz
    ├── 6daaa431383920bde85c4e0f6da895cad6b13f54.nq.gz
    ├── 6f8d3a478fc48ad2daa0e3bad1e2d7e60be8b9a7.nq.gz
    ├── 70ed13731d3e8cfc2afc976c04b911d7dcf9b761.nq.gz
    ├── 71e70024eead28e0666580e4fc435aafdfc1edbf.nq.gz
    ├── 726b53d52ca26bf32cff608d54df619323ee7b37.nq.gz
    ├── 73822802745f5e62db642cea35f3418d302d6a40.nq.gz
    ├── 742fc02d9694235ea75e2b12e04e5e4b630f38ae.nq.gz
    ├── 74b1f309d08fa8d52a518982e8bc2d83e5dc61ea.nq.gz
    ├── 754a792c89fb3c060eba4e6545bbd59c6c7602b3.nq.gz
    ├── 7bee953f07ce89cfeb98f15a3b5a8926eaac56e0.nq.gz
    ├── 7d6d000b38561d4bef0fbe2866b3a67c53131d8e.nq.gz
    ├── 7d975ec9d2415c3edea7cf9d73db1d9078358daa.nq.gz
    ├── 7db9f45e83f8f23199bffccb54a29a6e5a2c2a56.nq.gz
    ├── 8101aaeee813b21790ca7793c20b8954f5898b14.nq.gz
    ├── 81547a1726f66b4f3dded9224e0225cf302b7b68.nq.gz
    ├── 81a608cd10b95d51954e6074981014c1f24a0a38.nq.gz
    ├── 8205dd2af5eda489c884995e0363b9a9a0fb904e.nq.gz
    ├── 881a89b6c089b4c72188f794b556422dc18d41a2.nq.gz
    ├── 893b4c92c9a06f689f96dd6268168131297de576.nq.gz
    ├── 89483408cadd2a9083109d67e3b44547e83af7b6.nq.gz
    ├── 8a46d74f548367fd58e73139ba178a44d2bb0153.nq.gz
    ├── 8c75bf33088a198346dd5bb32070fb94ee692a7e.nq.gz
    ├── 8ceb5f21f7a250e5804322c7666ad4dbf20d2cfa.nq.gz
    ├── 8fa1eb6cd7ed041c8fd8a02dff82513ee8389a2e.nq.gz
    ├── 9002d9efda00f52a56912b36c8b536adb42547a3.nq.gz
    ├── 90c45cad02a7029750e19805b30a742838ccdb07.nq.gz
    ├── 91e8faf3336247029d8d7411b4e2f2000eddf583.nq.gz
    ├── 94c5f287d67df41cecd835a193e1ddb3545bfddc.nq.gz
    ├── 9603b29ab0e7ea678aed8eb704990706f51faa15.nq.gz
    ├── 978dfb9e7779affdbbf8b8f9cdc06e3a89945f92.nq.gz
    ├── a0e70581f5a02dfbc8e61a9d26e105ee6160a8aa.nq.gz
    ├── a14116ef3a931fc2b54caad3352d41e4421f2ce6.nq.gz
    ├── a2d56d63b16a8d23aeac182b9138ccd7c1141765.nq.gz
    ├── a4b8662f5951e59922d2c491e47d6ff4fa2a1789.nq.gz
    ├── a4e41482aeaa0c56887badfb77721475722696a8.nq.gz
    ├── a5bb79ce90103defd6460464a5b0f0917b54ad20.nq.gz
    ├── a75cd1af131973c0f78caa65a22c0a7e91645959.nq.gz
    ├── a92694cda082e896ac9ef8d6ce2bb49c27a2e4cf.nq.gz
    ├── ab4ad51cac2b4989ace5d9b02c723434b26ad92d.nq.gz
    ├── ab996938efd24dcba5580b4b70c126aeeb851152.nq.gz
    ├── ae5991f844d006459d186f225a9dbcbed1111c76.nq.gz
    ├── af12d68417235c960cfdf5aca13ba22beea979cb.nq.gz
    ├── b00483747b7eebf4fcdab729220de113cd2c014b.nq.gz
    ├── b14d5e023bec1f9cb5cb06b4caf7170489f3d4c7.nq.gz
    ├── b222b566a67f17cdea5ecd43543d14f58dbcf41d.nq.gz
    ├── b6236977649bbe2fa6c0de1f866299664f8fa847.nq.gz
    ├── b8da409f06efdf5565326779aa668bd0f13ae279.nq.gz
    ├── bb58287506d2e473ce2cd9e91970f704e8bf1cc0.nq.gz
    ├── bd8714de8e3b92c69a4a2ae563c250430c50e02b.nq.gz
    ├── bde5fe6ceabf26eaadaee79fd114da66a9e0609e.nq.gz
    ├── be081144d10829a08386f641597c1345982cdf9a.nq.gz
    ├── be391e28ab08259f56dc374ba6c2e735c45e61d5.nq.gz
    ├── be7c493fb81509865b8c9c5c3530b378701c8254.nq.gz
    ├── be7e058b029323cc0ed522001428417fa2583e0d.nq.gz
    ├── bf1730f13ecaa27f0c1966ca6e798ad87cfcdb3d.nq.gz
    ├── bf42d276dede1b5b3890ef579c1dad06b5a14de3.nq.gz
    ├── c08ef24c7cc0c4be8a21072b31167f34c812d8f2.nq.gz
    ├── c14f480d4a1618f3db6acf2ab5fc443e75c97611.nq.gz
    ├── c18670218144d9b0d236494ef2dd9934df295e52.nq.gz
    ├── c1baeced4ca81b8317cbb59bc752a9337f800434.nq.gz
    ├── c1f10173a5d8793af8efa4bed8454f22be554a6a.nq.gz
    ├── c2889fac9edbe7278be0beec30aa0684c4dd8cd0.nq.gz
    ├── c4a5f7f531d9f99dd2be14793610afbc2426d162.nq.gz
    ├── c4b2afeed91d71a98386a72058a4b487a7a515f2.nq.gz
    ├── c4b90962dae18e975fd55ed6bf3fd935030aef08.nq.gz
    ├── c4f569e5a3a2099cb15fabe6d94b48e025b9fbfb.nq.gz
    ├── c7ad2fdabd30ee585642b49e38db9afc489b6ede.nq.gz
    ├── c891b6fc926d639096ece056a9d9c1c11bddd87b.nq.gz
    ├── c89a2a129f3145253fcceb524d8f73be8597c8bd.nq.gz
    ├── c98db34130603de41e9092abfc7ef0271956d4d1.nq.gz
    ├── c9efc5844a2627a8474949724a2aefe4ab2baee4.nq.gz
    ├── cff5eb74e1badd1c5237ed2654b349530179ad1d.nq.gz
    ├── d10626b02086cfcf156a9838cac76f74a54c7a54.nq.gz
    ├── d3b0c42239591d3247b77a7dfe213c4c57557389.nq.gz
    ├── d3cb85212aa37c370516558c5eba6c1531871948.nq.gz
    ├── d3ef4447127c29b11d2e2904e4ab468860798c37.nq.gz
    ├── d3f00f5f204c534867d8c57f1d1c50ebd7c392a3.nq.gz
    ├── d45954723439de53b01da65c5b5b8817f1ef5ab5.nq.gz
    ├── d4cd62da94b28cc23a1714622b71582c171d8873.nq.gz
    ├── d5ced15a30b75362222df16496bc0157d8844451.nq.gz
    ├── d73b8cb8b6474de78861d513570b762da84a4515.nq.gz
    ├── d7dc8c91855e87838f7ccbe82bbbd40a23e17c71.nq.gz
    ├── d9abaeb9ea22883b1bb3febec497217a9be3dc5d.nq.gz
    ├── d9f3d671bcf8141357df8c48e2bf0dc909b90a9b.nq.gz
    ├── dbec5159db6ee4017447b1f274e6ea23060d3bd1.nq.gz
    ├── dc305b59559e9b97f96eacf2a2002d2b02e3fe41.nq.gz
    ├── dd506cb9fb816e6ea2fb358789ac0d08841bbfef.nq.gz
    ├── de24bff335122d02ebfba5bc847d16502504e5ec.nq.gz
    ├── debd8af4d659f482f70da47de82770e2645cda8a.nq.gz
    ├── df0481f62c0223f7ea5cd2900187f662cc73c4be.nq.gz
    ├── e0ca022ebcdc70599e45722ee32c07d914e85ccc.nq.gz
    ├── e0d147debd23f8d6a3c2693ca551eadeab8dae0a.nq.gz
    ├── e1c67233f5dcbed72cf8e421058824f238106d5c.nq.gz
    ├── e2d5535e3901e009c6861722431ad987bc371a34.nq.gz
    └── e3f0eba3b532b6b5552e6e3ead506ec456e12775.nq.gz

8 directories, 200 files
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
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
