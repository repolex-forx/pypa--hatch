# Repolex Knowledge Graph of pypa/hatch

RDF knowledge graph data for [pypa/hatch](https://github.com/pypa/hatch), parsed by [repolex](https://repolex.ai).

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
rlex download pypa/hatch
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7c26ebeaf8b83f5f0374a2545bb15e36c87db0d0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7c26ebeaf8b83f5f0374a2545bb15e36c87db0d0
│           └── chunk-001.nq.gz
└── blob
    ├── 00313af2dbe90d158e70bca5a48e175ab661883d.nq.gz
    ├── 00382793c054c1d805f7642e393ef2a66a9ed96f.nq.gz
    ├── 003bf5267cd0f71a728465a24b78de5c15624550.nq.gz
    ├── 00a33be4372a79b2455f210af0e6e277c34b0590.nq.gz
    ├── 00e0af96aedd45d084e32f89b1a30685b5f51b9e.nq.gz
    ├── 0127eff6feacd5ee5ea9223fb68da0cb14cba5ec.nq.gz
    ├── 01419284aefb1e54ca99d398a51093f6d765ae80.nq.gz
    ├── 0192ab7c39c73698b85035f7460e6a0b2c305335.nq.gz
    ├── 01cc6510002c87fd4cc89588ea59852aecab08cb.nq.gz
    ├── 01d4c0ddd9fd44b1b3124d5ad52a2b81efe48fb2.nq.gz
    ├── 01fb069535c043c72c4d75eac644deafa001f5f1.nq.gz
    ├── 0357785059e5ee74653c77de319c29f0fdf09cbe.nq.gz
    ├── 03c3088d550b55ed0ea6a51e303c6d2f0e2d10e8.nq.gz
    ├── 04072ac11320d8603d165d2c437dab524db1ba0e.nq.gz
    ├── 055ad4aff6a84318de23215264421060aaea92ea.nq.gz
    ├── 05761ac57f6bcedf28c34c3867849df97ef89a8b.nq.gz
    ├── 05fcf78ba40c9a4bc27885393e7ca649945c892b.nq.gz
    ├── 063f2b8643d7540146b63b3e7ea57b820929f157.nq.gz
    ├── 067ef4e91184182597f4eb9af35468c8bfe95eb6.nq.gz
    ├── 06afb4b5f0f2c6bdd26f5ef2577a2c06261bf279.nq.gz
    ├── 07a0eb5d7fa7214f3dcb277c7fcfa2913acf8d14.nq.gz
    ├── 08953b50debe192317f35b656550289100f9c5db.nq.gz
    ├── 09050287d37ed3ad085ed469975cd214e2d7f863.nq.gz
    ├── 09432b82847d14ae43a75ddf386fc7b665c5c38c.nq.gz
    ├── 0a978a59d911e4933b3a514e3a600f777bee2bbe.nq.gz
    ├── 0afa4b5bc1e0e64457d73a6f648747c7019a1317.nq.gz
    ├── 0bca8707f6cf98aefdb7de40d8d2a089c0d4cfb8.nq.gz
    ├── 0d061789ff2ef76749860ff281892e2c13a1eb9d.nq.gz
    ├── 0e49936007c8a6a3180cc3d700ed79a8a4042da8.nq.gz
    ├── 0e760746cf0ae9e0d5af3a7e2375b46993e53d2b.nq.gz
    ├── 0fcef793e193b5db7ba41e0cca7bd83666236e45.nq.gz
    ├── 10168d25bbf66f4557c579ae00b65a9703d4401b.nq.gz
    ├── 11637a1a9ee4e41255ef225171388ca060bff892.nq.gz
    ├── 1237671d6f233a64a3018b684228a1a604c0fe83.nq.gz
    ├── 125b2310485716936e9a99a865f90fd0e9d94d0a.nq.gz
    ├── 126b681ce6a71281f22146669c40afa38b45591d.nq.gz
    ├── 128b3151de6369284f591d94551db52d7307b40e.nq.gz
    ├── 12d7b1925a45449a5f4b58aa46e3a9db62089072.nq.gz
    ├── 1389d83d0517647ac9fb8898b1c0e27ee0548b9e.nq.gz
    ├── 13db3f6579fa512ec622077c578047b93e69672e.nq.gz
    ├── 142bc6df6ea6010d2c170f266c6317ec318f78d3.nq.gz
    ├── 1494828f73617b6c484570f648b467aa36a451cb.nq.gz
    ├── 16e8033ef7664d2a626608248c8ff9b3c1b88b75.nq.gz
    ├── 1717c4a515305b8ac421746c3b89ef749cbcc994.nq.gz
    ├── 1860384d1ee1fedb34c70418355135854a847222.nq.gz
    ├── 1a65f27fc5960836968074aa36014b23e29d88e0.nq.gz
    ├── 1b7c7359c1286669cd75eb7e88f0a7139cfa2437.nq.gz
    ├── 1ba0f5b6fd3804dd921fc22a8a542ca476050dbe.nq.gz
    ├── 1c2b20109011733f2d18da8acde3657456fe12ae.nq.gz
    ├── 1c320d18716ab43856a19ca83e088ed81b9c0207.nq.gz
    ├── 1dd01ee12e3012117fb8753e3c57d86f756d03b0.nq.gz
    ├── 1de3d4177040658cbb8e7c8c2c7fe92305810e87.nq.gz
    ├── 1e15b35789d0bbe226bed9dec350852d25df810d.nq.gz
    ├── 1e52e6862c84345c6661b75f3aa0687c3db469fe.nq.gz
    ├── 1e5374bb36e34d3805f810353aae296d062ddd9f.nq.gz
    ├── 1f4672a598aed406f96e23aaf0446f7ed35142ec.nq.gz
    ├── 1fa06b9a748bb4a2782b6ac2fe5c99f323892914.nq.gz
    ├── 1fdf0c35316e848f62082376466c5db046178c38.nq.gz
    ├── 1fedddacd74ed23fceabdf22e2e01a6b13d5abb0.nq.gz
    ├── 1ff7c44aed74cafc26d15ca1a98481a3abc0e51e.nq.gz
    ├── 201ebebddb232a4748cd9bb06224ba4de840c447.nq.gz
    ├── 20d275810ed75ebcd228b07b8273874ae6b0acb7.nq.gz
    ├── 2136d4723c09144f642d26401ed076affc061787.nq.gz
    ├── 21bfbaa6cbd479dd5930960d3cace10754ea0ad9.nq.gz
    ├── 223ef8a743ca5e918ccfd61c80bd982d39fdc849.nq.gz
    ├── 25e11cdbc0cd352a6bb63d5062487c23a6a8a1fb.nq.gz
    ├── 268a0b525fb0cc20302d2c54a30effca5f80e1f6.nq.gz
    ├── 26cb9fa5343f7310802c10977ec27ba18b90b6dc.nq.gz
    ├── 282fc61fd1f401be32ac102d769794ba7c45e8cd.nq.gz
    ├── 283be29dbde8005a205f202eaccae39b0ce948de.nq.gz
    ├── 2856a9411469e73c470e0ee7d96be89cfed25fde.nq.gz
    ├── 285a98bd4a026cedf61af6d9e86ca8ead8cc838b.nq.gz
    ├── 291267d7ecf21ea8325ed3b866afaff86eaa374b.nq.gz
    ├── 2964b4cfa3d2cd668b3ed65399814331ff29c9d6.nq.gz
    ├── 29c8b6a33e48c53fe227d8f5840b608512566e4e.nq.gz
    ├── 2a073e3d14ad07d81be7daa18ec0cb52dc8def3f.nq.gz
    ├── 2a7de69dc590c32c1fbf27da7f08fea4145c640d.nq.gz
    ├── 2c6b87048a68aaf085cd17a0f937c566f9096c51.nq.gz
    ├── 2d302df8f0005c36465b708a849e596705f405df.nq.gz
    ├── 2e3bb992f7bda33511eba7f1f7182a59b7a0477b.nq.gz
    ├── 2e3bb9e7969d81c87d3623ebce733c1e567383e2.nq.gz
    ├── 30524e171f810aa4f226595cf9e70c594854b76b.nq.gz
    ├── 3213af3a5dde06495e3ecf095d3b2e139ba4b95b.nq.gz
    ├── 325442f631356c969563a6cd4865920e81a2e449.nq.gz
    ├── 326cc9a2e74b5950ffeb0b1a3d6af7e1981e2dbb.nq.gz
    ├── 327c2a376f7e1514ea1429e937eb4f8cbe50c813.nq.gz
    ├── 32f0435c985b63afe4a4d360bf002c81f4a4d78c.nq.gz
    ├── 32fb73e9d493cfc3416483f43e82df2828d7b66e.nq.gz
    ├── 3464644b1e5cb45765ec2884b1292e8e41297ae6.nq.gz
    ├── 348144c38984aa0566806f204e648762bd8344cb.nq.gz
    ├── 3588cf83d66d975a5b5035091ead67bbcffc9d5b.nq.gz
    ├── 35dc4c35b4ea3489928b05492967603ba059b89b.nq.gz
    ├── 372dccf33d5d881299e4e111a7d37d5870694e56.nq.gz
    ├── 37a5a483f0cc0919123797d6956e554696dd5e06.nq.gz
    ├── 388c823d76fae6a50e06e4ea1811d6316c95bfc5.nq.gz
    ├── 38d9e1d1299878afe2a3c75ab0c29e6ea5ec7920.nq.gz
    ├── 392eac9c5034c6396c79bccb2cc8d722124ca04c.nq.gz
    ├── 3a4201cc2b1491c2e3892279c4559afbaf99823e.nq.gz
    ├── 3a730d7f5453fdb25be26b6bfbd8160208d281a5.nq.gz
    ├── 3ad565bd115038d1c9d8421b5a6a9be4a08684bd.nq.gz
    ├── 3b425d119ec0cb52c768a52b676c8bb5957f3cae.nq.gz
    ├── 3b50034a9e385f6727196c76cdb89e50e07d182d.nq.gz
    ├── 3eb0ddd91d62cc7d2c3cbc4981c20a6835dc8c0a.nq.gz
    ├── 3fee5affc28a8c0481bc73da108553bf1b02100c.nq.gz
    ├── 40237cbbe78497c73acd7a21a041b603b52d61c2.nq.gz
    ├── 41e52a66f37d6425eb992a6c46beb51bdccf2ba9.nq.gz
    ├── 4291bb5658e870c419c8df237f0bde08dc413ecc.nq.gz
    ├── 4328cfbcc0f1ab7756ab4d491ee73628093ef404.nq.gz
    ├── 442d9223084d9bccc9ee565de7fac48bf489e634.nq.gz
    ├── 4447422be31333b8920d637df66f91d85ea8684f.nq.gz
    ├── 449143902e38ccdfd58363425955ad5bbdbd2039.nq.gz
    ├── 453d00a0144e376b2f9d85174c9ed9a10317a522.nq.gz
    ├── 46b4b041435b6cdcb0fb357877f9f63d7feb73d1.nq.gz
    ├── 47638b7da98b1fa9184cadd32c210437502b81bc.nq.gz
    ├── 47f23a34f1d50373c81ecbc02ea0a72aeb7f201e.nq.gz
    ├── 48a3172920536749722027daae6b8460cc4b7173.nq.gz
    ├── 48c1b16166bc5e3199300f16424ff20b5a52de62.nq.gz
    ├── 491a57e9b72dfcbf91a0cb00b0ecc1fb5f660376.nq.gz
    ├── 4a8d03db5e611841b913262c9473c1e63da3ac04.nq.gz
    ├── 4b1b19d8716988ba9af30b7a8818283eaab97bcc.nq.gz
    ├── 4b304d3edf1a3b8bfcf92bef41e4d1c28d73a3a3.nq.gz
    ├── 4b360c291cbd839abbfaac360612e33785080250.nq.gz
    ├── 4b43fbec5c08062c4bab665f4d30aec7cc6e3734.nq.gz
    ├── 4b4de53127cc055343ec894cb45c3d9ae35b2a05.nq.gz
    ├── 4ba8abfc8513653f4fbdafe297bda7e7951323fa.nq.gz
    ├── 4c528f2fcda71fdc526fa894e1f0b58ef7a431de.nq.gz
    ├── 4c7b440e0d9a785e3ae2646bcd30e57b9a7d8abc.nq.gz
    ├── 4d2efd6116dd0e876613bb560c2ea91505288d6d.nq.gz
    ├── 4d915bfcec1703d63c5686f452768b79c22d4da3.nq.gz
    ├── 4e8ef3b248b80a06fb5fceac052da0f4ade5831f.nq.gz
    ├── 4fdff0f48a6439fdbfe8b8dc1fe5b1416ea1f932.nq.gz
    ├── 4ff3f8c6ea9549082ad53e952a57848dace9c3e5.nq.gz
    ├── 5031bfbd0284ba285c36401ca0ec6bf2eca1230a.nq.gz
    ├── 503ab6407faf6be90e8db885247541b7a1438305.nq.gz
    ├── 5071b81dd05f9e8b9eed5493422362084cd60f63.nq.gz
    ├── 50c0e69d1c56e2adf32faf2d87289a6855dbbaca.nq.gz
    ├── 50f9d1068afd185b87426791c72ca6935452ea99.nq.gz
    ├── 513dfc7460d96c7211dd11b3222927eef94e85a3.nq.gz
    ├── 528089fce490cb8803b5930493f4c83cf8a12f0d.nq.gz
    ├── 52e33bca6ba5608aaf52f96ef71fbf2a9ae8a78c.nq.gz
    ├── 5323fd7b9400a9408cfa996e8cba80e54a05ffa5.nq.gz
    ├── 53b1cd7e7f6aa8fea5e6e711660f3afe3f1abb27.nq.gz
    ├── 53e75efccad14dac0df0c3de31f02453571cde3d.nq.gz
    ├── 553d574d0e2d0f17812f663fd23231d99630d4eb.nq.gz
    ├── 55a40b7c866b3b86453bc196f1e250bb335dd4b4.nq.gz
    ├── 56206cd90858f7692e1525368854bb91918da49d.nq.gz
    ├── 56253792feb47b6e9905514cef302251110d1acc.nq.gz
    ├── 568962cdfdb9accf71c1bab3caee70a579efab1e.nq.gz
    ├── 57df723dbcb98e7cc9113e7e5eee88771cc97b7b.nq.gz
    ├── 588fc86fbff5116f4d2e5fa44a0842db4c79ba58.nq.gz
    ├── 58fe951a7a2faed2a005fbb46c4c6d8fb8e4838b.nq.gz
    ├── 5941b217c7236957987f2e722cee7a8a556c2881.nq.gz
    ├── 596eaa60a93ea84077db89cfb31775cabd86b846.nq.gz
    ├── 5b09fd4985a29a7161852b72bddf28a2f4456abf.nq.gz
    ├── 5b83bb2835bc174cdb4e16574269e38ec3d750ed.nq.gz
    ├── 5b907234a5a2f383740ada8addb8c4cfdd57f2c9.nq.gz
    ├── 5baa15e708d355e94ccf31d2534dd50271d504fc.nq.gz
    ├── 5bc72000feeeeca265141eebb4196bd146174366.nq.gz
    ├── 5c4845f6777e584af0cc502783b8666dbd4cf4b5.nq.gz
    ├── 5cc1c49344eef3a269caabfe0b32235c3be695a3.nq.gz
    ├── 5cda740f827759b157bf20a402ef100091672df8.nq.gz
    ├── 5d901bc9c8764e8044ff6d4e193f1ddf33803cc9.nq.gz
    ├── 5e83d22bd3d10341022cc1c26a64ccd5dea1359c.nq.gz
    ├── 5edc1f1ca028eec8fc9cfb3268408630b1313ba3.nq.gz
    ├── 608b84fa920effb334155e9d94d8e04fc69e51e0.nq.gz
    ├── 60d3918c1568413271ccd4f566f7ee6123a1d30d.nq.gz
    ├── 621eb1c9012e810a9f9be06bb17eaa44433c5a0d.nq.gz
    ├── 6267701df7163b4e7f808fe2858ea76da077e3be.nq.gz
    ├── 629b3bd4a2313223370559b9e6dae5a1767de20c.nq.gz
    ├── 62a75c5a327a787b4326abef8230b62ff2ba9908.nq.gz
    ├── 62abc69ed43d8185ba68f368c502a111fcf5a1a3.nq.gz
    ├── 62c076ec92bf5a2bbff14cd9e65c8c37d1fe813b.nq.gz
    ├── 63b0282a695eda62010a855fe15ce04e9f3b0441.nq.gz
    ├── 646a9acb1f04abdcd2d5d3123c2f6930da6e1f23.nq.gz
    ├── 649dcc6955a66e8942789d74f294c126c4d4606f.nq.gz
    ├── 64e0df65473b02c1f3c16f59b0921be646d9f947.nq.gz
    ├── 65b0dde52159a1a68d0c031b13ef7d74d237a749.nq.gz
    ├── 65cbaed91c8dabdf91ca322e327d0afe3ec1fa7c.nq.gz
    ├── 65d4ed897dd3be4827cd38230a0ccb9fe12722b7.nq.gz
    ├── 667f92b5d5cbfc117e045ec953125bf3efc9ca2f.nq.gz
    ├── 67e490cdc865ac8f34e7b3f5a463e6c8dc701a83.nq.gz
    ├── 686971cb33566706eacac5fc045e2d8ee90fe875.nq.gz
    ├── 6881a3e40e784ccd3ca4803824c33c71c995fb3f.nq.gz
    ├── 68b00c94a2973565b4ac8f73bfb9a8eb88101e78.nq.gz
    ├── 68b5ec0e60e6f7e0a84ea236a25597a7b80c11f3.nq.gz
    ├── 69ef04ac76a1f8167c49ef2cbd1c4f337123bd60.nq.gz
    ├── 6a4158828d471bf389258714521b4d99a20080be.nq.gz
    ├── 6aef79149c147acc43b4fd37b54aeaf40fc1d2b2.nq.gz
    ├── 6af095444f874cb83a69e4614af1a1d9509fe7e3.nq.gz
    ├── 6b4f865993715e3b19ebbd70616d115b58ae2018.nq.gz
    ├── 6d15cbd1e19c5d80551e3c61797321972a63eac6.nq.gz
    ├── 6d3af09ea908c32646b59b8ce94bf19fbe0de36c.nq.gz
    ├── 6ec6bdf6f79b2746dd115cf2d5b7583a9a5415a8.nq.gz
    ├── 6f506bc4e7677e5e29978dd4df383aa36ee0cf54.nq.gz
    ├── 6fb73ac68637b530d1c909e9af184dd5dd396f3a.nq.gz
    ├── 7112eb072d6c6a70caf854a250c101261caf8a42.nq.gz
    ├── 71bd98cbf10009b39dbb48c109b09ad634f5ecb2.nq.gz
    └── 7277c7fad60776801658255754aa55db210d8e25.nq.gz

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

[pypa/hatch](https://github.com/pypa/hatch)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
