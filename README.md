# Repolex Knowledge Graph of zopefoundation/AccessControl

RDF knowledge graph data for [zopefoundation/AccessControl](https://github.com/zopefoundation/AccessControl), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/AccessControl
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5746fe62282eede0279cde81fd1a75258fe07153
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5746fe62282eede0279cde81fd1a75258fe07153
│           └── chunk-001.nq.gz
├── blob
│   ├── 02df44cfe01c6403cf7e39e3225fd2bc74b8e8dc.nq.gz
│   ├── 05bfbad21720921be78dadf8b55c0ff1cbbe7eac.nq.gz
│   ├── 0982226c7610a2820b6d633e8336c141f8d8bfb2.nq.gz
│   ├── 0da07afab9c1643506ff56ed868fcda75b96f726.nq.gz
│   ├── 0ede738ebaf95494c9080544cee4feb7532f49c2.nq.gz
│   ├── 13df7380e1eca46ccbe3e8a258aeb79cf243bc47.nq.gz
│   ├── 22c85ba388bbca5f6ed48f69bcf44572b8bbb01f.nq.gz
│   ├── 22f761db96297c20ba356045d68593f38f229699.nq.gz
│   ├── 2764462d39afaf92550582bf5c6edf2f0df07c2d.nq.gz
│   ├── 2ef46c48e943cbd5b2ba355ca8f116d46922a005.nq.gz
│   ├── 380391cc3ec1e1155ebceefeab9e3c3235984f3b.nq.gz
│   ├── 3d7879e9b756217ff46d9d2fdefc5d26d0a82acb.nq.gz
│   ├── 3dada1dcf8600e36f0d1e663cd649d5cb88a8875.nq.gz
│   ├── 47421262ebc35cc06fddc450a01e837b32cb7bb2.nq.gz
│   ├── 4ab33c4bb433b4ef7e65d0d5d14840aaceb62a55.nq.gz
│   ├── 4b7e84d4189385d5b6e4f9f483836836c7d6b1e7.nq.gz
│   ├── 4c7ee09d0b16b76aba13bbc262d8279431ca8c9c.nq.gz
│   ├── 4dd702820227c839516f01fb65df2739445e1f20.nq.gz
│   ├── 4e99c3301d98f14d71ba271a343414be30c2bbd2.nq.gz
│   ├── 5239dad893061a28030f59c1c2cf15e7b6b3d29b.nq.gz
│   ├── 566b18bdc5c5a80e4cc51de61ddeb0c442d13579.nq.gz
│   ├── 57dd8a4bfaa6a6926253e3211fd3d37aeb9dc274.nq.gz
│   ├── 580a5fa31fa35052e0704a2b48e0a8f72a89713c.nq.gz
│   ├── 61283680b6c03adde007136e66a1916f47b87028.nq.gz
│   ├── 6132f81aa3a898c96efa5daa11f062cb3bed4d33.nq.gz
│   ├── 618cfc8367624862472eac129c1ecdc99fef6b6c.nq.gz
│   ├── 628086ef253dbf44de51f2c30c1c178298b77d3e.nq.gz
│   ├── 63442baf68fd373dcc3c559e2f28a7e2d4aa8f9b.nq.gz
│   ├── 6402f43936b36dbb2c7163f61201f8d6b326e49e.nq.gz
│   ├── 654694824701aa650c209dc7d2e81293181e2b88.nq.gz
│   ├── 67132276500ed4b68aee1d7e6f7cb8192a3f95c7.nq.gz
│   ├── 686787459aa2496e08a1f5560a071f21e4e008f3.nq.gz
│   ├── 6e5d4c940902a8cb6593502192ed8101dbf28be6.nq.gz
│   ├── 708733016655a2bfcc36f0a942e8a6a77f32cf30.nq.gz
│   ├── 71d0902ed3b2575ba4fafb147903ed3fb76d2506.nq.gz
│   ├── 74b95fee1c8a8126cc98c262e5c3a734d3a87de8.nq.gz
│   ├── 77f3c744e601e8cdd746df3914bf9c9c8ea5365f.nq.gz
│   ├── 78609a5f5a06dd7d09bef2926810c672a193b0a1.nq.gz
│   ├── 795cb1def5c0927608fea84a7b9524e004b95174.nq.gz
│   ├── 7fe116c7a76e5cd418bb8da0891b5e940f0b5e17.nq.gz
│   ├── 807ff92b29d4ef5b8a379dac730e2dbe1633a3f2.nq.gz
│   ├── 837394366fd11c9e8d7d3e15afb25aba5ac88150.nq.gz
│   ├── 84df4d0fb1c384afdd817eed530d2c31ecf396e8.nq.gz
│   ├── 8b239f984195a26a37a8439f251e555461d881c9.nq.gz
│   ├── 8dba73ecd79d75419bde8f8840d614b06b7a6954.nq.gz
│   ├── 8efcf986de665a59fce4eba356f223ae6d9c0b63.nq.gz
│   ├── 8f3c8090f101aab96b2ce648af617bf5238489af.nq.gz
│   ├── 9306037c54793c5985cf754a16f884e5afaf6217.nq.gz
│   ├── 956bc73ac0c33bf7e493ba1007ce42fc5cff3cc4.nq.gz
│   ├── 99099739c67366b2edf8d4b8c1c1ac18eeda90aa.nq.gz
│   ├── 9ba055b2e770cdab4c687a002d49752970961f7e.nq.gz
│   ├── 9cfa95841824426075c456348bc6bb4d5d73da78.nq.gz
│   ├── 9d412a59d8cb0670322f68a6b1fb67937d993d9f.nq.gz
│   ├── 9eea54b1658e7c85847d0fca9d2649c108f2e292.nq.gz
│   ├── a999d1e6f51abedd32909b164e4eac5a27836201.nq.gz
│   ├── b22bf3a58c6831eb990fc7970244a9bce5c2da40.nq.gz
│   ├── b3cd900eb95612b7f221a59769d59b1b65d012e3.nq.gz
│   ├── b71e5362d5fa568cac8c9044c243cc0dbe1a1608.nq.gz
│   ├── b8581dd898cbb33e63961b4d181ff0ffbe5d03ee.nq.gz
│   ├── b91200b82612646b89be31c296c4fa927d1dd18b.nq.gz
│   ├── bab7f94be5ef86cce49612e6cdab326a57143d7d.nq.gz
│   ├── c21d9ce0ffa4a75f72f46643a8857c16e51e366a.nq.gz
│   ├── c3ce272aeb53d1ff83c27c15a580010b6f202ad5.nq.gz
│   ├── ca2fe356fb51c7e1ea1e129921a62fe9af23dd06.nq.gz
│   ├── ca62e9fd049eeac7c52c3af68884071473b0bbb9.nq.gz
│   ├── cea710d47098eb22b822f0fd2dcd60510e08fa36.nq.gz
│   ├── d0ea9e50454f5ac0f7979db3e7c18a53d9a3da93.nq.gz
│   ├── d0f6dc19b5b19c3d3c3a4c8a8835592ae247d314.nq.gz
│   ├── d656661e9c05895b03e31f73a5dca68b0980e719.nq.gz
│   ├── d82dcc82b80812f950b4e02ea03e9fd05c833e73.nq.gz
│   ├── df28ec59316075a44bd020485968c138e72f3c06.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e4af414cee29477f98fe4f6da65c2450aa83ad10.nq.gz
│   ├── e62eec2685820226d926dae3ba92518b526a522e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6c6817ecb7b4bc08d67578b68672e048c72dea6.nq.gz
│   ├── e77b1b4f316b7f7123b1d062fe76714fe4950b47.nq.gz
│   ├── e8d4450ca80e3f49076063981781c6ebbf1025b2.nq.gz
│   ├── e9dec1571c89c3e1a3b9ed4082de57218059adf9.nq.gz
│   ├── ea5899f675174898cd75c9b01034a8b600a2e481.nq.gz
│   ├── eaebff21545e82a07a675d814fc49b768adda82e.nq.gz
│   ├── eb1a52057974fe6fac0fe15cf78b831750e26345.nq.gz
│   ├── ec366595459ca9ea3ebb11cd95aa867a7482aaef.nq.gz
│   ├── efb841e84e6cccd66bda871e781a40832cadde3a.nq.gz
│   ├── f391fe6d1de75931909df2b246b1cf436e3fd266.nq.gz
│   ├── fac99a181538e30bf9ccf6f22203ac4ba0c7e656.nq.gz
│   ├── fd933341a560a3bb57987535acab063268cbdcbf.nq.gz
│   └── ffee6a163301e8ce55668b2a9bbe412f51a594fd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5746fe62282eede0279cde81fd1a75258fe07153.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 96 files
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

[zopefoundation/AccessControl](https://github.com/zopefoundation/AccessControl)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
