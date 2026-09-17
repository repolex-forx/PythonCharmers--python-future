# Repolex Knowledge Graph of PythonCharmers/python-future

RDF knowledge graph data for [PythonCharmers/python-future](https://github.com/PythonCharmers/python-future), parsed by [repolex](https://repolex.ai).

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
lexq download PythonCharmers/python-future
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2bdbfa5664241fee622b23590abd3492f973afc9
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 2bdbfa5664241fee622b23590abd3492f973afc9.nq.gz
│   └── repolex
│       └── 2bdbfa5664241fee622b23590abd3492f973afc9
│           └── chunk-001.nq.gz
└── blob
    ├── 00d7ef60612d5cd64a036980459213dac0a6da9e.nq.gz
    ├── 0367b3db4d48657c0ea47d82c2eaa3829519577f.nq.gz
    ├── 04470f3f1f8474baeda246f70bb675b28cd911aa.nq.gz
    ├── 0456faae805a9c102a56e010de8fee71dd4e9a60.nq.gz
    ├── 04e52d492586f921ac4fb80c4e34788fc02cf592.nq.gz
    ├── 062507703eb2be7631f66e97ef5d475d9f897656.nq.gz
    ├── 062e0848deb492121f24866a902d8675e5aff45b.nq.gz
    ├── 070b5d1a838caaf32388f57a5a3bec3eaac0c4f5.nq.gz
    ├── 0778406a88ba2890942b517440f5aa4cd0406287.nq.gz
    ├── 081c1b49562b61e529313a1b6588b7b42ceb4c94.nq.gz
    ├── 0838f61af0e346b93f1811fda1711813183dfbce.nq.gz
    ├── 08c37c36d128a613e62be352cfad02f6cab78cbb.nq.gz
    ├── 097638ac1120e632ec4586a9638ed174a71b704c.nq.gz
    ├── 09f804dcf4a4cd8789d4b4ead3f27fa2ff74f58a.nq.gz
    ├── 09feaf59e1280d43567224c0b89c97b8c12c7d5e.nq.gz
    ├── 0a03929beb733093d3c7e1e2ef57ae678dfd3e76.nq.gz
    ├── 0b56250137f46b434f7b2276c7ee78eca18d4c93.nq.gz
    ├── 0b8e6a986c73ffd9cece87b6e8a2f682205186d3.nq.gz
    ├── 0bba5e69a6a616a0ca087d0721083e8b6a0617a0.nq.gz
    ├── 0cd60d3d5c37dfb177207bca10e864466340cd5f.nq.gz
    ├── 0d044df43674d26a049e7c88dc48f26ec157042f.nq.gz
    ├── 0d13805dce7a40d228fee9b03c2b344a4de2ac2b.nq.gz
    ├── 0d8afca6e784eaf1e9753203154efb9f2a46b3f2.nq.gz
    ├── 0da3fc2da0843a2f30de120a5bedfc307f263935.nq.gz
    ├── 0dc8f5715cd76dc44a301376af2f7532f398b848.nq.gz
    ├── 0dcc9fa6e6067deb7fb98b41a77011c1570e3741.nq.gz
    ├── 0f020c454f5bd07fb0732b4dd558ad021a37d437.nq.gz
    ├── 0fe599cf0a7fe08fb7b8b58b5411676427a768ac.nq.gz
    ├── 10e61138213fa5779cff8975c3e13f997c6ed946.nq.gz
    ├── 110280adfb7b64bc91a29a1435ec4ea99cecc9bd.nq.gz
    ├── 113370ca2cbf7dd5beff1f510951c95bbe142a91.nq.gz
    ├── 11520a6c2250b697b5510664645de0c9191820fb.nq.gz
    ├── 1187208424616682f69f990f29ffee5821a21186.nq.gz
    ├── 1293bcb070e48a77659f23387fceb4e25ea16ac7.nq.gz
    ├── 12c3c6b38cb6a321d381f592bd953150245c9ed7.nq.gz
    ├── 13b0f435460af2fd1793d5fba03a387798941e27.nq.gz
    ├── 15d2eb4650c34b1c09558dac7cf4b057f5d76933.nq.gz
    ├── 165cf763b53d56d6539426c4f7440a234f16793d.nq.gz
    ├── 16fb84c5ba778fe366b32a4b548745f663fb4091.nq.gz
    ├── 1734cd45fe39511aa6ece07c2ec4b9e906b809fb.nq.gz
    ├── 17af03c5e84331952972e64c9f179cd6fe40f7f8.nq.gz
    ├── 183ffffda48d414e4ee0e7cc0787929404736e4d.nq.gz
    ├── 196d3788575993eb403588b01ac6b0a3fbba13da.nq.gz
    ├── 1a5da35ed0c91f4f215113e74d7285dc50e8d9a2.nq.gz
    ├── 1a8af3454bdd21df6497be19a92367690c9285ac.nq.gz
    ├── 1ab437917d9e2cb0253846f6023031fea821adcd.nq.gz
    ├── 1b19e373c87be6d5956e98eeae1dbaa40f5cd2e8.nq.gz
    ├── 1b74fe2dd7ed97c89c3d2673f4c71d802adb94ef.nq.gz
    ├── 1b8eaeb535856ce96427453a4d1a96863c7a3f75.nq.gz
    ├── 1c69db60672ddd94467360cef644c2bfe8640066.nq.gz
    ├── 1c8a9557193c31135e93dc199ad2ede2ede565e0.nq.gz
    ├── 1cb1437d748c9e52fcb7949e371f255d3254c69b.nq.gz
    ├── 1f56aa1401b673e06cf9d431f365ba24db711ffe.nq.gz
    ├── 200d16cd89712cdd061acef284b9ef07c70eacbd.nq.gz
    ├── 211649e531356f0e9eff7497502b380cd47fe84a.nq.gz
    ├── 2146d1f2ae978e17fba71da31bf105ee8d677e68.nq.gz
    ├── 21e670eae5569ef177a672106d499df91335a7b5.nq.gz
    ├── 22911badae63c5ef1100c40d3236cb5256dbc6bf.nq.gz
    ├── 22bd296b63db8165483990e9ccb3359a6399ff52.nq.gz
    ├── 22ed6e7d2cb60dc4bfacd735608ca443a5ef40ef.nq.gz
    ├── 23471a1c85570717c45fd201b018305b67a9ee69.nq.gz
    ├── 2385ce68f3351024bee03316a7dec9c72cb73ba6.nq.gz
    ├── 2440401bdb953edf4a6c26ba9b3b510baa1e72d3.nq.gz
    ├── 24800c4b9c24aaccbb225ae0bdf63c35ffb50965.nq.gz
    ├── 251a530f897c45b60237b328321e615d51e19fa2.nq.gz
    ├── 2524672e70d194749fbd52e986ddc8e2cffe6472.nq.gz
    ├── 2554717cc2800516894dac31cedd0076812d482d.nq.gz
    ├── 275cafd3036eeb2c7c99091cbc987244d4d3bd09.nq.gz
    ├── 28072bfecdaa1d5ef9839ae29b4b7272aaed48a1.nq.gz
    ├── 282f185226a23d5419956eae97d2937f97d6f7c5.nq.gz
    ├── 290906540c08d80b65342ac14405e80694a66a30.nq.gz
    ├── 290f991eef498bfedb70f36f6a5e00ae01265b97.nq.gz
    ├── 296392a6e18f94b514a5d4bfcd155e7f88b472ed.nq.gz
    ├── 2971055782057bae196bba95606abd1e02f697a4.nq.gz
    ├── 2a8eb5aed75cc45afa2491ebd0c863b08632e7e5.nq.gz
    ├── 2b6e2ee6ccfc56b385235f145da48f3c89215660.nq.gz
    ├── 2bb5084aa8fd8dfd9fcf9d7e54aece1094ba8315.nq.gz
    ├── 2e9a4e476abf46e83226a06db6b44afe21854d64.nq.gz
    ├── 2f609a23aeb4e926a25ca7a2f3e42f7c785f7380.nq.gz
    ├── 31b84fc12cffb2f2960402265e43d58b36a6ce79.nq.gz
    ├── 33c0a585680e4adf08a79efc5acc6e59cdca4367.nq.gz
    ├── 33d9cf9533db55c138e25d351f372ab5a3c6c325.nq.gz
    ├── 3449046101e8144d0ac47df87c4e1ca489f98195.nq.gz
    ├── 34e5224f3d7128bc08e3f6123ba555b0cbc05f55.nq.gz
    ├── 3607cbddd77b7850af3723c46784bc99485defc3.nq.gz
    ├── 36c2205f9b331d52b65681f134b1be29f06e9525.nq.gz
    ├── 37d7feeccb3e6c0919f8d30e723c3af1a9445465.nq.gz
    ├── 3cb23d69146ebd4c0d81af02ae22966b262bf7cb.nq.gz
    ├── 3e84287cb6eabe0a99c800318ef484153c40a9be.nq.gz
    ├── 3e8cc80f04833a8576d7304bdd136c425b6e36eb.nq.gz
    ├── 3fa3dab9021849ca4d2e1d615d8c0f035d680ae0.nq.gz
    ├── 3fd3bbd54a34517c7bd77b0b84c66d1ebc9694f8.nq.gz
    ├── 4179174b566596a19163931419219215c9bd4781.nq.gz
    ├── 42021223ab5ea3bc249e63b62baf78fa2a3327f2.nq.gz
    ├── 420e2bc4e5fce6dd114dd92a8baa62d637b9cc58.nq.gz
    ├── 43f73aa576b30103a3e50376c710e10429fbf2a3.nq.gz
    ├── 43ffd2ac23562dd06e501528fab84ec33ab5bd21.nq.gz
    ├── 447186c950844446f2c6ef6b43513341187f4a99.nq.gz
    ├── 465cb50b3950b3006344dd7d6731db0274c2fb2b.nq.gz
    ├── 4708cf89921e57b1fbbb715bec0203ea0bbfab55.nq.gz
    ├── 47866c8cd6687d61c307a626ed95a96292345482.nq.gz
    ├── 47a7d7e37e809f45b0cc8c3dbc07ab8650a364d0.nq.gz
    ├── 4989c11420764e350bf0272c68bd3986e08a2213.nq.gz
    ├── 498ec14ac4d5520dbd87f7f7066cca7ca79719f4.nq.gz
    ├── 49ce7fc2472dde9b0e1aa2c8331813ef73c6681d.nq.gz
    ├── 4abebf7cb639b64fe9cccc486fd3524b3835b696.nq.gz
    ├── 4bd37e151238370fe72a2dc0b0ebcdeb94b7c98b.nq.gz
    ├── 4c029efd4f91ee5a00ad4839119d0e0340e4abeb.nq.gz
    ├── 4cb1cbcd6343fc4bc4d69954e412ea508984be2e.nq.gz
    ├── 4e75cc1dec0c05ad315e85053e459dc3d7b4acb7.nq.gz
    ├── 4ef437baa64e0c9dcb3c49a6466e9b58383361cd.nq.gz
    ├── 4f936f28449df379260d471627bbb1da731e6432.nq.gz
    ├── 4f99cb5a97046e268eab37ab02d2774db86e19cf.nq.gz
    ├── 51085481e98c10ef6d5e20dd41c70e90c3eb2b96.nq.gz
    ├── 518109c2549ebbd0a1a79302967adc160be550c5.nq.gz
    ├── 51bd4b9a74f000c36cc6eb150564284d8d27087f.nq.gz
    ├── 51c50620b7d38489f34405c2c8b37a6afea748c7.nq.gz
    ├── 51f198698a4dbb5a9fc2fea258a198340ea25821.nq.gz
    ├── 52630f98269e1205b13c0cdda1a829a6235be236.nq.gz
    ├── 528383f6d8371146d77c86eda6a749f422302ed5.nq.gz
    ├── 52dd1d1454e40131702908a9e6394114b52a7b0e.nq.gz
    ├── 53493d0ac511ac94b54cc43b1833f4f348e01131.nq.gz
    ├── 54619e0a608a0feb81900a2c0145663da9f0a975.nq.gz
    ├── 546f92b92cda94e73581ce7fef84ad37d7a9c985.nq.gz
    ├── 55f9c9c1ae15ef4e37b4971b4104e7147baa4c21.nq.gz
    ├── 5676d08fcd5198103102e7b41f1b3d9a43e6fc85.nq.gz
    ├── 568b897a0054d569ffef6891e6512130b495764d.nq.gz
    ├── 56a886091120f0c6a03eca5e90340121c95637f7.nq.gz
    ├── 573a0d53f19220cca4538a96fd1fd177507f8917.nq.gz
    ├── 579214423ef29026b1cf7c53361777d7a2404b79.nq.gz
    ├── 58d8d000927e0305aed9a7a044d5cd8f4148e2fa.nq.gz
    ├── 58e133fd4b497bd5c9a57598a7fca4706d96d74c.nq.gz
    ├── 593da466421131b92a42ce755b8303e8d224127a.nq.gz
    ├── 59b1b318f38033172724ed482d49752d1d1d514f.nq.gz
    ├── 5a0e378937b9fd8ab97a5e345d693d92224ab800.nq.gz
    ├── 5b50cc6bd1d45c7fd07887cef873614e11e4ab02.nq.gz
    ├── 5c718da5a3e3fe453e0a763b76a439fd4d9ad986.nq.gz
    ├── 5c73f6923a9beb3e551ffca45f10bfc719893746.nq.gz
    ├── 5cbfb174af513584e34fdc126dc117674ad43271.nq.gz
    ├── 5cf428b6ec4d7142223f2c5d52d448116e6bbe71.nq.gz
    ├── 5d46b115ecba6fd7d39acdf4f31f2ece180c44a4.nq.gz
    ├── 6269f4a68a7b8bd6d04fcfc22041a2329a7760d5.nq.gz
    ├── 626b406f7fe9df105d329dbf7d61f6c773191690.nq.gz
    ├── 628f399a35b9d201c40ece3430890ad01b513265.nq.gz
    ├── 632c46b10132292e6fee3c7d9a09b0f259a092e3.nq.gz
    ├── 634c2f25e68b5d94f5b7f5110931709697fa4a21.nq.gz
    ├── 63bf038c0223f8bfb4381f981bc37cabfab6cbd7.nq.gz
    ├── 63dced6e5e572545413a21c7f139cadf80efe202.nq.gz
    ├── 64318aa2e03a6c2f882448d667e1d7592a7f7d2d.nq.gz
    ├── 649908f0c237e1bc18ad137846d9cf2c108e8b1c.nq.gz
    ├── 64e8976027a9529ce005c386dd6eaf0f3192b309.nq.gz
    ├── 64e8de61b315baed1405b40ab6626428ac1cec30.nq.gz
    ├── 658955f6c0db2f7125a3d2fa3e6de25225c6585b.nq.gz
    ├── 65c8c1dac73ab5e0b63c6dd09bad35782b8e460b.nq.gz
    ├── 6633f42e0cbf0fa171e50a461b069d35b0dd1b28.nq.gz
    ├── 6639372bc8d5481beeee612922ab90dc179a1390.nq.gz
    ├── 663ede44d566873c64f1c3c64abbe84bab24d89b.nq.gz
    ├── 664ee6a3d007f67d1b93b335d89197a54467f7ab.nq.gz
    ├── 6849679987d926b1a6d1d65bdbff5e8974e35a94.nq.gz
    ├── 68ccf67b9a23824802ae22e10d7dfc0a34dc207b.nq.gz
    ├── 6975a52bb941522056890757143bcfb74a0bb546.nq.gz
    ├── 6985bca4d95d51677979d8baa6c5169e7b66de63.nq.gz
    ├── 6a048710f403ea0042b8e85f00b9664e23cb013e.nq.gz
    ├── 6a6f03ca2ce193ecd6c8232720376d703fdd4302.nq.gz
    ├── 6a7b6d64603880074cfafb8d07f635efd08cb45b.nq.gz
    ├── 6c224b3e47abd320bdcaa78997e4127e17337d60.nq.gz
    ├── 6ccf9c006f44dd56deea70bda6e70da837032b31.nq.gz
    ├── 6d7ed3dcb9ec651cdcd736fea01c0f076ee92696.nq.gz
    ├── 6dde6e8d300184857b92eb94a7e83ac1fe14d904.nq.gz
    ├── 6e839e6bf7534f7221cbd082c488f9748369899f.nq.gz
    ├── 6f0c2a86feeff6e9cae1436f78570312c1b792fd.nq.gz
    ├── 6ff389a49af709f5fae7269a57c9fd249e30f691.nq.gz
    ├── 70444e9e06b590bcd170fcb6d60b94ddd6764e1f.nq.gz
    ├── 72a33558153fb57def85612b021ec596ef2a51b9.nq.gz
    ├── 74cfb74e0d8c50ccbc6160f7cc1da3b6e17562a7.nq.gz
    ├── 74d8f6cebed39c1e4f060d32b7b3077be908f2fb.nq.gz
    ├── 760f06d6c35402519521617e330b1e746e0b666b.nq.gz
    ├── 762eb4b42e11e6c10ce7b612638e1a55fbb958fe.nq.gz
    ├── 7652027b48fff177ecde03ecda50a9d047d31bb2.nq.gz
    ├── 769b65c77ae41555250f18fd9ff63f48c3f2caeb.nq.gz
    ├── 7789ce9dd2c51db15377c8fe9a0bdd21eca617c9.nq.gz
    ├── 7915d8a8db1df9684bd45de3d8243db12710f791.nq.gz
    ├── 79f0e5a33ebd002c93ffdaf501427832cffbc9cf.nq.gz
    ├── 7a23c3e1ff4d8c61ab1d5a7540b4abeb2cbaa720.nq.gz
    ├── 7a4d3249762e7104426f2d09e87df495f63a81c2.nq.gz
    ├── 7a745acf66b47e898f765a3adc4b7c4e709573a1.nq.gz
    ├── 7c4a5291466b8022bfebf0dc7dc1667059ec0a43.nq.gz
    ├── 7d8ada73f8fd2fa4e5958f878c0f5d3c8da77bba.nq.gz
    ├── 7da318562f9048734b970cad4c5e01e95ce2ff86.nq.gz
    ├── 7f92075150e4a86265b1a393281ffe318d9f4b70.nq.gz
    ├── 82d320f8149d5eb798370484a28e591b0e2d501d.nq.gz
    ├── 82f211c656664a5bde51179870f84b6c1e1573d7.nq.gz
    ├── 8461a1a2137f26cdf6656e3c29b6fdb819268527.nq.gz
    ├── 869b3642898d6064fcbb191f433c04ce47f4066a.nq.gz
    ├── 87a3fb85578666ff3ae51f8dd7fcdd88828b7ed6.nq.gz
    ├── 884b674111569b8a5270aa0aedc5e0ed5614e3a5.nq.gz
    └── 8a43882e94bb408209e6ff924a3f362382ae640d.nq.gz

8 directories, 200 files
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

[PythonCharmers/python-future](https://github.com/PythonCharmers/python-future)

---
*Parsed on 2026-09-17 by [repolex](https://repolex.ai)*
