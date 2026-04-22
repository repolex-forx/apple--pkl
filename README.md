# Repolex Knowledge Graph of apple/pkl

RDF knowledge graph data for [apple/pkl](https://github.com/apple/pkl), parsed by [repolex](https://repolex.ai).

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
lexq download apple/pkl
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── efc9e2c819febd1c28c5626656cfcec3ab86de36
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── efc9e2c819febd1c28c5626656cfcec3ab86de36.nq.gz
│   └── repolex
│       └── efc9e2c819febd1c28c5626656cfcec3ab86de36
│           └── chunk-001.nq.gz
└── blob
    ├── 0013c8b4f8b28b94f7e416823903853e02900e0d.nq.gz
    ├── 001eeb12f9d54ba2655a380615d9a1b18a88ee7c.nq.gz
    ├── 0039825677f0d6520f1f07a3ede625bca5ea92bc.nq.gz
    ├── 00474d4dbdd8a661f5a201ad93573e1c138ab7d6.nq.gz
    ├── 00475e1e21723f7f221966c8180084f8ada9646d.nq.gz
    ├── 0053773041aa6d9ae4564132698df6aa1f9aa798.nq.gz
    ├── 0055867447d929174f81bcd33353f2041510ab98.nq.gz
    ├── 00606cc19dd7bf75d8d7f933887b146c889c1f2f.nq.gz
    ├── 0063a15fcc7b30a23bcc9b0b0f47594475de8197.nq.gz
    ├── 0066d4ec078819a93d09e7ef9d324aa3f360125c.nq.gz
    ├── 006aa4a39c019ba8c81fd0ee57efd723faf4b35a.nq.gz
    ├── 0096c6e10a9fc32d7a72ac2d8b16e6eca51d1325.nq.gz
    ├── 00a662312011ce0e0e6dc4ea474973678bfeed7b.nq.gz
    ├── 00ab2c30ab9d1b4dfa26247ad7a155ddcaea8399.nq.gz
    ├── 00ec6b8c9321b62624963961b3ffcf678ff32eb1.nq.gz
    ├── 00f2e3cafef717d6716bac682b8ec07c01e35237.nq.gz
    ├── 00fdf06ab0213b2eacaabb86531e7f514f5e4970.nq.gz
    ├── 0107eb77eb6a84324ef380b5494ac6364e391989.nq.gz
    ├── 01311296a64f78937277213d3d7ef01e4331da4c.nq.gz
    ├── 013edd42ff2531d7219556e92d97ad41a1e81e16.nq.gz
    ├── 014dd21b19b535f8d441dc5fe28dc318bffb5bc7.nq.gz
    ├── 018c3e63d390dad14eab57c5c565cd15c5ff98be.nq.gz
    ├── 01a5b744dccce79a5c9368ead5f2243b0a85f1b2.nq.gz
    ├── 01b4b93838acb8e5da2b992dd04f77a5df09686e.nq.gz
    ├── 01d969e906dfeb8cc2e1dc91c17f1e2e86fe47cd.nq.gz
    ├── 02093b4c84276b29e6f5ca19a1e5c97efbd580a1.nq.gz
    ├── 0212b3f9bd25bab11aa7668cb810198881514537.nq.gz
    ├── 021964c9a1de6c187c2da7df495b5000aeab2c47.nq.gz
    ├── 021aa9062c2c281e64d92b0536f5cff40e35dd9d.nq.gz
    ├── 0227b95d470a32dc862c6d33c0ba266b9ed8dd9c.nq.gz
    ├── 022ed77cf56bc4a9e2b6ac74e028bacbd7873b83.nq.gz
    ├── 0246e93a51a41853e7e1709ba0d5e0a7e87a2d60.nq.gz
    ├── 025224a57c123fb8ce9e5e7ff4c1a93dabaf530c.nq.gz
    ├── 02608f556cb95e9e22aed2fbbcd5aa8e8a911f2e.nq.gz
    ├── 02624569c12ce497291c1c0454ee9d7706c78b9b.nq.gz
    ├── 0266d275b574edd1f8f86f9c13cddcf39b2f3901.nq.gz
    ├── 027575d8ebd26c0a976d753a4018e64f098279aa.nq.gz
    ├── 0280836f11c09d9c06aa642786c2a68fce5327aa.nq.gz
    ├── 029939f76cadac2f1933ebf8fd6c5917fb86d151.nq.gz
    ├── 02a6beac21458ef3104ff0669dfd25317256d66f.nq.gz
    ├── 02e0d3d59499750c5ab37e6d4dd3440aa359d840.nq.gz
    ├── 0303199238b940c137ca1606c372e0ab82d45cdc.nq.gz
    ├── 030dc1d90cdd808b277d0e8687d9ca6ddd4c8d46.nq.gz
    ├── 030e00354fc5ca295453729f363f119325061f4c.nq.gz
    ├── 032a157304a0b5a23e5aead873ba9cfe83f6c869.nq.gz
    ├── 0355cbb60513b16da70a564119f8cb9cf230d9be.nq.gz
    ├── 037f54af9f2d47608a46abefb036c2dc9ee1a682.nq.gz
    ├── 0380e42f1f632ad6c057590c2c187af18fb76dc5.nq.gz
    ├── 0380fe4add7ee24a26f1196b5879bae8a5a6cfb9.nq.gz
    ├── 0387a9bea86fcc91270a419da5f8078b7d6a47a5.nq.gz
    ├── 039080a4f05590e6949ec06f43435d1414f652e8.nq.gz
    ├── 03a43f646b753cff06cdd406c9ffb059275bdfd2.nq.gz
    ├── 03a64aeb1757bf28d22c3ec3aa3a70b5f0c04f76.nq.gz
    ├── 03bf29ae515dc0bdd715c19f59c1b3762b83c104.nq.gz
    ├── 0426d7f4950f7a3c3d971a2d8231633584c7848a.nq.gz
    ├── 04308f62946637bf0da04f29a58c910632b4d3a6.nq.gz
    ├── 043784188480f049aadfecbdc3c78893f5ae579c.nq.gz
    ├── 043f9a232709cb0f6e8656cc270bdf8a5add17b2.nq.gz
    ├── 0442a2edd2a91ad8ac18d656fd228715add9c9f4.nq.gz
    ├── 047105b90195bcec09360092bebaeaf78631d207.nq.gz
    ├── 0477c5a4c2735ee432eb8276b062ee4843d81cd5.nq.gz
    ├── 047a086b54a6017c100010fb8003e9ffcdb6a501.nq.gz
    ├── 047c7ebc891a91012acf5951cef01f49af12f703.nq.gz
    ├── 048a9e58864919571d5c5f2aca581278f14c9745.nq.gz
    ├── 049749fbff277507181b76314567e4fe6d69843d.nq.gz
    ├── 04978b5a7be3b3bca22066519b5f534e7d82e0fd.nq.gz
    ├── 04a9d2c1029373f0dfd78f2549074eaa2e79c774.nq.gz
    ├── 04afff2882197eaaf777cb96d48487115bc20582.nq.gz
    ├── 04d58e17762b2b0a4c44cb8e13bb2f832f4a1c63.nq.gz
    ├── 04de1bf2478b2010b59905a2cf525532df2f2fc7.nq.gz
    ├── 04ff7050e2bc052e78cf121de91befa38998351f.nq.gz
    ├── 0504d3f90b280dad317bb28e5f1260c62692e067.nq.gz
    ├── 0505dcbf2aa24d290ed08fcda7c32b516407f0e7.nq.gz
    ├── 050e1a3c7c16424d68d336707d59f30f1eab10dd.nq.gz
    ├── 0514c634ba32d980b6fde709054ed8802a93457b.nq.gz
    ├── 05271fdb12a3012802a4624ce59bb7f43e3bbc93.nq.gz
    ├── 053ed56fe2a1e9faa518184d3c85d94b24822e22.nq.gz
    ├── 054349bbaa25b072cafb146da448d2bb277bc5b6.nq.gz
    ├── 055973eb0f75d5a2bb175c00b1b829ed3fc47ee9.nq.gz
    ├── 0568a93e01ac476dba05e65b75362cc9c2c81abb.nq.gz
    ├── 05761ac2addde4f41483acdd8c3c9d137f171e60.nq.gz
    ├── 05a74527b9140f69d7e2dab7558051995784f785.nq.gz
    ├── 05c10118735c457f20a008f98e63be713a9cc211.nq.gz
    ├── 05db31addb2cba9c6b6a57ceaa2e26976636a8b0.nq.gz
    ├── 060b091e693398f8145e4b26c711a5f7ae0ebbb5.nq.gz
    ├── 061eaf0b4f9af8bab6f36a4da8aeb26294158e76.nq.gz
    ├── 064435bf87699fd7f0ac5c0a626cbbc9c9d7390e.nq.gz
    ├── 06561e09cff1bd117e52f8ebcc57697d2bb2f9b2.nq.gz
    ├── 0658188d1849f931169eb44267aa4749810ce2a7.nq.gz
    ├── 066efc8467cf5c3e211c7c1def38aa578a1f659d.nq.gz
    ├── 0681a8e24dd4f0b0ad8c21474794b13cad7cb9e4.nq.gz
    ├── 06884f4edcb19a056d38577549feffc5c2a2229d.nq.gz
    ├── 068be6079bc7fd7c9d021a101282ac0635775094.nq.gz
    ├── 06b7b76ea6111a570bee6259acc0be3620a5b15d.nq.gz
    ├── 06caa3ca1e81ab1401bb84bb3eb46c4ae29bd075.nq.gz
    ├── 06cfc79f4d45080a59824c065e1ea9e9a027364b.nq.gz
    ├── 06dd1d65420cc328145d81c9d1b26f7de7ee15ad.nq.gz
    ├── 06e097ec4be7b4b5b77ce18c03eab6f3cf53405b.nq.gz
    ├── 06ee12eea00777045a14e7283fa333f3b8d7a606.nq.gz
    ├── 0713cc676c104d4b964f25ed1098242506020c10.nq.gz
    ├── 071c204bcf53f5015a32e94b232f744c5451ef4e.nq.gz
    ├── 07334c613492e6a65d20c330cb88f8e112e11990.nq.gz
    ├── 0737777a37a7d958a8c67ba5942712e95f007a31.nq.gz
    ├── 0754bdc3861885e4af4034785e86eda5253d460d.nq.gz
    ├── 0758830c2d573435b09784e5333b94e849cf4064.nq.gz
    ├── 07664d788451fe45acd062c0b8166cc4baf233f9.nq.gz
    ├── 076e2c258112b2f33b30cb07200201d56bea8f8f.nq.gz
    ├── 077c68bbe3b6643c86ec5ac63a2b83c8af912f16.nq.gz
    ├── 07870c135cd3ec6198bed37294c990b0a898ff64.nq.gz
    ├── 0796c31021c1bd27cf6c9b54fb506821dda66a77.nq.gz
    ├── 0797744470b17ad1eb6355f73bda6707ca4a6f86.nq.gz
    ├── 07ab17273a74441775a270cb1a29cab78d030745.nq.gz
    ├── 07be6a6ab71e1b6f5d12b94b385dff988c95bd4b.nq.gz
    ├── 07bf6d5964ef0aacde35084bbbdf959475a9df18.nq.gz
    ├── 07e80a68aa9a6b281e896915a33c2635acd6f76b.nq.gz
    ├── 07eeadc2e6fc4ce8b8f28932a95c6468fd9e1097.nq.gz
    ├── 07ffd07e82f87d27ec2e5676ca0db4b5e84f7b9e.nq.gz
    ├── 081315fe25009c1f59b83933f0f900cc1a500697.nq.gz
    ├── 081e82e0bc3084da4b29e1506c509b49b6498895.nq.gz
    ├── 0833ae070ddf47141c6bd1878d3a6a4ecc06353a.nq.gz
    ├── 083ac7c3ab00e4d4ec4f5469b108f33ad23be5af.nq.gz
    ├── 083e752cc10330c166fd2fc5cfa93b1db2a19d19.nq.gz
    ├── 0885e79b2b3c31868ca22e3f45d3618660e869c1.nq.gz
    ├── 08c12a3723ffe9af979de57979824f17ca3bc48b.nq.gz
    ├── 08c662faf86203779a94069f5a424e20d9c53085.nq.gz
    ├── 08fdf24c6ae3c56d21ff636e7eabe769c5a8b9d3.nq.gz
    ├── 0906923244005917d9a9af1fc00d3c24e2b302e6.nq.gz
    ├── 0915abf2d7f17314bdf31285c3d6c5d1cec17ccf.nq.gz
    ├── 091e26517cfb95781fee7f50dfc6b55f5d7fd080.nq.gz
    ├── 09349ba30d0becc2004759a4e7e15e644f799104.nq.gz
    ├── 0939a60cf3e5403ed3490d049542813c1a7ae429.nq.gz
    ├── 09512fd322ec24fec4c53bb497a7559dbcc3c445.nq.gz
    ├── 097dca13108c74eda005c4bb8deb443df55057de.nq.gz
    ├── 09a1edcaef7c1c3578ae0bc4727e7e2e1aef79bf.nq.gz
    ├── 09b54699557da2a1441dde5bcf79f78a83d392f8.nq.gz
    ├── 09c18c35febb11a09ce406854c9d6a822da52637.nq.gz
    ├── 09c467f114d3da549e338b8abd948897599ca7cf.nq.gz
    ├── 09d39b4b26af78641630a09ec9a102a564b753f2.nq.gz
    ├── 09fd70369c5ed3f232b9576d2ad5d28a5b3840a6.nq.gz
    ├── 0a1176ff4ff69a6ddc5b480a935c49e6f324ead4.nq.gz
    ├── 0a1f6c55074b287dcb611a4a898eea05fff4358c.nq.gz
    ├── 0a41cf3707f19209fd4c85ad84005ce05282410b.nq.gz
    ├── 0a4878399597344ac91e426165b159dc524e83ba.nq.gz
    ├── 0a8b48e851b9151559bca400073f16647e91ec77.nq.gz
    ├── 0ab13890630875bb07b6aff5e40509c51d80b825.nq.gz
    ├── 0abd73358fe1b9210a338f90733d714109f77c52.nq.gz
    ├── 0ac2d4941ac14e7f1f07e4c2d73eb918ef3be320.nq.gz
    ├── 0ad299d6eaa3377c9b73fe30b832bdca9b7629fb.nq.gz
    ├── 0ae4bd9e23208a9776f616b915935a09e416e088.nq.gz
    ├── 0b04cbbaebf2be18d237a0a358232d41118cefad.nq.gz
    ├── 0b09cbbf7b7fbe143fc9a2b1de4b2ec438e8ffe0.nq.gz
    ├── 0b0de05de425d8e72f3762b9db1e41ef48a231a2.nq.gz
    ├── 0b1079d8b03e7719a4e2e355ae7b05510fcfb207.nq.gz
    ├── 0b1f2dc862d58a3a783c53ede8d8f96e1fae3050.nq.gz
    ├── 0b2b2bf8d65fd6009a9021a0d8cb94f0218135ba.nq.gz
    ├── 0b3264441af864075ceb2b0e0ec9b003215e9dcd.nq.gz
    ├── 0b7aaccad8967df7c073b00fde15409c4636e9b5.nq.gz
    ├── 0b8d7f022bff26c0abf826e4e9fa5c229e9467eb.nq.gz
    ├── 0b9e262c56745c0088da9fb8357531396d74af93.nq.gz
    ├── 0be7577457a6a9e309292c508b03c961eb4e60b9.nq.gz
    ├── 0bf0fee18f2d756bce5e9e01237fa1dbd50e7cd3.nq.gz
    ├── 0c0715dfe18b43571618b6368327c3b0de412e99.nq.gz
    ├── 0c0756fb6c71e6d7798fb52662fe080f96c6928d.nq.gz
    ├── 0c07e11758190af09b23a29216222b492c21c875.nq.gz
    ├── 0c1053edb421e5ed61972fbe783e204477b6af72.nq.gz
    ├── 0c2ae084231cb701aa6498c5ded5ccafc5404568.nq.gz
    ├── 0c556adbac21a8b9b7a4f640c10567eb0992e796.nq.gz
    ├── 0c6a6ca497a977408d77bfa8b836fd5ec4764f22.nq.gz
    ├── 0c7c1a535ff356d497b53027ff539c6fdea59821.nq.gz
    ├── 0c7f137c858673088a27bd336b3976e7f7e15e20.nq.gz
    ├── 0c8cbde4e1b0a4d609b7e5ceda2b341b71b8fb69.nq.gz
    ├── 0c96cf504a04060259ea815759872205508d4a2d.nq.gz
    ├── 0cb9238d16a910844ea773442c80574ca8cbe090.nq.gz
    ├── 0cb9593d7fade5e27f412fe771f8c72b61f93784.nq.gz
    ├── 0cd25149a53f71615b8a1c4e7eb558f33e13bacc.nq.gz
    ├── 0cf0b90b992630eb1e061120a8da655ba3f33a01.nq.gz
    ├── 0d1ff55d69dcf3b3ebcce6adee3b777b9ad8e2a4.nq.gz
    ├── 0d39160918c1e622b1f77c0444d6c38366c86f3e.nq.gz
    ├── 0d454941a94a4a3f1dceb58bc6234ae1aa97606d.nq.gz
    ├── 0d4d4f1eea53f5d996d2bd3808ccb357bd8aa95e.nq.gz
    ├── 0d62cd791755f2352f7bef34eb32158b8f2ed735.nq.gz
    ├── 0d68f5a69c0617f98a0717ef54629ae51860ad2d.nq.gz
    ├── 0d89e5c545654f0d8adf531d7db30e4b1648a58a.nq.gz
    ├── 0d8afde4d5b830698d3a33ff78ae768f22ac0e9d.nq.gz
    ├── 0d9b059e7efed7498eae8241928dc4c7c2434c6d.nq.gz
    ├── 0db29574740b010d0cce26b1e50b45cfdab8d992.nq.gz
    ├── 0db2ab6d1a7afbc6af4e55e57900e1ddb1e601f1.nq.gz
    ├── 0dbfee905851ff95efddeaf6e9638761d5d79061.nq.gz
    ├── 0dd21f448d056de91a1acfc780f5cce960771d31.nq.gz
    ├── 0de0b12f7997cf8ab4f0f9209ca5d4c9f4e10197.nq.gz
    ├── 0de30e4ae2ec91c2f092e8ecbeac20edaf3ee51b.nq.gz
    ├── 0df25e4311618b4d6f7a372a8f62cd05d26db163.nq.gz
    ├── 0df802b95010f3a1da76cf0b18665126b8b92a27.nq.gz
    ├── 0e1df9946e921671f7c29f0340d8b0da0f55ad6d.nq.gz
    ├── 0e3d92038fb2da6a54c588e780e5275609d73846.nq.gz
    ├── 0e4ca041c741cf695b09cf7ebcdcc451b8c4c9ac.nq.gz
    └── 0e5053555dcb6f03250893cff58f4127dbb06107.nq.gz

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

[apple/pkl](https://github.com/apple/pkl)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
