# Repolex Knowledge Graph of zopefoundation/ZODB

RDF knowledge graph data for [zopefoundation/ZODB](https://github.com/zopefoundation/ZODB), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/ZODB
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 49497c7ade7d0027a90ced224bdd4f10322f930d
│   │   │   └── chunk-001.nq.gz
│   │   └── c50a0941d40b22ff5b6fb30a5eab625fa4beba62
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 49497c7ade7d0027a90ced224bdd4f10322f930d.nq.gz
│   └── repolex
│       ├── 49497c7ade7d0027a90ced224bdd4f10322f930d
│       │   └── chunk-001.nq.gz
│       └── c50a0941d40b22ff5b6fb30a5eab625fa4beba62
│           └── chunk-001.nq.gz
└── blob
    ├── 00f4adb10fb252728acbb98bd015ba081ab016c4.nq.gz
    ├── 013f46bded0988c78e70315124ffbc2e3ed40e76.nq.gz
    ├── 0188d11843d6291438ae75054c39755b021f5474.nq.gz
    ├── 019ea4158bbdd71ba8e9566fa80d9c5d881855d5.nq.gz
    ├── 01c950682eb49ef1a01986d9adc32f00a6b03709.nq.gz
    ├── 020afd6691b9d7f05adfefad20ea67b410edd8c3.nq.gz
    ├── 0227ac99e91764cc968fa3a223566a4f260559a8.nq.gz
    ├── 02c11fab21bd3114e1fa83e4cafb5beb0a67b019.nq.gz
    ├── 046fa0b199126015a4e22867b09f1f1e4219c1fa.nq.gz
    ├── 052c66f505a706e8e322780609a95bc1751fcaaa.nq.gz
    ├── 05ad765ac1e891aebeca7832b4a4fb86909fef38.nq.gz
    ├── 060bd67f60305e50833129b7ba4bafacb9c176ce.nq.gz
    ├── 06b2f7d8562e08b07f81d4d96b26b51c4414bf46.nq.gz
    ├── 0889b68e3a39e52450464316806aaf6eb9b33125.nq.gz
    ├── 08cacf26577b69c8e25b835935fce06ec15ebdfe.nq.gz
    ├── 09531348e1a405349a94d1974bc73ea9950095a5.nq.gz
    ├── 09fedec1dd7b9d51161e68dcd1077c28cbb99079.nq.gz
    ├── 0a5582ddb2ba9869e851860b1a413e9512b2be4a.nq.gz
    ├── 0b1acbf15751d64518a1945e9d8bf737d13bf836.nq.gz
    ├── 0bcfd26073c0e5a92debffe8b315b73aaa7142d9.nq.gz
    ├── 0bd1e7da330e34ceb4ea2281c98436e7bfe846d9.nq.gz
    ├── 0c4949d8ad67fd363bf93ad33ac97f39788cb2ba.nq.gz
    ├── 0d1ce99afd2241f24d936467c2516d1218a8d3c7.nq.gz
    ├── 0d323c14b5c9f3a43130c89f5154dbe6f6a67ff6.nq.gz
    ├── 0d4d0444858951285da9964d7c4655d6689b6d9f.nq.gz
    ├── 0e433d3a1b3ca9afcc05d29f17bfb5d721a774b5.nq.gz
    ├── 0ea6440600717da498645ed9fcb4e2d489c4d55b.nq.gz
    ├── 0f978a7e2af3819424698f78ae1d20a739bb115e.nq.gz
    ├── 10fb190fa70ebaa55dfae10be379fececf6a5ce0.nq.gz
    ├── 111de8f214fa79a116b04d47b4ae08ec18232c0c.nq.gz
    ├── 11d04b8e40d3d29591065b1a07bf57d57a9c362e.nq.gz
    ├── 120d3d7f2a21959037c448dfbadc93ee8869b3b4.nq.gz
    ├── 12624f7994d61a473ed6a489b8d48bf803e36016.nq.gz
    ├── 1310e70f557aee5bfb881604ab60f5ce9136b806.nq.gz
    ├── 131b1ac539b8e3ceae28977fbf31d86c3add163b.nq.gz
    ├── 13d24bef540757bc35bcc769cfd2920bea43adb7.nq.gz
    ├── 1423fc047554f5c961223b27b2a8dbb24a6885b7.nq.gz
    ├── 14a6d4f258e45a94648833884fc6da26bd29be70.nq.gz
    ├── 14b7b45f0b176185e1dc2706c12ab53d6141b79c.nq.gz
    ├── 15c5e01152fcb748bac910c338e4c9f8bcd2813e.nq.gz
    ├── 161f17cb6f08fc3ec9159db41b8d299744ed5324.nq.gz
    ├── 167f50c231a12ebf8f2159bffe81743bab28ff5b.nq.gz
    ├── 173ceb5f54170bb841c021f924bbd04fc2040851.nq.gz
    ├── 17803cc5f5ce8e3be0d825b2659f6e4c775d1940.nq.gz
    ├── 18498bfb3a9000b5daa61d4908cc77ca59126d6a.nq.gz
    ├── 19235ba4b9a936ce7fe5a081c66b4403737f995d.nq.gz
    ├── 193d22849edf24f9f1c17669649111685f50b569.nq.gz
    ├── 1989b7a8ea55495f8ff9e5870320e0d6b4685165.nq.gz
    ├── 1ad6c0f105f10755ac03fd892e6e05ce943ac2b3.nq.gz
    ├── 1b13359f108dbf28596ce178bd66b84a003a456f.nq.gz
    ├── 1b3dee81501c5639054aef33dae3503474313a8d.nq.gz
    ├── 1b9a4867f39d169b3b45af213e09cc0c7bf78b13.nq.gz
    ├── 1be8ec1d1cbe94b9c55f3ce696206bfd3d02d26b.nq.gz
    ├── 1c424be7abe26863b43022aff129913e1e133d73.nq.gz
    ├── 1cb6581ec42ceec255ba0b92a27c8a73455c0f62.nq.gz
    ├── 1e9574119a4ed41768132da8086edcbba9a92ab7.nq.gz
    ├── 1f5e69e760fe63793b43fac8777f0be0bda92107.nq.gz
    ├── 1fd2fb6ba6a28d38b3483cd74e78442d70d294d6.nq.gz
    ├── 23a99bcfc5a8961a9e83cb030ee265411f60068b.nq.gz
    ├── 24c877f4ba90db4ef03c60d05ce45d422456f740.nq.gz
    ├── 25fdb3f3ab5491f105414caf6565389b133ad443.nq.gz
    ├── 263be09ba52c88c4b7a53605db79ec2b6d8f5517.nq.gz
    ├── 28bbc22883fba47ab005e9d6930ee57c4c560e92.nq.gz
    ├── 28e6ae849ad41f1de95202cccc1da43fe9aca65e.nq.gz
    ├── 2912e3549a8b3a06023106c8822553831497f891.nq.gz
    ├── 2936ca8d171880e1b5b7e80e27d79fddfd10aaf7.nq.gz
    ├── 2956e0b7915a37191bb68726c29d08468dd8a8b9.nq.gz
    ├── 29963d38c1110f32732b582b5c419fe3b85bf355.nq.gz
    ├── 29b6bfcd98d987c6100a428b949586e736f1511d.nq.gz
    ├── 2a5906d593c6a625e12265449e45499f414b0b2f.nq.gz
    ├── 2b1e3765763c047537b54796c38dce655a867993.nq.gz
    ├── 2bbc2ffe6acaa9ba8d09d682c64900abed497d46.nq.gz
    ├── 2c483417146c022aadb01ca52f8e7690c06fd0ad.nq.gz
    ├── 2ce5b41bb8a81dfb9b0541031f4e910eb15d0ee1.nq.gz
    ├── 2d99e1c31a68cc32b15a5ff588803b892edfcfef.nq.gz
    ├── 2d9e8dcf69c1b29db1bf3cb4cb7cd7d8cf7898cb.nq.gz
    ├── 2f2b5b70fc8ec0519855596dae5d673f06716d3a.nq.gz
    ├── 2f31c6829104bc9108ac7fe2f5537b0f12d83c44.nq.gz
    ├── 2ffde320a9bba13c68b226fed5465aee2ad55746.nq.gz
    ├── 30702da6eb633d3c14c872d567d87439c25074d2.nq.gz
    ├── 30c15acb03563ac24e02c5c53e174e678bcda05b.nq.gz
    ├── 3119708cbe2de412570732f75f1dd1867be52773.nq.gz
    ├── 31e7200c39518c0d7ba3c091f377114da9fff747.nq.gz
    ├── 32a5f7d9ac8eaa971bea404dc149ee69aaf844a9.nq.gz
    ├── 33422a8c8fd0a8541289d46f838d30948c9c7805.nq.gz
    ├── 33a7eaaddabc1327e8b9e72c7d48be83dccf91a1.nq.gz
    ├── 33d52e55c56ba1d27cc897379ca726621a41563b.nq.gz
    ├── 342d1f12165efa1581147fa9516007bf3e1107c3.nq.gz
    ├── 34d26bff388e6b182140e7e8bba8f5e25a1ffe96.nq.gz
    ├── 36551afd20e1c54368a368f83c690e7338d88721.nq.gz
    ├── 3688fb9a4f563a6252f2c7ddd9db0e8a114887e6.nq.gz
    ├── 3746ea2b59c30160d082abe1c2110c2afcb36169.nq.gz
    ├── 3804ca927fa5483958c08d524defc8673280d24c.nq.gz
    ├── 38859d57e3bd349c7954572d3df9e87c3a05c7d2.nq.gz
    ├── 388d06df2cea35c3d34fa3931aebfacb61f19c62.nq.gz
    ├── 3a41b14e3d716a049934e27cac4c73c421dfc1b0.nq.gz
    ├── 3a6df62ebe00b8d8f7c06ec712f101e1236e76e0.nq.gz
    ├── 3cc202691a87b429d51a91b393b3193115973a08.nq.gz
    ├── 3f4c5f065f87c210f9430ee65a903cbce85b760d.nq.gz
    ├── 3f5c0562f5a5e7ef0b8cba036b8f881742c50556.nq.gz
    ├── 404a558d94bca4991ae2c84a4d82a53ac0fb5fe6.nq.gz
    ├── 406bc1c9f9eefe8aa87b5fe0a5882d6b0ecac0aa.nq.gz
    ├── 40927955fddd2de872190c6e53169a1686b225a0.nq.gz
    ├── 411010f58f04b00247a1006a80a2faf1b82e62a0.nq.gz
    ├── 4127d287050140e0443057c355b58e683e82bfe1.nq.gz
    ├── 42785617918bcc3fee63da6cd128ebbc28d240bf.nq.gz
    ├── 439dfc60e2348aa44332097b9b0c1b29ac0750c0.nq.gz
    ├── 445d3fc5343d29d278c66fde5b49859e1fc26620.nq.gz
    ├── 44843e70fe9c5ab284e8e9f845109d8ba2537b58.nq.gz
    ├── 4498e6c9ee41d207f44e110ee04d9b6a896f5606.nq.gz
    ├── 449f8f28aeac36360d02cebb9ec1496df152ee1a.nq.gz
    ├── 44e37c2cf3e8ae83be992777873b4b7a080c6137.nq.gz
    ├── 44e4b6a5c8609bb4e10c91c1bd6939733618ec5e.nq.gz
    ├── 44ec1fb88370d57faaaae419aa0642a971858d7c.nq.gz
    ├── 4535b8651635d3f2ad446d50f9b8097dc58001d3.nq.gz
    ├── 4557c586d1fbbe314d7dd9920794db2bcb0b0942.nq.gz
    ├── 4566d256f0401b4933ada75145221bc3e821bfe6.nq.gz
    ├── 46db77230afffb2f6393c98a623da2709f83b6be.nq.gz
    ├── 46f96b6589ee0e52ee787419ae7778c1332b7f43.nq.gz
    ├── 4702ddda678ebddb33d084ac7c0cdd384794c89c.nq.gz
    ├── 4790ed95801795e05c29363626d4ffe348a0b3a6.nq.gz
    ├── 4873c57cba52bce5b16c38e1b0b9ee3ba9b0fbc5.nq.gz
    ├── 4a10e9d40e1f5a0faeaf97c8736325283badf7c3.nq.gz
    ├── 4ab31776d1a59b888816e16a1dfbf478620f28f1.nq.gz
    ├── 4afe2ae98d3e7b0345677c2e9f768aa35b9b94b4.nq.gz
    ├── 4b15a095f7ff9c3829dd3f414969ea7dc6e9d74d.nq.gz
    ├── 4be98c4e9193d4019c56778156468b2cbadf070d.nq.gz
    ├── 4c767a66536b0119d58acfc2cc24ec9663828f55.nq.gz
    ├── 4e0a31ec0fdcb667478bda56fc865b9c374025cf.nq.gz
    ├── 4e6b1a8169448d05dc364b926fbc296fd0aa2ea7.nq.gz
    ├── 4f47b523227cd9b3eeaf08e6642c4c8fe4c23eab.nq.gz
    ├── 4f8532ceda9219784b54a7b777f005500c0944fb.nq.gz
    ├── 506fd83f54acd3dcfa739e8d66de3e4fcbdd4ddb.nq.gz
    ├── 519e7c7481d55ffc52bc4800366afef89927632a.nq.gz
    ├── 51f1f139ac8aa77829fe112217406d8699ee626e.nq.gz
    ├── 54013d49d9ef6212f3c2bcbc34e0a322f1fce758.nq.gz
    ├── 542fecc3ae873c35c94f6da79ae9c57120000420.nq.gz
    ├── 54b79611ffaab935ec9f61c784a5e09a9a2afea4.nq.gz
    ├── 55325d2e4a169c703d8a7c497bfb1a7d68cb7b69.nq.gz
    ├── 56125b60fddeebd38a124f14afd4a1d4eeed199c.nq.gz
    ├── 56ccf2e7cb1143cf24c92137e908dd2ddcc1e426.nq.gz
    ├── 56f904f6d00e601563286f499a1ef10ddcca448a.nq.gz
    ├── 579d7186029000eadec6cbe7c84e1b6b230c728f.nq.gz
    ├── 58e9c5701a0695ffb5a8834a96ba4c341c7a6ce7.nq.gz
    ├── 597dc2dc00fc7d98681112dcf5d27712ea91e6c7.nq.gz
    ├── 5aa1b0c2b6cf013dd123ae19703fe4d137af4461.nq.gz
    ├── 5ad853a5364bb63bdd427bfc31ea86a256bf4ede.nq.gz
    ├── 5b8c7e00f818baf993e9bf716b3b2c5c342fc03c.nq.gz
    ├── 5d12914215b0b502915fe896be2ff4b3f0c1fbc0.nq.gz
    ├── 5e42ac73323232a434f25f7c29ad4aa496788dc3.nq.gz
    ├── 5f12a84a45d1a76fef5ade4b2db980bf721a1b8e.nq.gz
    ├── 5f5e93b5dc2942d492bfefd6d9726bec6114b71d.nq.gz
    ├── 5fd043b28c5a9f01e1fc59a90d1b6fe45cc5dd94.nq.gz
    ├── 5fe93c9347ab9b7b00c7000d52297577dcad472c.nq.gz
    ├── 600d3b2ae57aaf3646db4ad48bd85cb794af744f.nq.gz
    ├── 60291dd2a8e14eb8c26858d893728e9d9cbdc8ac.nq.gz
    ├── 6085f5abf677ab61ae4750c8d0a261c46077225e.nq.gz
    ├── 60a671a635892e79bbfa72fe8a34a44c82a613b8.nq.gz
    ├── 6235070f70f946d74b3d909ab20758353a5ebc3a.nq.gz
    ├── 6260717fb173b7914b422142e42718bfe30be30b.nq.gz
    ├── 6290c33465377ccaeff3d7c76a8cab71a50ae158.nq.gz
    ├── 62ccdf5b2854c70ae595c19be89654fce38876c7.nq.gz
    ├── 636a2da5e7f75189e4b6405b26060b91566646c0.nq.gz
    ├── 644c5f0a78b77fe83b277e27a6eed991c5b32c9b.nq.gz
    ├── 65314b40891881ed76389dc2d2860a3ad085d76f.nq.gz
    ├── 669dd672e4262d32151355095b617bfff806e670.nq.gz
    ├── 6815e5d1f4348b6d1d187ea4e4e491d34813c6d5.nq.gz
    ├── 682fcc174e76652a48472251a6ed439d17f8f25d.nq.gz
    ├── 6870f70801a54f3217d3be7f080486be76275a54.nq.gz
    ├── 689845d108477c104f37081fa166914c315cd692.nq.gz
    ├── 68c8f2334dc2cbb2aca0088ad9757995f9fce1ab.nq.gz
    ├── 6957b0240217d1d176be63e2a309838ca37cea72.nq.gz
    ├── 6ab59c5c10d67fd89b7509a5eff3fc133b1ffb15.nq.gz
    ├── 6ae303925c5958750c551f5fe0d40dd0eae72605.nq.gz
    ├── 6c0c19c6ae64582f54c7770a90e2f782f29e7104.nq.gz
    ├── 6cb47ccb141e3cef036a0f6cf21a050d38b197d8.nq.gz
    ├── 6cc6a4014bc426ed625731f5f4e327a0657cd236.nq.gz
    ├── 6d0b58054cc557f280309e940a5e5043d0d58a40.nq.gz
    ├── 6df449a8b8edb5668d3571324a74396434bb8221.nq.gz
    ├── 6e4f60af04ea5cbadabe612b7cbec173f3bbb8bb.nq.gz
    ├── 6e6b47494855deb37a468d95f509183bd8a75fe0.nq.gz
    ├── 6f6b11dcd8b2c542030aad9004e01760bfd181e3.nq.gz
    ├── 6f769f19da8a311050e351d4a2f31f75f17b0dd9.nq.gz
    ├── 7014bf41164724352cd9e6dc91ffdef16eb1461d.nq.gz
    ├── 70a3f3ca42c54a23a2a92aa63b4ef106466c8da1.nq.gz
    ├── 719f67601e33ba44987b089ad23d8bf34139a0a7.nq.gz
    ├── 71de072f26290eaf66c5b6891316cee37fe8fff3.nq.gz
    ├── 71fd2e287b71009da7bedd1de52cf2aca932e0bd.nq.gz
    ├── 7283f93af70b61b7289c51b0f3fb40e8cebce3e1.nq.gz
    ├── 72d01e709194dc84f4f4bcedb1fb4b1b789d200b.nq.gz
    ├── 7348b541f263a1f28192155f711de0f8bc22d1cc.nq.gz
    ├── 735430753510c26c350f838a38bc4e70e5507dc9.nq.gz
    ├── 7404714bcd1572f91929e315d6299f501b839c40.nq.gz
    ├── 745553e09e5763a4f504a3a91a201f1207e66b8e.nq.gz
    └── 74ab86e02764d370d8c4fd60ab77d47add74f764.nq.gz

10 directories, 200 files
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

[zopefoundation/ZODB](https://github.com/zopefoundation/ZODB)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
