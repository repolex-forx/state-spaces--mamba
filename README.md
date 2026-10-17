# Repolex Knowledge Graph of state-spaces/mamba

RDF knowledge graph data for [state-spaces/mamba](https://github.com/state-spaces/mamba), parsed by [repolex](https://repolex.ai).

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
rlex download state-spaces/mamba
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e9594ce1c732d97440f0332fdc43170a2294dbfa
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e9594ce1c732d97440f0332fdc43170a2294dbfa
│           └── chunk-001.nq.gz
├── blob
│   ├── 015e2a0eff633daf2693e43a2648008652a38c7c.nq.gz
│   ├── 0279f8fee9f724c37ca469c7144b823f20d5c4dc.nq.gz
│   ├── 041db8eb4c24ef83494a48cbc0f108e2ec6ef74e.nq.gz
│   ├── 04440f407b27dea62e8714a85193ea2b70ec0696.nq.gz
│   ├── 04871814ae59ea2ce23893b841ca26bb8df92db3.nq.gz
│   ├── 08d172b7871b459ff535d69efca9d8296bb11e97.nq.gz
│   ├── 0d40e9dc6a284a504c1fb74969301de754a342a0.nq.gz
│   ├── 0d7555acddbd260636d1d14d5bd6324f6af0056a.nq.gz
│   ├── 0f7d02759055d19d71ea9724393fa7fd62867b1f.nq.gz
│   ├── 165a01bc53f68e55d092325f0d0ae4ed5a9a8753.nq.gz
│   ├── 19676c76b7f2b1d34536810e2568acb3325dd526.nq.gz
│   ├── 1b30f75f2fda9507f20fa99024ecc9bc875a6137.nq.gz
│   ├── 1b588ce2c53bb6e9a29fb9600ea7cddb0df326b0.nq.gz
│   ├── 1bd968a0bf20668bb312f9b7981529cf5c915471.nq.gz
│   ├── 1c64ebd9816ef6a91ae1cd934a8f53b8e6c0536e.nq.gz
│   ├── 20f619f2334fdef4ebf5de6b1d51a5ace102904d.nq.gz
│   ├── 271b7b15b3e0046cf2dbc93c0df28198c99bd528.nq.gz
│   ├── 29fc07977f0e276a4e41d34481e489d809050b53.nq.gz
│   ├── 2aa92d78987f18c325f74c447040cd21d44d5ed3.nq.gz
│   ├── 2b8615b1d522c119125d4cb6ff3dce42f2bd4659.nq.gz
│   ├── 2d67b5304efe87b9309b5321af0e97bcce4907bf.nq.gz
│   ├── 2fbde0a2fd607643df2b72e369a02cde5f58e6a2.nq.gz
│   ├── 318499d570a7e3674a6649ef2310952206aa9e44.nq.gz
│   ├── 33bab5c7cc21b96d5f5ccfe233e339cad12cfe2c.nq.gz
│   ├── 34c119c2cd9052e82bd80d791afd1508285fa3be.nq.gz
│   ├── 35908b261f0480a1c82d58e395f16f2545e8441f.nq.gz
│   ├── 36b16d4715ed2d753697167d65da5e6abba22017.nq.gz
│   ├── 37df47c8e96cd730b9fbdbe152a55327b09d2f9d.nq.gz
│   ├── 38557a872f8d603ed963a05c211de7032de5926b.nq.gz
│   ├── 3897018db0c5947a12887512ac65246c6faedcad.nq.gz
│   ├── 3e61f298da73104717be9b03da24eb3be08a60c4.nq.gz
│   ├── 3ff271b50eaff208ae33c16c87ab7aaee76dfd76.nq.gz
│   ├── 4a2fb49f607409d326dde92399aa17ef4c72d3e8.nq.gz
│   ├── 4c8a388217c4cd4d21d5ea4704a5d571be294781.nq.gz
│   ├── 5363efaa255b8558cb79ddb685ec9a985584aa34.nq.gz
│   ├── 55408c89c38f7c680dcba562db40c5461b8258a2.nq.gz
│   ├── 5541655c6616032a484c1e567f94a65cd6e4c88b.nq.gz
│   ├── 5554902342785b289b81c060a71a51734fc1e6bf.nq.gz
│   ├── 580001b8e25cc6f98aba461e800a93fa7bb2e540.nq.gz
│   ├── 5de93aea766d3c5f45a2eff0272c3e51a16b265c.nq.gz
│   ├── 61416552307f4d136650447ee70a06467017edba.nq.gz
│   ├── 62ba279e7d3a0d71ddfc927519b6d35bd49473b3.nq.gz
│   ├── 630806a6f09fa2c781a59ee215e55acaca70dd3b.nq.gz
│   ├── 646c9e1e8ac94b2e82974cc0d5dab83fcfea900c.nq.gz
│   ├── 69b109a8eed4e3c7516b23e2b39d37e842a4464b.nq.gz
│   ├── 6ac41179b9ffb19714e9d57b590323745758fabe.nq.gz
│   ├── 7279eda98e4324f1587e8a36c5129cb489923b80.nq.gz
│   ├── 72adaf5cb13c6429e2f345a0a823c6bc3722b95a.nq.gz
│   ├── 74c55279645cd0fd687584bc1b7374c8c3c73e56.nq.gz
│   ├── 75d5217b753259acba5239dea07a5971b669904a.nq.gz
│   ├── 77a6af28e9f4630c482aa2c108c74f5d1dad1040.nq.gz
│   ├── 7920ac045d0a2a1f4c4159ee3eebe51fe1e2c203.nq.gz
│   ├── 8a834b3c93267d05f81c3e5156b35622a3c2d956.nq.gz
│   ├── 91328e913ae816c1dd718fce6adcdfcf5cff8437.nq.gz
│   ├── 94760ecf420bd0bac388e8af162fb72617c7a855.nq.gz
│   ├── 9632ebd4350fa18ddc977c2bdedb0bab1fd82646.nq.gz
│   ├── 978f3ea4d8f1c962303b5cb6d8388c2289c4f7db.nq.gz
│   ├── 9e17601f2ea377b577d9573600fa352732ed87d6.nq.gz
│   ├── a7445800fb64f3ae664c0b994a54235105986d2e.nq.gz
│   ├── a7ed642231da80c455c0499702cc8a1cb4536ec2.nq.gz
│   ├── a8a0c17e6536e63496b57a16fbf6f92e3328ebe4.nq.gz
│   ├── a97588e6f0f069e2ceb0b80ff88f8e1ba208b977.nq.gz
│   ├── aabbda1f4949ea63aaf5496bfa55df87b7024461.nq.gz
│   ├── af95537b9121288a7c80b33f20d990e20ad9604a.nq.gz
│   ├── b178f48f99c5914436f33056796000558dd87e8a.nq.gz
│   ├── b516fb8acc5159964cef5e4861c2e595b96c1e33.nq.gz
│   ├── be82d1635ffb31cf838d55db28822124cee69665.nq.gz
│   ├── c142fe0208ea784679122ba04997d3432b05efcc.nq.gz
│   ├── c1b12212885ed61e6be88a95bdaaa0cbc21e5167.nq.gz
│   ├── c27c9d5082b01189a15c775668bbb587b2abb007.nq.gz
│   ├── c33ccca1d6aad8e7a7fbbb519a0fdb0450ab083a.nq.gz
│   ├── c55f0e858af4ebd246a5d251308ab920b4e01a50.nq.gz
│   ├── c6066f80d0ae3c7794855c8403f8db225587861f.nq.gz
│   ├── c64098a3ad650a23749366d0f984ce073f5a5df8.nq.gz
│   ├── c6b8596d1db2c230b015a6af693cf431eb806b3d.nq.gz
│   ├── c720ba28c0c89937128c3d3517e115a1f4f2fc43.nq.gz
│   ├── c8976a7c02fe06f630645a0d294a9dc3b5b29f48.nq.gz
│   ├── c91e891dfa4b7bcda87502591cce8eb438854e74.nq.gz
│   ├── ca515200117db8e1d8438986aae32ea6e8effb78.nq.gz
│   ├── cdaf115e34a303bdda35b03a189e50cdbde8150e.nq.gz
│   ├── d45152d677903c85a73abeb5833a476d40eed602.nq.gz
│   ├── d5895af73f112af617b9eb3d753e1e200935c87d.nq.gz
│   ├── d6aa53c967d908c917a3cd0407655b104510cd26.nq.gz
│   ├── dbde1b1172f14e2afc545c2c0e7d38c4d6074402.nq.gz
│   ├── de4b2f4815f6fa9d80291491e3826251f50ff5ad.nq.gz
│   ├── de669e85b3fed009b5538621e62bf10b6f2cb9e4.nq.gz
│   ├── df126d7c8d5f9f0862273d2fe21ea15b35757b64.nq.gz
│   ├── e1a536767b056969141df1c5f4244d9e21d32acd.nq.gz
│   ├── e1fa60d42b4e8972e638aac8ec3aacdf49b52946.nq.gz
│   ├── e3cf08794c79c821a0f6c00636b0029fa68ac326.nq.gz
│   ├── e4a7a78bf330f5e30b91615e0108e9ed90a22e0d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee99d6ab1b54b69790130c69a6c9d68ac9d8f0c5.nq.gz
│   ├── f29b3a621ebd8d09e3019efa29551b2d8362ad5b.nq.gz
│   ├── f3513b24a3c571cb2e9ecdb2018f0e1abdda24a5.nq.gz
│   ├── f4abe24eb520fbb077753ae4f34bfaa43cb3b83f.nq.gz
│   └── fc286b8a46d2a9a5675a9e5e6dd49b2bb99d3a65.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e9594ce1c732d97440f0332fdc43170a2294dbfa.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 105 files
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

[state-spaces/mamba](https://github.com/state-spaces/mamba)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
