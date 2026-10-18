# Repolex Knowledge Graph of gabrielfalcao/HTTPretty

RDF knowledge graph data for [gabrielfalcao/HTTPretty](https://github.com/gabrielfalcao/HTTPretty), parsed by [repolex](https://repolex.ai).

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
rlex download gabrielfalcao/HTTPretty
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f9f012711597634d40066d144a36888b3addcc46
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f9f012711597634d40066d144a36888b3addcc46
│           └── chunk-001.nq.gz
├── blob
│   ├── 036b795d05bb5802b96af3c9b5d03a8bf6b74598.nq.gz
│   ├── 0653b41c887d6b37ade0fb09007543a940162b17.nq.gz
│   ├── 08eeb362df43d9c7405a5f67ebd4a5bc30b73cdf.nq.gz
│   ├── 0f75935a050efeb85e7c04c2fe435a483dc02e25.nq.gz
│   ├── 149c6c6ecb4f2c94d1cbe3ab7a0ff456769cd853.nq.gz
│   ├── 16ca34c1652e45a21ff2fdc0a961bea4e987b532.nq.gz
│   ├── 1986fa6772f1e35256696de4cf1bb664aeca7ad3.nq.gz
│   ├── 1ad66618e54077f6192d003363cee7450964fcf2.nq.gz
│   ├── 1b47afb3b4209eabf5b1c1ccf85f2f098abcd373.nq.gz
│   ├── 1b809baab7d59e3cf52b1544ea3c716b13744d8f.nq.gz
│   ├── 1eef307ea8f15a3d3deb452aef86f18d65b46d6b.nq.gz
│   ├── 2131f7fd7c75ef9bda90587f6690ce80e984f0b2.nq.gz
│   ├── 25a58a93de9727ccc025cb837e27568ca129f9cb.nq.gz
│   ├── 29295aedbe2c7eb6fd312b5aef25d72d0ed0641d.nq.gz
│   ├── 2f34b3236fa06299c7a7ab4fb55bfb2273e14b1a.nq.gz
│   ├── 35a7b7d16af809d36a8885c641124991fadc2635.nq.gz
│   ├── 39d914b094cb9502eabcb969cdaf44b32aa9df98.nq.gz
│   ├── 3a606017423f9fe11b6ac3c4cd4ba7a9f2a8aba6.nq.gz
│   ├── 47c9e799d103f9310525e4d5ef41b548e2719ece.nq.gz
│   ├── 52aea0a91b337652ed7f6f2b54e5ef61acbc5b42.nq.gz
│   ├── 55aa109d46a64c410d77448716c185e36e4fce39.nq.gz
│   ├── 59e668e2404be63a6cf791705f6e6ca8377a8005.nq.gz
│   ├── 5a016abab4fb7d0769dfcdebb82ed5ed88185140.nq.gz
│   ├── 5c6fe20d2598a10169a1c82ebea6ab1d3ec29c8b.nq.gz
│   ├── 5e7d01fca5c7790afed0c8e4b4ac478f3b0986d1.nq.gz
│   ├── 623dd88432da57fe52398f7079e9a2758bb5b1b6.nq.gz
│   ├── 634924039384a33c3768759dfa2864e0f0f2ec21.nq.gz
│   ├── 67c2416004de1f8b3044d2b4edb811274d24c956.nq.gz
│   ├── 69686458b0b939edec4fe0285ec11210095b1d55.nq.gz
│   ├── 6e26bca41d5ddffc72f3d9780ee90f95e2e8279e.nq.gz
│   ├── 71fe992bf52a2e4599cd862d39e3cbe555c069ac.nq.gz
│   ├── 72578c876831cdab3e525ab7bf843902f7e6dcbb.nq.gz
│   ├── 72fc3fe8ddd5f36f72517cc1c8e9811082a17abe.nq.gz
│   ├── 750a3fc6886fe86b869ca2b1541b289a284a51d6.nq.gz
│   ├── 7b31d6122c718380602857b87a3d55321a24b59b.nq.gz
│   ├── 7d2ecee90fa2b5eb0d60dc2aa1034ca63a330af5.nq.gz
│   ├── 7ea5fe1d5a65b7e3f9ff860244558721b9b4b585.nq.gz
│   ├── 80c4a86eb78ae3a7371f805651f26a5adc341e54.nq.gz
│   ├── 82cb2b90ee90fbc8b710ecea4ae082d5ab7534e3.nq.gz
│   ├── 86bf09e774f3442b05d518da690769c94205a047.nq.gz
│   ├── 879decdb314c49db63831abd3f791dbfa0584b06.nq.gz
│   ├── 889b87175d6fca6d98152282a270ba727c297c4b.nq.gz
│   ├── 89b2abf2dee60ed8b50bdc92267248fe1bb902a2.nq.gz
│   ├── 8a6c903371d27e748f2757eb6bd733c5e0644738.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8db807b2fd8eeaf08c7b96d770b192640b9bf701.nq.gz
│   ├── 8fae09c248125e50ea436007ad82670d8aacb728.nq.gz
│   ├── 90474651e4192fc6b6697cdb5b590cfcb39e4ae9.nq.gz
│   ├── 90b40c2770d9128df8066c6eeecccebc0d7c322d.nq.gz
│   ├── 99d390b39921888f9cbf635d14f6d6428f2f0440.nq.gz
│   ├── 9c8ff39fe1647adc6ef68c0b573eeaab24fa1b1d.nq.gz
│   ├── 9ca9f9ad882109e6412c3187714fd7459249e1bf.nq.gz
│   ├── a5339d22dc9f264130af742bfe125d4cd5379dc1.nq.gz
│   ├── a8f551c771f53c318caed698cc8a94f592ec3374.nq.gz
│   ├── a9eab2a2d510a488cba71005b0e850a6af8f0f5e.nq.gz
│   ├── b38f578d8b28281d045a56f93714ff98204c09ae.nq.gz
│   ├── c1386ca08c016a1d0e1f0bea9036a36eed08d429.nq.gz
│   ├── c2a30a6cd4596c52b0ce4d8574a3caa4f5307660.nq.gz
│   ├── c3f90cde6933c8d89405312c204ce8aae980fe96.nq.gz
│   ├── c913d8a8b2bc76c1fa5c84344bee89dabfb24c79.nq.gz
│   ├── ccb409424c988cfdf67c9966df6979e59a309838.nq.gz
│   ├── cf144d4a9d496beac779b7adb0c56ee1dcb256bd.nq.gz
│   ├── d1f156a814d286d3845648ff726072eeaebc0817.nq.gz
│   ├── def2c55627119688f452f99269b65ef82083533c.nq.gz
│   ├── e53007b57b4e40c709116eb401141a22d11d6278.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7328a4c69348ec914031f95f44ac170e135a20e.nq.gz
│   ├── e85dfac2b11ff2072d3bc3b9f54393d1d657c922.nq.gz
│   ├── f21a5468715a23892854eb092c17e2f5268171ea.nq.gz
│   ├── f45d8f110c3034162a1091dafe4b03d2e56b323e.nq.gz
│   ├── f98b102bd6625e4dcdc91f5d7c2483dced6e26ba.nq.gz
│   └── ff8b756bf9ed8ae90c9ad8254b11d4d7ab757061.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f9f012711597634d40066d144a36888b3addcc46.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 80 files
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

[gabrielfalcao/HTTPretty](https://github.com/gabrielfalcao/HTTPretty)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
