# Repolex Knowledge Graph of block/ospo

RDF knowledge graph data for [block/ospo](https://github.com/block/ospo), parsed by [repolex](https://repolex.ai).

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
rlex download block/ospo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 35c8aeff14f09e5f70a9f08c8ee5cee7daea2205
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 35c8aeff14f09e5f70a9f08c8ee5cee7daea2205.nq.gz
│   └── repolex
│       └── 35c8aeff14f09e5f70a9f08c8ee5cee7daea2205
│           └── chunk-001.nq.gz
├── blob
│   ├── 0e8fea0e008518abc1aaa3e33c6226d92194692c.nq.gz
│   ├── 0fc51d71b1d323f39316bd0bae765275743e69bb.nq.gz
│   ├── 16d54bb13c8a867268b45c22eb7794d2625a78f5.nq.gz
│   ├── 16fd1b653e5b0614cdbb28607292a1f390af9fe5.nq.gz
│   ├── 173d7395b1f9c0b51cde9dde56ae2f501dac452e.nq.gz
│   ├── 1bcce73a2b6735eaae7bd135057b85275b999743.nq.gz
│   ├── 1c8ccc9e07915d5b8c3e0ed0a3aa8e08d436835e.nq.gz
│   ├── 1dc5519c0e7d01bfa31ed3c4e0699f814c75e2f9.nq.gz
│   ├── 21ecf13a6fc9700d6494b5a930d156bd547e15c7.nq.gz
│   ├── 229940653c647a22d82a4da43d255028ce4d0311.nq.gz
│   ├── 239bf01a9ea09805e0398fb00fbee8bdbbfd1207.nq.gz
│   ├── 29e08f9552b67b8d63adeb1a0d7c157edfae9367.nq.gz
│   ├── 30a88fb6ceb4e7c4ff21df21f16d5b1b71e94097.nq.gz
│   ├── 379fda3266bb40984b5a3b9bf421cb8373392bdf.nq.gz
│   ├── 39190a8892d0885eb69e26d272874ac1940a9c4f.nq.gz
│   ├── 3abdb585e94e0d0a901d61b452e34387ab6d3c18.nq.gz
│   ├── 3ba8062bba96ee9a0fd5dbf825019d5b59a02c6c.nq.gz
│   ├── 3c0b979277e0c959d0fda08e92c533486ff4307b.nq.gz
│   ├── 4894c65877e8f54cce2b0ceaad7f68b63559a73a.nq.gz
│   ├── 49c486a9aa5c19ec9f07ab29ea5a57414d93f564.nq.gz
│   ├── 4db316b041080029ff37043883dee3146c9ce8da.nq.gz
│   ├── 5099e3f7102c05b74adbaa9aa04460d22cb7648c.nq.gz
│   ├── 5591fb042d8b083bbef5469b98230b0d2ccf4374.nq.gz
│   ├── 56f043d30eefadaf2cc819f2eb7949e75e1c315d.nq.gz
│   ├── 57c25ea718df723d1e16f152f1a603de54b5953f.nq.gz
│   ├── 5d6c611ae3f9564c88c804dc265037a0883e76da.nq.gz
│   ├── 626d2fec1e4bc8e2fc3934a99ccb4b66fea6efa0.nq.gz
│   ├── 667aaa606ecf020949267bc341c52c2d5b6e256a.nq.gz
│   ├── 6ae30b903b1b2e766d8f9d00610a3cf382d72130.nq.gz
│   ├── 74d4009b527342f03264c9caefd390aa5247b376.nq.gz
│   ├── 77bf8e27ab55ee7408fb84f30e6b236e8b9f992b.nq.gz
│   ├── 7b7812e6c1578933f34cb68e7a427146aaee2979.nq.gz
│   ├── 7fe4bc2a74a099a188feebcd646dbd96639bc05a.nq.gz
│   ├── 86ea1dabef5119e9e863994fe4a10ea132e0fdd1.nq.gz
│   ├── 89d96580afbd72f10c03b1939dee751c9072be0d.nq.gz
│   ├── 8de7448386926ff8249753411840eecefcd4024b.nq.gz
│   ├── 9582fc588754f78d9875691a3bd5e674295436b3.nq.gz
│   ├── 9bfdab18811319c2c18967319a981e275791d0a4.nq.gz
│   ├── a5e19a0b83e02aca1b07a06bf1f997df53407f76.nq.gz
│   ├── ac6f61d054965273abff0b0e625f049e34ee9967.nq.gz
│   ├── b4aef0625391373485c9fc24be0f6d1ec2b5dc68.nq.gz
│   ├── b617b695c9d51a0a70578e8f3cd8605307001ff8.nq.gz
│   ├── bb4417b64350101626d0837f535ec00dcdb63306.nq.gz
│   ├── bb600fb65ac319ef07f5fcbdce9b2c4d4eb21dc9.nq.gz
│   ├── bbab312e762ab9753e5e539ff6f00aab1df32330.nq.gz
│   ├── bbb1e98ff543ef1c49a09cfc815b59b6f971a156.nq.gz
│   ├── bcfe4186c6e19eb998b58e3ea0cb90ef5a0138e1.nq.gz
│   ├── c251a843784a638c05c1cee7bf99a252374016ee.nq.gz
│   ├── c473cab09b02c54aabcb21aef185cb50aadcdbb6.nq.gz
│   ├── cd921c535f5be2b8aa18848fddfad8200b9e0863.nq.gz
│   ├── cdd41f0404a389f346efa9692d2025e0f5a1ae7b.nq.gz
│   ├── cf5f68532f3ec832627250e7cc25c71cb034b263.nq.gz
│   ├── d6422097621fd7c1b1ccc6daa670c46aed7ef5b7.nq.gz
│   ├── dfe0152281c38d186a1a061e21ff6c460ae21e0f.nq.gz
│   ├── e16c13c6952a6fff48e6dec6bbcf295aadcafc11.nq.gz
│   ├── ebd7b4b0300fddfdf851cf298b77a1a204a99361.nq.gz
│   ├── f157bd1c5e287c70a508a98a13f538491aa4dafc.nq.gz
│   ├── f3e404934359461881004b30fb2d3772ec0275be.nq.gz
│   ├── f9ab28032a42d9997c7f33e521341d7995e0b75f.nq.gz
│   └── fe723509ad6e0a247885ad3c17455a3af6fbf79c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 35c8aeff14f09e5f70a9f08c8ee5cee7daea2205.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 69 files
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

[block/ospo](https://github.com/block/ospo)

---
*Parsed on 2026-10-08 by [repolex](https://repolex.ai)*
