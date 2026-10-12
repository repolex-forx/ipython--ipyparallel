# Repolex Knowledge Graph of ipython/ipyparallel

RDF knowledge graph data for [ipython/ipyparallel](https://github.com/ipython/ipyparallel), parsed by [repolex](https://repolex.ai).

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
rlex download ipython/ipyparallel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d724f99d7e4949e116ca986ad00576bc1d86a843
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d724f99d7e4949e116ca986ad00576bc1d86a843
│           └── chunk-001.nq.gz
└── blob
    ├── 00435e7e6563d66c23dc16ca45e001d317bfe837.nq.gz
    ├── 00ea2bb64baea29f02eb09b3986560809c813062.nq.gz
    ├── 019c6c1ae5f560209e374faf7f40e6c17ab09539.nq.gz
    ├── 0216d7b33acf9c3e5c4509543780ba3fbe88e1eb.nq.gz
    ├── 02aeaffdad894f50532e5d0ea963acb253d4fe1c.nq.gz
    ├── 02f2f9a16c849aa8b6b732aac99a694c05920373.nq.gz
    ├── 03f1e4e046099f12e7d51e495d9a2ecb4fe648ac.nq.gz
    ├── 0401dcfe8366f0e533993642b1ed8d734b455a02.nq.gz
    ├── 067e45d4d75592d9d1f260ccaa6e58c46a493ab9.nq.gz
    ├── 07d0e6205eddcee8cf203acbf0d885c62629b2b9.nq.gz
    ├── 09632b7e47c69a9ed914f6ebc59263cb02ba1bff.nq.gz
    ├── 0a8e35788de34ae4f573736bbc337fc4e7701f10.nq.gz
    ├── 0aca7397cd828913262f7930d77495015ea269a9.nq.gz
    ├── 0b5848774a7d4de11c73fb1932ce043edc486d4c.nq.gz
    ├── 0b6bb423670ad1c7fece1321d343dfa7d897373d.nq.gz
    ├── 0cecbb9462df4c98a24957c311f22540e82684a8.nq.gz
    ├── 0df7d15d110b92c2ae17d068b8948f66d03c2472.nq.gz
    ├── 0e5bac797affc96213363de297842fd809ad78c5.nq.gz
    ├── 0e5ec1be100914582b9fd82ef7bad9018d3da75e.nq.gz
    ├── 0e7fd64cd48ffd4f2ef4d112d019d45eed81b6bc.nq.gz
    ├── 0e9f2fcbe862c56cef6f0d633b20ebbf9a0bd204.nq.gz
    ├── 0eebc3a4438fe0794d3b1c149f8849a10c9596b6.nq.gz
    ├── 102003096a617a65aeba277dabf7f278bdb1c688.nq.gz
    ├── 109269d8c682a219d586f43fbe3d1a1676d2dbe0.nq.gz
    ├── 11380a4240e3576b8471129df6ec2fba52522b49.nq.gz
    ├── 1258982334bbb39e4e85d686720ad40dab6785d7.nq.gz
    ├── 13c92b3f696e6df7eb66cb63512f402b1034cb7a.nq.gz
    ├── 17b40bd4b8095fbb397540206b77fca8b9ba2d11.nq.gz
    ├── 18b11bba1e69f7129e8304e049cdf5be0b9e06c9.nq.gz
    ├── 197ce1f6d029e7dcad277e5680ecc4093493e966.nq.gz
    ├── 1a085e9969d8811f404c46e0941b6bd990d4c743.nq.gz
    ├── 1ac7ecc6501268c61a7842c7586dd62d08105772.nq.gz
    ├── 1b3063015554302e15eb179404a72dc66597845a.nq.gz
    ├── 1b76bf1d7dbf99c572216012b7261f43bdbd43ef.nq.gz
    ├── 1ba42521bc02f638191be23b125afd73f319194a.nq.gz
    ├── 1f1fe99f892c5db2592a9fdf3b066060848de90d.nq.gz
    ├── 2057b0c9bc116085a665f92db346f39ee3d6f12f.nq.gz
    ├── 22e84e3ff275fb655880a1189a75f16cb312c340.nq.gz
    ├── 238b0fcdb16cd84cedc5c301e99ee323fe2a415c.nq.gz
    ├── 242ac0fada9ffc9622ed7ac7368e4f530733e46e.nq.gz
    ├── 24c68439a480daa7a678888e09da36620f7d3a91.nq.gz
    ├── 24d1430da6a9dc87021cd6ccd8ca6adb62bcd72c.nq.gz
    ├── 25ed377f3516e832cf26320548740d481a356a04.nq.gz
    ├── 26208e12bed6717be8b22cc04065da676a22762a.nq.gz
    ├── 26d794a2ae72f91d28bf9d71fd54237b095a7bb6.nq.gz
    ├── 27be94c91e55d1bcfca23966dd84501e933ed1b6.nq.gz
    ├── 282ffa10f071b6473cb93b0798af6aa892aaf4b5.nq.gz
    ├── 2845c0e28bd70e714dc85c44ba19366b48d28d53.nq.gz
    ├── 28829c675bf27874474f5e00ea31ff2497930770.nq.gz
    ├── 28962ed3e54529ea9328d848832f677fd53dd8c1.nq.gz
    ├── 2a2dfa301414bfe31fe3579d5a1d92b73e132e42.nq.gz
    ├── 2b605c55549587908c78a24a50e9012a932d47fe.nq.gz
    ├── 2bd21d86e8ecc30210acf672dfdf837716061db4.nq.gz
    ├── 2c417c461f5efde63f7dd75cb693e5b76bc450a3.nq.gz
    ├── 2c658dfc183d0dd1a3521d701c49485a12742686.nq.gz
    ├── 2dfef594103aa11a928848f0cf642683f6fd0cf4.nq.gz
    ├── 2ec9fdedcfe9570a8017afa535a13616e5a46466.nq.gz
    ├── 2f3e31ac810463f2f5c86e2dd353c79e6e030698.nq.gz
    ├── 317a853aa9f69ae4af063e9b497f038f283b4a71.nq.gz
    ├── 323e64d7a3c57b37aeed16864b5b9a709aec7bf4.nq.gz
    ├── 325858e8143b482b3fb48fbee9118a19309fba19.nq.gz
    ├── 327339bbf30189f0dd9ba772e208e3ab48133b16.nq.gz
    ├── 3472728f31500b3494a8e6bc45d3b462f397fec2.nq.gz
    ├── 3478d34d0ca369f93f4dd9be44546060b6a8dc43.nq.gz
    ├── 348b7da5d76f6e41e9cfc33e2523c74ac15ebb8d.nq.gz
    ├── 348e17533a6e31ad6b0f9e75995104cc6ba10bda.nq.gz
    ├── 34f2c08d100851b7e0022bf84865a6365c4e202f.nq.gz
    ├── 36151a93162c5e2a5248fc03bdd2bb1827bcbe67.nq.gz
    ├── 36c08f7dd3a18c224b318a27f9d5da5b65919275.nq.gz
    ├── 378cb9b79c3ed7dc770f7ef53a04491c89171948.nq.gz
    ├── 3884fc01b46fe6429f051432f82f5505750e310d.nq.gz
    ├── 3914d4020e3da1bf47b28ca25028678b4991137f.nq.gz
    ├── 39b804aa55805f0c5a999ce4f534122e4534667e.nq.gz
    ├── 3b010050ae71b6e4c362051e7d5649d315cc09be.nq.gz
    ├── 3bebe76f14cf5c39076be7bbdb564192ca3d4dd6.nq.gz
    ├── 3c48b71af1c0d1c6fadb0f016078537befaab4e3.nq.gz
    ├── 3cbba19cf338d5730f5d0aa8ad700951516bd4c1.nq.gz
    ├── 3f76c725169af2e2b3e0aab071b65056eac73464.nq.gz
    ├── 4061c77257063d0b1d5b506c70a959bbf0a8d779.nq.gz
    ├── 40738ae8fa0a50c82f8b7ed5970b929f4f4c0f10.nq.gz
    ├── 41640047b099d54dda663ec4d7e3aff9f1b7f49c.nq.gz
    ├── 4369331d4a4c613eb45b1329f7831e167246e0e3.nq.gz
    ├── 450ccb020672dda283b0952fe857dc5121da0fec.nq.gz
    ├── 45616a50254e9521674507c504c713d9fdb14abc.nq.gz
    ├── 46f61456099f53d8f555d94d88fff691861d3218.nq.gz
    ├── 473d8f86816f3b60452cfabeb81bf70cbdf8800c.nq.gz
    ├── 47c11a21dff8e48dd7cc5e8925774a5bbaf10891.nq.gz
    ├── 482378449ea5493be646fa27849b895c799cce6d.nq.gz
    ├── 489f53ca5cb2cd8cb3c9e0fb5adb2419196aa4d8.nq.gz
    ├── 48acc3ef4767f02946f701742d167d45e86372bc.nq.gz
    ├── 48d54cd22a9dd084daa544feb64b074e5f5cf823.nq.gz
    ├── 4913eb0e5dca5b32aafbf9a47195778312c2c71d.nq.gz
    ├── 49fa0cd2f069eaa911b1dfb440192a91fae3cf1a.nq.gz
    ├── 4a833898198ad3166279279dd6c42879c9e233fd.nq.gz
    ├── 4bbdbb548ee85400faaacccb6a2db76e24d5bf39.nq.gz
    ├── 4cb2385c2e6cdc4581ce907348cdc85715a66795.nq.gz
    ├── 4d34daa0ae20834ab8ce067dd6867af825cac9ce.nq.gz
    ├── 4e5e8e11abeb14fbd27933bada5018e5f2e8dd19.nq.gz
    ├── 4f176ded4daeb275d572b1a1ed6ac2103e1df5e4.nq.gz
    ├── 4f1ba10cdcab42b7511a2c0e5904917680968cc5.nq.gz
    ├── 511e2691e6fdc174f28dd3c4a1db5d31b6c30864.nq.gz
    ├── 51a10b5b85bc35b957a285687a4449ae3c998716.nq.gz
    ├── 544b38e4fc2d33adfea15d5bbc798073aa53ecf2.nq.gz
    ├── 54846bf1c650d05c8f11cc6c3530ef9d7adaea4a.nq.gz
    ├── 54848b6d5e818a65c7e067e7c6076d58e196019c.nq.gz
    ├── 54b89a00e313ba6d56b0bf2e975b16edbfec1df7.nq.gz
    ├── 54e73c04033dde018ade081569e5d019a64e9913.nq.gz
    ├── 5622fdcba7620275eafcf7b740705ddc6fdd47f6.nq.gz
    ├── 577ffd8f02a5567703c1da51e548f9fc74eb6378.nq.gz
    ├── 59303f8d7d06b6ee5f60fe99b3650de5357b4416.nq.gz
    ├── 5998bf153bf276a7ea23e1c7dff38c90f1b3597a.nq.gz
    ├── 5a7a79144341facef1e57406216dab2a717fc542.nq.gz
    ├── 5ad1fe2068c5f929ae4188cdb0caab9a22b7e37b.nq.gz
    ├── 5b7a93509851e5a078f4f155a2565e1fadc6adb2.nq.gz
    ├── 5ec780811bf35a525a835a3aa67c196db060e8af.nq.gz
    ├── 6494f89825c3199fad8bd3a0df26728e85f5f4bd.nq.gz
    ├── 64f143459d9dd0d3a45154b61eaebe833a82b101.nq.gz
    ├── 65208ec770cebe268a70f8360864073129f0951a.nq.gz
    ├── 667b9b1e4ef918ca648e908979403e07a52d5b93.nq.gz
    ├── 67c21003ffc65158caff3cdc299276bd5adc30d5.nq.gz
    ├── 69617ef0d703a8b998ddf8e3359ca3dd50385200.nq.gz
    ├── 69d7e1cfc28b1c039b9dfae47687cff7c59522f7.nq.gz
    ├── 6d98e1861d02bb2be36be9edd5b66927bbe05115.nq.gz
    ├── 6ebd6220678a8c6c4e760daf3ce895707729c995.nq.gz
    ├── 6fb50d2dc62be72a4f5f4bc30ae7590f02066e33.nq.gz
    ├── 711c1b57a4488480dd50fa1d8b53b92122e11283.nq.gz
    ├── 715e0b993b904cd2ddc879c0b4effce1c734179a.nq.gz
    ├── 71dfc16808d0b82bea96dea766c572fbabfd2563.nq.gz
    ├── 72a380297293a6e896e7c8706a0037a108f63727.nq.gz
    ├── 72fa294eb5d922c5044e701645d7087f592371d5.nq.gz
    ├── 73c0eca8f1ca236fee43412213aae57f3dc71dd0.nq.gz
    ├── 748dd83c35a2fc28b0383f64b31bdca35d0ef25f.nq.gz
    ├── 75e6c7c9e1d50e4f815016e568b029e9a1d84d7e.nq.gz
    ├── 7602250c270518d7538c1db514dbbc91e82309e5.nq.gz
    ├── 778168de465415b427b5d5f335ef2f21352e4d5f.nq.gz
    ├── 779977d2972d43aa2cb3554a67df83acb1890c29.nq.gz
    ├── 79260fbd03bb83bb71da33846b9411b39db6649d.nq.gz
    ├── 7a675980156906b1a5f6986c25997904641cef64.nq.gz
    ├── 7a7b48fd987b5af906f16e2ba022bc0b0cc9afc0.nq.gz
    ├── 7adf01c52611fb9553b12faaa0e1fc7b125d3ae7.nq.gz
    ├── 7ce329cb8861f087cc34e60988166cd6aad0e951.nq.gz
    ├── 7e1c3490b7d103977dff05737d1df70e3d9a00c8.nq.gz
    ├── 7f69accdaa6ed7a5b8658a7c85c8543e6f1051cd.nq.gz
    ├── 8051b16bf39ebd9892235e6f691e69f45d0c10e2.nq.gz
    ├── 8234c288d6b7a2ae7f9e094607c62541f089b8ee.nq.gz
    ├── 83a1ba9702d9b5a2be0cbcd3dc349c8f2f380db5.nq.gz
    ├── 861df38586eae46ccb35857b46500c9adde5dabd.nq.gz
    ├── 868ada4ef573e87c089d19b21df281079e4436b8.nq.gz
    ├── 868c69e726b649d234e0ff1bd4dfe8c655c9fa93.nq.gz
    ├── 87ec118af1167cbb6ea13a24333d1b85a743669e.nq.gz
    ├── 88af1aad811c00bae617a0db1be969817fff29ce.nq.gz
    ├── 88cfa4812941d990b06808fa04ae6fb565a39830.nq.gz
    ├── 89b800fdaeea12c213ebf2792e9f6fea210ac918.nq.gz
    ├── 89c40a370a640620318da5f2b0af94d4336d0415.nq.gz
    ├── 8a4cdb57bfd1c0ec8fd2c6091d52c0b3d15088b8.nq.gz
    ├── 8b40b06f9e97e1d56d949c994f4f6ab53ebe1a92.nq.gz
    ├── 8bff3b9616425b97ef928e7b32c2ba9a85a2d9ba.nq.gz
    ├── 8de171bff322144d1e8d0efdd65813b6c5157fef.nq.gz
    ├── 8de42a0288cb110258f6eae0516f66543777ba03.nq.gz
    ├── 8eb42ff89876c11c5943396e1f42c1d873d84832.nq.gz
    ├── 8ec0ccb1654b72d0101f791651c92b716d5c3690.nq.gz
    ├── 90197106ee6c717b3a3b1b40c81bfa5c05e69ed5.nq.gz
    ├── 90484c0ca998d97cd6457c0c73c7d489147ed100.nq.gz
    ├── 907c2becad001a9fae439d82b83b6d85e0ea527d.nq.gz
    ├── 92b5d03ee7b1ebde7f79b49897376980ca1f6cb1.nq.gz
    ├── 93273b39c28d99864ff55d4f4529e055307440f6.nq.gz
    ├── 953acdc2d5a84d001ec5f80e72cef56b1ff0da4e.nq.gz
    ├── 98ba6ef9112efd3aee8b1bac3f7eb4735c8e7dba.nq.gz
    ├── 9a2f979ff15fe17cf41a14469c8a20a2443ba2b1.nq.gz
    ├── 9a419b0c9c60058f69ac1a132991a3ae8656bd28.nq.gz
    ├── 9ac2272dfdf09ca44e204502d840ba6346c296aa.nq.gz
    ├── 9b79da1c993d78dbea6cf141d1eaa2abb0d94428.nq.gz
    ├── 9b8a65b88b1aec2afddf799a54f8973cac6ceae6.nq.gz
    ├── 9c82c02a2f0ac2134ce6c44dc593e829e17fbb1b.nq.gz
    ├── 9c85fede9233d601026b46d95330031b5c106ddd.nq.gz
    ├── 9cd64c646a6a4fe7ad711ee245e37a7974422626.nq.gz
    ├── 9fc9a1b040d3454261df18c896e7067296e45b14.nq.gz
    ├── a0e09cbd40148e22594b2ee64a50fc55d7e5160b.nq.gz
    ├── a0fb0f9e7db82a7a895cce25f49b068af9dfc9e2.nq.gz
    ├── a26fa231ec7704fb2ed8cdd8e213ec01e8919b36.nq.gz
    ├── a39832e378e4b140a294d6dda7a2786f80a29404.nq.gz
    ├── a3fd27c0dda4058da63f4ebb6c1b24350ceb0a54.nq.gz
    ├── a5c17225c882a9d8795931c65aa8248f8e37f083.nq.gz
    ├── a821aaebcff09d385cf5eefa40716569211a90bf.nq.gz
    ├── a8edfc21b7f2785919d8d0b5450639613364a09c.nq.gz
    ├── a9ae954d41dc5b5685e44d04874d5ad63c530cc7.nq.gz
    ├── a9bfe57ac4f286b10fd4682e5dbb3f22a84ed928.nq.gz
    ├── aa37f4fabb2c47e7a36d7b2b09cfc3945ab17b71.nq.gz
    ├── aaa430c952a6c61d6944ed7ba61cc1216250fe39.nq.gz
    ├── abb0d30b2ca6c20a3798b5e884394e346147b678.nq.gz
    ├── abd0ef82d980f597b8b575d1e0c8cedadf301625.nq.gz
    ├── accd5d32b53fcb031e031ace82c1762bbf5cb47d.nq.gz
    ├── ad0fd8ac97da8d69c6a94d5bb72db53a6bdb50bc.nq.gz
    ├── ae7ba695479ebf70e6b1afc7e040051929eca09d.nq.gz
    ├── af48a04840fce12ae2bb89c1a4060d672b627d07.nq.gz
    ├── af8a6e9c8b7816ca57408562c54607fe8aa4b911.nq.gz
    ├── b279b7e2dbd61f38dd91781c4b11c60a8ecd83e6.nq.gz
    └── b2d10bf161bd3efe850f5462d633e2e481cbf2e7.nq.gz

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

[ipython/ipyparallel](https://github.com/ipython/ipyparallel)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
