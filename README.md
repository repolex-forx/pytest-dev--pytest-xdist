# Repolex Knowledge Graph of pytest-dev/pytest-xdist

RDF knowledge graph data for [pytest-dev/pytest-xdist](https://github.com/pytest-dev/pytest-xdist), parsed by [repolex](https://repolex.ai).

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
lexq download pytest-dev/pytest-xdist
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1e3e4dc16523c8a8f6c67d95a950166420718c99
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 1e3e4dc16523c8a8f6c67d95a950166420718c99.nq.gz
│   └── repolex
│       └── 1e3e4dc16523c8a8f6c67d95a950166420718c99
│           └── chunk-001.nq.gz
├── blob
│   ├── 0a01cb49fe55165ec899721d0624634b24600894.nq.gz
│   ├── 0a07b7123e41f4a49cfc6348d309f8fe406a860b.nq.gz
│   ├── 15c724930c2f02e7afce7dbacc0794023b2930ea.nq.gz
│   ├── 201c8e7143d22f39c21761181856b1b8f93e274c.nq.gz
│   ├── 2148a86774df6e233acc8abd1e76324ee0cb2b5f.nq.gz
│   ├── 22881fc75df749fc1fa441deb9c5688a8c8e8d06.nq.gz
│   ├── 23275362b244ffdb1013e99bbcb509617a05b241.nq.gz
│   ├── 268d18ba1e320185a1570854b178f4b307919366.nq.gz
│   ├── 2e9129c37e0f4293048530fab4c93a097aa1d3e3.nq.gz
│   ├── 2eb4d21d8672fa0cf4bdc6c55ea832aaa7c7d1a2.nq.gz
│   ├── 30cb11b57c9b3f616962b7b96c37a4d63c33e23c.nq.gz
│   ├── 38f1e6f172d9ea5aaf434151a84960ad7c4da2c5.nq.gz
│   ├── 42d5479d325ce078ef335a41d616f43106551d46.nq.gz
│   ├── 436b5ddf8b124e4a88fa59379b29527b53171d17.nq.gz
│   ├── 4afd1ebeb31b939b9aa4c2b1dd0a1c8a836a7968.nq.gz
│   ├── 4c32ed85eac8095a08ff445c3f094337672bbdcf.nq.gz
│   ├── 4d6617578f67c4f1f99a4c1aff5ade32be4253fb.nq.gz
│   ├── 4f33e0760ec8e62c2df109cfef48239127833bfd.nq.gz
│   ├── 550372eec0d6d3a9c66b8208fc637ba8541fd34b.nq.gz
│   ├── 56f6092fe5a53d74796e1bf0460d8649ec9e48fe.nq.gz
│   ├── 5bf7d9805eb838337ddd96d26354b98f1aa06671.nq.gz
│   ├── 5c629700de693133ac7733c788bac008c025b9e1.nq.gz
│   ├── 5f209f35cb4b9bb2024e9cf5b7d1efe617f375ff.nq.gz
│   ├── 649bcce0cf28ad6245fa67164af5c8b349e00a62.nq.gz
│   ├── 6782b19ea52a0633e54f3463be24665144e4ebb7.nq.gz
│   ├── 680b7ae039cb84555b446c17a7bad7a6e6335bb2.nq.gz
│   ├── 69fa449dd96e2405945b2e4cff2fd0ab8b102097.nq.gz
│   ├── 6dad018d5ae2e5ac1c0c40240aebe62f0106fdf1.nq.gz
│   ├── 6fe806f9a4df1d66814cde8d2a91cc0102f6f385.nq.gz
│   ├── 717e667927df8e29d832b64cc7ec31a328bb1016.nq.gz
│   ├── 78555b7ec72a584fda80fc45f443773d0571fff6.nq.gz
│   ├── 798c71289ab7edf58719bd6d92b7ee283d0ef4de.nq.gz
│   ├── 7ddb09955524797435c9846e485366430ec6041a.nq.gz
│   ├── 81543ab3db9ce0c769fa87ce518911b14ac532e8.nq.gz
│   ├── 81d9e873ff8bbcf712ed51b1c66627125eedeb4c.nq.gz
│   ├── 8c29d9d91edde92fab91ecc13d9fc15b24e373c3.nq.gz
│   ├── 9fb4a64da004d1a3efe13c5c62892ff94ecae5cb.nq.gz
│   ├── aa72ad0a88c470560c70165fad9ad4b095271fe9.nq.gz
│   ├── b3962e5f7b34abec0e8560a832adc1ccfa8c401c.nq.gz
│   ├── b3e8a1c766b2bc788e8f730380a40fc44d326969.nq.gz
│   ├── b4894732dc24666e99cd92a148c377a2160f0da0.nq.gz
│   ├── b504882bfaac7c21acc5a748306da0f3d9fa0c86.nq.gz
│   ├── b7dfe08bf51247ca8d4b0035ee82d076a9ee2ef4.nq.gz
│   ├── ba24295c076409b479542f12d74b11cdaf76b0de.nq.gz
│   ├── ba8d612176f4f11bce07613f657e62019442251a.nq.gz
│   ├── be006de9a1ae3b9628e796c74277cd6d61e0a34a.nq.gz
│   ├── bf9145197ace09d18803c1ce8440be4f5dd1a958.nq.gz
│   ├── c00a09765de58fc4fdc60e19e95c11c3d126bf4d.nq.gz
│   ├── c0843370a5d8dacb6897ddd9a1b28afd1cf408e9.nq.gz
│   ├── c78b25cc84bc083183fdffd512ea4608da464a8b.nq.gz
│   ├── cbf1e3658e6aa8a22988927b510080a973450f52.nq.gz
│   ├── cf8f6a2bc92297fc1843fe81b90dc7c2399f1194.nq.gz
│   ├── d1e1855aabf6d0ec602996be2bf445405f5af7ab.nq.gz
│   ├── db3840fd083c6f74b47bac5d0ab8fd4e8329e3d3.nq.gz
│   ├── e3a8ac6f825d4d0d72923d86bd0538dc09688c3d.nq.gz
│   ├── eda0ad123212e07ed4d082574031bb39e2c632fe.nq.gz
│   ├── ee0c59d51e51199ca5957c9999ac2ec59653e202.nq.gz
│   ├── fb6f027f0f4ae94ebb6dd24b55b4dccf87aae967.nq.gz
│   ├── fd272f9f1efe7bea3660863e0605d5b973838dc3.nq.gz
│   └── fe5038a199a6ff5b12b162b7ec590b9acf3ec2c9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 1e3e4dc16523c8a8f6c67d95a950166420718c99.nq.gz
├── filetree
│   └── 1e3e4dc16523c8a8f6c67d95a950166420718c99.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 70 files
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

[pytest-dev/pytest-xdist](https://github.com/pytest-dev/pytest-xdist)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
