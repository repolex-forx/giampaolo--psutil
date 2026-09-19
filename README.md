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
│   │   ├── 5904ff94e3fd0fea3d0734a936834bef6e63369a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6130c19da2d01383befa0dfca2371a792f8881af
│   │   │   └── chunk-001.nq.gz
│   │   ├── 704e218db7da14e98a54f2aa9f93372d5900e0b4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9eea97dd6f1d16ea33f5144c8925f1ce7a0688e1
│   │   │   └── chunk-001.nq.gz
│   │   ├── a07e87a1336678cbcc929116cd826137779cf654
│   │   │   └── chunk-001.nq.gz
│   │   └── c948ef07e46b114a61492c9d207c741339fceeb2
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0d18187e79b349e577fadabd3589f8fdbf99bf5a.nq.gz
│   │   ├── 5904ff94e3fd0fea3d0734a936834bef6e63369a.nq.gz
│   │   ├── 6130c19da2d01383befa0dfca2371a792f8881af.nq.gz
│   │   ├── 704e218db7da14e98a54f2aa9f93372d5900e0b4.nq.gz
│   │   ├── 9eea97dd6f1d16ea33f5144c8925f1ce7a0688e1.nq.gz
│   │   ├── a07e87a1336678cbcc929116cd826137779cf654.nq.gz
│   │   └── c948ef07e46b114a61492c9d207c741339fceeb2.nq.gz
│   └── repolex
│       ├── 0d18187e79b349e577fadabd3589f8fdbf99bf5a
│       │   └── chunk-001.nq.gz
│       ├── 5904ff94e3fd0fea3d0734a936834bef6e63369a
│       │   └── chunk-001.nq.gz
│       ├── 6130c19da2d01383befa0dfca2371a792f8881af
│       │   └── chunk-001.nq.gz
│       ├── 704e218db7da14e98a54f2aa9f93372d5900e0b4
│       │   └── chunk-001.nq.gz
│       ├── 9eea97dd6f1d16ea33f5144c8925f1ce7a0688e1
│       │   └── chunk-001.nq.gz
│       ├── a07e87a1336678cbcc929116cd826137779cf654
│       │   └── chunk-001.nq.gz
│       └── c948ef07e46b114a61492c9d207c741339fceeb2
│           └── chunk-001.nq.gz
└── blob
    ├── 00ad666517c6de1e399782a5abb27363954308b3.nq.gz
    ├── 016dcfaa03814120bd9517ca5494badaabb296d7.nq.gz
    ├── 02373b6cc203900998a4f9a637a2f5c0de8a6583.nq.gz
    ├── 02c04a70c5d20fcad9516abda6e492a0648eb962.nq.gz
    ├── 02fe5a3744862d5cb850658b23a0cc2293f90cb4.nq.gz
    ├── 034b763faf6896171bbdabae7cc1f53478a25ecc.nq.gz
    ├── 036bf581b3cca7ba490c183657ac0af81f79479b.nq.gz
    ├── 037f1c968048e5a773e4a841ca0037dbfaf422cb.nq.gz
    ├── 03837e54eaa6aa1c164d5ff9e281d1d7ebbf2504.nq.gz
    ├── 039b8f98a22ee2e833f88795a0e7c1c29d764d39.nq.gz
    ├── 03ab738f208a70fda777f244081484b0b7eb64ca.nq.gz
    ├── 03b85777d01515440126e257cfc055de96fcb664.nq.gz
    ├── 03c7c77c170891c8861bb1b0bd8bf1035cd366f4.nq.gz
    ├── 044e6042d44220ac42a4da649daa376d5f095a3e.nq.gz
    ├── 04b4470124da22b81a3d7a5fa8d012ec817114f9.nq.gz
    ├── 04ba3ee4c591753938d2b98527e48d1e4932b35e.nq.gz
    ├── 04d553cf99a4b62cb408b7baef8b75f9ddd404d9.nq.gz
    ├── 04e7a8481e15406f7eddfb0f21a93116cd0175de.nq.gz
    ├── 051eb66b87be4ea02af3be80cb4fc589deb503bd.nq.gz
    ├── 052d19996b355a037dbb3be9816a91e437e25209.nq.gz
    ├── 053ee01bce075121bf16a2aff991d06f68dd7806.nq.gz
    ├── 05694fbe85bbc4f34917789cca3a4f6252458db5.nq.gz
    ├── 056fecc6e236c3a9cc78b9dbc6e189647cb55466.nq.gz
    ├── 058838de96368071694cccc122b90f6c84b8e8d7.nq.gz
    ├── 07ea0caf7939dd37d33a87f7320670648513b1fa.nq.gz
    ├── 084ba0a718af613dae02d225c341a17a2d76a809.nq.gz
    ├── 08574ae46a10d24c99a8b8b695f9690fe56a4216.nq.gz
    ├── 08c2e747fb3864843829f34b59bf7aa2d4f18349.nq.gz
    ├── 08e9618822e5259f2eff02a2993fc9939be291ad.nq.gz
    ├── 090324a93e003c44c13b43534e440ea87e521a3d.nq.gz
    ├── 0953a9b99a06c0c1d8f825ea595882ac5ab577c0.nq.gz
    ├── 09bee6820b3bf72599b7fcdd7b79d33beb37a276.nq.gz
    ├── 09f3055eda3b3d3f2d0efb85233d577cf3032c34.nq.gz
    ├── 0b3ed44849e767b00b663c888f854b79155ffd6e.nq.gz
    ├── 0b5f5c1fc82777beaf3197e5f3c33271c49c5ce3.nq.gz
    ├── 0bc62f5a15099a654eb3d8406a4b8a5f03680932.nq.gz
    ├── 0bde5e3c8b28afb5ccf69e32b14a3b4749806391.nq.gz
    ├── 0c2c46734d65cfa26edc7fac8c6f8c6bf1c42b55.nq.gz
    ├── 0cade49ccef5a6a5495603f249e2e715b87520e8.nq.gz
    ├── 0ccd2c609a1b7039d4014e7bc0f548e515822cec.nq.gz
    ├── 0cd56422c03731f42ae7c1ba201109a3540dcf52.nq.gz
    ├── 0e7aaca0b145721f316c02176d8551f0b0b302c7.nq.gz
    ├── 0ecae2f3b7350d3e7276e3a901151e66c1eab522.nq.gz
    ├── 0f8bd08d48ac521efa19e5fdb0e98aa3f84922ef.nq.gz
    ├── 10157cc9c1f0f4db7de1fd4a3c814359e1052b8a.nq.gz
    ├── 10934c12d41ee19b641fca103bee992b9336fc16.nq.gz
    ├── 1161268d4623a873bf2461ce4f07beca8a3e79cb.nq.gz
    ├── 11f47276558c3054b00e0622741ca75f82599a50.nq.gz
    ├── 120143dd6daae918e459cd17a60feaca5941bdcf.nq.gz
    ├── 12353d4c75d47116be87f62d1a2f12e3fd900e75.nq.gz
    ├── 12847320fc2e25870387384a6fe732cdccc44290.nq.gz
    ├── 12c2fb153bde076eb1a7953b07e5ad87b3a7313d.nq.gz
    ├── 13e1cda0bab545fae036e95a6e3cf79e6527a8f7.nq.gz
    ├── 14338588ef8b024d974980a8cb3e68acb768a1f3.nq.gz
    ├── 1480b60fab2a22b055477882104013e19a2232da.nq.gz
    ├── 14a241f29cdb30e32f055cd069cc87ae38af5f77.nq.gz
    ├── 1608ac2d1fb4b9ae1601abf162bff0fab077989d.nq.gz
    ├── 1619b7d34186d89d20fd3ae915fca586e1965120.nq.gz
    ├── 1623ff5effe0f121ffc75b500e623e1b9fc20b05.nq.gz
    ├── 1653c017dcb4a55ac87ba9fd71b1154d00a37cb3.nq.gz
    ├── 16673e4dbbf7fda069907df4799abfb8ffd28e50.nq.gz
    ├── 16c756c50e21b5952e92bcb3406eb9999d3a5ab1.nq.gz
    ├── 16f289f3c445c8026788c406cc94791b1d1f0313.nq.gz
    ├── 172bf1949999cf8768b4dac5db51031955dcbf6b.nq.gz
    ├── 17db0c3258b2fba6b7427b1e553c9549e9368968.nq.gz
    ├── 19a909125b1a7698de61aae6568a281fce92fcfb.nq.gz
    ├── 19bd9287c708b678e1b9897fe65f217e80e598c2.nq.gz
    ├── 1a674cb8d36ab48615af01abf92441531c55ccdb.nq.gz
    ├── 1cd0430ff3434ef6c5a86d35776fc802ccd338da.nq.gz
    ├── 1d1432b6db5addb8be06c9efd35c46489474a60d.nq.gz
    ├── 1d9d974cd1f9703b23478f105da4675ef96240c5.nq.gz
    ├── 1e992bd83c0a4e9541e89bb9602b87808e86df86.nq.gz
    ├── 1ed6e5fe91bb53cd91e42dd82638d74993fc4677.nq.gz
    ├── 1f4aab463f61116d89cad1917d9cce3c00b6fbf4.nq.gz
    ├── 1f628ad93c1b1464b16d63daee79fe161204730e.nq.gz
    ├── 203766fa7015386663a7ea977ea276e041e626f7.nq.gz
    ├── 20decd219cabf67e09d0445aa3ee85aee051f2b0.nq.gz
    ├── 224f9682608275123060f967722585e568261637.nq.gz
    ├── 23d47ebd27259072f8e65e5bd7d36735d6b3e6e2.nq.gz
    ├── 246c9c050f9a8781dbc2486e34229935d3965ee8.nq.gz
    ├── 2488d9ab278db407297d245b8762947c8b7d12a5.nq.gz
    ├── 25264a7a79525799065c683c507e92e2638c205c.nq.gz
    ├── 25395870c06d1095e2b9c905097a6bba2beb2a52.nq.gz
    ├── 2561e457a8cb4c72e4ed41e368bfcea3a5ead0e5.nq.gz
    ├── 26227cd3984fc46ee37cf861e68fe989362017f0.nq.gz
    ├── 264f3ed63978ab88b6c03567dec18e7261e5d897.nq.gz
    ├── 274541dc6d9798f8aca6653409489aed6aad501b.nq.gz
    ├── 276ed72ddae9b810d53c8142c2454b20b1aca183.nq.gz
    ├── 27acbcaf43abcc1554f2614a1f493b02a9bde221.nq.gz
    ├── 283542c6ca2bbeb82c37b9012326dd2017305bcb.nq.gz
    ├── 2a5a797436faf337974e2fabecf5b4d3e02333ec.nq.gz
    ├── 2a5c5535e977f2b8c76df93bd88bdf4561366d88.nq.gz
    ├── 2a7e9d3fff30b26aff1f0a7bb809218ea0462a13.nq.gz
    ├── 2ab139b600ac12eebfd5c6db57d5109dc8249e44.nq.gz
    ├── 2b6589c2cfb4b3e21d71531a36ba6ea801852861.nq.gz
    ├── 2c3b7de5b4b5b8f58773e671063a701a8044c6e9.nq.gz
    ├── 2c3ddaa82bf76979c82e6e4d819612e84609727c.nq.gz
    ├── 2c8ea02fc35da62a43b93576d9000a3e413e1d6f.nq.gz
    ├── 2cfb4e47c4230a1e46bbd851fc9616f6ae81857b.nq.gz
    ├── 2dfeb7653f10bd2bf6897e4419758e1782a588da.nq.gz
    ├── 2e3637c8ab790a10fc34b7c4766c03f1ab896980.nq.gz
    ├── 2f381da202f4965a9b9732e61b9675a9e76c53ce.nq.gz
    ├── 2facfe364c10bff71337ea9d4d67b00b9a3105af.nq.gz
    ├── 3020019178e1315904d535b5132759f8afe5d6b8.nq.gz
    ├── 306b1c32f69650c81478901390511525217b66b1.nq.gz
    ├── 3097f45b7a4c457c2ba65d0682aaaa585454ee2a.nq.gz
    ├── 31f9800ff4294d0623c828cb3fdb1ccdbce2bb50.nq.gz
    ├── 32354dfd55ad973dc136fb47b3e002a79c025ec6.nq.gz
    ├── 32b20a93fe7761ba8cfd3cf16fbd0553905ac75f.nq.gz
    ├── 32b5f0da2245de3c77b1cca3dea0ec88985f1972.nq.gz
    ├── 32bdac45b27d3b6d0ff43cdca72a1e66bd07ed8b.nq.gz
    ├── 33417e5062b9f80b1f7b6b9b61cd64e552b3d68b.nq.gz
    ├── 3376963911e51dd452d3fa6853bc4b00795c5568.nq.gz
    ├── 33833c3ed0b9619ca96c5b33ae73857acb4064ed.nq.gz
    ├── 3398c47ee35c621447c69419e1885b97e6225e29.nq.gz
    ├── 33b6282253ac3321193fdd882aaf38185dee9d49.nq.gz
    ├── 342a35560f31a3d0e50b4ac78ee9a8e6c8f78cc4.nq.gz
    ├── 34687aac1376b7122051e0b7ee0dd7498d606ab0.nq.gz
    ├── 349493b237358d678902e3a77df90940b3051f28.nq.gz
    ├── 34bda5775d96522c78fa2860630a9c41768e5095.nq.gz
    ├── 34cd54e1f04a25c59194db6314fb26f69a0d806c.nq.gz
    ├── 3500bd32d19ea896fd40d3752dae12bde25c0ea9.nq.gz
    ├── 35298db7669e48582b2374b10e234e99ce1c07ed.nq.gz
    ├── 3589b91bf818d196efc48aaf80895aadb9a511a3.nq.gz
    ├── 35ac61d74fcb1d9281bb757961953163249d89c2.nq.gz
    ├── 35f93c8205b80741ff99bccf925b991e2fbc8e16.nq.gz
    ├── 3689b22f2ccc4fb55529403e62105efec31a86d1.nq.gz
    ├── 368c53c91a803b0551a86560dbfa67fb864e77a5.nq.gz
    ├── 36d980d70fb470263e1ae94d5979df6529422071.nq.gz
    ├── 37027dc83801df4e5499257365c4233fa28325d8.nq.gz
    ├── 371264043a210a2fa85b59a25011c49f5c9c234e.nq.gz
    ├── 3719c8c18a95e51ba24da03d299174dc866705b8.nq.gz
    ├── 3834b0f18705392c0ef8c6065d860a9aacc25542.nq.gz
    ├── 3867ab07fad1f224c8685eb9d9a7d1e5fa0a15f1.nq.gz
    ├── 38ae74f8217a0baed950c18529bf3d4b6c2d000b.nq.gz
    ├── 39bb9a52be41e088c327417d51289a08fa899fac.nq.gz
    ├── 39be8cc7d5227083b5bfdda693c30df464fb28f1.nq.gz
    ├── 39dc113f1a0e7af2e2a053bd6bab69f4e5474102.nq.gz
    ├── 39dd15b23bb96546d278395448ae358a69b34b04.nq.gz
    ├── 39e43fc318ceee172a5694b02f5446793658c789.nq.gz
    ├── 3bc00d3fe78d89abe2d9da77b636c165cbef1695.nq.gz
    ├── 3c1acb58de253a65edba64b0c29d5c3e483fdc94.nq.gz
    ├── 3ce6b4957e592d82d286cb881389f8cb2c389092.nq.gz
    ├── 3d1baf9252092726331555cf189f0b9873991621.nq.gz
    ├── 3d83ae2f934e434b9f46460293efb5ae446049ed.nq.gz
    ├── 3e323ca149bae01e6c1ca952d43fdd44b3f6c4d4.nq.gz
    ├── 3ee1eafce0bb08f86df6d08d30a66bb2058c6f7c.nq.gz
    ├── 3f2db7df9fcdc7dc376683ef3e24e2432e1c5eac.nq.gz
    ├── 3f3afeeedebfb200ed61429d607477f817afdf6f.nq.gz
    ├── 3fafcac2b52ec7bbec3b876fe739307ebfc60747.nq.gz
    ├── 3ff399e22cd0d1da065f9cb4f1df16a786b10082.nq.gz
    ├── 3ffcb44473a32c5f1a16d3e705cdf16fa33f7c76.nq.gz
    ├── 40fc59151936c12ab082703429ea43cc511104ff.nq.gz
    ├── 411a451050b3849bb06321a73b206355bad03d95.nq.gz
    ├── 41b28490462f2de4a707468f579345a4c1a43af8.nq.gz
    ├── 421be47f7a9b0c676ee4199fd7f7e1b7902ccad9.nq.gz
    ├── 4246087d726cfc2d282b718fb46d69710f696fb8.nq.gz
    ├── 425a3478269f9ab49fdc0c6a1c6535aa7ba86852.nq.gz
    ├── 4271a1a16840bb3ff7d3539536dafdbe6ce90e4e.nq.gz
    ├── 43ad7b6531a7ae040bc92a57681c44ae6a008ae5.nq.gz
    ├── 43c91ffb73bcc26360ad210a01b424706d93a71a.nq.gz
    ├── 44d37972c5cc5adac0425458ed139d60eb938dc4.nq.gz
    ├── 450201d440d47bbbe40cc18e290bbbf7e97aae93.nq.gz
    ├── 4520683b6922e708aebbeafd801696bfa5b1e3e5.nq.gz
    ├── 453927011047860580255335f32a7c8c0406320f.nq.gz
    ├── 458c7f22251790a2ac3e81fd7d3728c0077d0232.nq.gz
    ├── 471944c6438a97ab75899f898fb82f0f9d5b44a5.nq.gz
    ├── 47d5361a40e11e18229755f08cb4733a642a0638.nq.gz
    ├── 47e46ea08e56a41e9feede67ffaa1c050884f39f.nq.gz
    ├── 48daef183458aea943539bb7dc2e36cd3f3a083d.nq.gz
    ├── 48fb6eb3b9cf82ae92109e424992eaf119663d04.nq.gz
    ├── 49da69dfb847eb7e665cf3353e36e102d4ffa4e0.nq.gz
    ├── 4a13f73e0da7d66a8512e2e38fd07b616c2d2dad.nq.gz
    ├── 4b1023d0b478b856c09a5de20011731fa5bc555c.nq.gz
    ├── 4b2d77fc7367cda28dc0a9e8acb0d402a9a7f11a.nq.gz
    ├── 4b39bddc2dcce21a2759530663e2bfd4518bacf8.nq.gz
    ├── 4cced2d9c93eecd0b5174658caf4f286b9d2ed89.nq.gz
    ├── 4d9bc00a768f7f1f8e167ffbc51284cfeec4637d.nq.gz
    └── 503ae49659113f6b59d40956d686905ac0522362.nq.gz

20 directories, 200 files
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
*Parsed on 2026-09-19 by [repolex](https://repolex.ai)*
