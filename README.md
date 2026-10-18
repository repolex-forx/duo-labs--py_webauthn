# Repolex Knowledge Graph of duo-labs/py_webauthn

RDF knowledge graph data for [duo-labs/py_webauthn](https://github.com/duo-labs/py_webauthn), parsed by [repolex](https://repolex.ai).

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
rlex download duo-labs/py_webauthn
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c9ba2b7dad6b76bec89e44c76c8ed81fc43287bb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c9ba2b7dad6b76bec89e44c76c8ed81fc43287bb
│           └── chunk-001.nq.gz
├── blob
│   ├── 00bf8ef657f7715feca49d03ffec43f348d5fc74.nq.gz
│   ├── 026aa409509caabecf23d6a03c0a234aad961b11.nq.gz
│   ├── 040f7665fdb703d484cb20aafc6b4042feeab646.nq.gz
│   ├── 04bbf9d54c1188a13609fde0aa19cd19abd5524c.nq.gz
│   ├── 06a43d09d7146deaa627c96b7842aa0de4e109f6.nq.gz
│   ├── 09aefc615295dac86e078545e323a51433c258f4.nq.gz
│   ├── 0a431b1063428be65b1ec30f860fd352515c532d.nq.gz
│   ├── 0b5c21ea501fe40c0ea105aeb1db7774c5559700.nq.gz
│   ├── 0b65ffa79b3165b0d0dc3c4305a5053021a71e38.nq.gz
│   ├── 12561965494a88b5e01313fbd1eadb3a401ae31c.nq.gz
│   ├── 169a3c0dc0ed5da5c6f701638e11a7123e2f3db7.nq.gz
│   ├── 173ffd509aa364ef17b509b959300051fc6fa466.nq.gz
│   ├── 1794bdbbe5d5b1370972bf6069af3fea83186213.nq.gz
│   ├── 1c8cfbc7d90cd71c429589b13e9b6330c21b7ef9.nq.gz
│   ├── 1db976798cc366b14b40090d70ec4c5afa48d4c5.nq.gz
│   ├── 20e393c305f13078646407be25befe9d43412966.nq.gz
│   ├── 252afc360fa1d9ee7c21a3b78984e785eab4f207.nq.gz
│   ├── 2576e722a85dd7bc067b8d7775b681234807975c.nq.gz
│   ├── 2b53f8e3317efd9a5201502e1e646b8f586d5497.nq.gz
│   ├── 2caf8dd9f87914da4a1504e658a39d361ec6570e.nq.gz
│   ├── 2e25b60433d736c3f2a799e065b3ce293a726567.nq.gz
│   ├── 2f33b952a0cd5a1ef9a10bbc0e5d223e08877c70.nq.gz
│   ├── 334d26886f3ffc5bd1d7d5dfd6ef2fe1589cc5b7.nq.gz
│   ├── 35561c476bb3c2777d72b9d6f12ed0a6c7b885d2.nq.gz
│   ├── 357444e5b28de884998a8b3832e6b74bfe29c1c5.nq.gz
│   ├── 3a767873c0eb414fd727fda1930422a21f5ffed2.nq.gz
│   ├── 3a785a060c964405d5140bfa991c221c7a114549.nq.gz
│   ├── 3ccc9a648e89ba806c70ab970f789b6e2fff148d.nq.gz
│   ├── 3da9a151df0af85a2427b24f1ae80ac7d09bfb62.nq.gz
│   ├── 3fe50d6fe362ef6ca8f28042909e2b52e4fe8706.nq.gz
│   ├── 41079e05cedf93bde3cd41d4ca3accd5e813dc9e.nq.gz
│   ├── 41f565639d739b02293b6d1b47c78553023a4893.nq.gz
│   ├── 4432c8434dca2b8c51aa97c395072ad1f14f8276.nq.gz
│   ├── 4695f320e943bb988b8bc4530183a660f4bc80f1.nq.gz
│   ├── 48176905ba550b842e304728d6646adfb307acf5.nq.gz
│   ├── 524a9c2ac3c339840713a4f52a6ef900931d491b.nq.gz
│   ├── 58212a8309fde6d3e12889342a0ebf8ffa94faef.nq.gz
│   ├── 5978cd2a717edaeafe41885bd455668d7444a34d.nq.gz
│   ├── 5b4be4f4da503032778e9d058bd022b5a7dfe1a0.nq.gz
│   ├── 5d23112af3c71d882f8b333c033f34019ef4a93f.nq.gz
│   ├── 5dde45f49eaeff92fac4e4a8a579ebbf4c5a2833.nq.gz
│   ├── 6142abbaa90a99119042ebea803dace7d15721ab.nq.gz
│   ├── 67f3bf806455ce6ad2cd75ac4fe0a92ad8711a40.nq.gz
│   ├── 68281e3190a659686b87a4557fdfe3864168aa6f.nq.gz
│   ├── 6b04e1950aa2029d8b67b8f7969d873387120086.nq.gz
│   ├── 6beb4c70536bd508a3c6a9a1396ae3954547c851.nq.gz
│   ├── 6c3f912ab9f986c425a0ab47dac75786fec28462.nq.gz
│   ├── 6fabf648c605150d50c3c6f1fe85dc938f862730.nq.gz
│   ├── 6fd0bbadfae4407f581f13d30fbc804da0e842f3.nq.gz
│   ├── 7016ed075292fc4a50bf03c2a920a2ddae0e2c66.nq.gz
│   ├── 7131ee7c272a3a6b4af8a7a17dc9a0429e000b04.nq.gz
│   ├── 721f6b2dead10443da43d8ce648dd87e604b6d4b.nq.gz
│   ├── 72d9692b3ae10169d8ae360d332838512b4d8379.nq.gz
│   ├── 75db9cd1aca3b51f3b5b634a6d405b428b651870.nq.gz
│   ├── 790b8094c57b89ed516cc5e8ef36f2f28d6c668b.nq.gz
│   ├── 7ac6fa2ad7077debb9d731f375a86bf38206608b.nq.gz
│   ├── 7b794a40dc676b5d04ff152e13d039271dfeda0b.nq.gz
│   ├── 7caf04fc9d5480471ac620a3fbc17e11dcc94e12.nq.gz
│   ├── 82742de467dd87034843cfec82e43dcc577337eb.nq.gz
│   ├── 877f5a57205bc573503ef775d38c3c338528875a.nq.gz
│   ├── 885b8854e42277daedc42fa53ad36a799ebd8507.nq.gz
│   ├── 892dad3c65bb681b394e5619984ff41039b30f1c.nq.gz
│   ├── 8b7ade69cf354c9d0959e96d6564aedd98f3b144.nq.gz
│   ├── 8f00a4f62b0fae57b5b68bd2d6d516d29179351d.nq.gz
│   ├── 9707f685ee81a25d2eee8a3dc56b6fa15193968b.nq.gz
│   ├── 9d2b88a4510cbdf35af36894e19b98c3247cac16.nq.gz
│   ├── 9eaa41e44a75c87f915cf0f8c1ff07a9e35448c3.nq.gz
│   ├── a4343ff7af434305b0e5a954ba625b438e45c8c3.nq.gz
│   ├── ac0ec19a4008921db441c0f211863f542c605b15.nq.gz
│   ├── aca4dfa2009ad8a883549d4fdf165f5208ae7659.nq.gz
│   ├── b4618e1d841b34bba19facba2e5e9ee7d09959a3.nq.gz
│   ├── b490b7989c8791978b035b865bb64134e81a11aa.nq.gz
│   ├── b847b930c42d3c9809a74f741148e274bb75fddc.nq.gz
│   ├── b90c8ec4c82caae80498e7a5553b8ab535f08da7.nq.gz
│   ├── bfd56f6b2597cc2785c575eda770289e7d15ebf2.nq.gz
│   ├── c25837dec0461a7b62d488eb19f0aee51474214c.nq.gz
│   ├── c2db7ee16188b80686c11867d1c9380fcaba228e.nq.gz
│   ├── c4c231d0c32aabd9415228a7e248297b4dd81631.nq.gz
│   ├── c827341d8fcc3f9aa52a4c25530766f0bc98281c.nq.gz
│   ├── c8545156e8ea1e71cea301715d302a901651d7ad.nq.gz
│   ├── c8c760d738695237215692de59097877da93b55d.nq.gz
│   ├── ccfe9f4a57704545b216986df40cd445f312ff05.nq.gz
│   ├── cf87f2770c7327d9725060d5f4adf100b0304ddb.nq.gz
│   ├── d3c90499e0b43c83e68cad837ee9bab3fbe2eb32.nq.gz
│   ├── d4771382207d3f7533e473fba2f47191b3db2d72.nq.gz
│   ├── d515453238c09c2cb8775fcd2572fbbff6e7fc2c.nq.gz
│   ├── d68f8946cf43f27bda63208a9eb680e98858265b.nq.gz
│   ├── dabc7f8152589c6609a9861841cc754194184e7c.nq.gz
│   ├── dca67f4f8aa81427be8cfaec21566c68338e7249.nq.gz
│   ├── ddbbfa7329359032057134795ff3e532892c78b9.nq.gz
│   ├── e22ee256a4de65c11a696be1c5c3302725a5a51e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e849a8d3461684d6b9a44c6b55ad681048ba66cc.nq.gz
│   ├── e953afd40d301afa19575b50c075b836a97cce4e.nq.gz
│   ├── eb162fb52bc0d5468c262b4fad64c889aa35083a.nq.gz
│   ├── ed3c9aa9371a743d881d2e2efd1e011065ab0867.nq.gz
│   ├── ef93cb23d0b7255e24c3f2ed2327e2ea8b8c0e01.nq.gz
│   ├── efd2b988d2196a7e1f627895c175997d86f1d3a2.nq.gz
│   ├── f2829e0e4850f642f89e74c12011d29e17c4a85a.nq.gz
│   ├── f5805e1d652aae36246dcd8a571845097ba8a836.nq.gz
│   ├── fafabacf77bdb8a478f7ab69570003995b990de9.nq.gz
│   ├── fb7c8412fdd4a4a035bfb73eab0b4966730292c6.nq.gz
│   └── fdd4212a67211459586e3806d6762d4d48387905.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c9ba2b7dad6b76bec89e44c76c8ed81fc43287bb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 111 files
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

[duo-labs/py_webauthn](https://github.com/duo-labs/py_webauthn)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
