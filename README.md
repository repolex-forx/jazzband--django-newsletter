# Repolex Knowledge Graph of jazzband/django-newsletter

RDF knowledge graph data for [jazzband/django-newsletter](https://github.com/jazzband/django-newsletter), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-newsletter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fbde7a13ba686156d355b613a1d03d2595b4b89d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fbde7a13ba686156d355b613a1d03d2595b4b89d
│           └── chunk-001.nq.gz
├── blob
│   ├── 004972bc8a427e143401458a7859ffca26e57453.nq.gz
│   ├── 00aa450fabe2abd381cdfcf84cf38d40aac62032.nq.gz
│   ├── 00d3a1b15829a11dbc83861677fcf677431faa24.nq.gz
│   ├── 012a13f62402a4c472ab9684ddfb89659ee66551.nq.gz
│   ├── 01c7981b8c0d5c13c7ff7f309d76d3b472fc458a.nq.gz
│   ├── 029fd7cf43953b08bceb81a83d4cbfcf6a22c76a.nq.gz
│   ├── 092a6d1b391a3aabc0f111ca03290e290fd0a4b4.nq.gz
│   ├── 0976544a5aa95fda68114157ae20254c8320a8e6.nq.gz
│   ├── 0ad25db4bd1d86c452db3f9602ccdbe172438f52.nq.gz
│   ├── 0d08dc0be71eb19aa5bc2b6e367b39756e1a908d.nq.gz
│   ├── 0f6e908785f3307708559b00dcd3919e515909a2.nq.gz
│   ├── 0f82fc44db00d2ff6847895e536fed1c3ff8f368.nq.gz
│   ├── 0ffd0a1ca7c13d535b5d19b26cb992a05dc55f0d.nq.gz
│   ├── 0fff5ecbcfeca1f267f584475f126b38dc797b65.nq.gz
│   ├── 142f8db293b00e55a3f60dd6bd77095847427f97.nq.gz
│   ├── 14cea26025ada77cfc14559099108c92bf164987.nq.gz
│   ├── 15177eec1b97fc3e421deba1136d9f8bd326c295.nq.gz
│   ├── 189cfc1a6f33973459f44f22ab56364a9260494a.nq.gz
│   ├── 1abe82c066a5f01f305146acd8c3e12dacf046e3.nq.gz
│   ├── 1b4ee5814570885705399533f1182f8b0491c5fb.nq.gz
│   ├── 1da11d5334c3c102ac38762a561696951bcd1da6.nq.gz
│   ├── 217d5f6f7321072013c7b3d3f8694f3c2c1e4987.nq.gz
│   ├── 21b01760aa012e8e2607c8bc48e8a8a07badcb52.nq.gz
│   ├── 221fa6b219968b6595803353a3fc919e96a107ed.nq.gz
│   ├── 230a94be6d75629c39804219f3da70451d8c7909.nq.gz
│   ├── 259158998db3e37c927ab0ae8cb1f374d589104f.nq.gz
│   ├── 27fe8ce0be6ca404f1a7d472c13224fa05f62fe4.nq.gz
│   ├── 2919b3e2c163c1897f000c8006c9449fd16dfd58.nq.gz
│   ├── 2ad7cfbf15295090d0a573f44259751478384bba.nq.gz
│   ├── 2f42193a2cbcbf5af41a606d45175ef3de150daa.nq.gz
│   ├── 2f8ccf4a3121cbfbb71ed67b01747c4135543d7a.nq.gz
│   ├── 2f8ff77af0eec50eca10b96e972cea7faf13f0c6.nq.gz
│   ├── 2fdde98e0b348ac36a3c866297e0baae819fd816.nq.gz
│   ├── 3053bd11b4996d24df0f41b674429e06de278e9d.nq.gz
│   ├── 30f400d4c497efb6931f568baef9d150b463aa95.nq.gz
│   ├── 31f646b25c37da054de01ae7c300ed483594bf8b.nq.gz
│   ├── 32c40b4fe882ad105cb42d3af3fe1a372cf4bd1b.nq.gz
│   ├── 357d4cc2a30a47ee1faddcfe6ae1cde2e32493c8.nq.gz
│   ├── 36ee3b87356d840260b67e13120e0d351c62a47f.nq.gz
│   ├── 370cb445b37286633c1dbc2155c062d3a2886cd1.nq.gz
│   ├── 383e9ab17e5490c0d6d0bd4a759a55de8270cde7.nq.gz
│   ├── 39be29b5631881da8e6e09342bfb8892dc8577ce.nq.gz
│   ├── 3c418ad2d50e24dd75cc33a77f19bb1de77af9c7.nq.gz
│   ├── 3f440c2a75b3864f2bf98b3e03f9f40810299240.nq.gz
│   ├── 40333c0f3e141db045255ba94d15bc338f5955c6.nq.gz
│   ├── 4266591a1ec98d8e3ba1551ed6bc3351cc497387.nq.gz
│   ├── 42db22a4aaecd00038d3fbeefe83aca2080c67ca.nq.gz
│   ├── 45dfa38f50b0681e52d593b2ad6a2939ce73b092.nq.gz
│   ├── 45e252944e952b9d3e913d8a669fdbb276d09df0.nq.gz
│   ├── 471c1a4f93f2cabf0b3a85c3ff8e0a8aadefc548.nq.gz
│   ├── 49c68ef1379aa2018a4a512fc19292c2e5c55828.nq.gz
│   ├── 4df9a0d6730e1b8724240ecd9803f68354b3df66.nq.gz
│   ├── 4eb3014639456ecbac64a3c822326114a44885dc.nq.gz
│   ├── 50798a88a38781ec4908f3f4b7357c541b395aa0.nq.gz
│   ├── 51299075479fbc380de6c34a67c0cfa2982c9a8d.nq.gz
│   ├── 547766eba9317ed1096efd060a2d2bc6ab6acd4e.nq.gz
│   ├── 555e122f0f60f3adbac507c4298756afd56bdda4.nq.gz
│   ├── 575bd6e8d77ceb7c22108ff9bef8c20d244b4126.nq.gz
│   ├── 57ea1d22c95f90b56e331115655e0d88f760e346.nq.gz
│   ├── 585c8174ef93a4e60d62bb28bac820615cb1816e.nq.gz
│   ├── 59245b6bb41e2d36f5f44ef45c75aa562a615d5e.nq.gz
│   ├── 5938de33154d3d3ff71c74f3e2d6cc1af5d7510f.nq.gz
│   ├── 5d1ad52e0617a961968ccf58f469c46ddfc36aae.nq.gz
│   ├── 6195919f0c737e981ca88799336d1d2b2b301d46.nq.gz
│   ├── 62790066499b609e4985e0501da3e0d920e27c82.nq.gz
│   ├── 6349d3e2dcd42c33a126450bc51016f3af028106.nq.gz
│   ├── 63653e889f2ac371acc633ee0b1967f402e9b74f.nq.gz
│   ├── 69738956f512557cf88977d7f4199d38c49e7468.nq.gz
│   ├── 6f0b132cdaacd93c3575579f319d94af5f9f26a0.nq.gz
│   ├── 7092cedb0b9ce0070fefb8f89c6207df2e39a87b.nq.gz
│   ├── 723fcaf6454b43ce719f929b921b38dcb58b1d6d.nq.gz
│   ├── 72d56d1633814331c2c671c4b300f23b94fe41c4.nq.gz
│   ├── 73361ae449a3f0a38bb7249219a745e3289bff07.nq.gz
│   ├── 733c11d72685f9b2ff7fab7201f32432c00f8329.nq.gz
│   ├── 73992827403791d6c1a75a079880e41dce7e0214.nq.gz
│   ├── 73fe9023f8dab7069b9c68b6c1453c3d07389fab.nq.gz
│   ├── 746662fd2af8674045fe7cce26e0bd27d85e4bb6.nq.gz
│   ├── 788684201b86f44a75d3bbf74d795a1ad6a6802d.nq.gz
│   ├── 78fc0258a8a48f5b87c5a93bdcc931a7935ce913.nq.gz
│   ├── 7a017b5bc1e66a478640312bbf1d94ff30184910.nq.gz
│   ├── 7a6ced1aa2babfc711d369bc02421ce17d52afe1.nq.gz
│   ├── 7de08f6e3426d0d3167939e8086e01a455ba8b60.nq.gz
│   ├── 7e2e96517671b21a58cb9ea05740053cf177832f.nq.gz
│   ├── 82974faf072ea4137eb17c61fe12fbce5878409a.nq.gz
│   ├── 8443d3a1cb788b7e196d22371506865115608ba5.nq.gz
│   ├── 848990e729d9bc9ae17f18d1e48a57cc56173f78.nq.gz
│   ├── 88c7d21e914aafda3415526afe5024d266580459.nq.gz
│   ├── 8a14e5c96ed30cf0e16923bddcae2f25f8e07eb6.nq.gz
│   ├── 8ad5651db260db7464f476ed0957c5ea633dd632.nq.gz
│   ├── 8e341cd46e8f854481cf5cdf3a66bba11fb72d00.nq.gz
│   ├── 8f9c5d5882835678f56556fa8e864b231bdfba81.nq.gz
│   ├── 8fc1f833e829b37f2a79583797ee56710904c3c4.nq.gz
│   ├── 90397d6f1651cc6a378945813450f82c0a48a0da.nq.gz
│   ├── 92039a58550a342bf671dab88d2a9f221d506615.nq.gz
│   ├── 923911ed9edbcad600650c6fde69b08452ca7133.nq.gz
│   ├── 9457abf9c23e6fd1d61f762dd1716e02c2d7001f.nq.gz
│   ├── 95f7df4a8d84501ed281b760cc82c4276056ffd0.nq.gz
│   ├── 99dc721b6cd7c52a3dd771c51c2d5b3c1e580e77.nq.gz
│   ├── 9abc675fada9d2f7defc8edc38b822fb261e03fe.nq.gz
│   ├── 9ac17b3bd538d5a703df8d2485d961534dc102df.nq.gz
│   ├── 9b93c46008a52531a7440755ea883c2d98efd440.nq.gz
│   ├── 9bf6060ca87f7f05f5ea4cbca14f8c44c1fb49f2.nq.gz
│   ├── 9c82384d89d4b6924f28248c034063d64736f3bc.nq.gz
│   ├── 9e1571ac4fa659e36e8d1c82832c4c2d2d4a0dd6.nq.gz
│   ├── 9f0bdf8c0ac63cd2a67530e850ecac58e01757cf.nq.gz
│   ├── a1bf44499675c02cf78eade6ecde710f6f5ff0bd.nq.gz
│   ├── a231d5de47db4b5a38e71da84d74caa854d84ee7.nq.gz
│   ├── a2ad5a37580db85161d81793afc9a85070cf519c.nq.gz
│   ├── a62c20941dc15b2668ca4f84605cc6742c1d16cb.nq.gz
│   ├── a658b72660f8989385ca0ca7e8ea2351bc1cc886.nq.gz
│   ├── abc18455f5ce22b1b4e6b997677a91ac250b5e3b.nq.gz
│   ├── aefd36ec9d63697d7692dc0830a932cd9ac58a5c.nq.gz
│   ├── af1679ad77f65ef6ccee62dde8ea3995617aae15.nq.gz
│   ├── af6ab3bd47804a99150bcb0c44aa791f218c2220.nq.gz
│   ├── afbe5d02ec2c3b69a384d961f51742ed36117e3e.nq.gz
│   ├── b030f4e41ec3140769154fd76f04f9a1a4a20313.nq.gz
│   ├── b50593c825d70b26a5cbfc7966b5b9df178000a0.nq.gz
│   ├── b628c8a9f2d72b2954399eb725b54e963f2182d0.nq.gz
│   ├── bc3048f72463abb07f71bf896088aba00f4c0a32.nq.gz
│   ├── bdbfe1511f0b97ed58dc5f16dd8fdab3ef647720.nq.gz
│   ├── bfb9b5f2ffeec4bd7801e16105a7712440c07066.nq.gz
│   ├── c21d251b37b4f44a4e8da80c52782c015505e942.nq.gz
│   ├── c2ccec6d7c8422702907058406135ddeed19afeb.nq.gz
│   ├── c3f75be447985aaa62f2efd754105815586aed03.nq.gz
│   ├── c474341dd6a9113ba487675be6bd510a29093eaf.nq.gz
│   ├── c6f0813efd23b9a56b7733edc8d6a4da4222e3af.nq.gz
│   ├── c6f511a84f3c2a95f241efee8f7c50ed1a2438e3.nq.gz
│   ├── c795bd578067c7aa445014d40a6a91b2e34487fb.nq.gz
│   ├── c7bbe6d8ee1ea376e7a6ebb84ec19168005fdfc5.nq.gz
│   ├── c7bcf322d05d079bdbf9e826155ae6c63f823f15.nq.gz
│   ├── c9b71759d57458079a8dabd62229bad453bd6f41.nq.gz
│   ├── ca689a20bd49d010305ca85014258329873555fd.nq.gz
│   ├── cdf029bdf55e8ee391fc78c93468890b4718c871.nq.gz
│   ├── cf3933e85fe819a07224235784dfd9531f49d0b3.nq.gz
│   ├── cf65859adebdb125cdc4fb5b655c673234572eeb.nq.gz
│   ├── d0870631edeed70341aacd1581bfdf31e1b51d7f.nq.gz
│   ├── d12adc38ebd124a2454cbf6da81ba80e071bd536.nq.gz
│   ├── d33b776b8d77dc98de98b65b40a33b82d0605747.nq.gz
│   ├── d4597e4e7a01939a241e6ad2b761080ed9658fa8.nq.gz
│   ├── d906ec1181f848e2fb8e59b0127b9094a846fe0a.nq.gz
│   ├── da12ad0492b81b75795baac0f6e1470cb706ebd4.nq.gz
│   ├── db99a864dc9c919b573ef436741af75bf7f061cc.nq.gz
│   ├── dbdca69476a7cfd70bf899e819b0dee89da414f1.nq.gz
│   ├── dd5ada9e0d2066703c686f8c31d4530a09dd318f.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e48d8b9b063e56b28751285b78ed440e87c21426.nq.gz
│   ├── e5659cb6d64047bd302211cff91a7b8fb50579a2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e77d79259ee9e630913ed1deade58505fbc29b7a.nq.gz
│   ├── e7a2d795fd6a0a9235f4b8c76da01af77084f7e8.nq.gz
│   ├── ec1e96cb0e000220e770fa6dd6f90da79c3b5014.nq.gz
│   ├── ed785c413cdeb7f90e43aa19dbb3558f62c965a3.nq.gz
│   ├── eefff9935a6e4dc3c54c44e0e3730b1d573e0513.nq.gz
│   ├── ef286b04e4de555c07cabb843ce9a20bda4a7605.nq.gz
│   ├── ef2ab69287a5cd25cec4735e42721d545b3997a3.nq.gz
│   ├── ef4e2557932b565f470332b13da8f35789426093.nq.gz
│   ├── ef56f82fcda410bc1aba75f0376b4dbf369c8220.nq.gz
│   ├── f2bc6b6e0f2da2c8b9e3d4a9e3a42a9122fd79f1.nq.gz
│   ├── f3f79c964880c4d6e723087d8678e8e68170ad40.nq.gz
│   ├── f46310a8274fbdc86608747b8c61b40d3aef8053.nq.gz
│   ├── f61b228763e5e0a3c6077f1f4d0a69a8d3ac599a.nq.gz
│   ├── f7cdeb7ccb81ab4996c1f33e47a95b8bdd25db17.nq.gz
│   ├── f9d48bbc787a51b7a79505e03d8184dd6934a578.nq.gz
│   ├── f9d95db7b3c0c825f8f61da0e34228d2fc14f59c.nq.gz
│   ├── fb2435fa3b04acd48f8aa27a111c4e4160e8802b.nq.gz
│   ├── fd3583194d318f2a7d4408e0e248acd471fc25ac.nq.gz
│   ├── fe86e4f942256ec251140281484ba31b1fe4e7fb.nq.gz
│   └── ff7f59c2c71a65cae5e7b39bf99d8303758f0c71.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fbde7a13ba686156d355b613a1d03d2595b4b89d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 176 files
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

[jazzband/django-newsletter](https://github.com/jazzband/django-newsletter)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
