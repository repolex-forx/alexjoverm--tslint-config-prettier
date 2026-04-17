# Repolex Knowledge Graph of alexjoverm/tslint-config-prettier

RDF knowledge graph data for [alexjoverm/tslint-config-prettier](https://github.com/alexjoverm/tslint-config-prettier), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download alexjoverm/tslint-config-prettier
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4898124666e7cba64d8b6dc3527884d9b087aaa3
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 4898124666e7cba64d8b6dc3527884d9b087aaa3.nq.gz
│   └── repolex
│       └── 4898124666e7cba64d8b6dc3527884d9b087aaa3
│           └── chunk-001.nq.gz
└── blob
    ├── 020a29686365afdb3e6156efb3c0cd421a648106.nq.gz
    ├── 030ddb8c92b0707a97e13d3ae9712e951f69a845.nq.gz
    ├── 03569ca9ab36a014dffb8e54e021546304a17db9.nq.gz
    ├── 065c8887b5f9ef760faaebb73e505ca9106f8b32.nq.gz
    ├── 0671e2f28fee19faf184af58294eac81140bbe46.nq.gz
    ├── 0735f8e9705254bae22ab9d86bbe235c195aaeaf.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 097720743c692d574ef9f0dfc622fb2a9443a633.nq.gz
    ├── 0a8a2b0a73210c14cb5e2c8639833a7d2ade9d55.nq.gz
    ├── 0c265318868c62130b2607bb6873ff4d5a64bb4e.nq.gz
    ├── 0e00d0b6cd2c926223715e8ee1c08dcdc4f7cd2a.nq.gz
    ├── 1040d0ce5c6a94f3e990591b791dad8232bc41dc.nq.gz
    ├── 109a78d9060395c41ba9c1a359670bcfa1c5b54b.nq.gz
    ├── 115e063e725228083104a551bb8292de644dc194.nq.gz
    ├── 119d17213970b5dc498b110c7e2383b340b0004c.nq.gz
    ├── 122ce053d318f0a820ed867f64908be93915bf49.nq.gz
    ├── 17956c8eb4793b3f8b3da4928ae797843e6ef0e0.nq.gz
    ├── 1845d7c88846bccf65da1825b27a6ec35374e239.nq.gz
    ├── 199ae0fcff5cfefb015b3f732e5d4e9c8e4bd0ec.nq.gz
    ├── 1a3338eda71a9d54b1632a64e2a455fbc96b72ed.nq.gz
    ├── 1a3820f33cdcab648f3c597847640dfe14ecd218.nq.gz
    ├── 1e7882a8f1ebec0e189a9d054de1511d6ba9b98c.nq.gz
    ├── 1fd6512cd0bf4d35f162817cf576cf75bca19f31.nq.gz
    ├── 215468b2aa1bf4d2b37a0042261942e27cc65317.nq.gz
    ├── 222fac000771735e9aa9ad1c583e4c050eaab3bc.nq.gz
    ├── 2255b9d420e53162fddace5283b0a5a39ae6b3eb.nq.gz
    ├── 2630957698c8b09777067cd264c3a6d12d743bc7.nq.gz
    ├── 297674f657c7bdb6a002e46aa059bf061ddc164c.nq.gz
    ├── 29d399c84e7616eef099eac240f2c43d74e50ca7.nq.gz
    ├── 2aeb4942e7eb10c2535fee04c37e7711bf255ae0.nq.gz
    ├── 2b93d88ed49ad07b972a0a5bb4cbe4aaaa580f26.nq.gz
    ├── 2ca147268e9e0896d49519a45e024d53caeda086.nq.gz
    ├── 2cc04f9d2b72a351bdc5e58ff500ce4fa69ee98e.nq.gz
    ├── 2df5601d9c6d5c336377ae3361895c4dea137f17.nq.gz
    ├── 30020d825f96a41a02b59bbed7c44ca4f81a13f0.nq.gz
    ├── 30e5c60e9cd2f7d003896840a508cf4af2069d3f.nq.gz
    ├── 3129109d24af803982431fe0094d00e26c6b83a1.nq.gz
    ├── 316ba8238e2e6b3148fbb7c41e5626bdce061ea7.nq.gz
    ├── 3174334be81a23731d2e062eb97a970042b3f371.nq.gz
    ├── 3317fbd80756df245ce6cd2a9d4eebb3fa6f38e3.nq.gz
    ├── 3372d3b8f3780858838eb257fe60e99bc4fa7882.nq.gz
    ├── 34260ee506f4cd25107d7025460f8d38e6fb41d6.nq.gz
    ├── 359ed0dbfbe1b1317ddcda5beaf90f0ed0837aeb.nq.gz
    ├── 37379fd63c9ade01b3fc86b58369d8ff13ec4e32.nq.gz
    ├── 37d0cf90c1a434f831356021830b1014bcf45002.nq.gz
    ├── 394ba10c5c0e1ad75a4c123b2c57294c3c42241f.nq.gz
    ├── 3aa56ee664369fefbee8b5997acb2be140b8adfc.nq.gz
    ├── 3b4d9a4edf8bdb333a6a659808c0a5b3a03c8d17.nq.gz
    ├── 3cde3fdc2a8e4c601cbbc773c0c3c48b46a28e11.nq.gz
    ├── 3fbf317a15738c0198aaeaca1fc579de7a122c63.nq.gz
    ├── 434aeac70db7fbea9c0d78c273e5ab21e0860b39.nq.gz
    ├── 43c92b1aadca167dd5e62db1c693fbda78564572.nq.gz
    ├── 4685e8016ad758b93a2efdd48634c439efe29c01.nq.gz
    ├── 46b1aaea28dde8c870c487093316d9b2caaddba7.nq.gz
    ├── 498b9e72554b4cdf8083fdfa4f671e0c9e236d73.nq.gz
    ├── 4df551668dd076e797948c5767ab5f64dc636941.nq.gz
    ├── 4e122083974146bfdd77a49e0aa37c8164346c99.nq.gz
    ├── 4ef0262f24eba5f48be66249ac68477b396e14c7.nq.gz
    ├── 4f2e4b66f27e3134affc91c5deaf99dfb45d838c.nq.gz
    ├── 4f8618cc88cf109d1518dd7fd88d95679a5442a1.nq.gz
    ├── 50a5b8fcae00a92b0af4982305b8ef5abc547b33.nq.gz
    ├── 51efda0f1d1123a61785243f5b8d08edc47eec75.nq.gz
    ├── 52f97959df9a76f8f4a05833b41162c7af850791.nq.gz
    ├── 53ad512cb0fc3db849e07ec1b3cc18dc763bda59.nq.gz
    ├── 54fa0c6d35f618eaf8178f84415cd846435198a0.nq.gz
    ├── 55dd3c6009baa5923b1e4f5646ebdb198f3c9a94.nq.gz
    ├── 5608ccafb589701eb5008365a2e94485336789fa.nq.gz
    ├── 568d36d01a29eda41c56185fc00df8180b8dc25d.nq.gz
    ├── 57d978e94946afb5d8783bd4aa029acb36a4fddd.nq.gz
    ├── 598c7a96920d4e2947d3f074918773eaa27ec38e.nq.gz
    ├── 5b8e7f2f3845295b7162597775e1247859e6c3ec.nq.gz
    ├── 5bc701edfd92d197404642939ccc790114fbd1a6.nq.gz
    ├── 5d72864479980ecba78ecaac1df51944b21771ea.nq.gz
    ├── 5e829897626b600fbd7e51d10c95551253b52552.nq.gz
    ├── 5f71708442d29a6772299f5445dd983cc56c816f.nq.gz
    ├── 5fbc0febb03e5e9b57a668c098de902ddeac7806.nq.gz
    ├── 632503d7d5c664b2a81bb07023158a611e584499.nq.gz
    ├── 63ccf0614974ca106443be84892443401bf02fa5.nq.gz
    ├── 65a6e7fa969b72f478549302120679e275db1d8d.nq.gz
    ├── 661f253672c6fd682247217e1b1fa2948996ef47.nq.gz
    ├── 663ef2d84b5c1d7fccf6bf1502e8e007b3022f8b.nq.gz
    ├── 67dd8a70d2751274ff8a0b133566fac43c9f6e68.nq.gz
    ├── 692d55e926eff92831b6a8b838068e49dcd82943.nq.gz
    ├── 6a23bb16b71689a9f02ea47dff133503193ae5b5.nq.gz
    ├── 6b092a02a99a87e44e463072cdb4cfa2fef65755.nq.gz
    ├── 6b2d886ea15afdfd1824a89f6e103775f849c791.nq.gz
    ├── 6bbfbc4775cb81c997ad5bb6515d842c046ad044.nq.gz
    ├── 6fe3be2a3cb125dffdacbe2114209b03a8a63381.nq.gz
    ├── 70a60dfc46d653b957dc31d192fd995bd9b0b3b1.nq.gz
    ├── 70c8b86a515d5e2a77a6812eeaf02ffa45e64961.nq.gz
    ├── 713c95008c59dc4a4f760418ec6130246cc133a0.nq.gz
    ├── 719680efff186fca9256a8410defa78ec48c45e5.nq.gz
    ├── 7267d7a148509957388cee907c1e7189b2e1a75d.nq.gz
    ├── 734658eddcfe84a8fdada80eb61f682a20d37ceb.nq.gz
    ├── 735c5f85f99b37ae3980caf07b6e95bba4960bce.nq.gz
    ├── 7546a2c27bcfb79e6a88f8c03de80192cca7d39e.nq.gz
    ├── 78cc8dfbbca0d1201d4ddc072285771a399dccdd.nq.gz
    ├── 79138b7c54e77355bfbd9329d579c76d565f19db.nq.gz
    ├── 791977d7dd71ae9b448b3493ba6cc171c8a5560f.nq.gz
    ├── 7972c7b13e738c5d4b02a7d8c3f3f74966f64b80.nq.gz
    ├── 7c1492bb97081eb162108408a5a95195b3389e70.nq.gz
    ├── 7c3e5f86d59368c262d02ff75730894567a05456.nq.gz
    ├── 7cd049d2253ed1a0f3d5f1db3679b5cceba417b5.nq.gz
    ├── 7e55d4bd82c1ee485b14fe73e97e561d30fc37f1.nq.gz
    ├── 80f003724f9eb2bb370e4f710e1444e74bc48cd4.nq.gz
    ├── 86c7a21a683f6cf0f824bfa5357339c200c597c2.nq.gz
    ├── 88022240729c9a0df6210136fa4231b39285f4d4.nq.gz
    ├── 895ae3c4a184e370714ee73df41774f6a13a8c84.nq.gz
    ├── 8b3f572e5644059a8ddaafb1f89e0d62506aa454.nq.gz
    ├── 8c5b750f280d773aa00f2cf6f3d9c712eb0603ff.nq.gz
    ├── 8d2a5f1cd4b37f9bffd7b1b4f10320f26e5bd8aa.nq.gz
    ├── 8d4ae90cfc039ea56178b7436309b6ecbea39a84.nq.gz
    ├── 8e9af34b6686dfc8c988395b196b1a9e3d952ef9.nq.gz
    ├── 90bba18020d9d979060ccc3f3e7347a17f80a1d7.nq.gz
    ├── 91dbcc8098391047b69b48874a70168156954863.nq.gz
    ├── 92b9bb1e54c120bb6dafdcf01648e70f0dc077ea.nq.gz
    ├── 9318e0d53e4ff95f78348647c2317e9eefbc4076.nq.gz
    ├── 9350ddf89541079337f70c16474831d0d3d7b8ea.nq.gz
    ├── 94069772d6dd1bfb4d832da10a00b685d54f0a0f.nq.gz
    ├── 95fc6292b7167f1b9015ba6fcc1ec279a6f8dd87.nq.gz
    ├── 96e975915dbf69236a327880d6ce18df27b9501a.nq.gz
    ├── 9a0b30d5bf8e03fd1541ede221aa903bea81d0cc.nq.gz
    ├── 9a730d1a29930b9b24073b3fb912fa4c991be90f.nq.gz
    ├── 9c05d45c05c14c457e061181511e63ee20b2c416.nq.gz
    ├── 9c394203c9db5b79ef0c9667b3782a89769afa9a.nq.gz
    ├── 9cdd7a2752abe4fcbbe142472a5d3c5d5875db97.nq.gz
    ├── 9d302491826698d629f68ab5e6328c3517fc3a8a.nq.gz
    ├── 9d9737b3e17a5d722b023d7257e922c5a53226e9.nq.gz
    ├── 9f7050fd55929b3b7a598907d56d1de0d407504e.nq.gz
    ├── a179d12127d9b7a43801801f18915ffe5d450a4d.nq.gz
    ├── a1df1fe78829a1c6914d14dc93452754a034c838.nq.gz
    ├── a20f655c4e873b562dcb6c5f0d1ad42a70a2d225.nq.gz
    ├── a2ddc9990c1192e014a99e75a97879f82093082a.nq.gz
    ├── a366a23efb2e83583f50b5e58e6d6fa7c29603ed.nq.gz
    ├── a381867c32def62b527786bf27cb74c6a1d0807d.nq.gz
    ├── a95e1eb9434dd97deaebe5bff18669eb3ee344a6.nq.gz
    ├── abb76bb69e03492f52db1a91968d3b1cad30faab.nq.gz
    ├── ae90fea974cb7b498ba63095eb0b08e4da6bb617.nq.gz
    ├── b39599e0c907f1cac195565e6deff24d16c343db.nq.gz
    ├── b41f2f31f698db2b7044766ea99cbd46b0bebaf2.nq.gz
    ├── b4385f10993445d75a7861f7a3f237338b0db60c.nq.gz
    ├── b662d75bf873f6ae5263dcccdb8f5f631e101e8d.nq.gz
    ├── b6f66a62fabecb552fdc6902c335030dbf04389c.nq.gz
    ├── b758f1f7706b954f4ff5293e95a69b7a93e7c3a0.nq.gz
    ├── b7a2cdd98de9fcf533d97b2e387937d0d3849b71.nq.gz
    ├── ba33191cc2195edfe8fa32670615b45ca77c8634.nq.gz
    ├── ba3e681096dfe87226646ba7d85448231915ae4e.nq.gz
    ├── baad51d21f1e01c2da4466495225c0f5ae9343f6.nq.gz
    ├── bd226f5184ac47519f98505a65be7f8646883675.nq.gz
    ├── bdd7293dde93436d5aa23e264c1414013c941210.nq.gz
    ├── bf1ac8bf9598a4fe63aebd81844641730b33100c.nq.gz
    ├── c0a3537ee0c06c1e1a81f14620381701e08e4824.nq.gz
    ├── c184cfb94c66e83acf4a366a447d3cc6692bf24f.nq.gz
    ├── c1a4a789267905048de0a6b5d2b7cebf7afb2ad7.nq.gz
    ├── c272afe2d4553108f108b398db789997176767f2.nq.gz
    ├── c3e453fbebe31f661d29c12b8c08c101655bfa68.nq.gz
    ├── c3fe8b8b5bd0722715bb0893359f09123f6c0a16.nq.gz
    ├── c80b150608c5c88e1908ff9e61a7c89aa5f99952.nq.gz
    ├── c82898ec9ccf3cea3fb0f1edcc3f3b9db40790ac.nq.gz
    ├── c82bdad0118e3da45b04c851eb4fd3513cf01b40.nq.gz
    ├── c9d34eadbbb6633b32bceecd4d25d5646fe7100d.nq.gz
    ├── ca75e96b5a122bfb0e3f4e429cd8c3936a6f3874.nq.gz
    ├── ca78bbeac488ba2a8a97e39f219e474e68954db8.nq.gz
    ├── cb0551df8674530ee7e20a6f5c4d8b1ecf1ebc4d.nq.gz
    ├── cb5723c00996a7b03a89a148db1dd15665a8f15d.nq.gz
    ├── cec1d289e192636ee6578cef15787aa6e10c32f0.nq.gz
    ├── cfbb798a6c30cab58035a0c239c9d0731a040d46.nq.gz
    ├── d0897fea11405d1968a101d6aad8577fa43b04d3.nq.gz
    ├── d0f1aa2ef93b32b8251fb0e5975f7203c781929b.nq.gz
    ├── d2f7a91d6d45ee01ba95ec7d372a614608d8ce38.nq.gz
    ├── d3f5a12faa99758192ecc4ed3fc22c9249232e86.nq.gz
    ├── d5f6071303dd810912531a697e07aded54ae5b7f.nq.gz
    ├── d669b440b17b26ef860caf3522a95dbbf82446af.nq.gz
    ├── d6e556c87d3d63910c3d4a93a08f66ffa82b245c.nq.gz
    ├── dc0887298c98f4af728913c52153a44b1791359f.nq.gz
    ├── dc5b208021fa01fbf5cba7448518b2abcf6f2e58.nq.gz
    ├── dddd0d8e574cdb85137d547d007e9dcbe7d94ddd.nq.gz
    ├── e06ff11ac68103cfc9c0802b3d5c9a31c3ae9918.nq.gz
    ├── e11814492788d0f408cb3919bfb8aad8d76387f5.nq.gz
    ├── e2f6913937f3130b52b4b93925a330306b92bb1a.nq.gz
    ├── e3df04bf9354d01be0d8d6352787ec2b5ae6bce1.nq.gz
    ├── e4e156de7c1cbb2e9931b072217f7cfb4bfc048d.nq.gz
    ├── e7baf6cbc5015a0627524bddaffbd84e23d740b1.nq.gz
    ├── e9e5921bc6bdb3de0db440d6d77e34151ce25881.nq.gz
    ├── e9e95096402429f7f468a08d13bbbce8751628c2.nq.gz
    ├── ea9b101e1c225939a5938249130755351f110ab8.nq.gz
    ├── eba7ea2e6f894d2cbf796c3c89125b11db3193a7.nq.gz
    ├── ebe213dd2aec314ca7d711a0180f4a7a3c70ae74.nq.gz
    ├── ec0d152e9f2b094922dff78d98db380fb4dfab94.nq.gz
    ├── ee23652e638016b54f1eaa2faabdbbc0cf38cb00.nq.gz
    ├── ee7733afc0ba569aded95aa6ffb77f961d5cba22.nq.gz
    ├── f16e1f9ca52417bfcd248da89ed283ab14bcfc77.nq.gz
    ├── f28cf014e903f55bdd92e1d6770d1b2d8e409e4f.nq.gz
    ├── f40347c2b8ebe9c37e3335cc55c18e6df3c917f3.nq.gz
    ├── f4619634c9e4ebe7e6a2a7bff6b5ecdfbc108133.nq.gz
    ├── f6dc8fdfc6d559f6a1719f6a128d6c8a3373235a.nq.gz
    └── f81bfe73957d774f0336318fc12162ea01fc4a14.nq.gz

8 directories, 200 files
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

## Source repository

[alexjoverm/tslint-config-prettier](https://github.com/alexjoverm/tslint-config-prettier)

---
*Parsed on 2026-04-17 by [repolex](https://repolex.ai)*
