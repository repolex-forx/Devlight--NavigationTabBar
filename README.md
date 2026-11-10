# Repolex Knowledge Graph of Devlight/NavigationTabBar

RDF knowledge graph data for [Devlight/NavigationTabBar](https://github.com/Devlight/NavigationTabBar), parsed by [repolex](https://repolex.ai).

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
rlex download Devlight/NavigationTabBar
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bd5d779548a002af24daf8c8a2b0cf0ee91531e4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bd5d779548a002af24daf8c8a2b0cf0ee91531e4
│           └── chunk-001.nq.gz
├── blob
│   ├── 04d0b4714193f59bb976ec727c85af474ea19eef.nq.gz
│   ├── 0b39aa9e9adc1f74020619567c820a8c94c2aefb.nq.gz
│   ├── 0f3dbd3675add51052ff3806650fa0c26e8953a7.nq.gz
│   ├── 146f0179d03f93b9726e6219be0cbc3b53462996.nq.gz
│   ├── 1d3591c8a4c9c29578c36c87f80c05a6aea3ee3f.nq.gz
│   ├── 245df8faea619c2b0951d9504ed0dd05b8f5e560.nq.gz
│   ├── 29f3fb5cd7b9880bdec867e7a38b2a8c0f7ad9af.nq.gz
│   ├── 324e72cdd7480cb983fa1bcc7ce686e51ef87fe7.nq.gz
│   ├── 3655967f94cfbabef263b2222bb12a675f4122c3.nq.gz
│   ├── 3c4280a1a13c9c0172ef21f4ed1d040e7aefd551.nq.gz
│   ├── 3d598323aeabf7a43ac998c49416c54da890023e.nq.gz
│   ├── 42818b7fca113bc558af88a311a055454babc36e.nq.gz
│   ├── 4d15c4cf0f494b2432c24c79199c115e948d7ae4.nq.gz
│   ├── 4db31380934c4576e7bd2211295b9ac7070cd952.nq.gz
│   ├── 50fbc839e8420d28cd95a1dd0622af1a9cf0e156.nq.gz
│   ├── 58b66e9729bd3f07c07358ae199c40dbf2927106.nq.gz
│   ├── 5cd42af2c11e28248ded40ffcbc061acf5205884.nq.gz
│   ├── 5d72919a92e34b975254fdfc97f63b0d522446bf.nq.gz
│   ├── 5f9bae98c46f4da8b3c4133e41feddcb200da738.nq.gz
│   ├── 68997ed3994e4830dc30c2a63e05963ca3b64c1f.nq.gz
│   ├── 69bfa212627c104f722990b6d6a6ab7f96bebbbf.nq.gz
│   ├── 6c5d7ef824cfcf611b48bccf20031b47c9a04090.nq.gz
│   ├── 6d5185635a623090a0a12f580fa101b4acbfbc92.nq.gz
│   ├── 796b96d1c402326528b4ba3c12ee9d92d0e212e9.nq.gz
│   ├── 7c4a02711a479c61fdc8bbec307f5538ef7b467b.nq.gz
│   ├── 868f2f8b88d3110ee20edcffbf0955cd89ace03a.nq.gz
│   ├── 86fdb58d2a5125d729cfc712b8d464b7fcbada39.nq.gz
│   ├── 8a0b282aa6885fb573c106b3551f7275c5f17e8e.nq.gz
│   ├── 8a3787b93d6aee61dff48bb195e9ea395ca18e97.nq.gz
│   ├── 8b58e64952f1481ba04c1efa4dc62648166f15de.nq.gz
│   ├── 8c0fb64a8698b08ecc4158d828ca593c4928e9dd.nq.gz
│   ├── 9072f5bdec787dcaf8ee7d61692dd4ebc9c2b8d5.nq.gz
│   ├── 91a7e269e19dfc62e27137a0b57ef3e430cee4fd.nq.gz
│   ├── 927295d2615da6629a9b48428a3398ef7dd61212.nq.gz
│   ├── 9474696b22bfdf5b1492c7e24298c949bba5709f.nq.gz
│   ├── 95fd221e9ab2a7871276ecf643079c7a5dee48b7.nq.gz
│   ├── 9e16a6644a5dccd093f6d52f1ee9ccf0fc5095f4.nq.gz
│   ├── a6f83fa94c074b03e6cd56ec9b4e103ca1defc45.nq.gz
│   ├── a838af1091d8705d58576651a542b98337900f8d.nq.gz
│   ├── aee44e138434630332d88b1680f33c4b24c70ab3.nq.gz
│   ├── bae526b8a28b4b34f5174e87923a04fb62dc59b9.nq.gz
│   ├── be81656b0116691164a52b78b42543346f4c4df8.nq.gz
│   ├── bfa42f0e7b91d006d22352c9ff2f134e504e3c1d.nq.gz
│   ├── c02fef5b11561acb71e89b52d637848ae24cbcdc.nq.gz
│   ├── c0401d52bfae0720341a361d689b8a6c08e07762.nq.gz
│   ├── c12ca218ece8c996b19222536a363771636a5d48.nq.gz
│   ├── c133a0cbd379f5af6dbf1a899a0293ca5eccfad0.nq.gz
│   ├── c88a4b6359606ed0d8e7d238d8e58541042ab9a5.nq.gz
│   ├── cde69bcccec65160d92116f20ffce4fce0b5245c.nq.gz
│   ├── d3798512ae6c43999236593540a0b5ad8c41e3c9.nq.gz
│   ├── d6187b771827eec65f7506936911a2eeba295a7b.nq.gz
│   ├── e27b1349129d1501cd406a8f2ff9b87496bfcfad.nq.gz
│   ├── e3392b1f63bfb383da0670162c7b718c65b7dcd4.nq.gz
│   ├── e9eb9232828761374ab0d106b8df5ca9f02e5b19.nq.gz
│   ├── ee9857b319d2fb03e62c420b9bbdadafba90a1a4.nq.gz
│   ├── f0f7e95507e6c0c86bef69dd13b220ceca7bcee8.nq.gz
│   └── fef301f54baa75f58c6034ee0c8c94ed3839c37f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bd5d779548a002af24daf8c8a2b0cf0ee91531e4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 65 files
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

[Devlight/NavigationTabBar](https://github.com/Devlight/NavigationTabBar)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
