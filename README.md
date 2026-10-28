# Repolex Knowledge Graph of huggingface/transformers-mlinter

RDF knowledge graph data for [huggingface/transformers-mlinter](https://github.com/huggingface/transformers-mlinter), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/transformers-mlinter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5a85da7c529c8e087b50884151cfe827e85b39b3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5a85da7c529c8e087b50884151cfe827e85b39b3
│           └── chunk-001.nq.gz
├── blob
│   ├── 002852e7da6aa204de6750d8b34fb1965e3d1f64.nq.gz
│   ├── 008e75022dad9a64dbd72d149fa90673b03ea63c.nq.gz
│   ├── 010a7f1ba6a6ad123b5ed79f98d9b1c869fe844b.nq.gz
│   ├── 01e85ed4507bc7bbe04ec0545cec3f0c8e5c553d.nq.gz
│   ├── 09f61063150edc864a9c8604489b342e5853dd38.nq.gz
│   ├── 0a5c289e94fccd813482d66bcbed412a789321f8.nq.gz
│   ├── 0c55deda9c554868b88173410359acdf05efe172.nq.gz
│   ├── 0c6f1171bb427118185b093d8be970e4c84d1bac.nq.gz
│   ├── 0c8da33277d2c3d22ca15240e365f5c440cb130d.nq.gz
│   ├── 0c8f751487aee664015a2185adb086ac4e8f654e.nq.gz
│   ├── 0cfac78bd374b55386d10678d1c2c00da1a58680.nq.gz
│   ├── 0d1ce1653a6afbe024cb52650ca3351facea4419.nq.gz
│   ├── 0fe21d6a03f8987dcce68955209a8451f3810ede.nq.gz
│   ├── 100b46d9ba866b04dd4b7a2032e38f8aa16da667.nq.gz
│   ├── 1317f31b018809964221c6125223db670e314321.nq.gz
│   ├── 1586e863f5b5ac744c2f03306d8eefdb2111af23.nq.gz
│   ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
│   ├── 1ae56dca2e3ad15ceca29d66abfd17071e4760b7.nq.gz
│   ├── 1b87da720cac780c0b2bc5852506242c0416f287.nq.gz
│   ├── 1ca2f0b212839af2677fa85256e13be15bdbd6e0.nq.gz
│   ├── 1d6299230195fe4f0b6098802d35488c334d3a46.nq.gz
│   ├── 1f1a171f9c1fbbb1c4820239f3bf14727389e3fb.nq.gz
│   ├── 209f6b7a9653aefc76054e43959136bfd273db46.nq.gz
│   ├── 20c9182475536b70abd0e8f8c5d95ef98e72d922.nq.gz
│   ├── 2506d0be28e1d27282cddb943fa5d4ce2617847b.nq.gz
│   ├── 2783ab031dc5ea748c64e5d9eed1fea160d15c64.nq.gz
│   ├── 27fd89acd6d3ef2a309db32dd65e2988698d20ec.nq.gz
│   ├── 293bd6a352d444bf52d425777569cd9ba92b2745.nq.gz
│   ├── 2a4e0882a6586aa5b4f6457aae9ac4a0e3f12754.nq.gz
│   ├── 2eb11099c33a615939ca6769d9b071a398b98ca4.nq.gz
│   ├── 30fd14d4456b9b2a26402641e8b7045d94c509f0.nq.gz
│   ├── 31aa7d11d0a545b360fe94cfaf3ab395e6085712.nq.gz
│   ├── 34c53780afc8db193ae045329a055c1c3d179772.nq.gz
│   ├── 34f5188316eb7210ae56d4973a31591b016299e6.nq.gz
│   ├── 35d0e16ec707ebc02571d2eefe09f537abb13bd6.nq.gz
│   ├── 3bd61a4c19441ef0f1cdc59788434572616ad7aa.nq.gz
│   ├── 3dc518d4c8f9a36258bea569beed457fbe7a0036.nq.gz
│   ├── 3df4846d0ef6457b6bd33643ea3b34761f9e95be.nq.gz
│   ├── 3f3c9266ee659a1797b6890c6b49e74aada63b58.nq.gz
│   ├── 40e22d424715e421edaef0c29534847784428076.nq.gz
│   ├── 41480ad9a8c4d94857cd5866ccdab32ef106f63c.nq.gz
│   ├── 4338b23530286f6847abc4ef9a4307ac04fb7c14.nq.gz
│   ├── 449eca7a9abebb73b0cfae2b25b464b94505a9c1.nq.gz
│   ├── 44fa7f80c2ee98fb0dd536042adafbd4b13a6e18.nq.gz
│   ├── 45d1e8c79b4364d3bb8afc622e07fe96f3d1840d.nq.gz
│   ├── 47f22a60e3ee81904cf5952bc1dc01eb7454a7f6.nq.gz
│   ├── 4ac48d6639d1b7171489e7fd9b73e251ea83583c.nq.gz
│   ├── 4ad815d9e558ec9debd3c28e343266ba536814d8.nq.gz
│   ├── 4b529ed1270fba3aa9bb27ed8cdd36da0c4c7c10.nq.gz
│   ├── 4caa2f5ca50c5b885dd8fb1ed7eddb15992541e7.nq.gz
│   ├── 4cf2c7a0e4c0909125f425b8604fbdc44c666ca9.nq.gz
│   ├── 4dab421f665358de31eefa0535c06ab9978bc73e.nq.gz
│   ├── 4dd0febe69a6e313fab94b3fb0336e82781e8202.nq.gz
│   ├── 4e2a439efa78cb10e11d5ae9c4aae3c8a5cd133c.nq.gz
│   ├── 4fe2f98db9da9372a0bff3c49fd323c1eadca11c.nq.gz
│   ├── 50ad9e8ebd3d6d11d7c68d9582a62142534354b2.nq.gz
│   ├── 5458402205b6d68c91ab0a5aadc47d2c3217b22d.nq.gz
│   ├── 5555a9b2264b1840643054a445ee39d4c90b0fbc.nq.gz
│   ├── 55f6cd78c6b9be9205df7fe07e5bf30faa11e3cc.nq.gz
│   ├── 5666e19d45d8afea9bf157d779be7aa813ff38ed.nq.gz
│   ├── 568e6ea2245e41cf7f8126293e3319126069bcaf.nq.gz
│   ├── 57ff98aacd87e24e432d99494c9af18de9dd32a6.nq.gz
│   ├── 59858cd0ad78b138d8c8df8e91fe7b3a58f0205f.nq.gz
│   ├── 59fcb8b8bf67bae99c0f1a1e621be7ba431e0c31.nq.gz
│   ├── 5bb63412f78d691446310e773aa63bfe52f800a3.nq.gz
│   ├── 5bd9435a742009f131b77d6a8f5f4d15709d24b9.nq.gz
│   ├── 5ddd317ac0338d8859c80b7b636d3f514b098597.nq.gz
│   ├── 5ee4f2c0b3d17f750125104f7543eec83fedbbb2.nq.gz
│   ├── 5ee88d63acfc591890d6f827c2446f762a1f1545.nq.gz
│   ├── 6042e64d9f5cab7e3c477940865c1d3bbcf5aa5d.nq.gz
│   ├── 611b18d5592b7482eb24d2286513792401308c0c.nq.gz
│   ├── 62b39299c8173c85a618c133d69a75be2415a16e.nq.gz
│   ├── 62c5abb9eded513b20a255960c33539c529a134b.nq.gz
│   ├── 63a724b580489d6d9e03c828298bd36e4cc88f28.nq.gz
│   ├── 6450e04ab56707fb72a5bd2c3b7dd67ba12a8910.nq.gz
│   ├── 64d908847b213fe277d94d420b30aee58fc61cb5.nq.gz
│   ├── 659d6a73cf2bb736a9689601fc3ada723145b6d7.nq.gz
│   ├── 67a059c7b986ab0d550ba29393f60791678199e6.nq.gz
│   ├── 6841a2817aa2311e5b8522fd852bec38e714e48b.nq.gz
│   ├── 68b7d66c97d66c58de883ed0c451af2b3183e6f3.nq.gz
│   ├── 6c24bc507d69dfadae34348738edbae8cf47b17b.nq.gz
│   ├── 6f13c848093bc43a5ee9aa05d4915227c76c52cf.nq.gz
│   ├── 6fc5f20a5e842801cfd4aca70a157b17e86bc4b6.nq.gz
│   ├── 7219646a31d1005ef771a99a0028296b86b64033.nq.gz
│   ├── 73c7bace06e562ba8bde9c9e26f365663e4d589d.nq.gz
│   ├── 782908443aa6a911b8bee1484fc47a0902aaec71.nq.gz
│   ├── 78b43d83cc15682d6f891d2d0c86b58407935386.nq.gz
│   ├── 78b92207c0e0811c04dd0b90c5d09be2e68278e0.nq.gz
│   ├── 78dadb8624e9aab675cb6209d203cd3d6b942077.nq.gz
│   ├── 79a45a78e9d2876c214f5fc57a344011cd8cecc8.nq.gz
│   ├── 79ed838cc31797df7b39bb8274cb47336961aa28.nq.gz
│   ├── 7cbe19405c47d5dc35a41b1edb500d81fbe8482d.nq.gz
│   ├── 7d74e5242340d17c665f6da7d793755cbe2d93a9.nq.gz
│   ├── 7e0ae30f7f20b66f902f40b8847ae8b0a0364872.nq.gz
│   ├── 7eb79b2cdb084d33bb8c83a3f4e4504d657d8d64.nq.gz
│   ├── 8204db5821a7ab04041f4da34e2c11735d47db46.nq.gz
│   ├── 848e0732d832d2aaebba3757f7433c3f4ec6e234.nq.gz
│   ├── 8651b86288796fab9e609d4f9e73d7811fc55251.nq.gz
│   ├── 876a8f26e75c60413a94588667f60cb7d14bf648.nq.gz
│   ├── 8af9178b415ab33fec14194a5e28474e55f678e0.nq.gz
│   ├── 8d7803367b2ea2299c9b182523cfe2404e9f890b.nq.gz
│   ├── 8dd03b0fe7b4c5ce23d8e7ee08e6e2bcfc64c8ef.nq.gz
│   ├── 9170ec305fb9b5f6c4f24c7bed7d94a376412bff.nq.gz
│   ├── 91775d774b6f6ea2ad2f4cc4c9fe30f947e04e33.nq.gz
│   ├── 9224dace90bd603d2c9bb3190257bf29bc0522a7.nq.gz
│   ├── 93f9e9346ea48099f3898d8fc86e8d285cb0f851.nq.gz
│   ├── 9468645ddc9e68d134b5afda5ce64f961e34f24f.nq.gz
│   ├── 9502bd22a8fcd1c505a9532815369e87f7aadeba.nq.gz
│   ├── 9543e569ec00ceb0006c0842ac76763d19f6b912.nq.gz
│   ├── 968bfa8b5faa88f17b634ec022e3a5f2727bd338.nq.gz
│   ├── 96bce1cd16acc747cf0d8bd547429ee8e280ffba.nq.gz
│   ├── 97716987b55eed9e076fd197204cd3f1d10bf0ef.nq.gz
│   ├── 97eb201e3a3bb26bd6c9fe094c85bccdf58a912c.nq.gz
│   ├── 987c2f8c8959027c17e926fb705bd3db5f1021b9.nq.gz
│   ├── 98bf1b2ea6c41e07ec0c51df158f9a637b1ff6b2.nq.gz
│   ├── 9a633b8e2c76ca904b45c83a6c0cf2204a3c9fe3.nq.gz
│   ├── 9be4faa931e390cc34430459a4f9aebcd0687672.nq.gz
│   ├── 9f168ef2b53b7d3e43efcdf44cb0ff987c2aebe0.nq.gz
│   ├── 9fa6f9530a29548350e53540ac23664734232399.nq.gz
│   ├── a2cdfa28c721af59ce14860f618cb94b4e13770c.nq.gz
│   ├── a38bffa1f5ca71e9440bfeebcadd024beacb4e21.nq.gz
│   ├── a4f9e3e84ecb16fb972595236b7315dfafcf0da2.nq.gz
│   ├── a71fe237ca16e0d8efe8c5f6834fdfaa1a272e24.nq.gz
│   ├── a885fb282ab9ed10fe98063ff7a6f5d81b85cfb9.nq.gz
│   ├── aab2dc71c601a5c9497347b4cf4949bc21d6ed38.nq.gz
│   ├── ab3bd1d87fe5605872d536cef0e2f471f3983ba6.nq.gz
│   ├── ad7256b0813d8bdd2680956703eb3a957ea4d207.nq.gz
│   ├── b28461c924a4217b9478062bea99d2306d7d4d05.nq.gz
│   ├── b560abfabe28b6dcb61f7c3d4e522dc590f1b5c8.nq.gz
│   ├── b7ee3ae82b8483126c5fc688ac6a0ebcf47b2f40.nq.gz
│   ├── b92abfbd29a766f0d65b6f10c4eaa89689f770ac.nq.gz
│   ├── b9b5fbf0c645852640b20381b30a39d0487bfd65.nq.gz
│   ├── bbfcfe73cfd5793c106ae07150c43d70f8eef42d.nq.gz
│   ├── beb6d1d23b68ab08614384e051f353e617303572.nq.gz
│   ├── c2252248d5c0bed461169e6450a71b5b7305ac3d.nq.gz
│   ├── c3a293efd1fc62ed7db74ab4d4a74008967e15f9.nq.gz
│   ├── c462f5d1d81219d4ebf07f52bdac0e4415b57be9.nq.gz
│   ├── c562aea64ef77f2cd48f29759a56fc0906c4046e.nq.gz
│   ├── c61de82fba523af31c71dd0989bd0d8dba467f75.nq.gz
│   ├── c6e1d76079f925505150eb4900382fef2a89e248.nq.gz
│   ├── c975d6dec41c54ffddcb206cd2864fdfd8d41d3c.nq.gz
│   ├── cc457b0838c50002d7ef91a99857e12e2f0e6de5.nq.gz
│   ├── cd0f560c12f86f47995f9ef5c59035ed7e6de850.nq.gz
│   ├── cd46ef0cfed8b3a21af685f3fe1da5dd59dc66f0.nq.gz
│   ├── cd9d3c558440eb689813ef22b37f2b07aec55acd.nq.gz
│   ├── d1008acf75a3c78f83d1e24469d6522e3676ea7c.nq.gz
│   ├── d2f877ea332999c5e7e47e35051927a1f14a6814.nq.gz
│   ├── d322a5ff44dd0130c8427910b49e897d071f87b1.nq.gz
│   ├── de2afe8f395a97e6fc92711b0a101d8d21bf0c35.nq.gz
│   ├── e174bf76bda55c0c353501546ee8cbd8618bb8f9.nq.gz
│   ├── e18077ef0dc844e591b2486166ea8db49cf84abd.nq.gz
│   ├── e23e584fb2ea6084116d2053236823a655ba6bb9.nq.gz
│   ├── e5b483e069be49a086105bef005f287a6da20d17.nq.gz
│   ├── e62922701739de45e997933f8e691d35b7696a7d.nq.gz
│   ├── e6eb6830adbcca9fe8f4023454657468dcf51cfc.nq.gz
│   ├── e918d3568aecf9e2430a56c893c827c0656440b8.nq.gz
│   ├── e91fcf1d655a29413fc084a30c52eccaf77fa263.nq.gz
│   ├── ec042d6f8a31a5df57e05755dadfdc523aed4740.nq.gz
│   ├── ec661cb02858b9a10e79a57e4937d7efdde8735b.nq.gz
│   ├── ede42b7a15bcba70613e116c4249649ab7251f3a.nq.gz
│   ├── edf53f1ea8cb8d7c68a3208429d72f1cb5e6fbd6.nq.gz
│   ├── f02a24d6238e00b57ec8ec6f3b59568e779e0af8.nq.gz
│   ├── f0ab2a5d20712c71b227894201c612277d067572.nq.gz
│   ├── f475426f05fe9e0c06dad0087ede856ddc0a33e2.nq.gz
│   ├── f620c4044631149dd95199c65dee0fdee6cf9f88.nq.gz
│   ├── f9561d61c7c8b3134670702936707d2738bc6e2c.nq.gz
│   ├── f970b3b5e6096328b98a4b4e0aa2754f8dba41e4.nq.gz
│   ├── fa1b8f14530289c52deb28abdc0f84bc83272591.nq.gz
│   ├── fbb472cdf3095f762e71edc30a488ad70f8ff86e.nq.gz
│   └── fc8a9f97e06fa01b4590f247988ea3945d6302c6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5a85da7c529c8e087b50884151cfe827e85b39b3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 178 files
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

[huggingface/transformers-mlinter](https://github.com/huggingface/transformers-mlinter)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
