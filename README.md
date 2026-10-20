# Repolex Knowledge Graph of klen/muffin

RDF knowledge graph data for [klen/muffin](https://github.com/klen/muffin), parsed by [repolex](https://repolex.ai).

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
rlex download klen/muffin
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 26b0d1edb3d383cd07b5280b529b86097c308416
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 26b0d1edb3d383cd07b5280b529b86097c308416
│           └── chunk-001.nq.gz
├── blob
│   ├── 080c7293fb1a2bbad20712ac8ff69f3573423c67.nq.gz
│   ├── 0a5d3245b04371289b71c4b289e28af66bb7e3fe.nq.gz
│   ├── 0a6ee958310ca78a98bf4803c291d5898c7fd5b4.nq.gz
│   ├── 12e81eed94afb8603e14bf3782885ed4d2bc7eff.nq.gz
│   ├── 19c6189bb94b083d240b5d5c5fdf7401bf2db43d.nq.gz
│   ├── 1ac84ca2b05494b9e9334270c7be3029f2535406.nq.gz
│   ├── 2133d32f5528633c3e2073ea9bde2cf931be08bb.nq.gz
│   ├── 23c5c150f58bdd129447223d88288e859f8cccb1.nq.gz
│   ├── 25a74bf0776c5cb489d138362b4b5002c89ee22d.nq.gz
│   ├── 262049792bd740a3d70923d540fa530680d5715b.nq.gz
│   ├── 27044fd332fb8eb2171293077ed92e5d02257735.nq.gz
│   ├── 2a1e5ffcd56f14f0c042c03f1ce963f432e7c926.nq.gz
│   ├── 2af58c678be9287a7e1b4c89eb0cc14665342143.nq.gz
│   ├── 2d2838d088e63ddd9a44357c3f7cd749cb4be945.nq.gz
│   ├── 43d9070458bed52352654914350c2f964139abc5.nq.gz
│   ├── 5cf7add5e2ddbdadd97aaa47d1fc622a9144079c.nq.gz
│   ├── 5f1d5686f3dc12105665875988bbe0b90d32c2bc.nq.gz
│   ├── 62b5a83a351c46222748d730981dc8f1916bc534.nq.gz
│   ├── 638e73f20a52bdb9767ae5cdfd379d2ea0d212bd.nq.gz
│   ├── 64a83dc65a3fed576d6a1cfd40921564a33efec2.nq.gz
│   ├── 666ce2a519fd8f0c3599a11f968422b82612ca92.nq.gz
│   ├── 67e2dea68cf9951a6958e48231fbd6af9e28805d.nq.gz
│   ├── 70aebee9033d8c40490a20db12c7ad9548235b26.nq.gz
│   ├── 71508ee2d40e0b7a08befc0f29632e157f3f6894.nq.gz
│   ├── 7353c541e62ac49b7d9ef9e7491a19f265bb9a17.nq.gz
│   ├── 76c6fd2515ca2128f513ffd617c0d688e7dc8a96.nq.gz
│   ├── 77b21e970732834c37ca22e9dd8175cb854efa39.nq.gz
│   ├── 78df056a6afd6b2f7c5a8695635380a19f30acd9.nq.gz
│   ├── 7a3f07ab83552f47a8705fa5d22729a324a2f71a.nq.gz
│   ├── 8cc77ae62ea7414f5089ce0cfdaacbe67dbca9f1.nq.gz
│   ├── 8e65d7c77126d2b031e32097b6bd76c2884b92b6.nq.gz
│   ├── 947b9a39aa23b2a4043fba39893f3fa3e430026c.nq.gz
│   ├── 9b1035dcca520cdbc0cccba2be17a0a3856d72d7.nq.gz
│   ├── a394a994b67f65d96024de45511078b2ae9ecb34.nq.gz
│   ├── a410da657683535d9bbaef51b7ef1a1069ba52e8.nq.gz
│   ├── a448309c06b9d99bfaee135e810f09169ac56a4c.nq.gz
│   ├── a6bbe07dc79e32063b2d64709c2a253b2b80432f.nq.gz
│   ├── b2ef62c890ba26b1cbd0ac7a70e64b6028b5f842.nq.gz
│   ├── b3fa847b36fb935ddfdfef1ec74bad0e6560b936.nq.gz
│   ├── b5af65097216d5f09d5d32e8f3fb762a1e77d35a.nq.gz
│   ├── b6fcf04f12ae5abe4b13b1eca80eaea7a44a5b0d.nq.gz
│   ├── b826280e8af863b5e4bba13b65d6edce89dd5078.nq.gz
│   ├── ba7cae361a5224cc85bdbf9c77eb4e241d2e7aaa.nq.gz
│   ├── bd56548ba341021036e3ccdc6a9c58300fc8aba0.nq.gz
│   ├── c16b430604ebd6669aaf682f95e32a2e19e56362.nq.gz
│   ├── c78b84295539c80b85e2ad7f5865b135945dbef8.nq.gz
│   ├── ce48f87110f5a00c4f3320f9ed0c8e630cb23daf.nq.gz
│   ├── cef77cd26a239e6fc6dd2e7f755e86e662b7ef37.nq.gz
│   ├── d09a5e8e77458b22d640ff71050235a260240f01.nq.gz
│   ├── d6ef4c32e16873df8f0995cca2480b1ff710edf0.nq.gz
│   ├── d7c2d8abe9efbf655869af553eeac82fb65ce285.nq.gz
│   ├── d87ca373d8cc668e6f9368d840f9ae4a4db758a2.nq.gz
│   ├── d944c090ccb928a22f4a09568fea806548f1f4af.nq.gz
│   ├── ddf90b120e5564599d78c49f90c7b2eed1e37bc3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e728d03676c20ba87a39556e60b642f5df17ebde.nq.gz
│   ├── e947bc4d63432b48f6b15b7caba60653b0ac383f.nq.gz
│   ├── f39e7175d8fcbb5bf58b7d090888cc1983521a5c.nq.gz
│   ├── f9d7ca4a44a16bf208beaa07f2363074d7cefd3d.nq.gz
│   ├── fdfc925921b2bf02fcc397022a102e44f54510b8.nq.gz
│   └── ffa862ee6e9ca07be81e56f6e6134875959690c3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 26b0d1edb3d383cd07b5280b529b86097c308416.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 69 files
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

[klen/muffin](https://github.com/klen/muffin)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
