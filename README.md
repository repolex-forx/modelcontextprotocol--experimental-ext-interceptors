# Repolex Knowledge Graph of modelcontextprotocol/experimental-ext-interceptors

RDF knowledge graph data for [modelcontextprotocol/experimental-ext-interceptors](https://github.com/modelcontextprotocol/experimental-ext-interceptors), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/experimental-ext-interceptors
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b60459844cc95f2170297ebe1c84b7de8b752953
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b60459844cc95f2170297ebe1c84b7de8b752953
│           └── chunk-001.nq.gz
├── blob
│   ├── 01068aa9270d2b4c99878a8d8eeea36472fc758f.nq.gz
│   ├── 0530ecb97e74063ad549249e782db34c51ecec75.nq.gz
│   ├── 059aa1c0c8d2e14d47800a87babc1aa436e26f64.nq.gz
│   ├── 0921ed2b7b128a463dd5f12e415d1d9d7df2e2ad.nq.gz
│   ├── 0941a2c5eaaa742944de38227c6b6c0bcc16f6ff.nq.gz
│   ├── 0dd7e3a448ba8f6ee63124e3d231c90cfdfee783.nq.gz
│   ├── 12da44f8a35b319e23ebb169be05ea6200e5f240.nq.gz
│   ├── 14adf9dc66cbdfd046e0b18cd140e0eb96ab09f1.nq.gz
│   ├── 17b4d4798b78fd834c3d0a1e33ab5741972f4914.nq.gz
│   ├── 18c5b64ec155a9030f8784140a6cfc5be415380a.nq.gz
│   ├── 1b68306b715500e02950665617c2b8f227b9dd99.nq.gz
│   ├── 1d3f33bc902e2cb35f809e9a29b7833ca226166a.nq.gz
│   ├── 1d6ac5be3d2548beab09ee11646a3ae2d60c9cb3.nq.gz
│   ├── 1d72c2a8613ca0d109ae88e28442f141135d6c2a.nq.gz
│   ├── 1dab675dfa1eec072243bf1e1aecc96095a675de.nq.gz
│   ├── 1e8494e67986bc2d50bf7b5a972814865db9567a.nq.gz
│   ├── 22855c0d1e9f8c59103580823ca4875ad4e16d36.nq.gz
│   ├── 22ec780576c31c09316c3ec6c191a703817943cb.nq.gz
│   ├── 258f3285ce1e61a5ce86a9e1b40cf73d74a3b7ab.nq.gz
│   ├── 263534d719aeee5082c5b983ce2954488344d034.nq.gz
│   ├── 2865dab92fd7cb1f130e0610aff9f543e3f68a03.nq.gz
│   ├── 2e53d6a4b7a29b5b589298fe13d203475536b79c.nq.gz
│   ├── 2edeafb09db0093bae6ff060e2dcd2166f5c9387.nq.gz
│   ├── 30b7fc43d092cf7dcafca9e90240919e735adc77.nq.gz
│   ├── 3500269cc857d68e893b9038f102a09f45b8181a.nq.gz
│   ├── 35007c87b55d27bb951b4a2dabafd9ce1d78e648.nq.gz
│   ├── 36eaa8c98df6cb008d200e36248db31e620a4c47.nq.gz
│   ├── 37424080e2b8bcb613bf6921cda656b175a605c1.nq.gz
│   ├── 37523a0da5bcc92dec8de78d25a7186e2480c37c.nq.gz
│   ├── 39eae711380b8b9336910a9e1ee7081109b6b062.nq.gz
│   ├── 3e13ccbca360218d3539eab11a1aa8249d3734a5.nq.gz
│   ├── 3e26bc95b6d02af9249aa44a8f021b255268059c.nq.gz
│   ├── 40601d6aa2fc962536d583c3126c7fcdd7976238.nq.gz
│   ├── 40caeba66d4e2b6bda6447735e063a345102163b.nq.gz
│   ├── 41f887a437b982d9c078eae7f585ab58c111625d.nq.gz
│   ├── 42ec4dec7e44f452c5b643960110afe079009af7.nq.gz
│   ├── 439eb06fc7806e018cc3cd2f84b99813d2ce2ff1.nq.gz
│   ├── 43ce8f88fe5a036e3ab083a94403a5dc92ff98c3.nq.gz
│   ├── 465cdceb6c73d28ef6018cde5d3ebb5987ac3820.nq.gz
│   ├── 494aadff52a0f688bea6846c9e0f79f15eebb7a9.nq.gz
│   ├── 4cc4ba7bd9a961069929b9bd9d5622e54a964655.nq.gz
│   ├── 4d19c440e672746feb4b2857eb66a82da78f52a1.nq.gz
│   ├── 4f0cc1b903c646da9190ec6668093311f320348b.nq.gz
│   ├── 501091c35b892bd2a4c5972341348946dc04fc69.nq.gz
│   ├── 50c64ef2db455828ee92a15fa08916455c95b9b6.nq.gz
│   ├── 50f0ea48a8e5fafd80f3fac6afd2a6b94f6b5e34.nq.gz
│   ├── 5732394b252c7a3959cd0529cde82943eab24614.nq.gz
│   ├── 575bd8764663f3a3de915ed919577cd2d1618637.nq.gz
│   ├── 5a155ac6f887aa2bcacdf933c2bdbff7a38fe033.nq.gz
│   ├── 5a1b64157dd4378df9922504c8c1b692fc17fdf5.nq.gz
│   ├── 5a431b6ab9f5847a53dbf44723b85a0127cbce7a.nq.gz
│   ├── 5b6eb98fc0e53b8e7cd7375afae9bc422e4a08f5.nq.gz
│   ├── 5c00413ad536555027e1015aa89f9a29ac4023ab.nq.gz
│   ├── 5fc353c1cd5dfbb3bc8219e22fc1b8594a202571.nq.gz
│   ├── 600503da29cb8463c36e8446c1387de5f7ca6e4b.nq.gz
│   ├── 612d1e6156d7dc0c99d5d7c7681e16ea38aaf1fc.nq.gz
│   ├── 65a2e766c260d518628c0f43c5999b4996f1a15b.nq.gz
│   ├── 67f270ae9c43c73ae5de7a88cc4e6d04c8eb99c3.nq.gz
│   ├── 689fcfac543a57aae49d4dbdcc48fbb3cabbcc60.nq.gz
│   ├── 68fd528f2c6b5b4d1238abc063a5a26a0870a4f4.nq.gz
│   ├── 6912b09556e4092fd0896f9aca0568ba2e902962.nq.gz
│   ├── 6f56f879dd248c24ad7eeaef18a46df964b50733.nq.gz
│   ├── 7015d28f61a10f09ca961a29b0b21cf86548d4b2.nq.gz
│   ├── 7170b8601068ea269b903b2b8bebfa5e5b38d739.nq.gz
│   ├── 7415e015baa74d76b0f2c99f890da6f5ee757bd4.nq.gz
│   ├── 763845f95b78a2b9e21e4dbfdf34d4b1d43ccb6c.nq.gz
│   ├── 7ac3e6f1d248154e10ae7b1e788ccdc346408864.nq.gz
│   ├── 7d37f72c629b89ccced9b067cf2a8945a7baf459.nq.gz
│   ├── 7f6c29bfa41164a6d247fedebba6543eee87b162.nq.gz
│   ├── 80b668321e29370e0a151be50e8d72850555b733.nq.gz
│   ├── 80d94326ef97e884c3ee7965288585b8a389626f.nq.gz
│   ├── 8266f97c3a1e47563cf405ea9523f821ca695b46.nq.gz
│   ├── 865e5cb1001615271c9648325935d38587723011.nq.gz
│   ├── 870a39068449fa202befd3562bcaff9571c1d343.nq.gz
│   ├── 8b72b22c503e95597e59628884e6e828509eae39.nq.gz
│   ├── 8d6a1e1fd1c41dbbc1a45efa1fa4cf04a0d2c50e.nq.gz
│   ├── 8d976e12a8c70e8725eca22ea95e532690c30d50.nq.gz
│   ├── 92e66e38a3c0fc65d6c7fb3a0c363e2033f30c16.nq.gz
│   ├── 95b019869856fa3de96c4d14e3c42d4e2c33f3f9.nq.gz
│   ├── 965aaec6530ff476f3aaf547c785187ce90a1b15.nq.gz
│   ├── 97b37dd1312b9768056771cf9d6d0a2d72ac653d.nq.gz
│   ├── 9f225536d4573431be23a1a396772a3387b0d368.nq.gz
│   ├── a22aeff1540bb7023afcdca45d82590824bcb6c8.nq.gz
│   ├── a2d43da4403585e3aa32e44d945ccf394de42865.nq.gz
│   ├── a3764b8775d2d9dc18a50f367a0a245fb2a71593.nq.gz
│   ├── a6044627eb50e5e37c52a86ff399a0c1cd3bc1b6.nq.gz
│   ├── a6054a02de9ca6d2ade848fa1e9ee9cdecb67d23.nq.gz
│   ├── a78598aabf4e890f0d8b0592fe1c16dc5ad1946a.nq.gz
│   ├── a8f7f83ef39b2248b2e15af4356eb737d6fde9be.nq.gz
│   ├── a93f66f0df6a2107b8d6423b62f7c79857016ff4.nq.gz
│   ├── ab00e7d4d97dc3b5a6b5a1a0b9c59d08bb9c7a36.nq.gz
│   ├── abdc7863211830f138c7770a20931dce0bbc111b.nq.gz
│   ├── abdfa0ca4057a86f9f1b8d93c31ca2636c64554f.nq.gz
│   ├── adf5224f60096da6f7a203ff2f37b06401745a0d.nq.gz
│   ├── af04f607c21625f2b823934746da4ed0ee72018f.nq.gz
│   ├── af4661563861661d36538a7bbb169e11555b36aa.nq.gz
│   ├── af47fd3e666eba79fabc53008cb9357b8cf1ada4.nq.gz
│   ├── b074e6ac7eb969aeb6c7e2327ea0449c41dcd12b.nq.gz
│   ├── b16d9e413117984a392157899ff1b27936502d15.nq.gz
│   ├── b681bd5bcbd658cd901bed61c54f18046b5caddf.nq.gz
│   ├── b6bbe080ae53892267f359a81208d29f9b43f760.nq.gz
│   ├── b7c8cbc1c1c03f2111ae0549414c93e25c64f3ee.nq.gz
│   ├── b855e78713d930450c1d0d169c837b97e0fd5998.nq.gz
│   ├── ba5ee6a2fd463c1a7d2fd4daa7802b201d135073.nq.gz
│   ├── bb63425a95119d9c6b47bdaea9c458db342e5fdf.nq.gz
│   ├── bfa5448fdd9d50837581e5b9203fb1a35fb63ece.nq.gz
│   ├── c3e0ed7a7fa83806a2a25ed248d4763554e33d2f.nq.gz
│   ├── c6dd679f6bffc1a37e79413f72328bab1d358ee6.nq.gz
│   ├── c8c47e2d836570c9b2315384b14ee69c29317499.nq.gz
│   ├── ce494aa39dd8f207b5778d4962cef352502f56d5.nq.gz
│   ├── ce67ceaf4cd4ee2305e182f8dcde95069bf49388.nq.gz
│   ├── cef9639fb040d3f1837587e8d643836b430237c2.nq.gz
│   ├── d09da0609d6b260034289d6bdf5a895588b5faed.nq.gz
│   ├── d3d9534b82805e6c4c1c8c26582400f46252eb9d.nq.gz
│   ├── d4216f65c92d3cf51764b061178a8cc5f231a7dd.nq.gz
│   ├── d46c40b66319d4e9e84572faebf5f710eed14706.nq.gz
│   ├── d4c380fd5ae4af9b2542d49305413843c77b0ec5.nq.gz
│   ├── d69705adc5a20c4e830c5551b6ed3fc00d452f86.nq.gz
│   ├── d85f0db9742f43e1ac728f1ddf2416a1b785eab2.nq.gz
│   ├── d95adc5c04f7728f5da75db2c790bdd4441fbcd1.nq.gz
│   ├── db42afcc84ad23bafd5c4bce2e4a80153b437ca6.nq.gz
│   ├── dc0c7fdbe17e491d67da5cf44918800ec27ae949.nq.gz
│   ├── dfc8f105c70bf899a3d436bb5300e3f99384e2a8.nq.gz
│   ├── e0a7b0337d2a20ee12648998827052d49df681f8.nq.gz
│   ├── e30495d753a0ed0aacb6be408431e2de862830f5.nq.gz
│   ├── e3abdcf5575fa8772d8a064bb0cf75fb599cf026.nq.gz
│   ├── e45b5a0bc576c40a6a232877655a3de929856a81.nq.gz
│   ├── e4896ad1db55de2a05aee93e49230e768ea296d8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7c7406eb7b5eeb25c39812fb3b9886faaa5b8c3.nq.gz
│   ├── e8713c8dd6f0909e88505fe171aa4519ce789d36.nq.gz
│   ├── e9a5b9df30ab6632021326da4d2da61d89f44fed.nq.gz
│   ├── f2717417133464d3f38f6c2c0ddd032eb9ffa184.nq.gz
│   ├── f358d21aca6ca06ea53c699bff790117167cee26.nq.gz
│   ├── f3679856f3644bbe34fafa0dece234014daebdde.nq.gz
│   ├── f66c696bd6f33316764dcf984245a1b160da9604.nq.gz
│   ├── f7fb8f62e2ee58f4d5a28d78695051da3c41a7ae.nq.gz
│   ├── f9e79478f1f658ea472cf750a02caee127461057.nq.gz
│   ├── fba0aa63d11e13de8c638a2fd0593e20c0735b73.nq.gz
│   └── fd341f64019b50ef9d2688581e0c674ba52dd89c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b60459844cc95f2170297ebe1c84b7de8b752953.nq.gz
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

[modelcontextprotocol/experimental-ext-interceptors](https://github.com/modelcontextprotocol/experimental-ext-interceptors)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
