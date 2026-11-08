# Repolex Knowledge Graph of deepset-ai/haystack-enterprise-sdk

RDF knowledge graph data for [deepset-ai/haystack-enterprise-sdk](https://github.com/deepset-ai/haystack-enterprise-sdk), parsed by [repolex](https://repolex.ai).

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
rlex download deepset-ai/haystack-enterprise-sdk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ba7c53bff4e45a7d2449fde95632b159027c661b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ba7c53bff4e45a7d2449fde95632b159027c661b
│           └── chunk-001.nq.gz
├── blob
│   ├── 00d5f6d30e61d674c364ac384aa67a5485696fe2.nq.gz
│   ├── 0400778ea3715b8d10e5a757265bdd491bc4ddc4.nq.gz
│   ├── 040f282df159e25e1ef75d6779f00a164a82db4d.nq.gz
│   ├── 07381eb5ec95740a9e9ccc6080631c5ea0ba699f.nq.gz
│   ├── 09c9817b2bd7a9dcc8e6038c41f3d69974076f05.nq.gz
│   ├── 0a7bfd1ae7bb1a39a6a0318cebb519d8da337c47.nq.gz
│   ├── 0af4b5ec5bff8f61931fc71b056e7cb24ec605a8.nq.gz
│   ├── 0dc8879db2a4bf8f1b46868b84584ef5e2250828.nq.gz
│   ├── 0eaddf4156db936fe39140c69cdbbe1cb6657d83.nq.gz
│   ├── 0f1013dfd636cecacab447b461b49679a8502e8d.nq.gz
│   ├── 105d84da1b8595ada92ff5900dd42a0873f2bade.nq.gz
│   ├── 1501d466e057b0f5e9d2fec3a560220ed5b6756e.nq.gz
│   ├── 157227c192e7e2eeea25edc8d31a6050b90c1570.nq.gz
│   ├── 19914b34cc8c5ce4bf5f82b820d1ea4b50fec224.nq.gz
│   ├── 1a5f0c6e1583c9fe1b503d06bdd17af63614d5c5.nq.gz
│   ├── 1ad08aa52004dc175acd440c9a330beab24776e7.nq.gz
│   ├── 1dad51e708aded7d0c44ec4c8c5e093616eaacfb.nq.gz
│   ├── 1de7d5a7ee8189918af619728f4ed3cc64efdd40.nq.gz
│   ├── 1ea2be8a99eed0f5853d22cb9125a1d38da2b8ae.nq.gz
│   ├── 2247e22520918d501d6dc318090cd485a2d81a5f.nq.gz
│   ├── 2580a0b4c8ace365f317f7d594d781c722bceed5.nq.gz
│   ├── 2d985a5d78fc190d87bfd90f1a5c2ed97a1922c5.nq.gz
│   ├── 2e358276090e3a7f54dd5ea0a8ee35934c499841.nq.gz
│   ├── 2e8ba2fe9d0b5c2d616505f6f4c0aefcf4e8518f.nq.gz
│   ├── 2e8c99f4f9597af9da6a8fcd4579c9b93ccb3028.nq.gz
│   ├── 30882513b49df1bff5aee3723049d77d5d55c054.nq.gz
│   ├── 30df7ce20f85f4ebec3b02951acf1ac0fe7cb5a6.nq.gz
│   ├── 330439ac34e6e9ee70a37255c85a00cd10e1e6e7.nq.gz
│   ├── 349dea8b84f3b8f4c36253d0f377a682edbfa114.nq.gz
│   ├── 354ac888467ab61cdecddccbfe3b03756cad2173.nq.gz
│   ├── 3734363ac4c57c9d0b3d22198b28799e947a5a11.nq.gz
│   ├── 379fc28d3fe658dbe486564f50c25154c7a822e0.nq.gz
│   ├── 3911ecab82cc22825dbe5232e221347c437f0001.nq.gz
│   ├── 3d17bc84c88c4b6bb970187a68e24bba5c8c8d0d.nq.gz
│   ├── 3d791561991f56386cc0867a3e54573ade3caac9.nq.gz
│   ├── 3daaeedb46cba6ba773634d6d415c279ea546783.nq.gz
│   ├── 41aa204dd3d1cdd2c75020104694a7681107289d.nq.gz
│   ├── 4214f7cb874428f089f7ff0ae077c8b2730ed296.nq.gz
│   ├── 44773f639e2230b551fd2ae43535fa2eb2121679.nq.gz
│   ├── 44c84caaaf8851ffdf13e9ab56f23c39c30650df.nq.gz
│   ├── 4519ff940a7e22c0bec9df7aca124ea2808637a0.nq.gz
│   ├── 47b3255b3022de09b6e4ca6d3fcea0984048746d.nq.gz
│   ├── 499b22073facd7a538e431923c42e040d9ef8dcf.nq.gz
│   ├── 4fb0fba52114b5d25debcf920b40de5cdaca8641.nq.gz
│   ├── 505bdb1d8af427e90c11aa26c927c9d411a1c63b.nq.gz
│   ├── 50c0e4cbbdedb38e8baa5234aa115756b667c336.nq.gz
│   ├── 5383212cfe23510a6a87f98b63285cb4811c20b1.nq.gz
│   ├── 53fb546406a314443e17c87351bdc23841defe2f.nq.gz
│   ├── 5654c7ba8ebfc56dbea9e4ad316bc32f8df5ee17.nq.gz
│   ├── 566ecebe33ce990d0e6c41168ff7f40ffa61b39d.nq.gz
│   ├── 58a96d4b1b3ddecf623c85d99f2318230d78df2a.nq.gz
│   ├── 58af0082005da29ed5120232018d8353692b16fa.nq.gz
│   ├── 5d21f91ad5326d9720a1e94cfc8281075d867bcb.nq.gz
│   ├── 5ec54f7be7ff0c7c4c6f4f7ea60147dab3da8a3e.nq.gz
│   ├── 5f7e201070effabfb9eb8bfe3b9d4c4f8f3408f8.nq.gz
│   ├── 5ff05e54779aed176a9f0ec56db4a3215db48d15.nq.gz
│   ├── 6043420b5a64effe68b6f5805cfcbaa4c0b49aff.nq.gz
│   ├── 60f8d3f09c4eb94dc6f2d58a7d9b61a2e4a0adc1.nq.gz
│   ├── 6375d687e6431994d19272ed02e37ed346fa3e1c.nq.gz
│   ├── 63ab9d4a62c3fe3bd2f6733e9cd1f7542f47c487.nq.gz
│   ├── 63f606d67ee8ec2f58a7a570785fb879993bb822.nq.gz
│   ├── 691c9913bbbc131c33d350bdac36cee31b30a21c.nq.gz
│   ├── 6ec0b01d884866e46d68eeb3ce5147680e5188d6.nq.gz
│   ├── 7020da24de0b4853071ec0be4d44930c7384ea43.nq.gz
│   ├── 71898b7d3551c266cf361edd63cd152bdca9644d.nq.gz
│   ├── 722efa1d150798caad04ba48c1f4f63ac6d322c0.nq.gz
│   ├── 7385ddb433ac092a62405cf3af2580552492578f.nq.gz
│   ├── 766d3a4eb93be4042ac820006e9fb87ee4fbd28f.nq.gz
│   ├── 77053769791bafde7b0db3565a04961b25b1d051.nq.gz
│   ├── 77a250b791c04645ebd0f7542a05b32b18c3b48e.nq.gz
│   ├── 781a1c16e6adc081798d4c2a103376108b918ccd.nq.gz
│   ├── 78365aedc3d22e8c50fc23e50b2b1361f257718d.nq.gz
│   ├── 79ec649028b145c62dbe7c2e65e2ca2c8e0bd27a.nq.gz
│   ├── 7a1e43fd81d1cb5ab9090aa87221620d83b8e8fd.nq.gz
│   ├── 7a5ad8a38bbce6b87239bfb332d70da8da597a1a.nq.gz
│   ├── 8638dec63938bbaa588daa5c78ac688053d7217c.nq.gz
│   ├── 882ee3276be882699a8b33628fd6d51d1f93304a.nq.gz
│   ├── 886d96d5e10cc61555e4092f437afaecf1497f30.nq.gz
│   ├── 8bc7143179b7e3825a45da40b2d99e7226bea0e2.nq.gz
│   ├── 8bd6648ed130ac9ece0f89cd9a8fbbfd2608427a.nq.gz
│   ├── 8ec0dd10011d7ceb589dca762e05beb98c9178bf.nq.gz
│   ├── 8ef31d69e33f57ae820f132f1c9da6d600b3c13c.nq.gz
│   ├── 8ff893f194f215b6f39d099be70c716030fa6f28.nq.gz
│   ├── 967511c94f5aff6cd9e8298da6842c6dff40b70a.nq.gz
│   ├── 9da2e0342ba7ffd145bfbad66ef1308e6b2a5882.nq.gz
│   ├── a275fff1fb11ba62ef6090a23edcdc357b84e240.nq.gz
│   ├── a34ed9cee8cea845b2cc7976cf358ac9acf48541.nq.gz
│   ├── a3797be4104a226ad80f7d752857072be93ee89a.nq.gz
│   ├── a43bfecb54237c8228d041cc5698526df4955adf.nq.gz
│   ├── a466be3d8d85f0c074b7b3d05619d28edffb25a6.nq.gz
│   ├── a499b4e186248ec9e215556a62862588baa6204d.nq.gz
│   ├── a61eeeb4594551d99b962828c2380ada11bd548e.nq.gz
│   ├── a7b167bc73ab5e927592acf6ef8a04827cc5ff01.nq.gz
│   ├── a9f555d346d19460d7c50202164b63d0cde00fdb.nq.gz
│   ├── ab15cc834bee9e908db2b16d2bd8674e6db47d6d.nq.gz
│   ├── ad65c9d81125f4ab2e9ce4a762d80a8450fbb281.nq.gz
│   ├── ad66dfd3e7e3d466c3c66770e8f2bc36a9df18ea.nq.gz
│   ├── adc4e1a7b2eb1d0ebd503456272e1d06c395ff34.nq.gz
│   ├── b04da54d75a4991458d6c4e22529831dfcdb71ce.nq.gz
│   ├── b1b96da0940afbab41712683f2577faa3de159e2.nq.gz
│   ├── b22516e94170b5cfef17d62f4396df97f5ef00a5.nq.gz
│   ├── b3f2a6d022545db5689d4740ccfb2ba72e578db9.nq.gz
│   ├── b4f04f43841a9645a9faf665a65270ce2e8051b3.nq.gz
│   ├── b7a5a14e35f1d9857cc8f526d7c19959dadab714.nq.gz
│   ├── b7d28399c37a499ae11866b398d5bab72d3743a8.nq.gz
│   ├── b91ead21c4f5af53583eac6e0fe9735d6b71b55d.nq.gz
│   ├── bac03bef3c5108ea64835469f7d4c6fe219878ae.nq.gz
│   ├── bd13d7ef80d7ce3b187ff0e8d9d1d65f616c32bd.nq.gz
│   ├── bec1e493b2478233c6c4cffc3ea8e4d2b5394e29.nq.gz
│   ├── c0d0823f393296560c179ceb0abeec53653b6333.nq.gz
│   ├── c13d04e8fa23b63bdd3e3d080bcabc2253dd891d.nq.gz
│   ├── c286a4d968ef20f41357e08e011a45dbac79acbf.nq.gz
│   ├── c3dd66db622d5bbb17191fe7fbc47c38eb38dbb6.nq.gz
│   ├── c5fc73b56405c9dd932238e3a034c57ebed07068.nq.gz
│   ├── c6b440507795766d53f8249b6fcf48858765b930.nq.gz
│   ├── c6b927203db4ec2ba74535dcecaf3efda43bb726.nq.gz
│   ├── c74760b4f83af0886ea53fbac73cec9068d20640.nq.gz
│   ├── ca115e657bea034dd3f3f3293272f2ec0b3458aa.nq.gz
│   ├── cb5f173b2ba7df98542b39deeb7e04d41cde8f13.nq.gz
│   ├── cb5ff3b1570738ea3c1e8db68fb506c3f8f88ac2.nq.gz
│   ├── cb79b86043276e7314c8e182886a274c01d3354b.nq.gz
│   ├── cdb85896f6bd9576c9d7d77e326c8e2dd53a7f45.nq.gz
│   ├── cf5049506ccedd72f9f879f462e8a93445668177.nq.gz
│   ├── d05dd7144cbdea18f687e612daa9ef1ba17a61e7.nq.gz
│   ├── d096f5c6061dd2c30b0eb3ab66deb1cb040dbc5f.nq.gz
│   ├── d1c648525a450aab26d7b41a23771b61b2333f79.nq.gz
│   ├── d53b8092038ba33306f6c2ba2d4083a5d75ada96.nq.gz
│   ├── d806fa423cbbed065ecf42daa39f1349318c4f0d.nq.gz
│   ├── dc05227979956d0f956b49cd551b8656abbfa186.nq.gz
│   ├── e06f9241d7be4ecc39221f1c4241243a5901cd49.nq.gz
│   ├── e118a3079c421620b584e799a2efda14150452cd.nq.gz
│   ├── e168e00e735c8fe957f03eb0695b3649bfd40dd5.nq.gz
│   ├── e3260f84b4eaad2f87ee758bf35f4dd619ed0c82.nq.gz
│   ├── e3591de93697360e7a8b3f2cd1d0da5166e7241e.nq.gz
│   ├── e37b4ca44d46f8fc46b1328a8032cd824366d863.nq.gz
│   ├── e3d51ace01ab01a30d0dfa31752e9fff4a049bf9.nq.gz
│   ├── e512691071e900802630434440bffa6fcf48175d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e804f803838b73bfa02b91d2285e51bf614c2411.nq.gz
│   ├── e93eba86e4c2111a67ca8ab9b5046191c54679f8.nq.gz
│   ├── ef1ffa1e096ae4d255222af003b758f181c47e11.nq.gz
│   ├── f1403775107112b26c9d4d4e46b19906efb8ac3c.nq.gz
│   ├── f2f879af819c1931950567f8d9a06f9e868ef32b.nq.gz
│   ├── f429347e9cfc32f0202657f3a8887624cf7af53e.nq.gz
│   ├── f45f76eba60b2d8d4922270de62e2f337d6c1fc6.nq.gz
│   ├── f4d49e724812a383f42c330168fcdc171eeb388a.nq.gz
│   ├── f6aa6c02628c3cda86119f8555a85c0e4040bad2.nq.gz
│   ├── f6ffcdb076c28b5d8d5de7aa847dc024cb7e052e.nq.gz
│   ├── f81fce04c4671b008ebf0aadbda2f28f9f63ec14.nq.gz
│   ├── fa6fade6157cea3f802fbb7ed849358cc06780fa.nq.gz
│   ├── fbaa72ae4b00e8424a275119852f5c4aead4a8a3.nq.gz
│   ├── fc31042ac4c4fecd3ec7eecdb4f191fa1abac125.nq.gz
│   ├── fd3389a48af87f56df15dd5dd8ef1dce4565d7a8.nq.gz
│   ├── fe9b2680c5c1bfb937b4968373b3c53ae8911b31.nq.gz
│   └── fef682bc0ecdcdab2c9902fc435e7fcc74754c72.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ba7c53bff4e45a7d2449fde95632b159027c661b.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 162 files
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

[deepset-ai/haystack-enterprise-sdk](https://github.com/deepset-ai/haystack-enterprise-sdk)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
