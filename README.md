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
│   │   └── c50a0941d40b22ff5b6fb30a5eab625fa4beba62
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c50a0941d40b22ff5b6fb30a5eab625fa4beba62
│           └── chunk-001.nq.gz
└── blob
    ├── 00f4adb10fb252728acbb98bd015ba081ab016c4.nq.gz
    ├── 0188d11843d6291438ae75054c39755b021f5474.nq.gz
    ├── 020afd6691b9d7f05adfefad20ea67b410edd8c3.nq.gz
    ├── 02c11fab21bd3114e1fa83e4cafb5beb0a67b019.nq.gz
    ├── 046fa0b199126015a4e22867b09f1f1e4219c1fa.nq.gz
    ├── 05ad765ac1e891aebeca7832b4a4fb86909fef38.nq.gz
    ├── 08cacf26577b69c8e25b835935fce06ec15ebdfe.nq.gz
    ├── 09531348e1a405349a94d1974bc73ea9950095a5.nq.gz
    ├── 0b1acbf15751d64518a1945e9d8bf737d13bf836.nq.gz
    ├── 0bd1e7da330e34ceb4ea2281c98436e7bfe846d9.nq.gz
    ├── 0d1ce99afd2241f24d936467c2516d1218a8d3c7.nq.gz
    ├── 0d4d0444858951285da9964d7c4655d6689b6d9f.nq.gz
    ├── 0ea6440600717da498645ed9fcb4e2d489c4d55b.nq.gz
    ├── 0f978a7e2af3819424698f78ae1d20a739bb115e.nq.gz
    ├── 111de8f214fa79a116b04d47b4ae08ec18232c0c.nq.gz
    ├── 11d04b8e40d3d29591065b1a07bf57d57a9c362e.nq.gz
    ├── 120d3d7f2a21959037c448dfbadc93ee8869b3b4.nq.gz
    ├── 12624f7994d61a473ed6a489b8d48bf803e36016.nq.gz
    ├── 131b1ac539b8e3ceae28977fbf31d86c3add163b.nq.gz
    ├── 13d24bef540757bc35bcc769cfd2920bea43adb7.nq.gz
    ├── 1423fc047554f5c961223b27b2a8dbb24a6885b7.nq.gz
    ├── 14b7b45f0b176185e1dc2706c12ab53d6141b79c.nq.gz
    ├── 167f50c231a12ebf8f2159bffe81743bab28ff5b.nq.gz
    ├── 18498bfb3a9000b5daa61d4908cc77ca59126d6a.nq.gz
    ├── 19235ba4b9a936ce7fe5a081c66b4403737f995d.nq.gz
    ├── 1b13359f108dbf28596ce178bd66b84a003a456f.nq.gz
    ├── 1b9a4867f39d169b3b45af213e09cc0c7bf78b13.nq.gz
    ├── 1fd2fb6ba6a28d38b3483cd74e78442d70d294d6.nq.gz
    ├── 263be09ba52c88c4b7a53605db79ec2b6d8f5517.nq.gz
    ├── 28bbc22883fba47ab005e9d6930ee57c4c560e92.nq.gz
    ├── 2936ca8d171880e1b5b7e80e27d79fddfd10aaf7.nq.gz
    ├── 2956e0b7915a37191bb68726c29d08468dd8a8b9.nq.gz
    ├── 29b6bfcd98d987c6100a428b949586e736f1511d.nq.gz
    ├── 2b1e3765763c047537b54796c38dce655a867993.nq.gz
    ├── 2c483417146c022aadb01ca52f8e7690c06fd0ad.nq.gz
    ├── 2d99e1c31a68cc32b15a5ff588803b892edfcfef.nq.gz
    ├── 2d9e8dcf69c1b29db1bf3cb4cb7cd7d8cf7898cb.nq.gz
    ├── 2f2b5b70fc8ec0519855596dae5d673f06716d3a.nq.gz
    ├── 2ffde320a9bba13c68b226fed5465aee2ad55746.nq.gz
    ├── 30702da6eb633d3c14c872d567d87439c25074d2.nq.gz
    ├── 30c15acb03563ac24e02c5c53e174e678bcda05b.nq.gz
    ├── 32a5f7d9ac8eaa971bea404dc149ee69aaf844a9.nq.gz
    ├── 33422a8c8fd0a8541289d46f838d30948c9c7805.nq.gz
    ├── 33a7eaaddabc1327e8b9e72c7d48be83dccf91a1.nq.gz
    ├── 33d52e55c56ba1d27cc897379ca726621a41563b.nq.gz
    ├── 34d26bff388e6b182140e7e8bba8f5e25a1ffe96.nq.gz
    ├── 388d06df2cea35c3d34fa3931aebfacb61f19c62.nq.gz
    ├── 3a41b14e3d716a049934e27cac4c73c421dfc1b0.nq.gz
    ├── 3a6df62ebe00b8d8f7c06ec712f101e1236e76e0.nq.gz
    ├── 3cc202691a87b429d51a91b393b3193115973a08.nq.gz
    ├── 3f5c0562f5a5e7ef0b8cba036b8f881742c50556.nq.gz
    ├── 406bc1c9f9eefe8aa87b5fe0a5882d6b0ecac0aa.nq.gz
    ├── 411010f58f04b00247a1006a80a2faf1b82e62a0.nq.gz
    ├── 4127d287050140e0443057c355b58e683e82bfe1.nq.gz
    ├── 42785617918bcc3fee63da6cd128ebbc28d240bf.nq.gz
    ├── 439dfc60e2348aa44332097b9b0c1b29ac0750c0.nq.gz
    ├── 445d3fc5343d29d278c66fde5b49859e1fc26620.nq.gz
    ├── 44e37c2cf3e8ae83be992777873b4b7a080c6137.nq.gz
    ├── 4535b8651635d3f2ad446d50f9b8097dc58001d3.nq.gz
    ├── 4566d256f0401b4933ada75145221bc3e821bfe6.nq.gz
    ├── 46f96b6589ee0e52ee787419ae7778c1332b7f43.nq.gz
    ├── 4702ddda678ebddb33d084ac7c0cdd384794c89c.nq.gz
    ├── 4a10e9d40e1f5a0faeaf97c8736325283badf7c3.nq.gz
    ├── 4ab31776d1a59b888816e16a1dfbf478620f28f1.nq.gz
    ├── 4afe2ae98d3e7b0345677c2e9f768aa35b9b94b4.nq.gz
    ├── 4b15a095f7ff9c3829dd3f414969ea7dc6e9d74d.nq.gz
    ├── 4e6b1a8169448d05dc364b926fbc296fd0aa2ea7.nq.gz
    ├── 506fd83f54acd3dcfa739e8d66de3e4fcbdd4ddb.nq.gz
    ├── 519e7c7481d55ffc52bc4800366afef89927632a.nq.gz
    ├── 51f1f139ac8aa77829fe112217406d8699ee626e.nq.gz
    ├── 54b79611ffaab935ec9f61c784a5e09a9a2afea4.nq.gz
    ├── 56ccf2e7cb1143cf24c92137e908dd2ddcc1e426.nq.gz
    ├── 56f904f6d00e601563286f499a1ef10ddcca448a.nq.gz
    ├── 579d7186029000eadec6cbe7c84e1b6b230c728f.nq.gz
    ├── 597dc2dc00fc7d98681112dcf5d27712ea91e6c7.nq.gz
    ├── 5aa1b0c2b6cf013dd123ae19703fe4d137af4461.nq.gz
    ├── 5d12914215b0b502915fe896be2ff4b3f0c1fbc0.nq.gz
    ├── 5e42ac73323232a434f25f7c29ad4aa496788dc3.nq.gz
    ├── 5f5e93b5dc2942d492bfefd6d9726bec6114b71d.nq.gz
    ├── 6235070f70f946d74b3d909ab20758353a5ebc3a.nq.gz
    ├── 6290c33465377ccaeff3d7c76a8cab71a50ae158.nq.gz
    ├── 62ccdf5b2854c70ae595c19be89654fce38876c7.nq.gz
    ├── 636a2da5e7f75189e4b6405b26060b91566646c0.nq.gz
    ├── 644c5f0a78b77fe83b277e27a6eed991c5b32c9b.nq.gz
    ├── 669dd672e4262d32151355095b617bfff806e670.nq.gz
    ├── 682fcc174e76652a48472251a6ed439d17f8f25d.nq.gz
    ├── 6870f70801a54f3217d3be7f080486be76275a54.nq.gz
    ├── 68c8f2334dc2cbb2aca0088ad9757995f9fce1ab.nq.gz
    ├── 6957b0240217d1d176be63e2a309838ca37cea72.nq.gz
    ├── 6ab59c5c10d67fd89b7509a5eff3fc133b1ffb15.nq.gz
    ├── 6ae303925c5958750c551f5fe0d40dd0eae72605.nq.gz
    ├── 6e4f60af04ea5cbadabe612b7cbec173f3bbb8bb.nq.gz
    ├── 6f6b11dcd8b2c542030aad9004e01760bfd181e3.nq.gz
    ├── 6f769f19da8a311050e351d4a2f31f75f17b0dd9.nq.gz
    ├── 7014bf41164724352cd9e6dc91ffdef16eb1461d.nq.gz
    ├── 70a3f3ca42c54a23a2a92aa63b4ef106466c8da1.nq.gz
    ├── 71de072f26290eaf66c5b6891316cee37fe8fff3.nq.gz
    ├── 71fd2e287b71009da7bedd1de52cf2aca932e0bd.nq.gz
    ├── 7283f93af70b61b7289c51b0f3fb40e8cebce3e1.nq.gz
    ├── 7348b541f263a1f28192155f711de0f8bc22d1cc.nq.gz
    ├── 7404714bcd1572f91929e315d6299f501b839c40.nq.gz
    ├── 789381fd7c7f2fc3123f3a820f6d50d0757bbeba.nq.gz
    ├── 78b3afb25e27b21fd3ee561668c33b8fa65df7e6.nq.gz
    ├── 792d6005489ebee62cde02066f19c5521e620451.nq.gz
    ├── 79b97f5a6d705785e929d4df94367bc9c0a00a69.nq.gz
    ├── 7ab31227e0453f253a1a70b6cd87bd501c5aeb45.nq.gz
    ├── 7b6b10cdee0ba181e0987240df1422749f9dff59.nq.gz
    ├── 7c0be47b35affd0f404b04b0398fe114d92983e0.nq.gz
    ├── 7c5bc0458384833e3832e1adc4be64cc740dde9c.nq.gz
    ├── 7d3d4416d0d5d8c0f9f14ff8830ef11a5bcc8e8c.nq.gz
    ├── 7da877e37ece81a948da2cb3c68277a851d71a19.nq.gz
    ├── 83416f2eeb2b767b2c407cd83cfe38ba3c2e79d0.nq.gz
    ├── 845740ea9ef21a7505332c7ad7f0f371ee998928.nq.gz
    ├── 870efe1eac0f2f7bb13dac291b1bd44ae6e7b898.nq.gz
    ├── 875b595a70f7862f8002696c6090cdd6dc2e9cdb.nq.gz
    ├── 88204fb26e2a3f5d105ab8c7f2cb06ec933f1052.nq.gz
    ├── 897e516ec14539b9f6843f44bcc3aa249dd86a71.nq.gz
    ├── 89e50ac5150ebad9e0515199d615e7645f3d388f.nq.gz
    ├── 8e0a6e9be2479bc6d60c554a955738413abeea75.nq.gz
    ├── 8f4075e6c1e847c862703b38f05b204d91df322c.nq.gz
    ├── 8fc49805070455478f961f00da369c6fbc9fc4af.nq.gz
    ├── 8fe6f772c0cbd3c7b319ff2540e97e1d84626209.nq.gz
    ├── 906b168e4a0a7b4e7bd6d03a781a90475427e428.nq.gz
    ├── 92262e9281c2ec75ba62e41c88033843f87a947a.nq.gz
    ├── 93fe47f8d01766f793f85ff7116e3a81cc8952e8.nq.gz
    ├── 957d732bc41a00cb4103d178d904f5ad91562fb4.nq.gz
    ├── 95ebb620bd4834f914b0b0ea014a722db7193b71.nq.gz
    ├── 961588e235c4fb9c54cacaacff8f3dcebb0ed3e3.nq.gz
    ├── 98739747c319a6581693f93b405c66eed2e3747e.nq.gz
    ├── 99c0c44466ec2c231609974b0416c380de803a18.nq.gz
    ├── 9b2ea6aabe8efbf57e00c7084610b741785a6783.nq.gz
    ├── 9bb44ab0df7677ee9dccee95a2d71034e7d51d5e.nq.gz
    ├── 9ced55aebabf521d6f2cee94cb8806d9116ac97d.nq.gz
    ├── 9e4556a9b917f157ca41489803435a9319fe1716.nq.gz
    ├── 9e5048c9432e417b6a646e6aac457c362792e402.nq.gz
    ├── 9f6be7898f599b7cfd8a70e68b17063afaf2dd73.nq.gz
    ├── 9ff5fe9ddd044399a3cf6aede04484cd1aaea866.nq.gz
    ├── a3cc9b2f6c9a193b21578dd476bfa012b8618dd4.nq.gz
    ├── a6c3482a6914be9e3001183128d514f2d2f2d2f2.nq.gz
    ├── a70575bf5153a4623c02d8411588a46a0054a183.nq.gz
    ├── a74641bea6ae48f17f8a757c31b6bf0a10a4306b.nq.gz
    ├── a9e4b3751209556f88502680acfa4fba4556ddd4.nq.gz
    ├── abed62ef949f9c2af842fc4bdd398d166e1e2351.nq.gz
    ├── ae56c9a47aee420b8fb19ebcca721a74f8aa45b2.nq.gz
    ├── ae71a0283eda850495e50898e8458794fbe73d9c.nq.gz
    ├── b04d1a65e0b12b37322422ce4d03811c91e22707.nq.gz
    ├── b0ba729e243a897dcbec8f0eb49e12af453b68ab.nq.gz
    ├── b0fc30ba8ab332a14aef191ba2feb3a5b9c81f0b.nq.gz
    ├── b4569b8a07acb04b6297a122d7fe5ef7b76a0e86.nq.gz
    ├── b69dc1a14b563c540fe3cebbc45b7261a0e7d466.nq.gz
    ├── b716401d5c3d2e364d8f22bb62c0330ea7116d2d.nq.gz
    ├── b73cb489f29860132b3e3b83ac93e2014359bd0a.nq.gz
    ├── b8581dd898cbb33e63961b4d181ff0ffbe5d03ee.nq.gz
    ├── ba826333dd04b91873b38cf0b3404987ad93bcc8.nq.gz
    ├── bd6e342fd2a18c91fc84930e35cdadb0d70bff42.nq.gz
    ├── bd7c7d3db628ae8a83e6fd5d85c261fb35cf4a18.nq.gz
    ├── c04f30011e7515f7941ef61d95ee583c24cd59bc.nq.gz
    ├── c0ac070a6d1283818c72b2939cb7892409be3983.nq.gz
    ├── c15ff0139e7694bbb36fa88543338e8c987a3d6e.nq.gz
    ├── c207fd57a7158f086fd5d6f1ddb7985f56d8a251.nq.gz
    ├── c2dbeba8e7da0c9cc7d7a31765376988ee3297de.nq.gz
    ├── c3a06a368f0cf476bf3ef2074f3e140e024ca717.nq.gz
    ├── c8b18a2a77608dbd024c823292f6d21991567dfe.nq.gz
    ├── c91713bc44b1100bc177340c8145d6cdd9a263ca.nq.gz
    ├── c965cee9ad2380d5f79aa68fd637b2f0e7541209.nq.gz
    ├── c9beb89ef24d3d540f588cc946171b862cfa729b.nq.gz
    ├── ca517f4eb0cec1c691c0c2b54cd5eb85e906f11b.nq.gz
    ├── cb314fe3b1fdf9fde55fe6af2d329de35403fca4.nq.gz
    ├── cdbcf60f7581d7c43cc11b9c5c03ecf1d66af73b.nq.gz
    ├── cdbe9bf777a1ef6e5bf7f9cf541e9c7a6bd935c3.nq.gz
    ├── d0d975eaf5eaac64b487d0ff7783f41b28a315dd.nq.gz
    ├── d10ec9546d74d2c431f0942d6bc3604e86331d99.nq.gz
    ├── d5d1d8aa026d3da812654e99cb001d6b69381547.nq.gz
    ├── d606931a1d67c9319a46a137ff35dbf491cbf660.nq.gz
    ├── d645b68719d89a034e1c490196e1958a65c068f3.nq.gz
    ├── d88e4b9b6fbdb3a7481e502bd3e757896413d13c.nq.gz
    ├── d9a0a93cb573ed30bc5b64819857e9de34cd3dcd.nq.gz
    ├── da30ff96eea4a108ee0d8cbd9f05d8532eb0e3ff.nq.gz
    ├── dc085443de26bed1b821c2d9c756e72d4f4f61b1.nq.gz
    ├── dddd6b82fe5515c193a1f7679f23bb47f7b7bcdc.nq.gz
    ├── de26a4ef7740300588a595ac4315d117be57162f.nq.gz
    ├── df1ab201ec181c8c447b0ad9b2e34a62baacf60c.nq.gz
    ├── df3fb5cee0a42e9821f4604dbbd3ee028fd465f9.nq.gz
    ├── e0afb1b8b3f1e25a460f77095ea2a56a41f5b480.nq.gz
    ├── e14276f366cc7bc42e956b57aa80c53714764272.nq.gz
    ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
    ├── e2d25b322453f2987e9c897fb22b53ae65b282a8.nq.gz
    ├── e4b867329e05886a4818f86b117fca2102bc84bf.nq.gz
    ├── e5c5a66cf8466644ab0452d293056925e88da820.nq.gz
    ├── e607b25e236eb8f20d145f139128670c1220d790.nq.gz
    ├── e60815177a2e6d16fc304c2e530006e5618fcb76.nq.gz
    ├── e6982690a826d917f4be9aa5aa7931a839e0fb55.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e9e474498918ab344905b4393dfb7f72e263f8e4.nq.gz
    ├── eacf6f7199dea15d1c1d794949d415b641d7d96d.nq.gz
    ├── eb195725be1fb9fc26439fb04e6394e321664a75.nq.gz
    ├── ed2054601aaf0696d164f05eff5af5c65b4353bb.nq.gz
    └── ee46a7e799f954066141ba0d0ddcb903ab41f2b4.nq.gz

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

[zopefoundation/ZODB](https://github.com/zopefoundation/ZODB)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
