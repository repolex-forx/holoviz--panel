# Repolex Knowledge Graph of holoviz/panel

RDF knowledge graph data for [holoviz/panel](https://github.com/holoviz/panel), parsed by [repolex](https://repolex.ai).

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
rlex download holoviz/panel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d417056d8f422efa1a35de866b4f7dec29882abd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d417056d8f422efa1a35de866b4f7dec29882abd
│           └── chunk-001.nq.gz
└── blob
    ├── 0026b58161612e17e35c5a7e3d1ea7ccf70c4336.nq.gz
    ├── 004393065029ada5c05ac565ead3e89aa3725170.nq.gz
    ├── 0053ce308cb78028858f55b89c38c0412a0cb53b.nq.gz
    ├── 0055ba3257ecd538803fe432360f7e09304003c9.nq.gz
    ├── 00d928eeba85b9fcda0d6b3da29ef1e739edcfc3.nq.gz
    ├── 010da6878683f990d48ff3a2f4a04da15df1f08a.nq.gz
    ├── 0181a38dd76c905104d5a1f50864c511743d7b5f.nq.gz
    ├── 01c070bd717a71c86ebdde591c43aa0507c78137.nq.gz
    ├── 020d157979e864659d57aa90edbc96d9e6ed8a1b.nq.gz
    ├── 025b4e2ecd72a289847b141959b1c18544a75a56.nq.gz
    ├── 0286ac01f2a08ea5ddee7b5e90574d9b91b3437a.nq.gz
    ├── 02dd93675162ca180211ebbf432b720cfc892048.nq.gz
    ├── 02e8355c7ba2d07a44b37eaca831488ebb0cc7c3.nq.gz
    ├── 02f248ea4820f175bdf7539be8ac144ac8b1066a.nq.gz
    ├── 032d8815871f304fe1c7739700b3fc9d263e96b6.nq.gz
    ├── 035a32f5f15f26594b2c1f8803391e998e2cd64b.nq.gz
    ├── 03605aeefd3878e01e8a0d6bcd81de4278d0bd92.nq.gz
    ├── 0404f0f61916fc71e449ef43dd94782f5aa5483f.nq.gz
    ├── 05deba320eba7dbdaac75569b25a2d6fabccd70d.nq.gz
    ├── 05f6eb927a0e1a5bc5edaba39d35ba050dbfa7da.nq.gz
    ├── 06437a6bfa153d00badd9e610255b3f2966156fd.nq.gz
    ├── 06ad936bb3b407a1d8280370f3c4208f15195743.nq.gz
    ├── 08835dc82fa847e0513457fdf694a9f54d55c4a7.nq.gz
    ├── 0aa791cba9cc8dbd918b628524a40c1524b50e60.nq.gz
    ├── 0b1e8e04899f7c0c6740d4250474ed4b90968596.nq.gz
    ├── 0b4041572e65454bbcbba8c4236274b544203853.nq.gz
    ├── 0bd4e56f4ab5a0398f3799a02ee9bd434fd0af76.nq.gz
    ├── 0da8d1e72aa0ae321f9e0c80cbc6e6c8e2e814f9.nq.gz
    ├── 0dfae1b4ae30dbfa908fc43c91242e751fc07513.nq.gz
    ├── 0e08391039e8f9721ee6c6675d536fbcf299dc6d.nq.gz
    ├── 0e245e2e8d314fba147fba5b71253e294f51fed5.nq.gz
    ├── 0e2f56c2c6b4b0c116af6ce56fb8d6c4eac7a466.nq.gz
    ├── 0e3482127fe9d5933a09023615dd6d2d91634e17.nq.gz
    ├── 0fbf291ac2ba4478eeccff5f2f8098216a57bb08.nq.gz
    ├── 0ff42bfaf072147dd7e989bf98d69fe9ce7820c3.nq.gz
    ├── 10209170662fa850418eefac8ac62d872e3d4f43.nq.gz
    ├── 10a8adf2b427f9454c896cf5ff3a42056e94d3d7.nq.gz
    ├── 12a818cc65ba3d8963a487b04ebd7faee00585d7.nq.gz
    ├── 1328c335cbfd83c35d660484a1fa1cc69ca5ffc9.nq.gz
    ├── 13371e3ea882dfc07e92751e38d17b38efeb63f9.nq.gz
    ├── 153586e9b120f02e0cfb465194f467131a973063.nq.gz
    ├── 1658edb3a90e45a38c97c1b0e1d41b9294791e1d.nq.gz
    ├── 16d1b9f13594b307e0b915f215b27f63bce76b31.nq.gz
    ├── 1714ceea7a46b16c90f01b44fc1634af9eb673af.nq.gz
    ├── 17373a80cd76fe5a4ca6bbf49d847a630e64f422.nq.gz
    ├── 1769a546746728ad7bfc634bde02790a740afebf.nq.gz
    ├── 179f35341871ceab95b1aa6578ae1c2505d80fee.nq.gz
    ├── 17b873a10423e77164f33c840280948f79fb8187.nq.gz
    ├── 17ff7101a692e17a22d0acbabb1fc3b8a97e11c4.nq.gz
    ├── 19371ec42a0528ea8186ea2db74426c0b89576ce.nq.gz
    ├── 194570c7dd13a2d6f23941a2780440ea885f0955.nq.gz
    ├── 1a7397f4bcb93274bb62c30d47e85c6f9bb5b81d.nq.gz
    ├── 1a8d08617c3a828fd9b756042dbe4ffc24a83674.nq.gz
    ├── 1aa64a2658b2e88eb91b41dea51fe9f65b495956.nq.gz
    ├── 1ba945037daac8e813a3cae1ebdbe2c8b0b1590d.nq.gz
    ├── 1c359b67463cfab619ec03dcb216b46cf6c7b361.nq.gz
    ├── 1cea05a9ac6d55c2bd38bdbc15d2767523c36497.nq.gz
    ├── 1d073537efd0214fbf147910d4776a65568277b5.nq.gz
    ├── 1d2b1e4b7bc1d3661f26d1b3fb027a8a747177a2.nq.gz
    ├── 1da103e64aff591884b9aa8ee271172e59dba739.nq.gz
    ├── 1da70133a5bca09d7f63d7161badc8de8f963d9e.nq.gz
    ├── 1dc62b42a3f82a1e3508599dd7a5cf5561ddecc6.nq.gz
    ├── 1e371b5af598900dda0611f88ede460878a1daf5.nq.gz
    ├── 1e3a0bd19fec98a7bf00f93672864ca0c6617f6e.nq.gz
    ├── 1eb279dee3b8f95fc1345b7c775afe8d520288ea.nq.gz
    ├── 1f47206d79d693c21c8f4bc2b8dde68761c1dc34.nq.gz
    ├── 1f59ac26f9ad8f38d1de80974236d1058fed07b6.nq.gz
    ├── 2001e3180df9a0cd512601b07f3ec5336c1d77e7.nq.gz
    ├── 2044ea7e3eff1e52e16e6fe93cfdff07e344a4ee.nq.gz
    ├── 219ad0d75dcd17f5f111edff67b3382a27e8367b.nq.gz
    ├── 21b421077db291725ad1d3a96c0a61331d7f0e26.nq.gz
    ├── 21b5d8fd6df1686aa0f2c1e45d2ee660c67f3064.nq.gz
    ├── 21b7f1833185c69086cd87d36f96348ad8baf504.nq.gz
    ├── 21eb2a4e322643d04542fa3aae692d0dd8ea45a3.nq.gz
    ├── 22184d3d2e8e8740027e2c374d83f0b22c457473.nq.gz
    ├── 223ba6d0c7623658fcb125d5b105c8318f07bf18.nq.gz
    ├── 230224570c9dadd95e380d326accfc31d0b3959f.nq.gz
    ├── 2331746debd6ddbd402197421f3a560588609859.nq.gz
    ├── 233303644c149e01fc5ce63dfda0d2efa5f607f6.nq.gz
    ├── 23585ad4d752be93ebc0ffd9f0e7420f8d577f2e.nq.gz
    ├── 2566b11fac66ab913fbec21a7beba874f850f5e6.nq.gz
    ├── 2572f92bff70d6df27dbfcc1a8f361e602f653c4.nq.gz
    ├── 2609081adc3e7109d27493163b69b455e0af1e32.nq.gz
    ├── 26309f556564c83271f23498c55ab841e5361c54.nq.gz
    ├── 2757bb12a7e4d9f1c30ce0d4102ae25b3743267d.nq.gz
    ├── 276e5c8be311783821a5f27dae822881dadea0d3.nq.gz
    ├── 27a1678b18c91ee9edd1eb4c2fd646788e6386b4.nq.gz
    ├── 28f1c459e8c4a3ade68370e10ecc9bc7eed751cf.nq.gz
    ├── 295a2af8e234cab017cedc249c6aa44d8e69664f.nq.gz
    ├── 29d469a0053198647b04ec12d6abd022e3e81b23.nq.gz
    ├── 2aa18ddff308cf6aa3282cf19a5d5b2d844a1261.nq.gz
    ├── 2ae5d683239974d2e484349c98a798cf5513ad36.nq.gz
    ├── 2aefb303f813d74bc9c101a84bfd335629aaa660.nq.gz
    ├── 2c37fd93372d0f10609a437361ca6d8d462b61fb.nq.gz
    ├── 2c74c55a8d8832ebc579153bc8afe8b279537d43.nq.gz
    ├── 2cd27848e133f0177612b81d23fce18c91f772ac.nq.gz
    ├── 2ce3828d8a4a9b5086b8b12dd6a49804b79d3351.nq.gz
    ├── 2cf9b62e8c8a8cd005866910858c337e855e5ea0.nq.gz
    ├── 2d3e779136556fd67cc0aae035d95f6b72caa16f.nq.gz
    ├── 2d54dc8997fe7e1c2d1475c26e574a5e87262eeb.nq.gz
    ├── 2d8a6d798261acbeacc2109139150b15e797eef0.nq.gz
    ├── 2dd09b150667639dda56f3d6e6f2d9a5425c7c7a.nq.gz
    ├── 2df95721f67a43bb956ecaf5dd78bed4a2d95b3b.nq.gz
    ├── 2e0c0c985d4a1905e5dc1c61380010c4c4b147f6.nq.gz
    ├── 2e6a3557d913a1d2b987d7e3519208c20d4743bb.nq.gz
    ├── 2fad4025a6499d96eaae16f72b776c039b0b0a6e.nq.gz
    ├── 31039b25cf392e383feaf25213d947f1b6b9ca77.nq.gz
    ├── 31ee6336a035b4c4aaf71f5f7497fa5d93f7a719.nq.gz
    ├── 322cca81974134e955bd2f6578121b5f0f2f69eb.nq.gz
    ├── 33a8f8870a34c2f919e5430c163514e5e2f94548.nq.gz
    ├── 345be0508acc62efe2224b6dad342b0c8e3dddc0.nq.gz
    ├── 349c8c156f4d4455448e405b0112dc0aca5ed60a.nq.gz
    ├── 34c4d04a24e68b1b61839c23d6a9bba1de70e599.nq.gz
    ├── 3581adc9b387db6c3c4cac61d37a74e0bf9daa00.nq.gz
    ├── 369528fa7820a45d44baf4eb3f19333795728424.nq.gz
    ├── 371a4771b32547acb4b41b8498f66faaee0e5344.nq.gz
    ├── 3726f7dc887c37814ad337b2184653591e5a2230.nq.gz
    ├── 3737dc936217f381b122be815f9d36daaa1e4726.nq.gz
    ├── 373a7c97ce645e39ebfeda952fd8a80c94502055.nq.gz
    ├── 3752a0ea9e4de333b2a46b49daacfcf3fe9f818f.nq.gz
    ├── 3783d540b76b2745394581351dc40e6079da7b64.nq.gz
    ├── 380ab2d752728e5756e4cd5cbb3093d1bd966ee8.nq.gz
    ├── 38239ca28cf5323b9651e664ca1b4454a5cfdd05.nq.gz
    ├── 3880e2f25fce58f0dbd9bc746f9ae7d66ee05db3.nq.gz
    ├── 38b266abde2f5088a4c44bc2e7acb87e13c658e0.nq.gz
    ├── 3b624950cf243959548adf4215fdfcefffdac9d7.nq.gz
    ├── 3b7e2b746b970823337aa78b5186efc1372a265d.nq.gz
    ├── 3bb55f002b981ab3ffb211fa1fc45bfa9e7dfda3.nq.gz
    ├── 3bb8c0fbb174cbd8a1adc119f7e783e113a75de1.nq.gz
    ├── 3be8c74780c51b56ebfa212cb6856642bd8d7669.nq.gz
    ├── 3beb5f68cd7f98206a6f7ace1f50cdbb54a3f636.nq.gz
    ├── 3d20cf2b01788a6995ddf2c5dd366d8990d1c42f.nq.gz
    ├── 3d64d5b87a14631980e9ae378fc26ab4f382b26b.nq.gz
    ├── 3da193eca79cce0bc56a3aa2720854a6e4bc51a9.nq.gz
    ├── 3db5a1451aeb1955abd6a62e9774027ecc96a7e1.nq.gz
    ├── 3e521f15e461299fe47a7358a4398e88a4ff4e1e.nq.gz
    ├── 3ee91e473c9a79934f8d7e59c48c304fd2171ba0.nq.gz
    ├── 3ef8b7eec6e193a6e664e2320e7da557d073d9b3.nq.gz
    ├── 3f00ac834e4764abf1637fa3eea574652430e7da.nq.gz
    ├── 3f434b07e21c718a54af728994a47f1c88435eb9.nq.gz
    ├── 3f5614a068d39e31e028c4feedaf680eb9dc2565.nq.gz
    ├── 3fd5416717b74101d85d7247b6c2e3f1b2de1489.nq.gz
    ├── 3fe4fdc0a24f50e3610fcb45c793a4e6a81e66c5.nq.gz
    ├── 3feeaf68d45708704c7d117218f10236fe3cb737.nq.gz
    ├── 40114d516a5dc2ab24cde0fb3a7a7de11648b064.nq.gz
    ├── 4056ece28577612c7fe90f699de97b44c4cc580d.nq.gz
    ├── 40bee3bd38371a42cff08032d6e74a7e28bd11ca.nq.gz
    ├── 40d2a837da1c404a95a1ee952cd5c0836445e39e.nq.gz
    ├── 40efdff1de5d69a11d86dd20ed9e89e5cef44e84.nq.gz
    ├── 411e756c8b9c686cc303cb8d98cf1ec6d823272e.nq.gz
    ├── 41ec37765888887a02c97491cffd42ce6ce7b014.nq.gz
    ├── 42a31e5b944a0f9dba717caa26c72915f872a430.nq.gz
    ├── 44c1278c752f141a3036aea528e58165036705ee.nq.gz
    ├── 45049164d907ec2af38a01128d82d3007d4632b0.nq.gz
    ├── 4575b2106b8078c44b5057105ac837c0f83373b7.nq.gz
    ├── 4779fc64259b92c55072b1ac79f5b6012cd4a6cc.nq.gz
    ├── 479815ba31c29d959c9e10b257370cffff8219a1.nq.gz
    ├── 480ce77825a16645f912cf06bb3dea03d341c8fe.nq.gz
    ├── 4850c1233adb95ed962c32168fdfba7244d31f38.nq.gz
    ├── 485d35786e3d5e580d11d8478bcfde2a5ca0f265.nq.gz
    ├── 4866784c9fb6f1fec7ca44a5d1364f95feaf045f.nq.gz
    ├── 48978332794a532296e64c9685241640d77fe782.nq.gz
    ├── 4a4f1f2f3f23198d4e0c7c219da8577cca83cc9d.nq.gz
    ├── 4a5052d4f93a79edf007c5b5722c486a1760da07.nq.gz
    ├── 4a9460afe02b61541f4a1db91c0a5f7c6cc991e7.nq.gz
    ├── 4b1c011db30eaa6ef4be795b185a8c8741f8fb7f.nq.gz
    ├── 4c2695f9470272d54bdb01ac1ff1bfa1e9c43b3f.nq.gz
    ├── 4c6990ba0972642120b746b6c5228a39f77d94df.nq.gz
    ├── 4c8080db2b0bd21701d3acfe006ac6e9d5fb01fd.nq.gz
    ├── 4d17bdd658b70cdf7bc4e495b0512ea3d0dcc35a.nq.gz
    ├── 4d359d0157d80b78a88941498a7bd1a796c81353.nq.gz
    ├── 4d4fc57f9339a8dca0ef64d227fc52fc2d46232b.nq.gz
    ├── 4da4894fa4e5cccadba19f42b59bc2efadd7a7ff.nq.gz
    ├── 4ef470e5f7319b6793195c8ed725744e52470736.nq.gz
    ├── 4ef699bcf41534835d0dc366d27eb57aca9b9808.nq.gz
    ├── 4fcd75587485fa496e3c933335e6eba13efdae86.nq.gz
    ├── 4fcfceeda0845f53d2742c8b72e60902089aedd6.nq.gz
    ├── 50e20f12d49352dd9757930b07c75f3f79439458.nq.gz
    ├── 50ffb2bcf60d060966cfd7a07710a568a16e6b37.nq.gz
    ├── 51353cd32f5469dda1d9418252b4eedcd4946552.nq.gz
    ├── 516c98c8eebb7612514636a5d5207917a08ca662.nq.gz
    ├── 5276b6352a340415fcb722e23c57d253829c288e.nq.gz
    ├── 52d8790fc664f4d66e8e25c8a3f2caf8f1cd0af6.nq.gz
    ├── 52fc383cab3d72d6697fb7d8874f362e51d6d2a7.nq.gz
    ├── 54730b4eef753fcc2f2ecda819f122c104534df6.nq.gz
    ├── 5535b92755993abb3b717cb133e6f7aedc394f05.nq.gz
    ├── 55d8d0cec150b41aec19d474713d8842c1943dbe.nq.gz
    ├── 5638ea0bdf48036afc64f192aadad5abc691c787.nq.gz
    ├── 569430ce5f8a019e0c258e099f97575fd4dda114.nq.gz
    ├── 5724b0ba905b559e51b92fd3fb2be253de48448b.nq.gz
    ├── 5775ca55303bb6ade2404d145db2a524b42650d5.nq.gz
    ├── 578c358ba48c674febd752c2e5b92d6b57ba1623.nq.gz
    ├── 57fff7a4ed104e932252adf29b33a8e6d413ab4a.nq.gz
    ├── 59817675ea810a8b4b5511554fbc603e5489246b.nq.gz
    ├── 59b70db0fd4be86a656947e0f55119513245386a.nq.gz
    ├── 59dd83574af912d795cfe4449a86ea988a0b059b.nq.gz
    ├── 59de0950a49572b8cb30126c96650918df2a30f2.nq.gz
    └── 5ad99ee363d64ca7a920fd772b91972322203e70.nq.gz

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

[holoviz/panel](https://github.com/holoviz/panel)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
