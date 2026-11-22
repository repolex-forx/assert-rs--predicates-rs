# Repolex Knowledge Graph of assert-rs/predicates-rs

RDF knowledge graph data for [assert-rs/predicates-rs](https://github.com/assert-rs/predicates-rs), parsed by [repolex](https://repolex.ai).

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
rlex download assert-rs/predicates-rs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f54f2cd016a1df6c88a022c867e3ee04c70f9a3a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── f54f2cd016a1df6c88a022c867e3ee04c70f9a3a.nq.gz
│   └── repolex
│       └── f54f2cd016a1df6c88a022c867e3ee04c70f9a3a
│           └── chunk-001.nq.gz
├── blob
│   ├── 03b69b21c380422fad4776c27607b7b9b87dbc5f.nq.gz
│   ├── 062766afd94913284f13640128c68b293014a996.nq.gz
│   ├── 0a362dc7ac9f644d54d0626bf972493ab5787a38.nq.gz
│   ├── 0e56b3859f4f3cbd15f92acb1a36673467d07215.nq.gz
│   ├── 121f757ad7cf07766de8af98bd20bebe2d8a097a.nq.gz
│   ├── 1d4c5dc66f4e229b407587965d09da9816e06eac.nq.gz
│   ├── 1d4fd850696ddf8d3d0b9e3387d47cb7cf8c66e4.nq.gz
│   ├── 22291ea0bdf5cfefb9a6e2f963e9d158ccac670c.nq.gz
│   ├── 254656c514b175b364d11fbd2201f3c0138a6530.nq.gz
│   ├── 27bf59a884cdc6948c686a9eb9b3f0fe99691c95.nq.gz
│   ├── 2e473d9a071fcc21935e4e073031afb6cd025661.nq.gz
│   ├── 343a9c16a2e239c74d88a2f297c0ae5317628b39.nq.gz
│   ├── 3baae44354394b3e08a4d65294608c59fdf227f0.nq.gz
│   ├── 4211ae3842810ba7207dfc2148a5354e28276bda.nq.gz
│   ├── 4a6a1abdd612113aea698f0f51e28cb675ea8ead.nq.gz
│   ├── 4c2305c7a91c6ac2bb9d23cab3f0e832855188d2.nq.gz
│   ├── 5e254de27f3ff8bd540b3d5e734b2bc6ef6d3d63.nq.gz
│   ├── 65991173c4d18bacaf49aae24a2d4d1faaf46cac.nq.gz
│   ├── 67c10aa2ea645cd0d1b781814293ce7db40da1e2.nq.gz
│   ├── 68ca312f297b95570e6ee63deec561566f90ed20.nq.gz
│   ├── 6a65733e3946a78990f43b98a1603c933d7f636f.nq.gz
│   ├── 6c8d17ad0a9082cddc08d26c916258606e7f0096.nq.gz
│   ├── 6e0a8a0cbca41af647aab2f240e907c376763886.nq.gz
│   ├── 6fac3b4dead711f74676225185568d333b4b7b3e.nq.gz
│   ├── 70fc8932b86a081eee61d7b04d16dd90a0653387.nq.gz
│   ├── 76c3377d5420cce9ab7161901a196c5c8005b67c.nq.gz
│   ├── 79cbb86643b01155aaccb4b28861b00698f060da.nq.gz
│   ├── 7ecdde67b709c86d0662edb015a06bf507b96027.nq.gz
│   ├── 85351edbee92b01ba612718fe93fb61d80c278a8.nq.gz
│   ├── 8c0ed9a03b2735518bfb528704456e6291407898.nq.gz
│   ├── 8cfd4474bd8daea837df82952ff7a9a1b1dcbc76.nq.gz
│   ├── 8f71f43fee3f78649d238238cbde51e6d7055c82.nq.gz
│   ├── 90b2ed819d85103714e47187a6ed8ebec283ccd0.nq.gz
│   ├── 9138a8e3fc824971be7888ef3eaa8074095cd94d.nq.gz
│   ├── 96856bc30e5667d823586db731b482804a9f5816.nq.gz
│   ├── 98a7546d598b194b6d7ac3777e5730f3f7309052.nq.gz
│   ├── 98bbe0b86f8c55f2e81f81f23f70f7d33375e732.nq.gz
│   ├── 99740e81dddbd0a27d2532f9f0fa63cfd5aab76f.nq.gz
│   ├── 9ca9671a0eb7d557c5eeb569723837914d827870.nq.gz
│   ├── 9f76fbc70f2085601741ff9df81b9b68f759fe2c.nq.gz
│   ├── a2d01088b6ce55e837a6d193943580f978fb2d2e.nq.gz
│   ├── a3d44b7a65f89d00626130a376fe2a31e434ae5f.nq.gz
│   ├── a4429a46bb62b7eaece76f407cff66de72ea6d2d.nq.gz
│   ├── a730f14fc397fc8dcb7966a02d26e2c7cd14b393.nq.gz
│   ├── abb46f8216f71f4b4ea85f19d47d8a73441ee58e.nq.gz
│   ├── ac79613ade0db9b9e8d2e088a239363e35cd4496.nq.gz
│   ├── acc35e01a69c9ef453383ce0e8c8c3520bd1c02e.nq.gz
│   ├── b216ac77d3e05bc24143c8efafa5a540015a5653.nq.gz
│   ├── b5aaa7bcc729fccb6619fcb251bd9fab22153029.nq.gz
│   ├── bcb92c74b6b8a96841b9980141898e4048ebc668.nq.gz
│   ├── bf961bd056c741131ee25a3b86586433466fd644.nq.gz
│   ├── c57eff55ebc0c54973903af5f72bac72762cf4f4.nq.gz
│   ├── cc1fefc3b51896c4f83c75763ca9a55776dcdb53.nq.gz
│   ├── cf4c1bfb053c86eeb9a1dcf27051f14bdee9f5ec.nq.gz
│   ├── d204145b126a2d03d9bc17d91b8abee2a3c8ee89.nq.gz
│   ├── dac7b6ba400d86429e955948bc60234f027ad1fa.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6eecaaccf3a84831a4baf5db03e18291e19280e.nq.gz
│   ├── ea42d6c007d112082f78de8d9a9cd63a62163abb.nq.gz
│   ├── ea9e4803620f62e52884289d8392dd8493fb2a86.nq.gz
│   ├── eb5a316cbd195d26e3f768c7dd8e1b47299e17f8.nq.gz
│   ├── eec09f78b373dded950b2d56e70929bec9370af5.nq.gz
│   ├── f1b6a2139a1e2d57821357587c01ba0eff7a1007.nq.gz
│   └── f74b710a6b8371dc94c8995e1d49f508c23754d1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── f54f2cd016a1df6c88a022c867e3ee04c70f9a3a.nq.gz
├── filetree
│   └── f54f2cd016a1df6c88a022c867e3ee04c70f9a3a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 74 files
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

[assert-rs/predicates-rs](https://github.com/assert-rs/predicates-rs)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
