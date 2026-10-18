# Repolex Knowledge Graph of betamaxpy/betamax

RDF knowledge graph data for [betamaxpy/betamax](https://github.com/betamaxpy/betamax), parsed by [repolex](https://repolex.ai).

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
rlex download betamaxpy/betamax
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8f3d284103676a43d1481b5cffae96f3a601e0be
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8f3d284103676a43d1481b5cffae96f3a601e0be
│           └── chunk-001.nq.gz
├── blob
│   ├── 078debf7161776af97a226a8e2769d56d39eb028.nq.gz
│   ├── 0973892c161e9d541c49e505b9e360d6dba014f9.nq.gz
│   ├── 0cff58274c56408db479662725ceb44bbe5e1bf7.nq.gz
│   ├── 0dd0bb4d9d9f9224f9f0d95e0a0a33ed88f72eb7.nq.gz
│   ├── 0def8079788fb51876a7bd5ebab9f63d2e3ee743.nq.gz
│   ├── 0e074af166919f49be5dd559e4712cb0e6b70e87.nq.gz
│   ├── 0f2e3e0875491601e1847573d5125221dce04c61.nq.gz
│   ├── 0f9e6f1082b848f2519e5220e427d69985aa560f.nq.gz
│   ├── 114c680041d56f2982d3a49f3469a627f4366709.nq.gz
│   ├── 11c360c1fb3e737e95e8aff5ffb176dcd2d0f1d1.nq.gz
│   ├── 12c638dda09412c3338bd22b470b285e619c3804.nq.gz
│   ├── 13824fa13de5c8cab17a9d0ba94ead27b81030f6.nq.gz
│   ├── 16f51c5a7b650c56029e84eaa05adb953f690328.nq.gz
│   ├── 1763ebc643dafc361ece4c028dafdeee3f6c6189.nq.gz
│   ├── 18d84637e485a51273660f8fcc4df70c57dcecc4.nq.gz
│   ├── 208d1b3dcdfeeec96a5bd9a37d783ba4dff221b5.nq.gz
│   ├── 26156d4287aabb10b0e169b05fd869a4eb42bf4e.nq.gz
│   ├── 2707af8fd72d4d153a146e9e50edd44bfb503b93.nq.gz
│   ├── 2721e61311eba454b846988a7a936b32372d7f4f.nq.gz
│   ├── 2946c668fff4b36c28d08416304c7731cc9955ce.nq.gz
│   ├── 2b2e5cb1f2f66e2743eeb957f0620f3184c1fa09.nq.gz
│   ├── 2cb39169c2a8e41ee29f6029c8489558db0b9149.nq.gz
│   ├── 2e42b2fedf490840e4f3b5e18d5e23c80c437270.nq.gz
│   ├── 361bec609d8705eb838eb3706839590bed6312a0.nq.gz
│   ├── 3708a0d852dd15a026f27d82e6c3664a517df0a7.nq.gz
│   ├── 390fac477bcc96452a7aaf1678d23dbc0e0cdba3.nq.gz
│   ├── 3a60098f9d3c0d382767c9123f6b017afc91e0df.nq.gz
│   ├── 3bc5a85cdd1eacbc10579d924ab44920ecc7e44d.nq.gz
│   ├── 40d571315a112da3fe1b7f30e020924031788643.nq.gz
│   ├── 418687a6a754c94fc94b4e3bf31d80c3f6f8ff57.nq.gz
│   ├── 41f33ebfc83080991c4e1647b04393ec4ef13897.nq.gz
│   ├── 432104c52b2a8a49a595ab0ea75baa0a2597be7f.nq.gz
│   ├── 44a8a0ddb9c243b8863f6bcba892d843a8566e3c.nq.gz
│   ├── 4cfa7f8fc09aa0a394b4a49347b08417592363e3.nq.gz
│   ├── 4d98866346d503fcd53e18b7050a7490963bc9f0.nq.gz
│   ├── 4d9a7bd5e964f5bfaddee9d44f49efb321de48e3.nq.gz
│   ├── 4f00b933179bc2a3818571900928a555c3528026.nq.gz
│   ├── 512ca07ce176d8ccab85824842dd2dcb03e7d24c.nq.gz
│   ├── 5355294eeba7aab07e3c2cda7a6584e970fab299.nq.gz
│   ├── 53c023043f2a3d613e92e33defb6a52a2ae65eb6.nq.gz
│   ├── 53c0653b6a3d450a67f034c445162ec5959f5e34.nq.gz
│   ├── 597a26e7664e6599dab11854521124121c428411.nq.gz
│   ├── 5b9e9e7c3ab1cf6882d2d2559461158786749ed5.nq.gz
│   ├── 5be31121ba111bbf7414319798c10d804875498d.nq.gz
│   ├── 5d958ffc4c3bfbb804174368b25abcb8f2d86573.nq.gz
│   ├── 5fbfa6da9ccf213ffd485eff3fe2066dd48edefb.nq.gz
│   ├── 60fdb902a635388d8eb24ce44315de8153d17850.nq.gz
│   ├── 62b39b620e2c3a65d6fb8115caeae4ddb0a06aeb.nq.gz
│   ├── 62eb81a11f943ecdacae180806a00054029d5f51.nq.gz
│   ├── 65b2fd58082a2934b4e380e93b85f1d52c2aac07.nq.gz
│   ├── 67445eabb76a1ebf62d8bf564531c4144cc11d78.nq.gz
│   ├── 6e45dfdc9ec077a705c5a7cdebc4f9878ce1f38a.nq.gz
│   ├── 6e810a9bd721a68cd765aa6f9353e6230c579783.nq.gz
│   ├── 73764ae083d4704cbd341bfc313531c3ed992bb5.nq.gz
│   ├── 74790b4ace2c4855c5df5e5a71b78dbc0fa4c679.nq.gz
│   ├── 74e9d94dfa68b398698458a6a1e8590ac570449d.nq.gz
│   ├── 799a8d528bbac2e4286e793ec5b7b443864599c9.nq.gz
│   ├── 7a7e36621d9e4e0763268a62e0ca3faad2bf351d.nq.gz
│   ├── 7daabdfb6b7842b3d36c0c9e8a318f6bc3443dcd.nq.gz
│   ├── 84da228875697e4af4787dd92dd5603ebace6f2c.nq.gz
│   ├── 88b9379ec622aa161389401453a21a4a5aa23462.nq.gz
│   ├── 8af0e7675d2a16720391330e7742eaf4a4e7c807.nq.gz
│   ├── 8e12cc6f0910f9ac26ac398e425af88da20c6529.nq.gz
│   ├── 95d69290a7c89b2e19db71d647da61f7e8cbcf46.nq.gz
│   ├── 960fc973884683a619dfbbafd3fb991a5e37a796.nq.gz
│   ├── 9886ad575962ad0d9c06130c443f8fd924a85ce8.nq.gz
│   ├── 988b8515c0e1dbe76a219e8c20d5e643e91239f1.nq.gz
│   ├── 9b02da323c2cb0478470584ec96e9a46c3a761a0.nq.gz
│   ├── 9b26229c754b230249d2aecbd5f5535b42c4904f.nq.gz
│   ├── 9d7f295507e5fc7ef5d1cedd9ceceabd440da0d5.nq.gz
│   ├── 9d7f718a179341023784f13b3ca279d0081887b3.nq.gz
│   ├── 9f76b00b056b596a61c3ba76815994a108e981e1.nq.gz
│   ├── a141da3b20beae7e113b5165c3b8f9e95a75c2bd.nq.gz
│   ├── a26fe275bd36dea9727a06700bda23457d1b84e0.nq.gz
│   ├── a3a213d3848572d14e83461ebcdbe34cb3346e17.nq.gz
│   ├── aceec41b73e536b4a6fda2f8e40e0821c1036d9a.nq.gz
│   ├── ae505cc2ab00b0ab82946ce5a950b5754220144b.nq.gz
│   ├── b065efffd45efbce2f45ef78221a390c73aa6d05.nq.gz
│   ├── b206e5b9b80665d55a85d4d152b9ea25476a542b.nq.gz
│   ├── b837d53e2795761a4c364bd50e5316c294fe02fe.nq.gz
│   ├── b8da4cb30f30dfb43d4724a3173f92765d0e737b.nq.gz
│   ├── b9870812d413e3fb99d4704d38465f3cf826d95d.nq.gz
│   ├── bad620501afaf30ce6d96fd43d5c06858c1a6503.nq.gz
│   ├── bcfcd62a03f409c737c7ef2289e6afc1f69fd09e.nq.gz
│   ├── bdd7dde9d0e3b279f093ff38de984d6b82d99b4f.nq.gz
│   ├── be28cab8b74c75f3f10abb340f929a3b517fc4df.nq.gz
│   ├── c2bcc8f1c29a7c18fb6c21b6a51ff1533c17fd29.nq.gz
│   ├── c3fab4ee32d96a81e2ac67c63199510badbbe311.nq.gz
│   ├── c4ed3acd8aefc845c4d95e1298f41a684b7d0fb6.nq.gz
│   ├── c64d46ff950f86c44046614675e4983930088a50.nq.gz
│   ├── c6ae75343c761b0ae59f067f981cb899ba7dbe88.nq.gz
│   ├── cdc9beb0184e8f7ee6e0332f492d0d6a2a206dec.nq.gz
│   ├── d21ce0d9f34a27d088fc34019b1e68d7743c1dda.nq.gz
│   ├── d2c0a2790ae37e2b3664bffb40b7e7d67ae44bed.nq.gz
│   ├── d7b8c19548d2d1939209c53d9592e481b87b67fb.nq.gz
│   ├── d88edeac9b35ebf115303ff5a519329388f6bd02.nq.gz
│   ├── d89b8bda06198b25b816fc7c636447e48f3e4ed9.nq.gz
│   ├── dfe8f55486120337e71b99ecc3317e815185bf9a.nq.gz
│   ├── e11753d78e22b46c196b971c26e065a088e1276e.nq.gz
│   ├── e12c53fda460e0b8578efaf3d4f3c5088fc8e243.nq.gz
│   ├── e3304bf46deddd18fdf95d0e98bd9b6873261242.nq.gz
│   ├── e3f6d8193d316154e849622128a7471a4860e044.nq.gz
│   ├── e47eb022a5c8485095d615f3639af9c78fc7e895.nq.gz
│   ├── e5ce185a762b141a6abef71fe4291c404783dbb3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e783ecc4d9d509f2ac46a8e9129d80c5f58b6313.nq.gz
│   ├── e84196a3b2f99ddf635c63e83a7780f5692075e3.nq.gz
│   ├── e87c9161ece89ad4ac2f58fc884bd5c79e9e97bd.nq.gz
│   ├── eba36eed94554c5345de1ab3233685e28a1ea246.nq.gz
│   ├── ec3fb2a3b65fb1ddb4be8833eb483d18955700b4.nq.gz
│   ├── eee55cde5122e87f1f076b73619731026775797d.nq.gz
│   ├── f3ea978dba1b5f52ca7099883aee4343fbb896ef.nq.gz
│   ├── f4231087e37b47694efe7cb103ff4bce85f5640a.nq.gz
│   ├── f60c079c047dc635919fc225a2230f035ce71455.nq.gz
│   ├── f9ce300e5b2bc1eb45e9fac745bd0180e0c3b0e3.nq.gz
│   ├── fa7b54836f8400b2dac8784fdb92cb0b771b377e.nq.gz
│   ├── faae2f2c198f11db5899e20200139a4a444b4380.nq.gz
│   ├── faee9dfb1a8687e7046194c3254ed840bb43b12c.nq.gz
│   └── fc3d1e79454c37850749fe2be795720658a5444f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8f3d284103676a43d1481b5cffae96f3a601e0be.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 127 files
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

[betamaxpy/betamax](https://github.com/betamaxpy/betamax)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
