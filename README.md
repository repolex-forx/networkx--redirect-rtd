# Repolex Knowledge Graph of networkx/redirect-rtd

RDF knowledge graph data for [networkx/redirect-rtd](https://github.com/networkx/redirect-rtd), parsed by [repolex](https://repolex.ai).

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
rlex download networkx/redirect-rtd
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2c38b0a7c4aad1c3b86c96826da37ce7ada6f2ae
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2c38b0a7c4aad1c3b86c96826da37ce7ada6f2ae
│           └── chunk-001.nq.gz
└── blob
    ├── 003c6f55f9f907b06a7859a4f8bfba8d8a0a74b4.nq.gz
    ├── 0048d675be364e067525438015cdab32eddea03e.nq.gz
    ├── 0105778dcf96358e1f3b05532d861dca397c937e.nq.gz
    ├── 01359e5cceafb3cd0061d137df5ffa7fc10cbfd3.nq.gz
    ├── 01ad16c8008382594f2e25e055591f08b9782723.nq.gz
    ├── 01c40b9c8ebb9439a474db661eaa96b0a5f2dff7.nq.gz
    ├── 02441f60108803334d1b71fb654841d8490f0c55.nq.gz
    ├── 02623d53cfdfc26e105e57fabc5aca3097885f00.nq.gz
    ├── 02a0c527a9193be61cf4637bb025f8c9f7915f40.nq.gz
    ├── 03483e8090ca91a674bd347ba99b60734f7787b0.nq.gz
    ├── 03a8c72a96c79247752596de4c51e3f9f6500ee2.nq.gz
    ├── 03a912b21d3339f011b1352400d68bb7ba9e10cb.nq.gz
    ├── 03d72a1711d81a331054e2b0c43552de9118ff3c.nq.gz
    ├── 040267ad4a8980abb29c0697e2c752ad9f50873a.nq.gz
    ├── 04cca28be2cd093524a3b219ed7f347ab003b0bc.nq.gz
    ├── 04d8784c5d9b700f3c5510adf82010ef83603521.nq.gz
    ├── 04f50c9c009a3552ba6f1211eee5bf82a97b58d2.nq.gz
    ├── 054d667e005a5d15567d61f00f2528784a70208a.nq.gz
    ├── 05b9c4bf7d8d6494fdc8b2fa2174cc0fc0321803.nq.gz
    ├── 0604324965e425db77bca213b592ecc63b550f08.nq.gz
    ├── 0636130e0a13101b672910be92b6b5c2cd4a1fcf.nq.gz
    ├── 06788f81776504d9e5e07f4ed6be7ecebbc4801c.nq.gz
    ├── 0779b37f7b52e3b7c9f8393e6285153f387e1cff.nq.gz
    ├── 079d0de547bdba6b61627713d2f476892f0e553a.nq.gz
    ├── 07a2648f89956f7fb299e2d7a858295cc986029f.nq.gz
    ├── 07afb2dbdc29a0dfbfb497694560e6b8711ff483.nq.gz
    ├── 07c97040ff92b3806cfea55e7c689a1cc4133252.nq.gz
    ├── 0810c4325957c13f81443a79dc3e04310ec1759a.nq.gz
    ├── 081c8aa2933825dea2db927814458fe496e855c0.nq.gz
    ├── 08620318ed9c88716578955d559f41fb29046041.nq.gz
    ├── 08d35924fd4144b347bf9e49a89caa83798d683e.nq.gz
    ├── 08e52171bf0ccc6f754c88b0938506294fb69588.nq.gz
    ├── 099f00d8cf81f0b7e117f8fd770e931f05c7c0dd.nq.gz
    ├── 09fce79c23ec956f46ab079300bd883182f72753.nq.gz
    ├── 0b3f25cdc13ed698de42f7fffb88d594e9a8a42c.nq.gz
    ├── 0bf3e38352ff44fd46a6f32e7d5122e0a6d295fd.nq.gz
    ├── 0c55d5a361622524a9e7ef88d1d1d1bf4f7abc98.nq.gz
    ├── 0e7b954e8c837814476a9655ad5f576bf94101be.nq.gz
    ├── 10dc89ad54a30d750794b1b7e6bcdf6cf61dd17c.nq.gz
    ├── 10ecd906a235b6b5b86593384e83e5e3fdbd2cd7.nq.gz
    ├── 12127118804c35aa8efd2653b1eec453e0402754.nq.gz
    ├── 1248a672fa39cb0f2fec46370c55f23719f1227c.nq.gz
    ├── 127e0593125e752772bea282daebaff7c29f7774.nq.gz
    ├── 140a0de5552c6a13f6044a97a0e735b3145a6c13.nq.gz
    ├── 145f0d454828f8b8cc50b7a966bebc41050ed986.nq.gz
    ├── 16e63d832bca690045d946a1e5d5e9f7272117a1.nq.gz
    ├── 173affd7018fe67ac8a7f393827b2cabc541de29.nq.gz
    ├── 1793e3d78af8b8f4d4242cce595e6370b6c888ab.nq.gz
    ├── 19b496623f5910a40d3591cf0106118793a4cb33.nq.gz
    ├── 1b5ba8158ff6f84844bffe799dbc6448ce2cc3e7.nq.gz
    ├── 1bad62bdd3bb4ab5ac6fc04fd37a32a9bf20d8c2.nq.gz
    ├── 1cf582aab91aa97d2590b9b6e7be6bcb07b828ab.nq.gz
    ├── 1d834ab48602f3d819bac0c6139029d43ede04f7.nq.gz
    ├── 1e113339eb14671a2e6d9d436ed78cab8a9e35c0.nq.gz
    ├── 1ef97d1ba656eb7189dc71c7ef64500311de3d9d.nq.gz
    ├── 1f1bad1b22c22941372ecb4d5fe99ab406afb0e3.nq.gz
    ├── 1f41af20901d07f1bf049fc05c2deee08b32819f.nq.gz
    ├── 2087b6fb3345fac945bfc779b785fec869f56bc9.nq.gz
    ├── 21b4733b05a29e9049094d11c5597c9b175a9577.nq.gz
    ├── 22150f94666af82bec3a78359cfd8e252ec5270f.nq.gz
    ├── 223846b14542ee0a696f2934f7a0adafb7b2afea.nq.gz
    ├── 230f0658861ce559414248a56d0eb10f1405f55f.nq.gz
    ├── 2363f7cd1f60cbf14a509ded1d7ed7b323489704.nq.gz
    ├── 240fe44e567148316b37c36786cd68a19727a1fa.nq.gz
    ├── 24ea83abdcc8bb0756dee4f0b9aae277085e0662.nq.gz
    ├── 25c7bf4650ffa85ed58bea125166235c8b3eb8f6.nq.gz
    ├── 25cd3381ee494f9e1e117a30e2aa4888a44be37a.nq.gz
    ├── 2734055465a098c3ef7bd53f3041bda2c913e6c5.nq.gz
    ├── 2746e995e036eddf03f58b27db8698529cdb9d9f.nq.gz
    ├── 274f60f2566b7becc1b91c14ffda5b31259984ad.nq.gz
    ├── 283da30ca6f07dc6393f8a4de55f869a92881d45.nq.gz
    ├── 287d7500135e6c946e3763263478f2df259d0ab9.nq.gz
    ├── 28ce3f3ab9a234d969d7bc3fc858e2009aa46bd1.nq.gz
    ├── 292168c4450f39231c09165ad34f888561018d7d.nq.gz
    ├── 29290cb3878a47fa5056133ae8f65fdd5a70c567.nq.gz
    ├── 293d33f550bc64309d783d57feac6d4be38624d7.nq.gz
    ├── 2add72b33065a9dfb137c9146a509538d660ed54.nq.gz
    ├── 2b53b7968a3db0b6511d18836ab85deec216868f.nq.gz
    ├── 2bc4fed174bb1539a7f67e95f167e5cca3c2c0e1.nq.gz
    ├── 2c2f348750f82c7286fa7ebb34c3b40c734dcc01.nq.gz
    ├── 2ca6232f92531d6b10e2fd343dd139a083051466.nq.gz
    ├── 2d0325fd9b560f6ff7e59bab28a87de3fdf7a749.nq.gz
    ├── 2d1b6bf68e3cb9395573187307f1853800a4be1e.nq.gz
    ├── 2d83ff822cc278c8a18d49ebb65fab11d9d9875f.nq.gz
    ├── 2e760bc64c6653d3b656591cd8d91d51636a6275.nq.gz
    ├── 2e9243d5c0e44860500cb287f8e3d4ef4c821136.nq.gz
    ├── 2f8565b6b5c7887684d7184d41cd74351e739bc1.nq.gz
    ├── 309b2ffdebabeda938f0a53630bd2dce3e80c06c.nq.gz
    ├── 3158120b3eecc679b759d61df6068203081be0cb.nq.gz
    ├── 32c2c5b3d53c10659ca1ad4445d0888a299814e9.nq.gz
    ├── 3528ce9c505590ac9a1cc12673d5ccb511676b81.nq.gz
    ├── 35553d9a7ab3b8cf3d3d99de2cf838a05d3fc382.nq.gz
    ├── 369c09a3365c15eef10bbce1ac0ea3f9f6be179c.nq.gz
    ├── 36a4d8d2953d03b7db789e84c638d53d6910c50f.nq.gz
    ├── 36a630498f1cf22e77911be93e399cf1566abe41.nq.gz
    ├── 3707eece3d706115348546db923feb7eb5970231.nq.gz
    ├── 371423dcbad581a70f9418713176d07919b3cc40.nq.gz
    ├── 37833a7eac98f62368dea50ec10f38683fdcfb30.nq.gz
    ├── 37992cb15f68cf56b75c820ce3c0801bf310a439.nq.gz
    ├── 37bcd4df6f393fa81752b69ae02b1666f5c4dc69.nq.gz
    ├── 383077e4f3c477cbb1bc85965243e4554f016c0a.nq.gz
    ├── 38bd33cd3f4d2908d35bd4d3a5db43ba1c2c0b2a.nq.gz
    ├── 38c8bfc54f1b0490cf2bd4f7bd4fb4709f2ff7e0.nq.gz
    ├── 3a8daa87dc0106dbf6a8e23d5b2815b2252c03c5.nq.gz
    ├── 3aec131783ecd3fd37e50be164cf5540f8d5c20d.nq.gz
    ├── 3b745a830e337694e62753626cb06db2562b763e.nq.gz
    ├── 3c33c24b033f130cb98a87b702e7bc5391cf07ba.nq.gz
    ├── 3d51271da9be7a168fd95d92b94dbac6105204a6.nq.gz
    ├── 3d9517b6e9fc1f8eb1ed84318645a6d6641a138a.nq.gz
    ├── 3f8e8cb4a38aa1341787fe0305a8ab45045f4f22.nq.gz
    ├── 3ff80e22acd60da66500293cee3622a6dac3131f.nq.gz
    ├── 4015040af07670498439fbdd2f7836f358e6f768.nq.gz
    ├── 405266ea8e9b54f1d9e9092273c7aaa86e24cc37.nq.gz
    ├── 409c3428baf25fb71a543e300711397059d7b426.nq.gz
    ├── 40a83615854d56a88574a13c293d10998324a193.nq.gz
    ├── 41bbbd1b758bf35a2263ed31a16de8de7e548157.nq.gz
    ├── 424f553c56daf5d7d91c0f17c2155ae02fcb28a3.nq.gz
    ├── 425b03ad5f8a97a003fa290b78b23a64006c0516.nq.gz
    ├── 43fb7d3cab0945c8859a3d88d60cd4eb565e2e4b.nq.gz
    ├── 442cffe843edb664bade92dd0e6cfc49873b058b.nq.gz
    ├── 446b2c90ed9869e92fafd8366424ae3b60e775ba.nq.gz
    ├── 4470feb996b9624a98dec16e1ee0f3ec431773f7.nq.gz
    ├── 45ed84b8a932787dd0743a420a2c46e7cd5b7bd1.nq.gz
    ├── 46654445b3a956f500a4524371cb336839f645a2.nq.gz
    ├── 4688fc0c19f9f5d0c29e9630567abc1e04b51bca.nq.gz
    ├── 46f45e3e9c349f4418bc85cda0ea8aa3c7d36eeb.nq.gz
    ├── 47769c44d1517cbaae2f240efd576e796ac4bfc0.nq.gz
    ├── 4807d11a6edfeaf0e2ed29fcb70b143ea5585057.nq.gz
    ├── 485ae93344da005dc686ab1e5e1804bfe7327c65.nq.gz
    ├── 48bc61490509e698ab0e83c41faa41bb3f680664.nq.gz
    ├── 48d1c6af0c9abfa00767f77687b46a6d609049bd.nq.gz
    ├── 499f37710fdfa19aa7b61dedcfcb0c3093a05b6b.nq.gz
    ├── 4b956fd4346b3eb458cb40ae0d64d8607222622a.nq.gz
    ├── 4ceb214d1747298940162e7e3e3b52ff56c5605e.nq.gz
    ├── 4d6cc226934782b567a44bf42c4bb8a806b66da2.nq.gz
    ├── 4f9eb4ec8c37915dad7ac21058633a8394c2f76a.nq.gz
    ├── 50b5924eea87a5bae160940487657cac60f5cf6c.nq.gz
    ├── 51915bf0efd91ff76e6133a91d26663970d9f691.nq.gz
    ├── 5197522514d549c2ab1ea2d380f07090c92e56c7.nq.gz
    ├── 523639625f28d621a3d2f234372b8ffd16648238.nq.gz
    ├── 52926949c0fd05e804cd3d48cf2ba028edddbfbc.nq.gz
    ├── 530aade707bd5032f142420a5cf242949fce450d.nq.gz
    ├── 5392ccb207d8a5bc78a357a681bc67e1d0681601.nq.gz
    ├── 53e893e9e942f57df09952d65d782c3471b4ec9e.nq.gz
    ├── 543b8c79ea444e1edb2cf8ae5041ce1ee5fc0c25.nq.gz
    ├── 5457a937e49a657ea9fe3a73119921543c9fdd83.nq.gz
    ├── 54939b6d81327330c47b1393c0f3954089c6b5a1.nq.gz
    ├── 551d32679c158cf2ea0ff4bb0a9862dda5c434ab.nq.gz
    ├── 5534b6c7a9924e2b10064fc6af36864dc61d5870.nq.gz
    ├── 55c81fbfe0275dc0bb86c4ea4f07e619719c34ea.nq.gz
    ├── 55e95bb6d6cef3370ba4b3ace803e503d19c9224.nq.gz
    ├── 561290934efaa6dce2134276ff1facaea487638f.nq.gz
    ├── 5626ded040534c8a2799a912ade7406a40dcba03.nq.gz
    ├── 574dfc534aab7b166046460c253cb1b2a69c6576.nq.gz
    ├── 575052290786730342850dc4e1087c8fd2dd6f02.nq.gz
    ├── 57820612c42848ea9fa44661c3da063cfdbd5b71.nq.gz
    ├── 5795653078a1360b5f91a79fe38e29633b068cc3.nq.gz
    ├── 5798321706cc2b43066375c6a597a63eb52a216c.nq.gz
    ├── 591f3a42ae16af1a908df92e5f728fdae410375a.nq.gz
    ├── 595480a905c99dec578bbbf272503a6630459f02.nq.gz
    ├── 59578ded770ebd250d23e54365ef4b03b521063c.nq.gz
    ├── 59c5cd4dccae6622db7428d135e6bb8d328d0f8a.nq.gz
    ├── 5a3ee2aec167f4972f17088e65e88c13e9b5cdcc.nq.gz
    ├── 5a7480af10398edac850650a73ecc13252b750ac.nq.gz
    ├── 5a9a7cddd428c3bc69421366c77da5318aae33f9.nq.gz
    ├── 5b5e74d5d9c54a952c00b8e2d70ab6daa36aef0e.nq.gz
    ├── 5bf14ab1fc63f70a65d6d4c1702cbe12b602099e.nq.gz
    ├── 5cabce2f4c1c8d92244aa27a04f311e9326c9956.nq.gz
    ├── 5cbda56ab09a3138120688f98049ceb520ba76e5.nq.gz
    ├── 5d5dadba17acb6f8bca882fc4d4a2f396a636b12.nq.gz
    ├── 5d653f85b2bd83c979beb18272aadb6e0b65fcb5.nq.gz
    ├── 5d9c5f179ee7a78a7445205b1cafa3df23af5ccc.nq.gz
    ├── 5e79777316205d0e65e3b93c60b1d6424d976819.nq.gz
    ├── 5e93ae101c43f17b76d6d1dd1ff2e86e13937ddb.nq.gz
    ├── 5ed147e907a4463d5f68ba9f572c9c1ebce08af4.nq.gz
    ├── 60d6e9e132271aad1ab606c790f40f8486b47424.nq.gz
    ├── 625677c1288b6041880837f0e13b1bcaafc4229c.nq.gz
    ├── 6292348fe7282f66ab0b99af71e31307ffd04e46.nq.gz
    ├── 629724040c450aff09cd18bf1bdb46f861e5f092.nq.gz
    ├── 62b1af46f5503ff5bbb10cbcc55383bb88633979.nq.gz
    ├── 6316f4ae767ec476c97ff1bdeb0e56eb30d8ff26.nq.gz
    ├── 63b618454b96fd1d6774c5d8a9cd306283511b20.nq.gz
    ├── 64da8efbce65cc9aaa3f99edf89c0d0ae27427da.nq.gz
    ├── 6530c79f4590d6e269221754570ddbaa8151d5db.nq.gz
    ├── 6615e27e39702311a7c304abf11be27e74016c23.nq.gz
    ├── 6842bad2ee842006c87a674ace26611f275cf6ad.nq.gz
    ├── 687118ba13a93ef01385dce4191315a5b524c126.nq.gz
    ├── 696db981536c38949c2395ac010c96c431de4d3f.nq.gz
    ├── 69afb9f850a6a6562365532133592f10ac373529.nq.gz
    ├── 6b3864399d17b6b9bff9a2261a8ada0131a61fb6.nq.gz
    ├── 6b5961d0528ccd378d3813093e044f3431f215b7.nq.gz
    ├── 6b87cfbc8e5cafc84933cf05d4bffff88326856d.nq.gz
    ├── 6ba5f4704246ff6a14e6795f9abb1da0b7539103.nq.gz
    ├── 6d4c9d2dc4ea2d6c7ca0cceb7262e1772b57c5f6.nq.gz
    ├── 6d75ea0e4dce18d4b87bd2fca8c8d49061092ea0.nq.gz
    ├── 6dfd24d8d1270713549b960c61c7aa6b18167486.nq.gz
    ├── 6e73cb525970e26062e06c77009536b736f24828.nq.gz
    └── 6e84b75f058aa450ce3c4ddd9bb56115ff8f18fb.nq.gz

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

[networkx/redirect-rtd](https://github.com/networkx/redirect-rtd)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
