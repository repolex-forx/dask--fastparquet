# Repolex Knowledge Graph of dask/fastparquet

RDF knowledge graph data for [dask/fastparquet](https://github.com/dask/fastparquet), parsed by [repolex](https://repolex.ai).

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
rlex download dask/fastparquet
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d5c57426e8bfe4445d351c362e4379787957ece0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d5c57426e8bfe4445d351c362e4379787957ece0
│           └── chunk-001.nq.gz
└── blob
    ├── 00a3c7eaa300e02b922278b99f5b58f838dfa522.nq.gz
    ├── 012d0e825c3f40d71013f8367fdbf1be3da5cd34.nq.gz
    ├── 0138143740d2469c2afac899a314137d99f85d19.nq.gz
    ├── 02449f68687ccba490cd607e8a5d0953a66f68c3.nq.gz
    ├── 02687fb76cc53a76187f661aacca6c6a745f8e00.nq.gz
    ├── 029c1c4053d13840b17cab4c0213b0dbdb06c9b1.nq.gz
    ├── 02f20a64c8b4a809aafe270ce6a0a91606e57d1d.nq.gz
    ├── 03023debc503fec86f86bfbd5579ccc3a7a0aaef.nq.gz
    ├── 039c5ff610b64d6250e0668c109979a0701fce6d.nq.gz
    ├── 03d1568d59768fa59bc2ef86fa61df3e676d4537.nq.gz
    ├── 05421021d6129d56fe34dd88c89988e0a73863b0.nq.gz
    ├── 0607207f908db9266013ac261935250278019da2.nq.gz
    ├── 076cf0e36f2c1f68c78dd029a80cb46bd4108666.nq.gz
    ├── 07edb0c655e7e3d5921d56f70026c00fc9ceb1c3.nq.gz
    ├── 08cb61b3c8948678d8de44400471e5c13e1f2948.nq.gz
    ├── 0ac5f4cf571ae84fc12c3f0f9ff9ddad2692e422.nq.gz
    ├── 0c0c7236cf76fd268f9ba588859a71f1c3c59a54.nq.gz
    ├── 0d0d7ec9a107ff31bb58697badcd023ee3beaa73.nq.gz
    ├── 10e7135f674f16ebdf918a91817c89a3b47a03c4.nq.gz
    ├── 115bbb05eee10054a121c6015c16b96b9e752ede.nq.gz
    ├── 117e1e4812e98052c17cb167f78e933d645dafe2.nq.gz
    ├── 160714166087b232586e9226d192f1495921a39a.nq.gz
    ├── 165abb463288ea2df5c32255db507af81435d1d5.nq.gz
    ├── 16b1703802d7c206af9c9feaecf264dbeb092690.nq.gz
    ├── 16c58a3a28bc24ef2222a38672b1d5004ae724a8.nq.gz
    ├── 1818051c080446ec5f77e432348df7ec6c9b978a.nq.gz
    ├── 1a249f6233951e8bcf2ada7e2e6c216b745776fc.nq.gz
    ├── 1b03ebf159d7956d977d7b3d371e2809f6699bb9.nq.gz
    ├── 1c72ff959d6e28cf9e9dd6110ef1d2580d45e4f3.nq.gz
    ├── 1ca1dc9afccc7346843482380e4f26349eee7ce5.nq.gz
    ├── 1e2b71eecdd9c381f0457228b03539467dca7ddc.nq.gz
    ├── 2210f84303ef1a4c1c3fb98563007374872b7c53.nq.gz
    ├── 22e3ef224a52fe0e186710ef1d13ea8b62a55815.nq.gz
    ├── 238c0d4c2275ec0b784771cce93658a6ef24a1c5.nq.gz
    ├── 243ac8c6c3f45a5e674f8ad27462f3cbfcf5ed4b.nq.gz
    ├── 25f444ffa24f7373f446bd081b0f4f0f010d8da7.nq.gz
    ├── 26180147302d4bb964399cebc2c69bba5e6426c1.nq.gz
    ├── 26c54c13f70142211f6579d4985a0caa475f1741.nq.gz
    ├── 2a3d25f2c60c787c78da590637f1098b6b7eaaf9.nq.gz
    ├── 2adcc15e06b571fd5d670cb3df32a99f7603d8d9.nq.gz
    ├── 2b77bb1e9a20740694fc7b1c391bf06d0b419b07.nq.gz
    ├── 2bdae3633f5dc731db1ddcfd63e8187aeb3da544.nq.gz
    ├── 2d3274d9537be3a7aa23f3ebef581833d900fcfa.nq.gz
    ├── 2dd0da21baf90bd9bcfcff5956c0bce07422ddb8.nq.gz
    ├── 2e192c81c8e706576632fb08c9a601a0ef61bfbf.nq.gz
    ├── 2e5061b0c0923cafd3c91e2969a9d46f90909a1a.nq.gz
    ├── 2f29c6e83b454d1538119782592a877d4ce0eb50.nq.gz
    ├── 2fb649ef52e5dee701dda0eed6b1eccbb1019447.nq.gz
    ├── 2fd006eff78a2e63b270464b88dee70edb9b6185.nq.gz
    ├── 30f2334846958b04b134177daa47cede7ddb8a89.nq.gz
    ├── 31877949ffdbcd3b78a796161d7e3c8fc67a37b5.nq.gz
    ├── 31a59ac63a47bb74cc01b0669fd20932bacc2d1c.nq.gz
    ├── 31de68a0beb87ba83b7914278efbe77201eed9e6.nq.gz
    ├── 32239d03e18367d1f6de1ef11ba3aeca9a54c1a3.nq.gz
    ├── 3235294a30e5e22a88ffc29a565328a7a44aa6c2.nq.gz
    ├── 36ec404e6ae453337e97940f12ba8563fd22d791.nq.gz
    ├── 379abc6e411957eb959cca3b9828d15a521c76e8.nq.gz
    ├── 383ca9a196af83017c17b1be4db57e4134ee3f56.nq.gz
    ├── 3b034bf4eb1dcd9cb2a8c1c05a397541d1232fb9.nq.gz
    ├── 3bdd8272b4d3f8a84ad1d11534debdea250c36c8.nq.gz
    ├── 3ce4ade729f642061f82564f07d37d47336fccb6.nq.gz
    ├── 3d25fdaaecf9aaff227f8ef151db380051a10f47.nq.gz
    ├── 3e2f4eeed9e11be998459abac357e3d412761022.nq.gz
    ├── 3e576f34a2585edb900c8d8ccde1a9d725efaac4.nq.gz
    ├── 3ea3ce2b69edafb4e099ae356fb34e57f78693c9.nq.gz
    ├── 3f203038592ba324262c62b098a1633cbf3ed68e.nq.gz
    ├── 3f8bc386ed8b0f9a1c7b52ad0a5aa4280bbe32b5.nq.gz
    ├── 4131271368034e818b88c60a959ff84c47a12603.nq.gz
    ├── 4142134e9b8b3a048ea5b27f759b07b6d6b919c1.nq.gz
    ├── 427fa7472009fa98d5624b91724e3cde336e6f9d.nq.gz
    ├── 448ce496b1e3a6ef86671ecb6c7c6a36b3c27c9a.nq.gz
    ├── 44d80d403c84d46229c17e825dff6b1b22330d2f.nq.gz
    ├── 44e71f562398b94f308bf5e7ea30446aba54100d.nq.gz
    ├── 4947287f7b5ccb5d1e8b7b2d3aa5d89f322c160d.nq.gz
    ├── 4a4c3939f830179aec66f54db522254a1798ef2d.nq.gz
    ├── 4b3bd07436302cb5ae8d4a6f2f970a26b9d24f86.nq.gz
    ├── 4bd0f0b05b5e36353dcea6d292ab5d22e520b54f.nq.gz
    ├── 4dbadf8719974769412ccbde7f9db54067b7e4a7.nq.gz
    ├── 4f651a17b94e07923e5067a78da694f7f486c20a.nq.gz
    ├── 5008ac0b22b622cbcf37d5e286c749324fc26535.nq.gz
    ├── 50faf3c70583a09e9ea0452a15e3db176ab8d4a5.nq.gz
    ├── 5338e277ff669ea6e5f2f9c09c7d31648d58972b.nq.gz
    ├── 53b6045cd1a9f165e1770ff31a9cd40059edc6f6.nq.gz
    ├── 541d2e309f7eca016dff8573dc1515f7a6053a25.nq.gz
    ├── 5464051f440420d46bae64c18d46fd93a8cb703b.nq.gz
    ├── 55234428f1e9cb0ea339b781a98a442b9af37b08.nq.gz
    ├── 55c586ecf49ff4a6a3b7b778c3148d02808ed881.nq.gz
    ├── 566e51f401352724b6376063b7771295b5feecc0.nq.gz
    ├── 577b49ca17cd82322a7c719b760ed4f45f22a7cb.nq.gz
    ├── 585c5a27028120465a394b58e4bdd935e4dac825.nq.gz
    ├── 58d5f286965458c3842e8f425106c5eb586ce561.nq.gz
    ├── 58e90c45fb5254570867b594cf8b7dc0bbc986d2.nq.gz
    ├── 5a6761e3471e8b95fe1f037d040433821e083639.nq.gz
    ├── 5b1ff6650be853685dab9695dbca732326b15331.nq.gz
    ├── 5bbf0d50c72057c51f0e4ab9fe8286ff3ae18516.nq.gz
    ├── 5fd997831eb790f84bbcc88a99cc4759939ae2b8.nq.gz
    ├── 62a87cb28642c033028c654d634c885af8dec3f4.nq.gz
    ├── 6388e8f4da7e5d6d94dc4c57669392da15369750.nq.gz
    ├── 6524f2dbd18e8e1b1c704349788f4019b1e3b87e.nq.gz
    ├── 67144031733cb36f277cf77413cbc7799029688d.nq.gz
    ├── 678efbe381e1db454fabc677523004bc5c366c9a.nq.gz
    ├── 682da640a3fb4fd62beb873a254bac63997d574c.nq.gz
    ├── 6843df6717a8200ff17c609f9228a485c7143560.nq.gz
    ├── 6b90851a9a6c90bb41cd15dcd831f4f8ed0b2b4e.nq.gz
    ├── 6c76568c18373020e7edaf10e1453a5427946da2.nq.gz
    ├── 6cdcc4ad915eec607eb3445d0fc85edcf890c2e0.nq.gz
    ├── 6db533e5e99f5995423ab088c1cc328cefb79217.nq.gz
    ├── 70bf079236b600dc06d8065c5c5426e16dd3b86d.nq.gz
    ├── 73a32f19c2d5c4a5bc3353f037ac8515deca6856.nq.gz
    ├── 75326f039cd5c3d8f8d9bc262ad104dae4c41e12.nq.gz
    ├── 754d0ab1fae6dc487c5e9de18623908d6a48e67e.nq.gz
    ├── 759a1ba8dab63fcf6853fe722493ce0e630580b4.nq.gz
    ├── 79bce2fa3c2073581562f6427e5833df4d2ad52e.nq.gz
    ├── 7a0825fa69dc8eb9d5115d2c24fdaca18faeb53c.nq.gz
    ├── 7a24878d99e7dbc2b69ef3938810efb062bf5e5f.nq.gz
    ├── 7f3270918150a6a26d34a483c26ccc482a22cf08.nq.gz
    ├── 82c32e222d4877e57880e765616869bcee4cc28e.nq.gz
    ├── 83a43afdcee427abab7939ef23a8555ec52b6189.nq.gz
    ├── 84512618485b59890255f9c3dad288621473547c.nq.gz
    ├── 8586054858b851769a507851595e8f43d409c1f3.nq.gz
    ├── 85be1e99f42ee7bc2436edb8eba3b32d0a636062.nq.gz
    ├── 8cec0e1e22d11bc4822a26cff240d7d3b96aeb2e.nq.gz
    ├── 8d5cce5b327ef8ab40651ff7aa3d3c86e986f73b.nq.gz
    ├── 8e4e7aeba443c53847e9f9e971a680afe1824f0d.nq.gz
    ├── 8eca4fe2eb18112988a1d1009cce9468b7139691.nq.gz
    ├── 8f5a5cc2e86c06167a81e8bf3d5870ac56ec3407.nq.gz
    ├── 8f62babf5257b5d1332fe42fa1ec2b9eedbb9105.nq.gz
    ├── 907ee296b3b387e2318ed14c75af456c0cd30d81.nq.gz
    ├── 90f33d8741691e08a7c17f564c5ff353142f2455.nq.gz
    ├── 9266e95b8fb65ad82232becc9d84cbcbef355503.nq.gz
    ├── 9af0397cb6a9e37eee63495b07db1397fd85409c.nq.gz
    ├── 9e1639746e48358049d605ffa633b01e33fe9da4.nq.gz
    ├── 9e9f37da5ac86837e5f897fcec71e5a4af643fe7.nq.gz
    ├── 9ee084d2c5cd2bd9d6bd14fa16e36dc56ee6bb5a.nq.gz
    ├── 9f0eb1d92a9ea24b224a46421835387cdfe23423.nq.gz
    ├── 9f791732c671956402e493c72e1f056819987f86.nq.gz
    ├── 9fcf775e74655f25548e65f1392c292f23b83eda.nq.gz
    ├── a1cb43a56e0919400c3da683af647abfd2618840.nq.gz
    ├── a26129f129b2c47749fe2677f4a5f4d9577a8fe8.nq.gz
    ├── a3f3f25db42a90484c10d8b845a8db6e32d9772b.nq.gz
    ├── a40c57479ac2035ada1046ef2660e36ea9916bc3.nq.gz
    ├── a42dff1fd5317a9c26f88b4686b9d618dfbed60e.nq.gz
    ├── a4c8a943b312b4b0d238e5b4dac44accbe799e04.nq.gz
    ├── a8210858461d15fd7b3e8679b5c40c99e6d329a6.nq.gz
    ├── a82d47139d0aa925caaaf88dba8f8a0b65f5c057.nq.gz
    ├── a9fb9b8e26d710814636efdf1502c85943a30b49.nq.gz
    ├── ab0783fe31c3a50bdce2d29e8e83f9ea495106bb.nq.gz
    ├── ab347168b4ec0ccc007a23d6d6252023bcb83822.nq.gz
    ├── ab6f6a7eb96445180770694268d23225a0dda8ec.nq.gz
    ├── ab82c4e97bfffcd95c9ee3b255948480882c5c16.nq.gz
    ├── ac8500c0bd530539350b256bfd4bf588d8bce619.nq.gz
    ├── adefd8e51fcf17862843d83fd7ea34546ef09fca.nq.gz
    ├── af12b7abf727df1a7fa87046977880ec3f9dfc2a.nq.gz
    ├── afa7bc3a4592c9837c3b5db7a21f81d2d30472d3.nq.gz
    ├── affd3626174093ae36031a95e7ea4f18e4646f82.nq.gz
    ├── b2f6df8fc40bc9be3bd007eb8a4dd19fbc110a6f.nq.gz
    ├── b3520275b5ec879df67c0a78cc829b4fa28008b8.nq.gz
    ├── b57a3935f47a3c92a835ae0ee009715bc2a54f49.nq.gz
    ├── b589f1b351ea36a49e20b2cbd8c3e8f920d2eb92.nq.gz
    ├── b68a67ad957c93336406a308b7a77f51db267097.nq.gz
    ├── b7e478982ccf9ab1963c74e1084dfccb6e42c583.nq.gz
    ├── b875b2e3ebd0e8b83897619e2ca6bff531509983.nq.gz
    ├── b8ae51d213bed20e42112a604830d9bb040c8f72.nq.gz
    ├── b93fabd37c11071d1469d679d0a7aea95afde00c.nq.gz
    ├── bc61f97c9468fd8b7b26a91d61ae4f4deca8e962.nq.gz
    ├── bd0838c7f811e7ab22c41d4ec7a3735d6a4f5557.nq.gz
    ├── bd65916230018bee78dfd227bea32626de6ef107.nq.gz
    ├── bfbd7afbac16025a370a99cdaab9dd8539ce878b.nq.gz
    ├── c18756d327a6ea6a29cb1f0e1e76554b0061c674.nq.gz
    ├── c33b3a738378dfce80f9e40c2878b35e3e1a7ecf.nq.gz
    ├── c37380f6223bd92030c4fe38561708694c9f4775.nq.gz
    ├── c3ffe1b4bd57e85578dc9bfa2c77cb8109c286a6.nq.gz
    ├── c64bea5889baf0bad7cff84a76663dbf8f1d4f59.nq.gz
    ├── c6e176d2134c805e60da739312b8bfc39987ceca.nq.gz
    ├── c8041689b535bc0b73487f0e97e1b9227c7cd804.nq.gz
    ├── ca503bb6b051117c112c1514545324570bdd113f.nq.gz
    ├── cb833230eed941cbfe3a66e5c8368c44673feb14.nq.gz
    ├── cf570279daeff3c2d841d637507e7b7e174a651c.nq.gz
    ├── d095ff54eedfdd8ca24e7c4681bc867b789ff3ff.nq.gz
    ├── d23dbaa7fb6123658d497df1800d845a2501c425.nq.gz
    ├── d2fbf0fbb159be70388790119eee2e6698a92409.nq.gz
    ├── d7fd21174d60114db2cbc76fcad24fff6d49dd4f.nq.gz
    ├── da97c40209f7d56b01aee4c724fde30b0c87f2fa.nq.gz
    ├── dacb00c207f1f04cfe9c12e945bdb042d845152e.nq.gz
    ├── db2dc4dc1438ed1353926e46fdd606b2d2ad8f43.nq.gz
    ├── dc63835dc0081b591164d7647542e51d7bc2a27a.nq.gz
    ├── dd236ec2cab44b67d4c1d589bed4ff60a6baed1a.nq.gz
    ├── deb1ddb3b04cbf85e1ccad6f28cd67ef2aa2f932.nq.gz
    ├── decd75cf44ffa9601f8bb667303d5977afaea771.nq.gz
    ├── e0dd1841dfe1812bde2fa8a2b95797e49cc3f089.nq.gz
    ├── e2541220d8ffd8898efb2eb8bf1d802a7131d6bd.nq.gz
    ├── e25ca4b898a94a2488cd2cc54c8f43b8074c282a.nq.gz
    ├── e299176dca4a0f4a4668d6723acd190cb92d83e8.nq.gz
    ├── e32082522b1d0beff187d5f7df48af289aa353bd.nq.gz
    ├── e423a1dc0f09b7f07376001fb3aae8e7c2f54a31.nq.gz
    ├── e52c8a5b1b919d39aa3e57a690e294278afba16e.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    └── e97ae65d628121fba57f54de1e3b247fb6dd7b6b.nq.gz

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

[dask/fastparquet](https://github.com/dask/fastparquet)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
