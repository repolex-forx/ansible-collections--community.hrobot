# Repolex Knowledge Graph of ansible-collections/community.hrobot

RDF knowledge graph data for [ansible-collections/community.hrobot](https://github.com/ansible-collections/community.hrobot), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.hrobot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c6406c3c2354849c3480c9949c1a22aef0a0e59f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c6406c3c2354849c3480c9949c1a22aef0a0e59f
│           └── chunk-001.nq.gz
├── blob
│   ├── 012065c8539f2bd3e61eecc74acf5a046956de40.nq.gz
│   ├── 056c13e9bedc31e85d96f16486738cd4de51d4d4.nq.gz
│   ├── 062ac5aae2d35f0c212076ff3a67af7ff1f1c27e.nq.gz
│   ├── 092cd20a37815c5a9cf394ec053d0fb39b63b6f8.nq.gz
│   ├── 0d9329fadd5ee62c8c3b7ad26c85db12e95df6b7.nq.gz
│   ├── 107fe125698754beed8efddf473a003bdc2a80d7.nq.gz
│   ├── 1d6cf8554ada641c9a963a6f986822bf4be2da9d.nq.gz
│   ├── 252378499e5feff34f07a3799b9b54d4a94b43a3.nq.gz
│   ├── 25fd0970da22ad8f213718558e074c49231f68c0.nq.gz
│   ├── 271415fad46e01fb0937ee0e17819f549c067190.nq.gz
│   ├── 27148a63ec1bf6820fee7bea512c63ddaed6993c.nq.gz
│   ├── 2751c1e014f25d8be713f5d1ffc0dae6bf2cc89e.nq.gz
│   ├── 27871cf87b251ddd2dc30cb4b299db96cf441969.nq.gz
│   ├── 28fa92f5d95e591ba4619b307eca3f552a904348.nq.gz
│   ├── 2918d77efbc5c9189ec92cb144f69c38bc8d3e43.nq.gz
│   ├── 2ac21780234300a1bcf2c1a962771dca76e1f7b6.nq.gz
│   ├── 34f5b50233cb8ad940e98dd160f17b010095b953.nq.gz
│   ├── 38590f2e4ec486212f404e5f1405e69f7ec27db8.nq.gz
│   ├── 39d59ce3e43b2467038e31673cd64cbe56052a90.nq.gz
│   ├── 3f9590d48cedac53b720d714c949b5afa5cc3914.nq.gz
│   ├── 4362cda5213570411aebc4b5e6af0901cbcd079a.nq.gz
│   ├── 44a3944a71d2961b1890be907adade6a2b18643c.nq.gz
│   ├── 47427aac5333d65902deb2ee1c994bf164c7e233.nq.gz
│   ├── 4c28654ee80c0bbe562563956eaba0153e4ad4f2.nq.gz
│   ├── 4dab43cb8da323428aedb240ea58afba36090978.nq.gz
│   ├── 4e0bbdb3cff69c526f37718e0fcdc9f53d9b7904.nq.gz
│   ├── 50bc3a1511039efa33734a82cb5407c1aae26e97.nq.gz
│   ├── 52e838ec729d733b53ad9756f7303d3e31b0ece7.nq.gz
│   ├── 55bfdbbb4583bf772f352ec2513bf275a0bb5599.nq.gz
│   ├── 562307b138285b73debcb4375e61d35932531a8e.nq.gz
│   ├── 563e007d45faf30c30dd167ccb5c877b95f76f95.nq.gz
│   ├── 567f606b63815b2b1d16cf6228dac6a5a99e0cb3.nq.gz
│   ├── 56c8cfbcab8e5a2fcf85921a2bb5ad9cde5ecee7.nq.gz
│   ├── 57bf51c0e61973efe20965c84f55dca070856799.nq.gz
│   ├── 58afb4fe2115a8089f874e5d35cfbad32ba1b01a.nq.gz
│   ├── 5afb77a017afed71738ba59f6959a2857ef74c5e.nq.gz
│   ├── 5b511537db1c671cecf1bd58e626828776506d2d.nq.gz
│   ├── 5ee7812edbb236187b2434d8d01342f71c10b922.nq.gz
│   ├── 630d8bf7fdd817886c26287dc77c2f3d29cb59b4.nq.gz
│   ├── 6449cdeb86db15f1e2ffd6da892a27b140f6d1b6.nq.gz
│   ├── 6810e04e32878215c32b2039277d4b1809f4de4a.nq.gz
│   ├── 6a4fb941e3714bfbdc522421afaecc3e78f93ad6.nq.gz
│   ├── 6b5d4fce7971f5a4381fdddcac1c9923e11dca5a.nq.gz
│   ├── 6c2156135aea59dab02f46f4f9e56b6fa26a18f2.nq.gz
│   ├── 6f1448ba2c668e877a503d7dbf52ff512473fdf4.nq.gz
│   ├── 728531beef0690ae462387f1a8fb019f7683025e.nq.gz
│   ├── 732c8aca14e47b8d1a000facf21cc2289012052d.nq.gz
│   ├── 7701572a6265270f2fb359c6f5751c4ca8f00495.nq.gz
│   ├── 797f871e1fff97fb5d4c36c5279c3e330fceb45f.nq.gz
│   ├── 8ad2b846f57be4d3ea500cb7fe7b290bbbd02c88.nq.gz
│   ├── 8e26d8780c155710d60a5c1ea797de008f5e73b4.nq.gz
│   ├── 914626d7f15b37adc1ee364844ab893003c719ac.nq.gz
│   ├── 922aeca2ed2e476d541684893e93ee7909cbafd2.nq.gz
│   ├── 955a3b3ddb1a54231b4c0d079b7e89cbaf0af798.nq.gz
│   ├── 98774e9ff9f37f34783f31e5745aecd4acfc40cc.nq.gz
│   ├── 9a767a29fa19de26b2c69c2c561f7f2b33ec34c5.nq.gz
│   ├── 9b16455f7b55b8daa8cdbe03b23d5a1b83537861.nq.gz
│   ├── 9e8ef50bb1fce6fc34dce0ec45888b8722a3c923.nq.gz
│   ├── a6707e291cd008e31aaa116fd8e4a8e7f9411bd7.nq.gz
│   ├── aadd6f705f13ad84fa32509dd579df38fa2e5a1f.nq.gz
│   ├── ad9e9b2ddb75190031f14a2edf520905d422fcce.nq.gz
│   ├── affb1ee05f097ee334ad23841525ad1fd9b1a847.nq.gz
│   ├── b5884a88bb5b2172f7ac53912443bbcfc8273f75.nq.gz
│   ├── b6936a04922d2befdc3bb6920db8b5244a4d4f7c.nq.gz
│   ├── b69d5d1781f92be5a710b4a0096e5c150610f217.nq.gz
│   ├── b9796cdc43c53092ee4a2085a5b1329c974ca2bd.nq.gz
│   ├── ba1c375f3efa918ca035adeca8ba5ed69f05d43a.nq.gz
│   ├── bc755502be03d02a0419d2dd17196759e8cedd36.nq.gz
│   ├── c2ee87a5da7bbb484359c258638743a110f0a18b.nq.gz
│   ├── cbc246ae3d870590135aa0acb2751a35aaa22b87.nq.gz
│   ├── cd67269eb56ab5f807ba82cb6db4fa6864f9b613.nq.gz
│   ├── cf071ad98d8b10bb0a69dd52cdb152e1d14c3d73.nq.gz
│   ├── d144c7a3bdedf9fa324383e9986ca7cee9f63cf2.nq.gz
│   ├── d2fab094a977055a03b72d781289673ac0455ce1.nq.gz
│   ├── d5bc8c854cc5cb20806eb347326f8e77d384f672.nq.gz
│   ├── d80a1433ece30c1d60fda8390c618ca639b36e44.nq.gz
│   ├── d9baeead4e549ec3bd035e24d1156803fefa37ea.nq.gz
│   ├── dac34757ed253f5c1ec5991f1f584f5868fbb5f7.nq.gz
│   ├── dc1a3911d25f69a8cd847e6c066b673124d31c3c.nq.gz
│   ├── dcf27d249aae1a34d6a1548a0db731b696a52303.nq.gz
│   ├── dd1f081356284505116ee019c62f250de5040429.nq.gz
│   ├── de8947d74e8be1ce7f67166e509629b0ff7e9850.nq.gz
│   ├── df59bd8ad2af42971a978e3fb4496a3ff8744f11.nq.gz
│   ├── e103491cfc7bbb8041eb9e32399e87b57901c961.nq.gz
│   ├── e1f51ae664a224a13df1efce32582d9a7a4d6474.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e88855f8d5ba3867c76b4e316a6a40fa3e94ac26.nq.gz
│   ├── e99819053c00a9b7cdc5130f48fc79bbbe13b401.nq.gz
│   ├── ebea83396be7bd2f2247f09620571bb693d781ca.nq.gz
│   ├── edff8c7685d5f4817c24b0ac7a99e0826bd2cf18.nq.gz
│   ├── eefb92a3a49dde3fb95465f749c576c86f0a5418.nq.gz
│   ├── f1403c8465f66a737d36679e20911aa8a6dd0aba.nq.gz
│   ├── f1d9b8a6fe720759cbbd5ef3913b759b07ceba68.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f28a6e7c902f36db1f42824d8ce3bfcc27935d8c.nq.gz
│   ├── f2ecef50215b0677ae70acf813c71daf266329f5.nq.gz
│   ├── f43fad8a61d320177d182d5122d47e4b2284a0c5.nq.gz
│   ├── f71b322d2aabd560774185ebb7c3fec99c47ef3e.nq.gz
│   ├── f83335dd6ca76cb3b7fc82733a02cdbe86afc654.nq.gz
│   ├── fb6cbfcd379375d46f04208e327be9c08e64a15a.nq.gz
│   ├── fbc65e5bd8646e566c593d841a9eb93fc5b85939.nq.gz
│   ├── fcbf6f3c164de07112f6c4539ff3230c142c2d46.nq.gz
│   ├── fe745ff6eb25dbdbd45fa966e175da51752bf6db.nq.gz
│   └── ff95bb8217b6b64162a2911f958f8c367bebec4c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c6406c3c2354849c3480c9949c1a22aef0a0e59f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 112 files
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

[ansible-collections/community.hrobot](https://github.com/ansible-collections/community.hrobot)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
