# Repolex Knowledge Graph of ruby/prism

RDF knowledge graph data for [ruby/prism](https://github.com/ruby/prism), parsed by [repolex](https://repolex.ai).

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
rlex download ruby/prism
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 774aebc1f307c4b86ce08d569b055fb1a182d2c0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 774aebc1f307c4b86ce08d569b055fb1a182d2c0
│           └── chunk-001.nq.gz
└── blob
    ├── 0083ef540ebbe22ba1fa9d482a1e8e1d70604d2f.nq.gz
    ├── 010e6eed5e708ca9a845704d0fbb69e0e6da4350.nq.gz
    ├── 01e1de644681eab7a552bf76654ec21bb10615b9.nq.gz
    ├── 02125b374da97f5d726309103fb3ff50dee96a3b.nq.gz
    ├── 03e17683e459bb18689d60cfaa54d35adb028e83.nq.gz
    ├── 0419b771124a9edcad9904cb65fd742bdc9d3a73.nq.gz
    ├── 047a3b67457bb41d9eaaaee99c7b68d03be52aaa.nq.gz
    ├── 0594f1c5dd48c6b4ecef8b37012a48ca567bf6c6.nq.gz
    ├── 05fe7c4d5f6acad49075ae8a859c5e48b6869df0.nq.gz
    ├── 06eefa4a1be9b4dd728a8389b2ac73297e739fa5.nq.gz
    ├── 070378d75b3f1735228561c46aa00df74023430d.nq.gz
    ├── 078174b4485096248fb0f9a13d8bb293fbecfc05.nq.gz
    ├── 08466554fd0f597e1b75eace2d463d13b2242fa6.nq.gz
    ├── 0945d611e9879e07658488cafa6d1564d5bb353d.nq.gz
    ├── 0960b2548b8dc46b06405eec27acc1aaff1dbe00.nq.gz
    ├── 09971a2971c9f360d73949036ce93db27333b205.nq.gz
    ├── 0a5252c0018b73c343d914eb1719e059a60b01a5.nq.gz
    ├── 0a873838d98b4a313aae82b8288935b69b10fd5c.nq.gz
    ├── 0acf868244020ab4b1a60e4c2c336c450a94cb05.nq.gz
    ├── 0b8e31632db22d8e234f4cebe281f26f1ed2aa61.nq.gz
    ├── 0bb6b9d2ba1bcc4adcfd3db8aa20cb13e1f81b15.nq.gz
    ├── 0c13801f9e4fe693b4090ce9fd88d0ccb8878d43.nq.gz
    ├── 0c7ebb3d304f9457d790104efe15133180e0ad8f.nq.gz
    ├── 0d2ea883a15e5d4174cd63d781edaa5916595a33.nq.gz
    ├── 0d4308afc50feeffd5080c85f43cd1c289acb80c.nq.gz
    ├── 0d5c858e0ca5e2f828fc8e599dac61585c5f1438.nq.gz
    ├── 0d995a04d1d670ebb0c316c35c111c8fd6b03fa6.nq.gz
    ├── 0ec160a71e73d2f3782c70a9c682e291bc641518.nq.gz
    ├── 0f5cc339618b949152bd0bdeda4c5244ce01c700.nq.gz
    ├── 0f94c9a99f38e2795ed11114089dab5148a1c629.nq.gz
    ├── 1094c461f44d7026b0583d6d3a58085bb3647d80.nq.gz
    ├── 112d68cfe1a6e457a8c037a8ddb38563d983d7ad.nq.gz
    ├── 11537023ada61a941fb792c240642e8f571be1e5.nq.gz
    ├── 11f23f034576b4978c17fb326f18bd68a80dd255.nq.gz
    ├── 12279afa2480fe0d63edcb699bf9e61e75cfb200.nq.gz
    ├── 129c349433739adb73b86dfc01b4ef325c0cf35b.nq.gz
    ├── 12c8fac1267db4a9c4b7e69404d56310132853bb.nq.gz
    ├── 13cbe26a9f730738c5b1cacd63051a5181d1d978.nq.gz
    ├── 13e3b35c9e83b639edf6057ab378af4519b453bd.nq.gz
    ├── 1460f7dc034abb4219b1dc16143b443d5ae4f9fd.nq.gz
    ├── 153fe8a1c6f7e99d65886e8b6a72cd3b54c406ac.nq.gz
    ├── 167eee194a66729a1eac2774d338a406df3a92c3.nq.gz
    ├── 1697931773e1fa46dcdc9bccab979199454622d2.nq.gz
    ├── 16c2e68a2b996abdfac09205b3873c78f6921377.nq.gz
    ├── 18e096f1ee2ce99a47a21349e361a3a7fbdbd38a.nq.gz
    ├── 1914c1208c75dea5fb61f966c0c9c04034e562b8.nq.gz
    ├── 198eb3f5973f4e93a378808360170a16678f320c.nq.gz
    ├── 199b0dca12ffdac6436529eb8a1ff1bc17c6228b.nq.gz
    ├── 19f999e2a4254a5b5f0c996a10f4f7da53a06d69.nq.gz
    ├── 1a93dc6c694326f3104cbd3484414370f0243e83.nq.gz
    ├── 1b22649b5ac4aa79721a8fe299f1794398e1967c.nq.gz
    ├── 1b4f90058e6bcce7d592688e39ad94bc1632c840.nq.gz
    ├── 1b86662008dee422ecd4a528126a9c1f9811d541.nq.gz
    ├── 1be2323db096a9f44d99be4dc6b367b82b0561e0.nq.gz
    ├── 1c521108c04f04bf29480869b64a64c219171f67.nq.gz
    ├── 1c58c05cc5b6795b54a9e6cb3319f55d18ca26b9.nq.gz
    ├── 1cd6703c82c4ce77ce1342ef8f0704608e39f2aa.nq.gz
    ├── 1dab6902a2785e24ebbe4ea7d267860a7ac193eb.nq.gz
    ├── 1de938f376ffda8871913c49ccea0102b1872ee1.nq.gz
    ├── 1e7b2e5179140a8df2694b2f0d110db31d1fd009.nq.gz
    ├── 1e9c2a94be09bebec3807390a5cf6e3bec987f25.nq.gz
    ├── 1fd9bb7327c2a5665e35fa84b646ce673135644e.nq.gz
    ├── 2002d67315c5a6366862405593d84477dc32e4a1.nq.gz
    ├── 21515ae9ceff6d9b7f150c6b0acfce546a439e7b.nq.gz
    ├── 21530307d2c960ad6885dcf2f97912fa6ccac39f.nq.gz
    ├── 2195c9e422e573bf4e56589fd6f71b2bfe15cbab.nq.gz
    ├── 224e33dd01095801f420fb2b426d8f825e15cabf.nq.gz
    ├── 226128cdaea51f7efddf58c8de1c15ffca77b2ac.nq.gz
    ├── 22736d30304944e12f9462a551fa27484e9ff57a.nq.gz
    ├── 235a041e904bc30996ac0b28c4212aeb0e9b7f08.nq.gz
    ├── 23f512fc1c089c2adede3382b10ebca7f8bac513.nq.gz
    ├── 240a6e78169f33eaf6c7fa3b1349d8d465630fef.nq.gz
    ├── 24e701d5661e7f7ff58fb728a767bb54ea29b24a.nq.gz
    ├── 25d43e00e1846ffb50b589c2beda7d4e6e972728.nq.gz
    ├── 25d77dac2d5df578470c2a01fc97bb7aff491b06.nq.gz
    ├── 25dc0b26a216a3d22ae8e5513f6aa9aaadc56166.nq.gz
    ├── 26029282e0355ec8eaa2601eb2700977b1e99bfb.nq.gz
    ├── 2897189518976be11c01c95fee14264bc7472c4a.nq.gz
    ├── 28b204f247d9f5c847bd03a0712a728700582c98.nq.gz
    ├── 291a775b356f5b2372978cf7cc6caf716c80b39b.nq.gz
    ├── 29af5310a15b1a7154e935b0c2982ccda7bcf777.nq.gz
    ├── 29f14c91abdfdf0d598ebeefadc921a747431440.nq.gz
    ├── 2b022a55f626cb470cd9d8d638bf85d06391eb89.nq.gz
    ├── 2b118aeb3e3f71961ed1a9768d5c87411839ea91.nq.gz
    ├── 2b228334604e2de21e7a6c79e2edf78da0b23b40.nq.gz
    ├── 2be13533199771bb9b78bdffd58849ad2bd5fdd5.nq.gz
    ├── 2bfced81feb169bd50bb071e9249faff847327b3.nq.gz
    ├── 2c386cc6a98dbff99a6a62e1229acaa4ef113b84.nq.gz
    ├── 2caaa5136e2ef282a08db9c6016b61601808ff24.nq.gz
    ├── 2cced0db75d50b73583e82da8c6067be8d9d3c06.nq.gz
    ├── 2d18c84b5710a5791befda73cc3d2ea08a77d41f.nq.gz
    ├── 2d250fba063bbcfebf38d0fef63df48892e69cb2.nq.gz
    ├── 2d711357fb58a58d3d6782e2d73fb8d855df54d2.nq.gz
    ├── 2f50494abfc901f1cc1dcc73cb852f130614a677.nq.gz
    ├── 2f52a253e0fbe91f9b4ce2512506cc7cebaf1ec3.nq.gz
    ├── 3034a9ad0fa0495e238e09df63f2ebdbe9bb23d7.nq.gz
    ├── 3058ebce963cbbe61f078455f733dd9c722b82bb.nq.gz
    ├── 30af56c719da9f7f786396e967d09a29bd354f1b.nq.gz
    ├── 3112f269e125aa1e82d891ca3b0a5c17453400d9.nq.gz
    ├── 31b19dcd6e6c0b2b1fae112b9b543537d2e0becf.nq.gz
    ├── 31c344ea90202e1991fef17fcf6ec25b66884d94.nq.gz
    ├── 325909749285c7a6dcfb4a34c21643b1ee8bf3a2.nq.gz
    ├── 32a2d87b2454194d19d4429a6876285c3be8f518.nq.gz
    ├── 32b77d127c0a66a820038ca55df6411a6b1c4807.nq.gz
    ├── 32e1ebdaae172a53982529b3630e8420282fbede.nq.gz
    ├── 333a6862ee8d2ae8fd1e392784077faab90529c0.nq.gz
    ├── 334b8d74dab8a86e80b2d3bc5fcdcb1a28878888.nq.gz
    ├── 33ceff2489fbd91d18dc01c19d19bd662763f6ee.nq.gz
    ├── 33f4bc0e73630cfa11069d1d85c6f96722d5e982.nq.gz
    ├── 360c5150a51f93aaff37dba87c91718744a8ae73.nq.gz
    ├── 376dacd7ccd8880aefb1dd6a1f477acbe161ab8b.nq.gz
    ├── 377860d12a2444cf9878fda95925bc999a21346c.nq.gz
    ├── 38cb995c09325865582a74299f5f6e8f77b1e1c5.nq.gz
    ├── 39181bc4c4c0012363f5b14147b20c54ab7ac184.nq.gz
    ├── 393cf63f5a9bcd050a19c766c05d4e7fa63f348d.nq.gz
    ├── 3964df0ead1e8fda716f2898d37c79545be57529.nq.gz
    ├── 39c40ad7b964444892849fa14f364e82194ac8fd.nq.gz
    ├── 3b605657de11374643456bf38c8f5e8f774e548c.nq.gz
    ├── 3c750a7ef915944ed36ba7570697ff526d1183b8.nq.gz
    ├── 3d6d7f42867adb059f0395a70bcc33252808a74f.nq.gz
    ├── 3d9040fefb7bc305054e747fb7553e2c4cf46b87.nq.gz
    ├── 3dbb961777a8f8eb6021163e03353428b6b0e3e2.nq.gz
    ├── 3e1da36821db8c0d6778fc3a8aa1897e8cccefbd.nq.gz
    ├── 3e88c098378ee52501aa28acb5fa3c24bfdf65b6.nq.gz
    ├── 3eb49743190e5956e07bcb644062f4622f412e91.nq.gz
    ├── 3f6af5e0ee49a9830d60109bf5f18b058309978e.nq.gz
    ├── 3f70813c16e0e276f3cbc3fde438e614a7c8a822.nq.gz
    ├── 3f78b434d6c43626f8371d5afc2a3ee9f59ed9a3.nq.gz
    ├── 3fa9b5a0c56abef1f0ebccfdf965350d735925d8.nq.gz
    ├── 4004aa882da1f69cc998decb805fbfb80782e955.nq.gz
    ├── 4046cbcb3e55ab7935aadc30c7711acb7a531234.nq.gz
    ├── 40c0474badc142634dc69203f596f961f527c745.nq.gz
    ├── 40fe7d862e135cb3edea4be6bb578a6111c77d42.nq.gz
    ├── 432531b577c70cc5bf4599f4f3272819c6378b0f.nq.gz
    ├── 4420560d2bee836cd82da7367aae62383937ec58.nq.gz
    ├── 445ea0efe90e4e9f471150a8385d895c776d8375.nq.gz
    ├── 44863d7afb95c96af5f4b5437a394ef66a7e26c6.nq.gz
    ├── 44dde97c79e016bbb9d9c2c6a1f773601e568ebc.nq.gz
    ├── 459da080569a4497c0903ab75c0ab3a6f645ed46.nq.gz
    ├── 469110f86feccec1cb81466743991ef937df153d.nq.gz
    ├── 46fe75aaba325b0778309f9f422a1ab32f854c44.nq.gz
    ├── 47ff3c907025d67e548f3d433343abe7daeff400.nq.gz
    ├── 481457bf0ebdd3fe58eea8da0713e1ec692b8f13.nq.gz
    ├── 4940b736c81883e2aa0eba90878bc6969dc03e4b.nq.gz
    ├── 4997896e4a9da8c2b0c292f98741878648c3daa1.nq.gz
    ├── 49acf2ffa282603ee35013be7d1eaef8dd367821.nq.gz
    ├── 4a8e9e91e14afe6ad76987724f3cd0a4f5d53a85.nq.gz
    ├── 4b3b985e52099ea556b8a525287e88fcbe88b6a8.nq.gz
    ├── 4c529af1bb20dc93d54262048e5dbcf931415445.nq.gz
    ├── 4d23970595fdf013baf8e06921214671459348d0.nq.gz
    ├── 4e084661bfa5b4f3a976c54b72e3fe73f2213293.nq.gz
    ├── 4e1360580c4982428a2eb5424a1f193a8f6df594.nq.gz
    ├── 4e7a3c0a142af6ec6cfc36795a23e6c49a447d48.nq.gz
    ├── 4f35cd84af66f45ae6d86c815c0aaae6d9c09228.nq.gz
    ├── 4f4dc6f9c821123c85105e3706393d4bc265f8e0.nq.gz
    ├── 4f6dd71b389055cd5cceeaf71faa41ef45992cd6.nq.gz
    ├── 4fb4ce99f8c3da8680c60508b8e8d872a34aecff.nq.gz
    ├── 500b2d9875007d6434efda33d301d356c6f014ad.nq.gz
    ├── 5016a7c6b961464e2d82bb496f6538756cd99b97.nq.gz
    ├── 504eb94d5b5f6b52dfd6cfb4884ac5adb556b485.nq.gz
    ├── 50795c935338960b812118f622504ad9d8d5e15b.nq.gz
    ├── 51dde02ea38ebf80e40c5ef7745b1303ee59694a.nq.gz
    ├── 51e62076038d40fa29f85901981e622064d9cb19.nq.gz
    ├── 51ed4df11b2c7c46af139091883ac853ba28e785.nq.gz
    ├── 52759b838fd1d915419ab7d9adbbfe5c2ac4471b.nq.gz
    ├── 538073fb0e02bc4b85ef4877734ffd41ec72bce0.nq.gz
    ├── 5410b01e711a3ac7544fd0f1aa6bee506f8bb265.nq.gz
    ├── 54c003a35cbdc45dccd5b0c0dd3b88382797454b.nq.gz
    ├── 54d8f588d7295014cae7fee133efb919dbb32894.nq.gz
    ├── 5512f2089e9cc9a3276647568db43bf2430206ca.nq.gz
    ├── 55dfd316ac7886a022104fc6a94115dad389d7a6.nq.gz
    ├── 560d61ef4d01f1a61ff94cdc9e8d15c73951f9c5.nq.gz
    ├── 5666019ef1aae197844df07e888ae5f9da0dd063.nq.gz
    ├── 56bd1629987ce812b171cdca730e912b97baeb05.nq.gz
    ├── 5717c60762ca7a82fc63c145f964339dad5f776e.nq.gz
    ├── 574b2a4280c7dd49633bc157688b714b5443e44e.nq.gz
    ├── 5968124385510b552bf6eb8151448d9430a0d28a.nq.gz
    ├── 59a70e6db50f27e9e0885e489dca4acd5553aef2.nq.gz
    ├── 59b79bc5746693d8cf0fbc4c9764466e083cec6b.nq.gz
    ├── 59cca7dd5dc153959568f487246cf8b1009cbb05.nq.gz
    ├── 59ee4d0b88bfe0963a42af1c3f7f41472cfb2079.nq.gz
    ├── 5aa464167f7f43b24d845a7118a81537774650ca.nq.gz
    ├── 5abb8d6334a3f960148f37559672788b9852d498.nq.gz
    ├── 5ba379f3a037efaf2550c478f18c279aca6b2e1b.nq.gz
    ├── 5c1d3390b03822fc179073af6af1c45247b1e51c.nq.gz
    ├── 5c36d15e1b8556f44c3f71da31efa28f696cc82c.nq.gz
    ├── 5c4ab8d92a8e7295e82bee6bfa138a4eb3247995.nq.gz
    ├── 5c71ddac1578886422b259bee5cdafb4a57ebc0e.nq.gz
    ├── 5c73907cae8ea7fc6808ead2f3a88f5a46b3ed58.nq.gz
    ├── 5d143a3f5dc71d9ddcb73afc09a4fdae8d27463a.nq.gz
    ├── 5ec89d6fcc0e9df5ed692455e0691d5b804211e9.nq.gz
    ├── 6048008584e8042911dc68a23f509c09f7e8ab86.nq.gz
    ├── 607602cfc6edb269616386ff415b62c34bd08d94.nq.gz
    ├── 619b2c915eb1792c01ad41c37d5f2818a7a4bc4e.nq.gz
    ├── 62292519692bf77d657b48d55395f7893cf06bc7.nq.gz
    ├── 628c36ef1331cff71c908cd9ef8800ba6d8cdba6.nq.gz
    ├── 63293452b3248827384c711e4fe5835d1888a5fa.nq.gz
    └── 63ba92e5339f2d7353198f1a2cb3da3c9f8bed78.nq.gz

7 directories, 200 files
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

[ruby/prism](https://github.com/ruby/prism)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
