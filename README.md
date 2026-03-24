# Repolex Knowledge Graph of twitter/the-algorithm

RDF knowledge graph data for [twitter/the-algorithm](https://github.com/twitter/the-algorithm), parsed by [repolex](https://repolex.ai).

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
lexq download twitter/the-algorithm
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
└── blob
    ├── 0014634004b99403fab5cfc2375bcc3b809b447c.nq.gz
    ├── 002e902753766db73c806df3842f005a6e638ecc.nq.gz
    ├── 0030bcd402e7c823ea0f7ad6c0a6e2b719b20c60.nq.gz
    ├── 00368f07b119d4b3f19f1c56b4761a1e128a7855.nq.gz
    ├── 0037f7e6927a3e71f3f565131da0bfd29057e54f.nq.gz
    ├── 00383f6ce6c7b386200b733883f17faae9b36a92.nq.gz
    ├── 004a141bb239f432d92c361600caa093e8dfe9c1.nq.gz
    ├── 004f52092a4df3b65f1a0a89c877646dccda84be.nq.gz
    ├── 00510a3e3ebb11dec46ccfb5aa228157e9996966.nq.gz
    ├── 0062a95e08ea0b600dddd9e93911d183c351fb9c.nq.gz
    ├── 008a59f709e542e98448f5fec5e983a6b04124d6.nq.gz
    ├── 009c04a683031db4910ae7138f3fe657512048c5.nq.gz
    ├── 00a78b53533ac4076a420a8832771069405157e7.nq.gz
    ├── 00a90b0ce2c81fc8582163dc5e62b1420a751727.nq.gz
    ├── 00aefb80033948c114683eac64a45bc503b13e8f.nq.gz
    ├── 00b2668cadf26a902e4ce076e3e8e9fbf097173a.nq.gz
    ├── 00b4d0454bd8da031c60e31922cc813e0037140f.nq.gz
    ├── 00c0534392a0270572d9362a5c1bfea5ea39b824.nq.gz
    ├── 00c5cf7360bb9d89464608702dac784d58586962.nq.gz
    ├── 00c72d4e5035c45695deade0f7ceb8330e44f9e8.nq.gz
    ├── 00d7cf6a16334f8636a641fcdf7cd140cd214ad7.nq.gz
    ├── 00d83fad1b830c9310442ed74df1473208b8a2a5.nq.gz
    ├── 00dee12094b4ac1cc6756beec3aa48fb1a3aec2f.nq.gz
    ├── 00e2bb20067a0a568772431d05e9ebcb872b5c63.nq.gz
    ├── 00f1c8deff75a281e6da5c026c8bbc0570d1b3c1.nq.gz
    ├── 0106d7a2893409ac0f76d8925fbf45903f4c6581.nq.gz
    ├── 010adf56b355caf01acfc407f6949bc635a2561b.nq.gz
    ├── 010aea509a851cea7c27711362fd4cab846cb6b6.nq.gz
    ├── 012103b14332d8511df57309eb0c0a69ef04ae39.nq.gz
    ├── 0124d0be397123c21c5fc6d5cde01ee87963a556.nq.gz
    ├── 013215cec10dd4db43f5c75efd3cb053851f3e3e.nq.gz
    ├── 01324f3c58d7a251f10e2187998212a6cf4b6923.nq.gz
    ├── 013bd0dea0a03bc1bd3fc149c1c5dcf239e1baa1.nq.gz
    ├── 013f1dccc9caa3c7815f7aefc780f54b5a3a10a0.nq.gz
    ├── 014393870c1bbb725f5eb387cff5d71caab89d18.nq.gz
    ├── 014533a43518f66e3d6bc7099f268eab7666c416.nq.gz
    ├── 0146a34938c07d0d2ad7c9e5ea33ae2626238c73.nq.gz
    ├── 0148c5f393ec38c92ed660014fc7f745fa22c727.nq.gz
    ├── 0154a17033951442d525776267de069cc65157aa.nq.gz
    ├── 0154c71dce7aa16da37473a91cde3e04a1253d2c.nq.gz
    ├── 01575db925a2b840205cae99678a358568e9d6db.nq.gz
    ├── 0158b833ae5c815c50d19c0939345281a654394c.nq.gz
    ├── 015e065ec0c72675777bbfab777201e8cd44a2a0.nq.gz
    ├── 0169e6dd748c2e55ac7974598c1c8ce26d5197ec.nq.gz
    ├── 016dd4262b2af889c82b077ac17c71e4a6853437.nq.gz
    ├── 016e6262e087f7beb723dd5632645bbe2f42e762.nq.gz
    ├── 0177996ec906295fec7b972e2c14e938546fc8e5.nq.gz
    ├── 018cef9eb47f45ce7dca93bb7a9dc259c3fcdeff.nq.gz
    ├── 018fe413bb39eb28c8fbb734ba609b6648535e66.nq.gz
    ├── 01984a51d2a8f85a999af4c653a5db377ae7e775.nq.gz
    ├── 01a1ab393949f1a7caf766b4ce7a0fa703c91cd7.nq.gz
    ├── 01a327f86db8a4292ceaae971fdf22842e7b66a1.nq.gz
    ├── 01a5f96fda127353f02ae6a780d9a8bf1ca20be6.nq.gz
    ├── 01be88a26c9e119ee32d61385093ecb69bd07ec8.nq.gz
    ├── 01c8d0a725cfdbfbc7ff4dd464a7d802c0e55261.nq.gz
    ├── 01c930e8ed8e3991a75860267fbe0c308da85b2e.nq.gz
    ├── 01d302661ee48f3b578198e0f2c086e285ee3799.nq.gz
    ├── 01d391f11b2c36907ac1506cdf4f04ab6f601a3e.nq.gz
    ├── 01df5365fad6d9585ba3bd678671c5c00f0d7f1b.nq.gz
    ├── 01f1501ad0066a6829b9b3347ab9f0e02850c1bb.nq.gz
    ├── 01fbd8f38f0c0abb3e43f56338469513ef9a72b1.nq.gz
    ├── 02019fa6d6fc147b80c52d79324b8a7ab6e59dfa.nq.gz
    ├── 020a0cc5292833ec23463d87b9c6ddda860b708f.nq.gz
    ├── 020df461b453031e302f858b7d092390c0715a8f.nq.gz
    ├── 02181ed12d21fc769435983eed92949b7ed75c00.nq.gz
    ├── 0221bc318adf4cfbbf1edb978f80abcab7134c16.nq.gz
    ├── 022343cea40582c896d7e0c809d67c5ca3dadeda.nq.gz
    ├── 0227f8057fbc34a170bc62d9d673d844cdf6acfe.nq.gz
    ├── 0228b4a0f41c41957c09afc28a271d0e4c2c402e.nq.gz
    ├── 0235a20deb136d09e1bf6f7ec3e5bfca83a15b52.nq.gz
    ├── 0238b654476793b9372004ae19b9cb3a99e0d2c4.nq.gz
    ├── 023adb81e3cddd042481ddde3ddd0e32beca680a.nq.gz
    ├── 023b4c63ea7a3b690dd596eff9780df05649e4cb.nq.gz
    ├── 0241d51dc62ea47e1d008ca02fd176e4f5ee9bfd.nq.gz
    ├── 0249798bda512d37a480303f1ba87babe448cd28.nq.gz
    ├── 0249e29e3301b75901f7df05d888a7e20f6fb25c.nq.gz
    ├── 024a14ea4691582d1e482267676b2eabc20eaf16.nq.gz
    ├── 024dcf55b8169df5cbb72dd9af2e8a2a68317116.nq.gz
    ├── 026be56990aeb3a30acaa8216e721a5815940028.nq.gz
    ├── 026cfa696df6f83932330951923c0561bb73ed73.nq.gz
    ├── 026df3a26cd530891fb94ee6be009e3f2c895265.nq.gz
    ├── 0270a81ab07e4b493dbbbde63143925d0540ca9c.nq.gz
    ├── 02752d08dbab57367b3fa1c6548d3aa920912174.nq.gz
    ├── 0277c6aaa310c28eebc56ed172b0bdf3c7b049cc.nq.gz
    ├── 0281c1a30764e69834c0640b5138af2aad35ee54.nq.gz
    ├── 0281de0ef042255a32a075348f95371186418e98.nq.gz
    ├── 0286023c72950180d6c1a90b10ed22c7547fe0c0.nq.gz
    ├── 02944c556f414b3150e101bfdcf26ff300597c63.nq.gz
    ├── 02c92b0d6d6329d62183121a9dc6e57a2b3adc96.nq.gz
    ├── 02eb46b5a728e319cc988558e33576725ec34648.nq.gz
    ├── 02f0287f5cf0dad9953333dd2c077d05e5f4858d.nq.gz
    ├── 031b6d9d8efda133c7f138c1a009503798feafac.nq.gz
    ├── 0325abcabbeaaa7212c2443cf50763a007cb86a8.nq.gz
    ├── 0332e981951ab51be8467e51e9b9307ad2401b39.nq.gz
    ├── 033b746623b0dfe9a218beb13cf857e211623430.nq.gz
    ├── 0344fe0d07efadd4e733cd7ae73c97dacf78e752.nq.gz
    ├── 035cc04bf2a842a760bb1dab2207620cad099d70.nq.gz
    ├── 03639da26df3a217a61b54d263a6b30e4f0bcfb7.nq.gz
    ├── 036e6730ded49981e2e9130365926eb6992a55fc.nq.gz
    ├── 036f91bf8448edcf3c57735d8fb4b6b5433d8a61.nq.gz
    ├── 0374791115c82222bc00d3da2b03abd119cee406.nq.gz
    ├── 03826fb3348a46dd8f0553ad3f4b6bac4572905c.nq.gz
    ├── 0382b147224434a63ac01ae65a5a6872e284c795.nq.gz
    ├── 03844fd38c6807e4296551b75ee66e8a41a35efd.nq.gz
    ├── 0386c5fa841d2a3c3a3393f2225c95aa63343ec4.nq.gz
    ├── 03894b533b4d34a02ced40ee82775b21100e371c.nq.gz
    ├── 038ff90db0a9e248065a523d75b3488be95bde5b.nq.gz
    ├── 03996dfd762441b0c9efd26da8aa2570157de41e.nq.gz
    ├── 03a1125784b9e307295b41f714a1580b8300da61.nq.gz
    ├── 03a247afbdac06d145f57af2b8c91ad0afc08f0b.nq.gz
    ├── 03b1ea2aa39935ecff3091e39b7b396998d44a77.nq.gz
    ├── 03d70445e194a5810f0d34f1891ca0e6970a07e9.nq.gz
    ├── 03e094025f09845d4fccf419f3d7cdf5a275c745.nq.gz
    ├── 03f0946f22ebde7c8ca35301d9a704a265a4793e.nq.gz
    ├── 03f0e343e282702d4053eac021bc90d815f325e8.nq.gz
    ├── 03ff94ff2d439091e8efe22616785a1c1eab6ee0.nq.gz
    ├── 04000837b7173a910cab0ae7aae3ab6e6cd6ba8e.nq.gz
    ├── 0405436609189666d616a3405b5b123c444e4ada.nq.gz
    ├── 0405ca0bad3f5ad6f09ea7d433fd02a341832422.nq.gz
    ├── 042789dcaa4dae846b3dac3ed4d0142c7ca01e8b.nq.gz
    ├── 042d214f24f557c84e10e4c19dbf63abea1b4064.nq.gz
    ├── 042f9dc6945335c73e38b36fa19db62b5e50a5d5.nq.gz
    ├── 043279b447f9e6a5a50d9becebf43e5e86ac2800.nq.gz
    ├── 0436ca3c7c42520c3377eac5dca5b02bbab247cf.nq.gz
    ├── 0441774384cbc2515c4ebe82c2eb406b4e92263f.nq.gz
    ├── 044c0afdb6c9d3c054028c299ab2c56d4cd39dd3.nq.gz
    ├── 045d1256d907dd980c2922c267cd7e78ec624b90.nq.gz
    ├── 04614da8c6bdb11b217057aa3b48d59b72d65ab7.nq.gz
    ├── 046ff226aaa64d5c8c5a1a486dcf4a67cd10c857.nq.gz
    ├── 04746792b03d4a8b2626bb043ff46686afb1d057.nq.gz
    ├── 0476dbdedc6c9bb38ca10978fe59726d3db7bafc.nq.gz
    ├── 047e349ae40779850d5390af723a74ff71bfbf91.nq.gz
    ├── 04887b9cfddc70221a1f1f53de9c4d321c15604a.nq.gz
    ├── 048d22cc1642d69f6ff8517b287b6f39c1eddd4f.nq.gz
    ├── 049762e28bcba0031631dc7079f232834813a602.nq.gz
    ├── 049d33ce837a0bb8e597d7d5c93fc17c6fccd43b.nq.gz
    ├── 049d731a31bdf591c9ff21cc9ec0d7877119545f.nq.gz
    ├── 04af003f08a64cea390476c276955ca06811d650.nq.gz
    ├── 04c03eda683aa3858deb2bcfbe51eedf15363978.nq.gz
    ├── 04c22067a6a38f7e7a1f84fdedfc438368fa5d82.nq.gz
    ├── 04cd08e300e58499b82f07e84697aa80d9a6b43f.nq.gz
    ├── 04d686c207fd75985b83c19e22bb2a5c9b1c10b7.nq.gz
    ├── 04d6fae7b61686da7b1b2ccfa75a48dc27f3f83c.nq.gz
    ├── 04d8b8cb1622ee339f1c7f4ed616ffe88aac111c.nq.gz
    ├── 04e797b1bbbd41920349742e90c53fa6f82dd27f.nq.gz
    ├── 0503d878211d08f1d87ffdb1693948edda85ff33.nq.gz
    ├── 0504d7429ec413212eba12b8b17890d3534c75e9.nq.gz
    ├── 0509738a0d44a035e4d7c2710d3ca1e38668e92b.nq.gz
    ├── 050ee22d1d921e914528394bbf2231d10c6d0f8d.nq.gz
    ├── 050f2ab674b9e39c20c8a3434188053ed4546ef0.nq.gz
    ├── 05240a66ac65dd566ae0b2fce0ec08a288237a4b.nq.gz
    ├── 053a4e1156bdc7801f6fa90da6ef646e9f0594b1.nq.gz
    ├── 053c16a3e53c664ed6e857406a61035970bd5e84.nq.gz
    ├── 0542cf4f5dd4569212943ebdd201b860f8455eb0.nq.gz
    ├── 054d5d4283ee1031de471204204fa145196a38f2.nq.gz
    ├── 054e12242b0efc52cf0b0814627fc80ae5bfe0ed.nq.gz
    ├── 0572e43bfab716f094f630b09ccb0535c362fd1d.nq.gz
    ├── 058bcbce5e3cd75a2640fada0d1e3e35ee10509d.nq.gz
    ├── 05ab3a13a89ee653cccb148fba7fee4f11dbc9e8.nq.gz
    ├── 05cf496d89ec68dd8f04bb95973b8232b4c98de3.nq.gz
    ├── 05e98c17d861a3f0172f81e0145d4f3a722606df.nq.gz
    ├── 05ebe46f7391f60c6df9fc9c806022ff3b68c4d6.nq.gz
    ├── 0617d5733c7eb7928a9a5f8fafdd9ff9c975b1e4.nq.gz
    ├── 062295b568899efe2df753c5727ec84ff836c225.nq.gz
    ├── 062428d767c050b8a6f125fa705e18d1d5f52b42.nq.gz
    ├── 06295fa251bed57991f1f86391d5ad1ae94162ca.nq.gz
    ├── 0629636c07638c29507e56d4776ea8ea2dfb8205.nq.gz
    ├── 063b873dff996bd17ba5b2c0e1ba0505557b5023.nq.gz
    ├── 064819bb0fce113761f111b23dcf7024d2e52ee4.nq.gz
    ├── 064bb8b1aa8a8a4977f4547ade9aa1c0c477d61a.nq.gz
    ├── 065a83eece751622700776632299fb9ad6870ad5.nq.gz
    ├── 0661db8fc2465c48e0229194a816329ff89c110e.nq.gz
    ├── 06666adc0dca3388332dcde9c1cd38cb9d91fd52.nq.gz
    ├── 066b2271fefefd2f1bc6e88384eed937b556ee3f.nq.gz
    ├── 0672a76be8d06f37efaeb3652e6aff6e497229db.nq.gz
    ├── 067ba1a46f7892f47c001a1666e03c2a2e333700.nq.gz
    ├── 067fa833f1707685fd168364598680a61d0f5c58.nq.gz
    ├── 068450e020358b8a934b77368027cccfe3f879f8.nq.gz
    ├── 0685446f31593942fb72f15abf89eb35e9f94bb3.nq.gz
    ├── 068a283ca1f4646c2143af002ec1a1bf8be871b1.nq.gz
    ├── 06942205dc2535229ef4e465a70f93d556da941a.nq.gz
    ├── 06988446665466ea1ab9200d425c7bd354f3af7d.nq.gz
    ├── 069e65d797734b99950df2c01fbb70cbb41b867c.nq.gz
    ├── 06a2a8c1021303e4605373c10a66b21e454e7bac.nq.gz
    ├── 06a358249aaa9b326c413357e5d9cc8f501a4d26.nq.gz
    ├── 06a50726fceb7622405248543c81feb1f4ec733b.nq.gz
    ├── 06a6d79f52ae13759a788b0dace331a26e9c0b94.nq.gz
    ├── 06b19ac46ccbd9017b2d86887980526d6b527183.nq.gz
    ├── 06c61934e658c41b4cd132eb06a1326e4ac334b3.nq.gz
    ├── 06c66038c90e9672f72db6ff79ea150c151540a4.nq.gz
    ├── 06d9a21861f004276291ffc0eb0127e560b001ac.nq.gz
    ├── 06db35e078d9c62e7288cae99fa741ff609a8e7e.nq.gz
    ├── 06e88cc08e9d84153f7a215d7442892805002ad4.nq.gz
    ├── 06eb2492df3dc45a50d8ac404b52f1abea1f010a.nq.gz
    ├── 06f59a50d97c2f82f5e70a663f6159e4d8866f9d.nq.gz
    ├── 06f7bd14cdaba2cd64d551d9f1bc9f1589fef166.nq.gz
    ├── 06fbbbf99c11b02503fab3df479b222d3689a28c.nq.gz
    ├── 06fc76d18339dcaedbf4592d573873fd3b18bdf6.nq.gz
    ├── 06fff4ed2fb2a7bc3056efb64bffa79c95af2c73.nq.gz
    └── 0713f728fe996ff50118fd00e00f57ae268ccf97.nq.gz

2 directories, 200 files
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

[twitter/the-algorithm](https://github.com/twitter/the-algorithm)

---
*Parsed on 2026-03-24 by [repolex](https://repolex.ai)*
