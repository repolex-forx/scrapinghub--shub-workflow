# Repolex Knowledge Graph of scrapinghub/shub-workflow

RDF knowledge graph data for [scrapinghub/shub-workflow](https://github.com/scrapinghub/shub-workflow), parsed by [repolex](https://repolex.ai).

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
rlex download scrapinghub/shub-workflow
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7d6bb9a2602b3f6e7a6f5060b8d1a0b104e3086e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7d6bb9a2602b3f6e7a6f5060b8d1a0b104e3086e
│           └── chunk-001.nq.gz
├── blob
│   ├── 008ba7b5f0dd0aedca350bf59d8996804fb703d3.nq.gz
│   ├── 029afb312bfd5ba46bd049c980b1a63c9513726b.nq.gz
│   ├── 02ee7dad5c6c4d862ae4d8637b858db832c19346.nq.gz
│   ├── 033aed7b0f7e6b5033a2ce19f21f6613850c78d4.nq.gz
│   ├── 075af26dbd3e8558e5da8a2c745d807e7f472972.nq.gz
│   ├── 0826e35e9d3215bd15bc9ea768177b22d834bbbf.nq.gz
│   ├── 0930495d0b99034fc3622ff8919342bc031e60c1.nq.gz
│   ├── 0c267a1ecbefbb077c0e4831849578d4aec0f245.nq.gz
│   ├── 0f2c0674936eab045cccffde0d9092a50b3af149.nq.gz
│   ├── 0f91274d9fdeb97a887d63ddccb15ffafac3d12d.nq.gz
│   ├── 143f67053e0405301b62325e8411a145d2041ce8.nq.gz
│   ├── 19d1d987a3302bb7e57ee897832cdc855e691ef7.nq.gz
│   ├── 1aab32db8027049320c6c30ca286655f88536b1b.nq.gz
│   ├── 1bb01c37051227041bccc06b2f58c6ca8ae5298c.nq.gz
│   ├── 1d6316e450e9214c0d9ae3ba7b48afa0b4d1c752.nq.gz
│   ├── 1f831fb309b7f087b911e3d80a943c92ada75a6b.nq.gz
│   ├── 23359393bafdb90a3e2c11ff6b7da5a644d01ae4.nq.gz
│   ├── 25fd3353ac141a7f6b299be6c141ab5952774ee1.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 262b9d035c5e89f6e88d10df042a34a4893395cd.nq.gz
│   ├── 2a2b1a23aceca3c88ee43cbd9343dec07f78323a.nq.gz
│   ├── 2b2d0e810663af7fc749103e07633ff341bd84f2.nq.gz
│   ├── 36a755704068acc60f701430f955e93e10480cbb.nq.gz
│   ├── 3d40a75dfea4dff08d5efdf6f1ea879d13c8145b.nq.gz
│   ├── 3e76c5935952e77818ecbf3c66758836725b79c2.nq.gz
│   ├── 3ed48ed0a99bb541bf2e293ed16e774ee4429089.nq.gz
│   ├── 4845678042c9ef8c6210fe00678392b16db095fa.nq.gz
│   ├── 49da032ee818faa27c954a977d80ea3b08478826.nq.gz
│   ├── 4dd36da4d69d3752bd7f98df4435cf34229e967d.nq.gz
│   ├── 4fe5f815054c187926c6fd48e054a57523aa2915.nq.gz
│   ├── 518fb5f60e9f40c4d329a2a0a20c6f5ee0905308.nq.gz
│   ├── 52943c7532542ab8c81e200e81a59bd7a12aae6b.nq.gz
│   ├── 558a802b907c4ed41dd3f008e6817a4580f0a975.nq.gz
│   ├── 55ec8d784c3cfc688c31cb32a4225e5f551937b8.nq.gz
│   ├── 630db931cf767d895f0b7db021f265374997a45d.nq.gz
│   ├── 664f8fd2f67b69a03cc715853e7fd9490ec8812c.nq.gz
│   ├── 67fd30ff3e711e2e5166b16904cd6c18c3e077c8.nq.gz
│   ├── 684853e20076afeecda4a19a6c4ab6e078ebcf93.nq.gz
│   ├── 6ba83556b9b768c1f4a3b04e19bbb35938fd9439.nq.gz
│   ├── 6be245ac0bab67dada679a5d0b3fef06d5fc920d.nq.gz
│   ├── 6d0fbfae37053be4e966718d95f6f07ff3910568.nq.gz
│   ├── 6d55b741df1ef63d22df3ec4c3e77f2622e5697a.nq.gz
│   ├── 740dd31bd2809109870945af2610a1279dd40359.nq.gz
│   ├── 7515bf21f300014d73721b92be1ed243c4290d2a.nq.gz
│   ├── 7620eb26497ff73356579b105efbd454ff80e4ea.nq.gz
│   ├── 7d71f77a447409e1ae2c7b0ead2fa21dbd24fa14.nq.gz
│   ├── 7e793352f3f4514cb982df6b7b58c1e7272a56c2.nq.gz
│   ├── 800c332f8e91905676a51c5b3c4ae00d8e9a7cbc.nq.gz
│   ├── 82a121d6336771b6e8ba510b833535403727d778.nq.gz
│   ├── 83aac241ce9c1ca92df6ef2691a92aaf2f74b482.nq.gz
│   ├── 888f8ba2e25a8c455b98bb84374cc05383ad24fd.nq.gz
│   ├── 8d4ee883a91f38b5b4686f9da63689d7eb5d908f.nq.gz
│   ├── 8f38da0d70afae0ce8ff2adea58d62c3fbfdb7e3.nq.gz
│   ├── 8f5055190bbbea850519b94f6467c676e265c335.nq.gz
│   ├── 8f65c25b7a1ea464a9bb5a3dfcc4d88c82c8586d.nq.gz
│   ├── 9342924a9c091d1984f8ab06621c4997236253ec.nq.gz
│   ├── 9655eab8dbf6224d7321005d20dfab26ecdfd0a1.nq.gz
│   ├── 97b9ee19d8e05ff844905c2cde4fc1a656a227c3.nq.gz
│   ├── 9882f77b59536a52987941c0e138775a4d17195e.nq.gz
│   ├── 98d0351eae0977bc975c689d2d7d995aef24d566.nq.gz
│   ├── 9b9c73925ed5caec5e57e710bd1ab6996b70643a.nq.gz
│   ├── 9c2de2005be60ffae473b10300937b8f28446184.nq.gz
│   ├── a08aec5931ff00624e3757b8d79a813b5d716b8a.nq.gz
│   ├── a3887b2e60ed155b0e7af821728cbb1ddc8c6431.nq.gz
│   ├── a47d4e7296936c8d1d8002c35a92121cabbfc6f3.nq.gz
│   ├── a519436dc55c7f51f995122e46ece8f09f03872d.nq.gz
│   ├── a5f242d1b8a9ce3e99962ad863676aa67032892b.nq.gz
│   ├── a6032897eda55253c140c5713919116804d8d5da.nq.gz
│   ├── aae182ec8fbc5115d64e9d0da763bfcba4a0364b.nq.gz
│   ├── ac528570627c7120eb1a04aac01ecaecf87caa77.nq.gz
│   ├── accfa4a04fb76b4c04492d318c5f7dec37035c72.nq.gz
│   ├── acf67421eed4e81fb443e2b12538357f6b3e36a3.nq.gz
│   ├── ad9a42386ea4665261ef1d3c481c947fb3d80bcd.nq.gz
│   ├── b139c71810fcabf495c5ead592283103b288533c.nq.gz
│   ├── b51ae1a8bb6d9ef21acc489254881b8f2b0ea1ad.nq.gz
│   ├── b6a5c875a5c530eaa4a94d06def84ff61ef6d407.nq.gz
│   ├── b81eb0379dc862f7d4fd3369173f976b15af0927.nq.gz
│   ├── bb99305ea2de16c7d97ae6373bfe5f980ca03b6a.nq.gz
│   ├── c1c8168fee63d75ce5a3b0fb851c3b4322893c04.nq.gz
│   ├── c3159c7611b0ca81759b2bbe8c061782847ec087.nq.gz
│   ├── c3ed87ed1334e0ba7ed0af937bd53ef673284698.nq.gz
│   ├── c4af5bef2ea50fe4c4e37fd79b43c608c153dd7e.nq.gz
│   ├── c4e3c2125d0112025c8d9ccdf057214d395f578f.nq.gz
│   ├── c545e48b40ce9148718f59d8456555996ffec41f.nq.gz
│   ├── c5c57fdacf2bcec95cfde86181b9442ec150f7f3.nq.gz
│   ├── c8ccbfe9cdaf9a628524b9b6d0776cfcb23f04f9.nq.gz
│   ├── c908e934faf9a431b3a593c04c0e023c09841c51.nq.gz
│   ├── ca9e775d2fe465dee5d2d96852a1998cfff64a45.nq.gz
│   ├── d022552509bf6ecfce53699d23965abf1d34a13c.nq.gz
│   ├── dafd8d0ddae74eea0470bdec6d625f4e445533a3.nq.gz
│   ├── dde4b0ca9916e82923689dcb093503ecb5119fb1.nq.gz
│   ├── e288a654fde47ee8aa4255feab766a689eddb63e.nq.gz
│   ├── e38bdfa1ec0c8d0acf6f7ce220600af77d13147d.nq.gz
│   ├── e4062d73a102bc664bc34ea7bb52e30525a4c502.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ecfbbcd14785937c1e6aca440f7ff810a1e66cca.nq.gz
│   ├── ed219f1dbec79e0a77551c3b40dad20641b556fb.nq.gz
│   ├── ee570e419b1f93341be7e199c08ee4b2272b55bd.nq.gz
│   ├── eeeb86551a78e576f2f884adc88c6280e5a572d4.nq.gz
│   ├── f162fe44dffe2a904a6ab9a860b9481c5b1d00c8.nq.gz
│   ├── f346e8188ed23507eae027c4c90cf4dff614b323.nq.gz
│   ├── f6a845d8d04ef67cc7b8fbf8f8c0ff67bcb452fc.nq.gz
│   ├── fa4d28d30686abfb9918a1b9b7be3002227a74b1.nq.gz
│   ├── fbada1cf20b3dfcff8e1225181089cee9402c989.nq.gz
│   └── ffd52e18dd65192a6ee56649b39d1408979de236.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7d6bb9a2602b3f6e7a6f5060b8d1a0b104e3086e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 113 files
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

[scrapinghub/shub-workflow](https://github.com/scrapinghub/shub-workflow)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
