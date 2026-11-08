# Repolex Knowledge Graph of cohere-ai/integritee

RDF knowledge graph data for [cohere-ai/integritee](https://github.com/cohere-ai/integritee), parsed by [repolex](https://repolex.ai).

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
rlex download cohere-ai/integritee
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7a458b3ba6f9eb2ce1bd4bebfd4e151783ca8baf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7a458b3ba6f9eb2ce1bd4bebfd4e151783ca8baf
│           └── chunk-001.nq.gz
├── blob
│   ├── 01fa4838dfdccebe3db1b5bcc45cabef4e9caac1.nq.gz
│   ├── 021c1989bb9453ff17e697f5c2b623eb097d4f87.nq.gz
│   ├── 05144cbb9df9c16f0e41aeeff07bdc64429d3005.nq.gz
│   ├── 054bdc3104ffc82f36e6ad6470c8a77fb2dae8a8.nq.gz
│   ├── 0861dc30972e4f9552fe3b8a1384ad4918dc0b72.nq.gz
│   ├── 0e35a29dd648f34b4fb40e244c8521d3f8c7c7c0.nq.gz
│   ├── 0f27d12af8c1616b665b6529b3f349a0f3ab84f2.nq.gz
│   ├── 10058b16152128213571377461530c8ee9b8869f.nq.gz
│   ├── 10b89d9374698700fd5c4b2529ef3290577acda0.nq.gz
│   ├── 1104220b1ee3ff4d45a14bd1156b9a7a05614427.nq.gz
│   ├── 11fabb89cfd211f0cc8b4ce098f93cf6d559f9de.nq.gz
│   ├── 12619552c474b8ae1d55a8f81d1da079bc1a04c5.nq.gz
│   ├── 1303e34595abcad607f99a62a63713a664e49f09.nq.gz
│   ├── 139146dc13d371641a48df17d413c6e55a4c7508.nq.gz
│   ├── 13f5f0659f994f0b79526a46e0abd7fdd4808e5b.nq.gz
│   ├── 16a628c9a28f02d660ed79271b1fdd88235b4a3d.nq.gz
│   ├── 183f69a068ffc859c83f1d1fcd2cae0ca39aebca.nq.gz
│   ├── 18918b45a30b314f7415a9f1026cc2cc07fe97c0.nq.gz
│   ├── 19d11379789a78e99dd808f442580b14af6423c0.nq.gz
│   ├── 1ca4f0de12f52ef71a2820d5134e99269f2b6754.nq.gz
│   ├── 1d34a79c37f06a03c6dd63c6cbb92874cbf4a4cb.nq.gz
│   ├── 1d37a8204e7871d77beef52bcd06f03da7795be2.nq.gz
│   ├── 1dc7bb37953bc0bc47e96d2921d6c9e50b404805.nq.gz
│   ├── 1e18739f4165276ac0e79d9750d366453353377a.nq.gz
│   ├── 1fd28b2f78b12af90191b10224379bf4b0ad79d4.nq.gz
│   ├── 204ad727a7386a191f3de8cf0fb4a268a956ad22.nq.gz
│   ├── 20ffbc2413d74ebe956077c31355dc60e4549c87.nq.gz
│   ├── 210aaaa664ac50067f45da6b5c1d618705e12f66.nq.gz
│   ├── 2326d576623fa307143362c8401637792ab0b571.nq.gz
│   ├── 2575be719b59f9ddcc14788a9d70a05853f023b9.nq.gz
│   ├── 25bd3f1fc5ae26448da7859185ca63c2aebf6ec1.nq.gz
│   ├── 2690eb51f61808e2c943300ccdc90a8fa7ec159f.nq.gz
│   ├── 273edb89edf4099d0a58a96508a20f334f44bcf1.nq.gz
│   ├── 277a657b77898bc5502e576e4fda34e272342d93.nq.gz
│   ├── 296049b6a7d76ed29849f0b39d39daf38971cf74.nq.gz
│   ├── 2a425e301b72d8414b763c39daad89da30799ade.nq.gz
│   ├── 2b5fca19b3cfa5d5d7c409cdde39ceb771e8cb86.nq.gz
│   ├── 31286b3a894ba878f9b4d169b3c23800379a4c62.nq.gz
│   ├── 31e821d3d623373cc130bc250c2482a50a62535f.nq.gz
│   ├── 32bc6e25a71bfa1d2ed85f2917f826af3fcdd834.nq.gz
│   ├── 352d4336c9dc377e2b850cbfbcf649f2634752dc.nq.gz
│   ├── 363f72c44c8e9bf52b4a10f0d414d5837d740a87.nq.gz
│   ├── 372afcb69dcd1a7cfa5ce6df5fa0a2eb2b247b38.nq.gz
│   ├── 381857992de84afaf1e635f636ebedd07abdac7d.nq.gz
│   ├── 3aa5c12e51b98ee5f7ac4b3a066d2a658570c596.nq.gz
│   ├── 3ae512aa8f86dff1c32f849a3fd0e85a351661e5.nq.gz
│   ├── 3ebcf3a7ef0cc1cca9ec69b2a7ab940aec80b2b7.nq.gz
│   ├── 45977093334f9ab0d18a104e0846ea9c9e83870e.nq.gz
│   ├── 47d1cbd9333adc49e80cd1c6b36fa88c21b9dd4e.nq.gz
│   ├── 4a60b643e007cf25e0b15b1b4676582465dd0a5e.nq.gz
│   ├── 4b8fac8cfdfe37f399916dcb13856aed280de9ee.nq.gz
│   ├── 4b91178ae00f372475255fcba92ecbc930f5f7c5.nq.gz
│   ├── 4e46e99bd6074b63c83bf2ce6e2d5f01bf6cc859.nq.gz
│   ├── 50466bdea0f910c233e1b11ac02cd2daae588b14.nq.gz
│   ├── 50d838a5e827eef7f88e2fce15fbd46a674c31ac.nq.gz
│   ├── 5537920b38d85699169d18208b1a2dea2a0146e7.nq.gz
│   ├── 5660ec77ede2d63caec4aaff0e7ab16b655185f1.nq.gz
│   ├── 5c6d995604ca2712fa9aef6415bbfde595666994.nq.gz
│   ├── 5d6b71ffeb318ff3505213148636c0a0291a9a90.nq.gz
│   ├── 67f73830d6abfaff6b9591fb0fa4717cf2e215a9.nq.gz
│   ├── 69d8942e4f7f95a8a4cb8aa75a3a0c894afd87bd.nq.gz
│   ├── 6a1315b1d1e88982b851d97623c229752981e189.nq.gz
│   ├── 6a282bc0c0410bc9c01fe2104d05d86b11e87845.nq.gz
│   ├── 6a6e1648034486049799d1b7e1c5b950c985097d.nq.gz
│   ├── 6af38e7ab6b86ce3b757a494ea863047cfb89458.nq.gz
│   ├── 6b244244884f26053d2ea0c4aa947afa72305919.nq.gz
│   ├── 6ec5975bd82870ea8750b5fe7ac3d54f68d3eb02.nq.gz
│   ├── 75446a47c3d6ef875b8d948477eb7de9aaac110d.nq.gz
│   ├── 7692e26f42ee2f548ff6798fdca86220cf49cd4a.nq.gz
│   ├── 77086142c8e05e37a7e3e64d20907a4a99748578.nq.gz
│   ├── 77a9dfd10a8528971d7499f82e9bf5fe02557352.nq.gz
│   ├── 7846cf16b1b6142c3e99a868fb9b3e83ec133571.nq.gz
│   ├── 78763b2302a20e118a806805baaaeca7bf0dc7c1.nq.gz
│   ├── 7c88efe3d93aac7f60e34f78c0dc9a49ff896cef.nq.gz
│   ├── 7f3d3d84b61ff43f00ca957e61b4f56b04e035e8.nq.gz
│   ├── 803e31a7ae3739b740e0f279a63489328b96de49.nq.gz
│   ├── 82ba9dac024a1311b945f1c427d1fb02741542c5.nq.gz
│   ├── 84464928529527eb55f9e8cec3a1f3277bcf288f.nq.gz
│   ├── 84ae12cdab858c4d9701b6061ba704966c9823dd.nq.gz
│   ├── 84e703ed95c0c243f64a4456c51484c9ec565ab9.nq.gz
│   ├── 8565788ce6dc457956d67d671b470f3d69e2c6bc.nq.gz
│   ├── 88799e6ae7a7cac0b689678b90eb1ee812d019ff.nq.gz
│   ├── 888d9ef30067046dc9bc2c21066b8cc99d5ccf47.nq.gz
│   ├── 8a7b21993eead45439b0ffbf6d553dc25576ce81.nq.gz
│   ├── 8d7d21051c20d2f4536b7c8bb7c97c9ab48b835e.nq.gz
│   ├── 8fc16097936cfbbc33ed3e3039b3b8106b1d9fd1.nq.gz
│   ├── 9196614b56453b36e4606b6114ab0c02d2a0bc1a.nq.gz
│   ├── 9235403b729d41b43204f8e0c6d9dcd82cae4611.nq.gz
│   ├── 9302b1c5a53dfab7c6b34344b2f122774b0debf6.nq.gz
│   ├── 932993d427a9a38e3df7413023771d1a2d569284.nq.gz
│   ├── 943d4e1f775183d611bc9222559cf064beb21938.nq.gz
│   ├── 95afba4283edc11b192413f61bf3a09201c8fb0b.nq.gz
│   ├── 96f4d277516c3049bf5b8f9dfd0c2d55a3fd02cc.nq.gz
│   ├── 98e656399c678edd25baa078cebc55e5d9f0e34f.nq.gz
│   ├── 9a2af87319ff8a7ac1774be2d3ed10ea31bb0921.nq.gz
│   ├── 9ad3a1f0b73ada0f3d604e5688d7cceebcc76e25.nq.gz
│   ├── 9bb7fb24c0408f58374dd06637fcba688851bb53.nq.gz
│   ├── 9f48221560af7ee729a8fbe7a6cfff0c03fd4b87.nq.gz
│   ├── a09db2b0d6a1fd22ba9fe0e9af759dd57c5cd5bd.nq.gz
│   ├── a3362d9cef1cf6ee21581dfda4a0ad43597af008.nq.gz
│   ├── a69780a696cb78c35fcbd48c230495e941979f47.nq.gz
│   ├── a6f2c5f4daee4fcb722472c90804949c41219971.nq.gz
│   ├── a7643c1f1122e3ef029ad8d0ed810ae705630310.nq.gz
│   ├── a7893a2e13622b97f8acb9e98088a555efe00030.nq.gz
│   ├── a7cacea5d1e86da12ca5a744dc7d45692672ab7a.nq.gz
│   ├── a8352609385e21939300decf6dd804354e5cec8e.nq.gz
│   ├── a84436ccf484608c90e143f926d9a39ec2c0f914.nq.gz
│   ├── a92d5fb8b2b7c2be7d4cded05deba4a007e95613.nq.gz
│   ├── aa4c49d610e353e5fc64d70f731e506bdb3da820.nq.gz
│   ├── aabe2443ca4e6869063920e5ed06cf5bcbd918f0.nq.gz
│   ├── ab45cbaf081b16a6545d5e03103285c0295467f8.nq.gz
│   ├── ab466a03528f2d20e3e70082a61f629204a6fb94.nq.gz
│   ├── adb516de4f5098fbb6361c3704923e1600bd028c.nq.gz
│   ├── b16ec4864843fa18c1c4209ad92ecff449097876.nq.gz
│   ├── b37e8870318f4b990598d4108054b90baba033e9.nq.gz
│   ├── b39404a2263d1add3abcb5babaf7c24296677863.nq.gz
│   ├── b9862d2bd7a7c8b86103ef8e15e97120da1060a7.nq.gz
│   ├── ba284a4f3fd94b006c5b24fcf93c617c15358a9c.nq.gz
│   ├── bb5fb20d8ccde7ea1eb352d1e92abe55c89e1067.nq.gz
│   ├── bc8ce5ca233dc06a88b6339a44d33016194f6cf5.nq.gz
│   ├── bf9941856821906885311bcf4ca9813142071c89.nq.gz
│   ├── c0227a3835bbdd19830928d0b6e10f9873654d45.nq.gz
│   ├── c1c3f7c631ced7fe8532a15b3d9ac6970669ce30.nq.gz
│   ├── c1da4c9fe6ce7d8c7fea2264feec8037ba4e159f.nq.gz
│   ├── c4bbe635183d9d4792ed01cc6b1b1fc2b6bad5c9.nq.gz
│   ├── c561d5cd051ca2b9c4f925f74657999b9d188273.nq.gz
│   ├── c6c93296c124b7658fd56c0c8cb54dbab0bf4229.nq.gz
│   ├── c6f11aca23497718e9d89fb9f1c26d064c7d7d8e.nq.gz
│   ├── c72f8c3ed5c618f31cb54a8f274fbab910323a95.nq.gz
│   ├── c7a4eab3b76c5bea10f3305fcb78f889b47774ed.nq.gz
│   ├── c898f5d4793cf689247c2349af32baf256c51c6f.nq.gz
│   ├── d391d5433c4d0cadc2414f262474376e94344f72.nq.gz
│   ├── d59bd26679bf88421ff4cdcb88d252e10cbea8ca.nq.gz
│   ├── d73080af4564c290cca8b2d732384dce5e081246.nq.gz
│   ├── d78455259e19450694dc91f42822773d47759372.nq.gz
│   ├── da3c4d20c69f46ec83e0337fe967686b05055af9.nq.gz
│   ├── db7a2ffe73b06f7fc8070f857aaa3f8385a88968.nq.gz
│   ├── dbbf511d5cdac2747f8959585aba5c347b1ccce8.nq.gz
│   ├── dcf406533c5ebe31a3e5c4a982ea64607b2f6cd3.nq.gz
│   ├── dded0a36401560768a4f0eefccb3b0694277ee52.nq.gz
│   ├── ddffbae8bf274a21d01d38903187ccd08fd67fcb.nq.gz
│   ├── de6a41b0102d11755d341f005c0ed302f7ce2165.nq.gz
│   ├── e29a67448c498697e148e74276ef648ff6eb9937.nq.gz
│   ├── e2c2d407eceb7e23ebf61f8bb4d88d6148a0c0f1.nq.gz
│   ├── e5ed5ac3477ebdc8feac676ace5c961edd5b3cff.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9684b8bd3f8ebfd8e9f558057135d86ca3b8f4d.nq.gz
│   ├── efa9f7e9bf2b330d9eaab05fca89b6b773479c5f.nq.gz
│   ├── f253bdf4e45cc45dab3e6d1b64a2dd9d88f68785.nq.gz
│   ├── f42769880b3ee6f811354436e501ba24d1397da2.nq.gz
│   ├── fb2761b5070900cd3aaac64a8bd6e20a7d60f260.nq.gz
│   ├── fc80608d792eacfe4f54b8dc2afffd6eee0f8f15.nq.gz
│   ├── fceecaf42ef0ce974c19d16da36028d29a0991c8.nq.gz
│   └── fcfa7f9c7a0134de9642c325249d6d435a250687.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7a458b3ba6f9eb2ce1bd4bebfd4e151783ca8baf.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 161 files
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

[cohere-ai/integritee](https://github.com/cohere-ai/integritee)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
