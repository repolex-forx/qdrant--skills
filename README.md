# Repolex Knowledge Graph of qdrant/skills

RDF knowledge graph data for [qdrant/skills](https://github.com/qdrant/skills), parsed by [repolex](https://repolex.ai).

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
rlex download qdrant/skills
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9f55f6a7fb225932da70c6e7dcd671c7e9a8929a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9f55f6a7fb225932da70c6e7dcd671c7e9a8929a
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ac33ddbecad9db7ce45473a225f1ec51faef56.nq.gz
│   ├── 02ca962bb5db35c5780c3e21a9670b14ea096ae3.nq.gz
│   ├── 02d60ac5a98e021b564f613c2d37d9b1cb2a45b0.nq.gz
│   ├── 0b9ce06a7daf388753dbd4a9a65ca42b13518492.nq.gz
│   ├── 0c1570f1597b768041bb2e9cc170d9fc0758973c.nq.gz
│   ├── 13ec6ac1be8714de747602e209a2d601a2688c63.nq.gz
│   ├── 14330b7bbb43507e737d6626d56b382fc8a14365.nq.gz
│   ├── 1a102345becf4725bd6cb8a67772a70a4e4488f1.nq.gz
│   ├── 2342f7a36698033f83cb6c12f4cc1278d11a5f94.nq.gz
│   ├── 23e8be0f29609d94162e59e5ffefa111a287afe5.nq.gz
│   ├── 255eba0f26802a5e17931ea653f4d89d7432b61b.nq.gz
│   ├── 28f79c5a5c287e2a57fa009030ee11eddcc0a823.nq.gz
│   ├── 2c10f6914aebe65d8acf8df4705ab372a2e76661.nq.gz
│   ├── 2f74b2be8c3dcae9793e98bd2f0d44092210e75c.nq.gz
│   ├── 311e8a6ca3d78270db3393ee9e7ffa94f5acba38.nq.gz
│   ├── 35acecd4b9313972a06842cace0d74aa69d6f00b.nq.gz
│   ├── 369618f25034060b0e8156c24c7d158f39a1b5de.nq.gz
│   ├── 3831598a18d8bb5263a089af2ec48ac45e9ee48a.nq.gz
│   ├── 3af0509dc357c10860c763515ff53a433aa9722a.nq.gz
│   ├── 3b88aff7be1ad4b29878868f21dd58a3f80f03db.nq.gz
│   ├── 3f85ac5e97f344f404aad666b4a6868a07010217.nq.gz
│   ├── 40108c61bf3aeb83456b0504ebe646e3390b3987.nq.gz
│   ├── 41e3a32a4e37fa421e281e056d8d42e446263bbb.nq.gz
│   ├── 4447eda166aa931180ca73fbed4a09ebc0554a51.nq.gz
│   ├── 456fb05e0e936f439cf42c517b19797dafd53ff9.nq.gz
│   ├── 480451a5aa90c426f000f26a7241d0250f33bd19.nq.gz
│   ├── 4919d19e5acdcc25cb0e02b6028cb6717cbf556d.nq.gz
│   ├── 4d51892eedec36702852cbb7d77ba61d9cab711e.nq.gz
│   ├── 4fb0c2ddb00348222fc101b73a32c3cbc68f7aee.nq.gz
│   ├── 52e565f98d2c854d4e43df6fdca6c27c747b2baa.nq.gz
│   ├── 57bf4276f85016e56389330e90d7a73023f4f670.nq.gz
│   ├── 57fc7b2047436baa3f99ff885b849d75679e8c29.nq.gz
│   ├── 5a16c1b5ba777616c4c4a36599b05131f863c222.nq.gz
│   ├── 5b648d9cf0b7196096896af7280d5a2b58c917b6.nq.gz
│   ├── 5c197a8074cd27abc52196f49647379fc0e74dec.nq.gz
│   ├── 61d447ccee4544c980bb520882d5ac71356b60ba.nq.gz
│   ├── 655ee18e2ee60b5cd2ede3fe9aeef0c7d13bc25d.nq.gz
│   ├── 66bb2c6805e8d0cf9d969f2800b7c1f4ae125d31.nq.gz
│   ├── 6742dc196f44ae14e86db2366ce1dd1afa0dcc58.nq.gz
│   ├── 6a1109a94053331ca6335f6ce39ca301f4817821.nq.gz
│   ├── 6b43be7025b7288c6a9ffb66cefc81f56a18b92a.nq.gz
│   ├── 6bab5a736369e2d2b6bc1eb1b60af3ba8fe6bcc5.nq.gz
│   ├── 6c430afd24b3b23aa39de37cf53f72aa13d37da7.nq.gz
│   ├── 7165642cf0d3bc5c9f3c75130b1550f60b4273b7.nq.gz
│   ├── 72edc2754d42f37a4f750195ea56cbd344ec33b3.nq.gz
│   ├── 7751795d8559812f9472201af1f38dff4602b40c.nq.gz
│   ├── 78fc4a9f4ed707c3a818052023c28cecdf94eb5f.nq.gz
│   ├── 7b5267ffd3cbe59c4567b427d5becfb03bd9cfb9.nq.gz
│   ├── 7b8782ff4a6ccadcbc4f1555cd4135b730857e6c.nq.gz
│   ├── 7c37aedc4d4cdeb897ed997bbc4b3c10adbd4861.nq.gz
│   ├── 7f6b14873567f6ba528cac276967318e9880e51d.nq.gz
│   ├── 808b7c0aabab6f68231462688dd3d054cbbfb15c.nq.gz
│   ├── 80e8b6c224647c24f693209840afec2cf60d57af.nq.gz
│   ├── 83a2b240122a233921e54b57ba1259ab99b26a8c.nq.gz
│   ├── 88e72e9bf1966cae929fdbfe89f6342210a0b051.nq.gz
│   ├── 897b479d1deaf3443d9a25ee22e32f680a8741d3.nq.gz
│   ├── 8a441f1edf9824b156c1ce4157314ef5d2073a7a.nq.gz
│   ├── 8a930c23c316f0774ee5a2a512d8a8f1cf11ad18.nq.gz
│   ├── 9145b1000a16c5cb7cdc04f7d8ed0a7394e9d367.nq.gz
│   ├── 91be44bc7a17aa092051d288f5d8609390ca5938.nq.gz
│   ├── 939e9fdbb20d95010f9c80955730eefaac505bdb.nq.gz
│   ├── 98c9daf469d7496ae6efde523bef00b79ef748d8.nq.gz
│   ├── a11cea8fd023d0b7efbcfea969c6e70e70ba0ecf.nq.gz
│   ├── a1d445cbe925b30b5340854fc67fc27336357bbf.nq.gz
│   ├── a414246d2188e1f22a4b3935ac87ea179c782471.nq.gz
│   ├── a70f9aa816002c524f430f7642c25e2d10ed6252.nq.gz
│   ├── ac599e141f37259601d016e7d8feb85d2563ef80.nq.gz
│   ├── b071bdfa58d2c57da5a0ed318633408523696102.nq.gz
│   ├── b38b9820024dcb3d904ec6870427f229a7e12c3b.nq.gz
│   ├── b591a8c0107258e9aa806105323ddf93df2b0006.nq.gz
│   ├── bb576325ec94e107ffedf2e38244647887fb226d.nq.gz
│   ├── be398e8c5aeb64157a12d76e9bf63e922bb42c14.nq.gz
│   ├── c4eae9bd3a570e204689f72206d6d1308e9f87f3.nq.gz
│   ├── c709d4b2dc0707311662f95363401c4478e48620.nq.gz
│   ├── cad861a4dbb8901479f0fa3cca9d9269e850cc02.nq.gz
│   ├── cd2aad95225258527dbfacac8417a39e138ef740.nq.gz
│   ├── cf67b5ed1b17bff5723df77008c356662050d85e.nq.gz
│   ├── d3f273a709b90840afd3d91e08fb82c19333f422.nq.gz
│   ├── d4c87098bcdc82510251e78deb9b4a94b0360996.nq.gz
│   ├── d67f7e2cb310f133210c353cbe075453322e4b5a.nq.gz
│   ├── d879d6ba7d1d8ee03427e29600f74c06417ef239.nq.gz
│   ├── dd992762d56a0dd6f1faf3f190a3a25696bb930a.nq.gz
│   ├── e16e24ed2eaf18fa33a343be2947e3a309e1b36c.nq.gz
│   ├── e83645257af7de1f149b46dacf7f64c6fc467989.nq.gz
│   ├── ea4236fa931ad21924fb25e4d160955d071be849.nq.gz
│   ├── ea736164855d723d189a8b2f06ec9f278633a0d7.nq.gz
│   ├── eb38bf98d0eebf5236bd40ee46b008ace48a365a.nq.gz
│   ├── f4e29318d30d0bc89f27abaa2a9e202ab99245d9.nq.gz
│   ├── f57d467384aea14ffec9c595f6b2aea4876c1c0f.nq.gz
│   ├── f725f649f4222274432342468884c55fbb23a301.nq.gz
│   ├── f756c4403fa58e280b64bd2c9ba5c4f0702dda7f.nq.gz
│   ├── f8300dc1aea65ebd77722001dacbd29bdb5bd57d.nq.gz
│   ├── fe063c5120bc39446bd733f21cc7029fad081e50.nq.gz
│   └── fefb6d4def3dc467eea3680afa2d396f036ba581.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9f55f6a7fb225932da70c6e7dcd671c7e9a8929a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 102 files
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

[qdrant/skills](https://github.com/qdrant/skills)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
