# Repolex Knowledge Graph of canonical/haproxy-operator

RDF knowledge graph data for [canonical/haproxy-operator](https://github.com/canonical/haproxy-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/haproxy-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── df7db2c37c931f7afaccb579e150053bc449e4b0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── df7db2c37c931f7afaccb579e150053bc449e4b0
│           └── chunk-001.nq.gz
└── blob
    ├── 00955eefaf456bd31dbe0c1034c4df2bfb1dd4ed.nq.gz
    ├── 00b5eea6587c3bbf13efffdfea6a601b5ff1febb.nq.gz
    ├── 014a81d0e33f4f2661d7ff2818f077f3300647a2.nq.gz
    ├── 01665e432bfdca4558be0f0243077fbd819c885e.nq.gz
    ├── 02722a7dd114ac1230d5fb2ee4abccdf00ca5644.nq.gz
    ├── 02f470a739cce6c64de512af818481f938c7161c.nq.gz
    ├── 03666b170f6a96e43e6c2c5cbea3a5c9548efbe1.nq.gz
    ├── 03a835ec115dd48021fc4938ed08e45a4a09783c.nq.gz
    ├── 03fe3852086e82d2adc8905b9469f834be290e7a.nq.gz
    ├── 0441e1cfb7b20eb65957632152b6911fe916bf87.nq.gz
    ├── 048a5cc32ac2fde0069d499957d1881bdc13f366.nq.gz
    ├── 0577a3c4030e48e3182c5e7cfa1438b01f497a5e.nq.gz
    ├── 06ceda2997926009ff4377d6edc2edc5e23676ec.nq.gz
    ├── 07c57755ef9b044288671c9b1e4ecc449b16a78b.nq.gz
    ├── 07e0b48cbd1569fbf0e610fa77b6a4e96330574f.nq.gz
    ├── 08a99fc612f60c07a86c2ec013cb88fd4114a57f.nq.gz
    ├── 096fcb61c56eb346e1e70cafb96fed1c5df68cb8.nq.gz
    ├── 0aa5ea6835b822eb7c430dfb328ad975929ed763.nq.gz
    ├── 0bd815ea64c32c6a4385ee3a7144742186e5822a.nq.gz
    ├── 0d0349d775be5eb195102ba982dcc38ab185f4f3.nq.gz
    ├── 0d4771ccf3697f57eb01a4a6e09759da0f3cfb94.nq.gz
    ├── 0d75fe085e47d8959cbfaee2524f3668a0f546d2.nq.gz
    ├── 0d858e39837ef4ec9cf7a4cef530d7982855144f.nq.gz
    ├── 0e5afc2d6626f18b06bc2bd498613a1eb3cf3f2a.nq.gz
    ├── 0f38cf54b94a8b5d099a1d430fa142d152350de4.nq.gz
    ├── 0f60fca0dbd9bb5031898c23b7adcfbd527c0902.nq.gz
    ├── 0fc3fee4e681a2dcd3e553a5ee720d1bd2835f69.nq.gz
    ├── 106bb817d82cd54babf27e4e30a462484a545edc.nq.gz
    ├── 11e4fd93599a0cbbba66ce3ef8e327c11909584f.nq.gz
    ├── 120f0a9235da7318856bab2c886b7ca6037c8a8a.nq.gz
    ├── 1221e6ba4df1a9e2e88fb6502eba2d48e240c669.nq.gz
    ├── 1241fdd9827bb8da5566f987e39276bdf7e3079c.nq.gz
    ├── 12cd420fffb4bb9e393343a26916d9079cd55830.nq.gz
    ├── 12d1db5d48d2d6a8b7e6f9fd25a7cf2cfc86f5a9.nq.gz
    ├── 135bba1cb31134da6158d81f82b658d2b6711255.nq.gz
    ├── 13add339e209fe7dfad3ffe47bb5876dda6d736f.nq.gz
    ├── 13b3ac1042efad9bebfb38c50a8b17effd1f34e5.nq.gz
    ├── 14027efeadeb5226e6c243c8cb358dfcb91c1ae4.nq.gz
    ├── 143aecef181766e7bad06b2362103e29aa92f067.nq.gz
    ├── 14411a52f8f20232c777b44e5a3f3041127a1429.nq.gz
    ├── 14dc4b2d4585c5924e1ef83ef4b3b44020870e3e.nq.gz
    ├── 14e670b9432658212a5b1cffebdfdfd89ac1fb88.nq.gz
    ├── 15b9e6f9ca5b5fb98f332d9b43419f714e76e91b.nq.gz
    ├── 16b4b0188a362552b52a4beb1a7816056512c98c.nq.gz
    ├── 16ec291f5c8e2a8c3acb2bbec2f1b0f6b8ddb3fe.nq.gz
    ├── 17b5e6c699f1498a743bc9ed7c7970fb22cce6ed.nq.gz
    ├── 17c86d4be89ed1b3fe3c0c319e07fdfc3ba1a77c.nq.gz
    ├── 17e450e6af219f215d21f346affbb96da126f4ab.nq.gz
    ├── 17fa321273bc833b76e6f2aea419aa0348ddd750.nq.gz
    ├── 18593d87436d09cbaba83cd6b3246a00cbb2a3ae.nq.gz
    ├── 189bf0c073897cb986c8e93ce43a809bd40a7f8c.nq.gz
    ├── 18e49cabb6b8f9f27635eccb66f330919cbeea18.nq.gz
    ├── 18ee42434e5fe536bbb9ddc4a957f0437ca885d5.nq.gz
    ├── 193784a98364a6f421fc115413bef8aa7521c825.nq.gz
    ├── 194f8e8938c61fd23f17ba0e1877536b0e70fa28.nq.gz
    ├── 198054335e0ac082a473c3f62da40bc17fd2723b.nq.gz
    ├── 19f905c0c40b077894e74c22e0c1a30208033782.nq.gz
    ├── 1bd1a69092388d3491dcb30a4e32f035a7b464f7.nq.gz
    ├── 1bed66b348d18d8a5dcf640211a690cc991a5cc6.nq.gz
    ├── 1c8dded58dce43c368e3d06596dc8c26cc1dd8dd.nq.gz
    ├── 1cc7e2dba813d9b9ac75d60e5cf643d24b8c1b17.nq.gz
    ├── 1d20c888270ee90a6c3acea0bab6e2abcc2cdf5c.nq.gz
    ├── 1e208498a1cdd9417d89af3b4e99c2d3b7d95c3c.nq.gz
    ├── 1e9b633a215ba57e760652da45886789062e00bd.nq.gz
    ├── 1fa16b5540206346a035915b92e10813ceab2736.nq.gz
    ├── 1fcb727a9cc12460bb2308fb930859b63fab383a.nq.gz
    ├── 20b29572fe27464c8bbd3ce64d337f39a75d52f2.nq.gz
    ├── 21029a97d7d6020ac30fc125dc33c7db02300b71.nq.gz
    ├── 213d93f78f14f7698317f3e21a674676077ced7f.nq.gz
    ├── 21f27443ebe6d4e3c1cd96be08d8f7e9bb189829.nq.gz
    ├── 21f6825349528938f2b5cb38b48c7606ce689a55.nq.gz
    ├── 236a504be8ff0a6b58e354826373f1316406539f.nq.gz
    ├── 24e25160c40a30515fe855233507f692ec93b9c5.nq.gz
    ├── 2588b9f838c4c0a1097db65715c69890c22758b9.nq.gz
    ├── 25aaa9cb02199e3bfbf9b534f39c2d54b0eb4d99.nq.gz
    ├── 262a1ce89b3d82c372c3d525a79a88e00507f25a.nq.gz
    ├── 26649da957fca9a054283cb140f1d8734f1af175.nq.gz
    ├── 26ac226df88c6bc3785214f437d30606702a7736.nq.gz
    ├── 281ebaccaffbe8e67eb5a705a72bb4c82aadf2be.nq.gz
    ├── 28999a98c1faa8448fd313d281793d12fc7a0b86.nq.gz
    ├── 28e829e69ecc8a341726bc3a1b621d6120ce6e88.nq.gz
    ├── 29429feb910479278b86416ec408c8b8eef55c43.nq.gz
    ├── 29d45c2ecef1155c5eeb129f7afa2d55a01162cd.nq.gz
    ├── 2a216956942db8980e80ab214fef9d5176dd9df7.nq.gz
    ├── 2a36b19bc0deac388bc10ddc48fc88db7f1b8cc0.nq.gz
    ├── 2abb71695096267ce8793df6c31f1db514e3533a.nq.gz
    ├── 2c4dbcc0427b8689d6fa629eaa53ccc5dc3ee067.nq.gz
    ├── 2ccccfeb0d0008feb5790a5c818b1940589b6352.nq.gz
    ├── 2d3a5852ab5509c56b8f25cc789d0aac45002889.nq.gz
    ├── 2db7f38922b53bd3323492fe2532042a05ed74cb.nq.gz
    ├── 2e4148bcf48332a768db83c308d9750185f5bf0e.nq.gz
    ├── 2edaa43586b9a1bfd97896f8d772cb33a2887a3d.nq.gz
    ├── 2f0d48c9e399a2aa8a8e353281b6f25c416412b2.nq.gz
    ├── 3006f13e199b573708dde2114878ca4fa8071aeb.nq.gz
    ├── 300e62e6c2826571824117ff25b912f536684195.nq.gz
    ├── 3014a84f49e5da629a320e61b44bb11e73fea385.nq.gz
    ├── 30659e34cc55b5ae4f6b3a319431e01d972c5bfd.nq.gz
    ├── 3139298416e1421cc0f186aaab18373b2a46a7fb.nq.gz
    ├── 323657b329d18e2088c9599cbaf405a32a443c0b.nq.gz
    ├── 32f507922b835ef9d2b7a2d7cd0d1f72c7eb31ad.nq.gz
    ├── 3359972480c14df7bd269e584c5e54c5689ac86d.nq.gz
    ├── 3372cdf832ee05e9662c2b38bd09673703f18820.nq.gz
    ├── 33c81a76fe6c5dc50871d931b6248b6177b3cbed.nq.gz
    ├── 33eb05c2d8b2bc5be4ad628dd4d044aa24af6103.nq.gz
    ├── 35019fc17218299ccdc3ad5bcb80a974726e4d37.nq.gz
    ├── 3561e99ffb8c6654466d5b7a3df57531385aee5d.nq.gz
    ├── 35d2bdba3e1379580c061281522bab606b6ba899.nq.gz
    ├── 360d95f738747e47fc60fad1191fbace71a34890.nq.gz
    ├── 36f80e5c55c82c51e34533c2e6ecea2a544a1fe1.nq.gz
    ├── 3788a9fcdeb543223106e8fd2197f9d9ce2c2b04.nq.gz
    ├── 378b9e2f52f300ce88ebf24a5c8eab5b717901b7.nq.gz
    ├── 37ac4b405808cfb2436a420c20ce0c8554f8dc74.nq.gz
    ├── 37fcc869439d692a1aa5d943b31e6cfaa0c346b0.nq.gz
    ├── 391904fc1444ace2da21d57aa6a425d8030aece1.nq.gz
    ├── 394bf5fee825ef143717b89ecd9aeb8354420c61.nq.gz
    ├── 39ffd1b17d82e3e5c4e6ded17cb35348a01b901d.nq.gz
    ├── 3b7117bb3eccc4ce1a0afee2ada569758209782d.nq.gz
    ├── 3b78082d1f365e38a058646de5cdf707634e3632.nq.gz
    ├── 3b9e0481c25e971371568193c8d9834ae84fe2a5.nq.gz
    ├── 3bb3ff5850e5d31b08523aefbc932435b12ba829.nq.gz
    ├── 3c342466ec42b7e36b8498c16ed7e4eddba4a799.nq.gz
    ├── 3c5764ba55e28c1c4730e7aaac0afd5f22c16b6c.nq.gz
    ├── 3cd994efd9e5f93b1e59c1fb26f2a477906a8296.nq.gz
    ├── 3e07f139e5bc8eebc0e74d7c7a8e5863f62ec9df.nq.gz
    ├── 3e7bf8d7793b0ae776425650a24ff3de3b99f5bc.nq.gz
    ├── 4036c82187b951211aa0f9da7dd27795b793d74a.nq.gz
    ├── 40856c6ec616f87b4bb9c560d5cce317d5779b9d.nq.gz
    ├── 412234a27475cb6a922c95088098f622c52f2604.nq.gz
    ├── 42ac823e2e99b7fd9271ed7ba49d096b1337c7ea.nq.gz
    ├── 42dbc4b55828c7e24919164574d699dea3cd22f7.nq.gz
    ├── 439fc74b9f2c9f84ea9173926d7c224d39faec9c.nq.gz
    ├── 43bebb516f2c8c72551b940a5e1078951c6ecdec.nq.gz
    ├── 43cdaf5d36f5862f7d904129d15a1e4b6e702dc7.nq.gz
    ├── 4554255f0a3140219968e0fd450418f142f1d801.nq.gz
    ├── 4592cdc75be7065edc5c8fafcbd8cee8168fc489.nq.gz
    ├── 45dd5d5bbff54767cba71e1cc010864d8b4caed4.nq.gz
    ├── 461ba8d1e27003860da1b9193b5a4cf30bfd489b.nq.gz
    ├── 46a1693abe7b1a91972002e08731868c3e666d8a.nq.gz
    ├── 46b019422ff425780cb1b813d2c69d63dff7fd73.nq.gz
    ├── 4715522195acefceab122aca6aaee973c223f004.nq.gz
    ├── 488496f53a523ccd3346636e025000d96381c2cb.nq.gz
    ├── 490a4332ba9ba8ec4da3927b1381b678e7a2064b.nq.gz
    ├── 49fa4b69c5d1f670cb38a90c6f18f4c8396ec9e3.nq.gz
    ├── 4b8b005b4221683de826805b12bff5b94c2d0264.nq.gz
    ├── 4bee45210910731596ee2c1a5c6dad2c40ffabfd.nq.gz
    ├── 4c1c372b596057283bbdd1a22f40ac830122951c.nq.gz
    ├── 4ca38f53ca42a70c3be8fec3efde6bf15be1a134.nq.gz
    ├── 4dfa83a73ab31742df73e553e739aed2f4207196.nq.gz
    ├── 4e422d7d971ed025bb5c4a657f29669fb683de33.nq.gz
    ├── 4e88af8e609e4660496b86aa4d125116fbd10c14.nq.gz
    ├── 4eb10e5546f9be87f23e50f62fe7cdc791a212cd.nq.gz
    ├── 4ee206acc01b26687fac8473e533f4a899c57c2a.nq.gz
    ├── 4ef3e76d0a84f51320e36b20efc2a2f10183d9d2.nq.gz
    ├── 4f3fa0ae61f0eeeee54bc3889a79982348988c63.nq.gz
    ├── 4f7cad02b364fa0a87cc1ac3a172451b7143e729.nq.gz
    ├── 4f8fe3387ca96d44af4a043671b21bbc60ef0d5b.nq.gz
    ├── 4f9bb307e901f0de249eeb51e4018f1a3de339c0.nq.gz
    ├── 51aa80bd5424ab3629a8cc676a2606fc1e7a70ea.nq.gz
    ├── 5244b6fc391b42e0dc7ca97c776efcb875824014.nq.gz
    ├── 53159b284fc19b581aea9c4b75ff48e0b98a3fed.nq.gz
    ├── 5517c75d6df0329c6e4b5ff9022313c3a728e0b7.nq.gz
    ├── 5542483557a543ebb4d97c265eee4de7c7c5e7ac.nq.gz
    ├── 55922cb38feab3eef1d27c7f300123602404130d.nq.gz
    ├── 55b10427a856bbf21ce7d23e75e12386142ebd55.nq.gz
    ├── 55f1cdcec75cdddb915d9d867282f8817f25000d.nq.gz
    ├── 56031316f6f9cf1ef952c73b3b18cbcdfe02b44b.nq.gz
    ├── 563dae153d39960397b98dbd10eba0f62ba5ad91.nq.gz
    ├── 56a6f1c8e4746aa1ad5ee513ba0408cf93c3a572.nq.gz
    ├── 56b465cb4f047228d87cea745dce2157c1ac677b.nq.gz
    ├── 57a7a49e1ce59d14877660645de320355af7918f.nq.gz
    ├── 58b8c3798bd8fa2de52364d5283dbcb95fbca038.nq.gz
    ├── 58c786f56cf9ab252a6980f2b60e18ab329979ea.nq.gz
    ├── 58d8075b6ae329a48484f2a650802526b5eab0f2.nq.gz
    ├── 5a04dc0b4dcab97f08c1ad1fca41ead350a88c51.nq.gz
    ├── 5a17b7f52c86b062aac741761692e843ebf44f62.nq.gz
    ├── 5b103f976b6e84f22f47b460ae7089d561bd3776.nq.gz
    ├── 5b7a4bcc7980e1ec09ebedda6e32722b603cef6a.nq.gz
    ├── 5b80a85c0e6195d6eabfd89dc3461fc3b50d9fce.nq.gz
    ├── 5be1d93158856891c2a493ea37cb1f116fc81f61.nq.gz
    ├── 5d43d870d88ff4c12a1fbd362aebbcde46a8d8dc.nq.gz
    ├── 5ddeb9b49132eaa61b983846f1503ed285b0869c.nq.gz
    ├── 5e20bc4e24ec709a968d734082ed5cc49c248648.nq.gz
    ├── 5f08e5c2b8af84a7f541f3dbb5f4cd8d5c64543e.nq.gz
    ├── 5fcc4242a4b7f56731bb84345998bbd2a9e25f11.nq.gz
    ├── 6079857d0c1aee9c2c1e70d2b406d46b1b991341.nq.gz
    ├── 61d9008c1a5d28d2477d1a13c16557cefa139754.nq.gz
    ├── 63324bf7cb1c4b1dcc3ec57e0e028b8c0065a8e9.nq.gz
    ├── 635d153f01dec9ec2b029a5610a1485e31dcebf7.nq.gz
    ├── 6362650c8cb47cfb881f718ad931d92238619589.nq.gz
    ├── 6446ed660c057b7ff761af43820b28c4e41246e4.nq.gz
    ├── 64cf0ceb5b11ebec6061bd4e7a44041ae9e03618.nq.gz
    ├── 65dbbd4f7d4f9384660c562386b3119bd323e75c.nq.gz
    ├── 65e3131a04fd041b190dccca52c047e6e29313b2.nq.gz
    ├── 65f4410270649b54a4c1a652b651d51175f64783.nq.gz
    ├── 66140d4ef3db7309312f7199870eea1cb049de39.nq.gz
    ├── 662f49c0b0e946bc040b5c77b540c53161f0e01a.nq.gz
    ├── 66d81bdcff1097cca169685330ced51786139b85.nq.gz
    └── 67199a18a69f2f894d60a3c13546f70e7e790cb7.nq.gz

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

[canonical/haproxy-operator](https://github.com/canonical/haproxy-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
