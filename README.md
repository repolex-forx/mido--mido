# Repolex Knowledge Graph of mido/mido

RDF knowledge graph data for [mido/mido](https://github.com/mido/mido), parsed by [repolex](https://repolex.ai).

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
rlex download mido/mido
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7c1de5df224a5f0c602af8158c8fc25497ad351b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7c1de5df224a5f0c602af8158c8fc25497ad351b
│           └── chunk-001.nq.gz
├── blob
│   ├── 023b6e9cef88bf7afa68ae9530c50af70cf9865d.nq.gz
│   ├── 028bb18f71b91563671353e57d5d4e156b374613.nq.gz
│   ├── 0314cc0cb9f745708422276c20856509a9b36ca7.nq.gz
│   ├── 09aafa0c16a4105f72ecac42d5e23e3ccb04115a.nq.gz
│   ├── 0a7e2ba49edf197f2a9b1b59d92bc0436f773682.nq.gz
│   ├── 0be4fd75646781a5cd0b59466afec1c364635509.nq.gz
│   ├── 0c270d63f99dc721a3e14d481f7fe4caeade251a.nq.gz
│   ├── 0e259d42c996742e9e3cba14c677129b2c1b6311.nq.gz
│   ├── 11304dd0a4ffe926422404478875cf478a199a63.nq.gz
│   ├── 1252dd12eb1c51ed6c4238a3913c97584b3ea1ca.nq.gz
│   ├── 13ca539f377dc705af32b8d2ce89262298ea2f06.nq.gz
│   ├── 1601ea137cd14d9623430243d26cfe150f8b9a8a.nq.gz
│   ├── 16dd5a1620da9ec746d651b92a644e4e4484df71.nq.gz
│   ├── 178aaca97a18400574ee4d293d3c50cf578240b5.nq.gz
│   ├── 195e10517384ea3966a80b55d06537b33e571133.nq.gz
│   ├── 1e485c2b45b949938a3efa7db46259c71c575f82.nq.gz
│   ├── 1f85252504c51c1c1f1a3374b2c4aa6985117f86.nq.gz
│   ├── 2071b23b0e08594ea6bc99ac71129ef992abf498.nq.gz
│   ├── 20bb3379a4ae45e6181c6e7670184489f8506b44.nq.gz
│   ├── 20d7f93979ff1c5e35c9aa7c9b08ce42242786bd.nq.gz
│   ├── 2137266b45024a24fab7868e581e5fe360e0b0f2.nq.gz
│   ├── 28d93c2bcd83cbf405626b5102beb54da03f3b34.nq.gz
│   ├── 2a0644728f1c13ce154fc1aba456f3cf92bd01a1.nq.gz
│   ├── 2cc3e65a0da1ab6ae09299e5c4ebdf8f28145971.nq.gz
│   ├── 3020f28bc84f1f6dcee94f4134f59309c613edb1.nq.gz
│   ├── 32089f6405ecd77cd785298b9dba7ef6e7d70323.nq.gz
│   ├── 354f8d284a85efe238529d52d43640ae3e744261.nq.gz
│   ├── 39a8591c4a5ef08a108d3e87cdc9ba8dffe8c1ff.nq.gz
│   ├── 3b4f2d8dabac60a5a3f8b661cad1434a7326e262.nq.gz
│   ├── 412fc9ebc6c271aac18f89d22bb4cd3459bcb6c9.nq.gz
│   ├── 42a077799c6c78dfc8747032875280d2edc88885.nq.gz
│   ├── 457957a468897a23e57d872ed4b95820ad395f9c.nq.gz
│   ├── 47e1c07668c5ec435c81ff1c6d72fe62f9e0bf2d.nq.gz
│   ├── 47efd7ccd43f642a9b7f314af875bfd87f32d782.nq.gz
│   ├── 4a93bc4d345b40a1ec56ab160cb9432d7fcd4829.nq.gz
│   ├── 4aa325b91f53f149953fcd2e6b9a497e5f2f11cc.nq.gz
│   ├── 4b30ea2a7346d1d3b60358ed7b70cc297803b21a.nq.gz
│   ├── 4c98650cb4f0979a5d9003eb688f560078f89ba2.nq.gz
│   ├── 4e063be5ae5a2f7bdeedb657a1aa504272c1f2f4.nq.gz
│   ├── 50e0698a8140f0447383a9fb1b9475c23bc02990.nq.gz
│   ├── 5170915aa6410a37931c6cdaf7d32c5f6902be11.nq.gz
│   ├── 53e5e3a291c6f83f2eddcd95f3c6d65c016737a7.nq.gz
│   ├── 559ff978f72818b328f406ede1904b847b93b208.nq.gz
│   ├── 57324027207352c74cd60a407c83239d160ec666.nq.gz
│   ├── 5739022a4c96f99a2fb6b957d5a2dc105e0e93e7.nq.gz
│   ├── 57e182fb477294861a9def2081d353e626d6887b.nq.gz
│   ├── 588aa369c36a0b52bbeb83c9da509839e5eac466.nq.gz
│   ├── 5c97f49aea8ab30049803524669bc283f8bb5d0f.nq.gz
│   ├── 5f58110fb63cf2913e5408b271bb6d2148e8010b.nq.gz
│   ├── 6007f73eda5ed679d850401b584dbe87d8fe5296.nq.gz
│   ├── 61fa145682b164f2a2d08af016e117599085bc57.nq.gz
│   ├── 63ba03bf711d1610357baf075b7ed18ffc3fea9b.nq.gz
│   ├── 6415bcf97c84c9fcef6849dd3fdad920a6172afe.nq.gz
│   ├── 656f4dcd4277c8737692d0c0e2de130b424e9b77.nq.gz
│   ├── 67564a3eba49b22ef1d39fddcd3f189931776fa5.nq.gz
│   ├── 6910f44e1caa4fe154232270d74dd8a33ab290a4.nq.gz
│   ├── 69bff62553084d81192ebd30392cc88873547261.nq.gz
│   ├── 69da67174964256d4fc890b31001baafe19de3f8.nq.gz
│   ├── 6c4231d23bf3d6e1ea1f0bce9145ebcf1a3c8fa9.nq.gz
│   ├── 6ede00da3d98488fe5a03be4a88432f48df2fda7.nq.gz
│   ├── 71c6f47601312132566bc2bd03cff8c89183973d.nq.gz
│   ├── 7217019c901c22061b07a7d116b91639662119e7.nq.gz
│   ├── 72500d2e1ad50713b736e544260deba0e056a113.nq.gz
│   ├── 757802a820b9143b1aef5c2b67339d22347345e5.nq.gz
│   ├── 76c5672ba62e05a7fbe33e7d07ae3c8c97e71365.nq.gz
│   ├── 780d366b1db51d92ac3b9884bcfdf3f8106691b8.nq.gz
│   ├── 788ad007e15287e3f418d06d6cfb2165ebc01801.nq.gz
│   ├── 78d98bbf1aa31e9586f06089bdb6e2559f1dedc1.nq.gz
│   ├── 7b953a798ebc53e7a622178dabc03bebd184d6be.nq.gz
│   ├── 7e9fa17a06a40ebf76e2dceac4ef1dcd17544d1a.nq.gz
│   ├── 80e92573df3fb57f37132c4050a7d46eaba9ff4e.nq.gz
│   ├── 82f8e0bd082bfd08af788da4f931481f71a570eb.nq.gz
│   ├── 871f9bd435a8fc5add7457e925bc2b1d53ef9384.nq.gz
│   ├── 88855a1d5a38fa5f2d6e45d89601cfc07388f754.nq.gz
│   ├── 8aeb242f6be2f70490e41aeddf02887cff755d14.nq.gz
│   ├── 8c419105c6fa1a4ee196a0f8f41ab1d883c9e545.nq.gz
│   ├── 92b5bd1c749f466826d796a394bef2d5fe59e785.nq.gz
│   ├── 930cda30402432decc3ad8bb97ec072b068519dc.nq.gz
│   ├── 93213bd5d2de4ca73268eb7d2f0ea708068b60c1.nq.gz
│   ├── 9456d39f46ff9c1e732f0e70e94314d716a93f2b.nq.gz
│   ├── 99a7e3a2add0f1cfea64c6efe5d73062a0d20164.nq.gz
│   ├── 9b47f7a2c29f5741e86389f5f2c0894cf882079d.nq.gz
│   ├── 9d2def8da963fa898a0fa8c64d3269a4b604af5f.nq.gz
│   ├── 9da21a0951f5584f505a5de4c6dfed58036cf991.nq.gz
│   ├── 9e488b8982f82b1fc640710a2ae77ee2b7451191.nq.gz
│   ├── a1930645f2c8bb2c4524db868729d32d14735ee5.nq.gz
│   ├── a2300577ccf44a545c51d2b11a8e697c656cfb03.nq.gz
│   ├── a2a6e9b398434fb6921ad49412232f80d0641efa.nq.gz
│   ├── a50805709da60c597dbdb53b5ffb59300abf3882.nq.gz
│   ├── a53024edcf1a4bb59f5285569abf30fee3463330.nq.gz
│   ├── a53e33c264c6642cc99f49418b6be57c58c40bfa.nq.gz
│   ├── a70e7055db32d98ec0b5f13b71a113c858d322ee.nq.gz
│   ├── ac6f64b611084814c73ec10cb0877b5529f35da0.nq.gz
│   ├── b0f27ae3a006cdfce0e9ac69c0373d3af964b570.nq.gz
│   ├── b38aaece8e68c0a5ed23f2d11b192c0404b58885.nq.gz
│   ├── b3ad3054dd9e998d9d659c2cc88be21e38ada8b9.nq.gz
│   ├── b5abd3f99bef1e9cdb10757e8db81b9aa56e2a4f.nq.gz
│   ├── b5ddf3bad88226ecbe8a72d51316e11347f01126.nq.gz
│   ├── b6e45c74cf50f0d4c9119de0ca885c5773f29bc0.nq.gz
│   ├── b752714b1656f2652d8d454700311cd2e8d3180e.nq.gz
│   ├── b9288fcc0d5efdf215e949488d18a277362f7287.nq.gz
│   ├── ba1491d3edc8da9e4adcbf579794b1876a94b22a.nq.gz
│   ├── bb85185f38eda2abaf33c9c6bf80175d88351ff7.nq.gz
│   ├── be92a2a104396e02f25aef9847848cf1b7941631.nq.gz
│   ├── bea82d8d600f8e144db544f73dde31d6ebcb4678.nq.gz
│   ├── bfa6553d3852683af1f23910181a4cff4b5a94e0.nq.gz
│   ├── c4070535966e50582581f7be6a0967b8edd83eba.nq.gz
│   ├── c99b80e1adc57e8c2e0cfa253516267d02f451e4.nq.gz
│   ├── c9f04381ab423518bf60caf08a57835e9da70661.nq.gz
│   ├── ca7c818b0de82184bc34dd2cf424cf5f819ca7be.nq.gz
│   ├── cae6eb8d9702756e070b8fd0ee0b5fdc2596a8cb.nq.gz
│   ├── d155b502fcfb14142dcc2c600cadcd54ab924565.nq.gz
│   ├── d3df4c15e434024f7c19910afeb8048ab385c2cc.nq.gz
│   ├── d5cf30cad0ed02b1f086ff4e76b9d711d825b52e.nq.gz
│   ├── d8b593555d08fe69cc40cbce119615d7cbef8d3b.nq.gz
│   ├── d8e814cb36ffc182486b97b362e289a578abaf66.nq.gz
│   ├── dac3e7c506b6cc9823dc0d9089ee4b45953959f8.nq.gz
│   ├── dae9c706fcefe789820432f8688dc0d8d0a9182f.nq.gz
│   ├── dc283b0004cfbaa15a624755cdf08c52e85b456a.nq.gz
│   ├── de94095babc3c740a5efce93ba5fd44b78454abd.nq.gz
│   ├── e3738ce46b83a7c3c908440377fb74a660723b84.nq.gz
│   ├── e3c67fbfd0ae615089914426a1e4b06581c0fb54.nq.gz
│   ├── e52852ba27de3bfc38238e95b21c1dcb2d1597f1.nq.gz
│   ├── e5412678ab7b0ecbd129d2cb67dc50d1dc493b24.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7b1973c4e5f85dc62790c6f702047a6ddbdc2db.nq.gz
│   ├── e7b8fe19b8bd7e5efb73634595f5f484ca988364.nq.gz
│   ├── ea36854f7ec5728e45b102a70c9e80c2b10ccad6.nq.gz
│   ├── ec406a27cb26926b8b664384a7e250562c20a3ca.nq.gz
│   ├── ee31709803a956145c7e8fd6065a528a9d030996.nq.gz
│   ├── eea2276c4aa77c64dd965e495fe0c442aca34d0c.nq.gz
│   ├── f4e345aeaa0ead1ae17f8dea17b0494d567105d9.nq.gz
│   ├── f8414d3a44fa1a7ba9937e54ccfd82fa6bbaf0f8.nq.gz
│   ├── f8b6f79c0b7cfe93e3cca0c250fad46d6d0f21c4.nq.gz
│   ├── f93dd0c7992062f6ac700497ca266e92cb74ad3a.nq.gz
│   ├── f94c4ce0e6e84fe1eef00a68c61299bfe4d2bb60.nq.gz
│   ├── f96d86f2300395d3f6cbfbfbdae365661a95f7ce.nq.gz
│   ├── f9f71ff58b7bfec764d61f13a565326740c6f0fa.nq.gz
│   ├── fb651e6ec65cf91d8ce1880c48e9b015efb54487.nq.gz
│   └── fd968a2f7e4392f0ee1982fcc4f19ccd8a29b986.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7c1de5df224a5f0c602af8158c8fc25497ad351b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 148 files
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

[mido/mido](https://github.com/mido/mido)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
