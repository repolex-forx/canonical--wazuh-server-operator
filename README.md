# Repolex Knowledge Graph of canonical/wazuh-server-operator

RDF knowledge graph data for [canonical/wazuh-server-operator](https://github.com/canonical/wazuh-server-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/wazuh-server-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 61c27ce6224a4bac58978dec151dcb7bdfe57737
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 61c27ce6224a4bac58978dec151dcb7bdfe57737
│           └── chunk-001.nq.gz
├── blob
│   ├── 00db488bac177bba48d1531604dc069c271bcb36.nq.gz
│   ├── 0113832ca9b69bc9ca106722828b4a0f9e58be89.nq.gz
│   ├── 03ddfe631a1f113820f03856f38fa8d8080e7522.nq.gz
│   ├── 04401806b837c8fe90f88516e1b2a9d31bc8c702.nq.gz
│   ├── 0464737253b4b9583610ffdc855399ac1b301fe3.nq.gz
│   ├── 0758fa07717e9d40753e8ca1628b8f4cc00ed6d4.nq.gz
│   ├── 0a5df0b653f060ef5498fe6420b09b98ce069e47.nq.gz
│   ├── 0c84052645f60e1bcd4aa3bc0b3b7dac5316d2a4.nq.gz
│   ├── 106bb817d82cd54babf27e4e30a462484a545edc.nq.gz
│   ├── 120b75fab0bfc07a623b71c172a64defefd52e24.nq.gz
│   ├── 13516b538737429151a7fdad2b87e13810d3583b.nq.gz
│   ├── 140662a8bb4593946360ee5ad53ad8aa31d47a14.nq.gz
│   ├── 1553e14c7a90992624d52f84a7841d3be60af035.nq.gz
│   ├── 1634ef4adc4178572adc5cb56e0a4b4a2c380d0c.nq.gz
│   ├── 1699cf3bb46d4ebc91afb8f49673c05c80000dca.nq.gz
│   ├── 1762c6239627c71bef3d1e51293a3e1f71468074.nq.gz
│   ├── 19530af92347cb8dfb3d775ceef8fe1d01efe55d.nq.gz
│   ├── 1bed66b348d18d8a5dcf640211a690cc991a5cc6.nq.gz
│   ├── 1e3c2ae26cf6d368a2eb60c60696c8631d0e10d9.nq.gz
│   ├── 1f0c40fe0b76e2fa6f1993af1e8d0370e8829fd5.nq.gz
│   ├── 254042f9eb8b8bd29325c25519b5e58d89f7d37b.nq.gz
│   ├── 291772f0674ca54f92000b84f9aa507e945174f7.nq.gz
│   ├── 29d45c2ecef1155c5eeb129f7afa2d55a01162cd.nq.gz
│   ├── 29ede242ff455a64fa253000d80487a0bb723248.nq.gz
│   ├── 2a220ee7476c9461cec28e8ac45da83fd9ce82e7.nq.gz
│   ├── 2aac63552fed026e10db952fd606c925d7fd09ca.nq.gz
│   ├── 2b3f09f538c06e0379f66649ae1488a5173566a9.nq.gz
│   ├── 2d2ac4a800c586a2cb1574ded315e4beab6e49b0.nq.gz
│   ├── 312460da0ebfb758a45f5194252c865e0a6bd9fa.nq.gz
│   ├── 31b9849a658106e3cc9052871512a2e1f58da32f.nq.gz
│   ├── 31d8aa47b0b093407759e81e3a8873299a12fad3.nq.gz
│   ├── 32d9c11926be02ba95bab488a32d9df59746c633.nq.gz
│   ├── 3378eb217f13b77d79652d5d8579f7172c70432f.nq.gz
│   ├── 354c03895f5ff27b338a682add2c88a648984139.nq.gz
│   ├── 3684f76345611536cf0661e2fc1b9fe44534e166.nq.gz
│   ├── 3e3e1228817d0f13df073fe6a335cd16b310fab9.nq.gz
│   ├── 3eb0e90470ca0fbb421e56c1275e76a37a669626.nq.gz
│   ├── 3eee70566a21272d45d963beb5860da7682027cb.nq.gz
│   ├── 40d4e2e3e9a47bea2c9f394bc2b3c550c2402caf.nq.gz
│   ├── 42fa3f648c0e4f6764ea52b1001ca3611354e153.nq.gz
│   ├── 439c2ba3f172401987910ae96029f21bfca4b837.nq.gz
│   ├── 44f374bf14ac0ef6a396d4e9af72244e811a3d8f.nq.gz
│   ├── 4a4551318bba67dfb4e9dfc3879343cadd21395b.nq.gz
│   ├── 4b8b005b4221683de826805b12bff5b94c2d0264.nq.gz
│   ├── 4dc67d7277b553cfc31eb58e3bbfca93337741f8.nq.gz
│   ├── 4ec2899ec200bb3f935c579fb683ac67a5e1fd9a.nq.gz
│   ├── 4ee9da404b7dd4d2f5f610dc8c881d46c2b0d508.nq.gz
│   ├── 5146daa01222323cdf077964bb82656c4212d956.nq.gz
│   ├── 558a5b9e44cb914bf450c3f55a4ec3be18061031.nq.gz
│   ├── 55969d643048afbcfabdfa8a3314e271294fff2f.nq.gz
│   ├── 559efd29c02a7eaf95c974855561ecf506b33c2f.nq.gz
│   ├── 58547b5db386ee76549b4d405af6b97cd88ea372.nq.gz
│   ├── 5888a37be4029432188256eb2c91c1bd4df9e80f.nq.gz
│   ├── 5971899114b986b4a0167d3ee5ef94477c2a429c.nq.gz
│   ├── 5a5c18ca13192e97a52f163f2ff212f6379e1974.nq.gz
│   ├── 5bd52b34b0cdabbf4faeb37db4f8f42c63e463a4.nq.gz
│   ├── 5d7686739193f22896162f5e75eea2bcb89771f0.nq.gz
│   ├── 5dfd6f17bf1bb2936b049f13051f02119eebddce.nq.gz
│   ├── 5f430b2d13c15495b2a458a9a2bcffd0ea4b519a.nq.gz
│   ├── 60e7f2d0a74c1cf22696c02e651692deaa181384.nq.gz
│   ├── 646edc5ae2b4bd5bda1c5ee1ceac89dff08e39eb.nq.gz
│   ├── 65f4410270649b54a4c1a652b651d51175f64783.nq.gz
│   ├── 664586b35ae59b36e0ce67b6df7f14573311f92a.nq.gz
│   ├── 66610c27655ba93467785378eecb023e365acfae.nq.gz
│   ├── 671074e368d835f86d4c05d6cff752be0a1f582c.nq.gz
│   ├── 67af3b658ce83a28210fe0d5def977bc5c7e8630.nq.gz
│   ├── 68e180d92a2dd880665113baa52acbfcbbe83179.nq.gz
│   ├── 6aa3a575db0d5d31d5b5f2f4b7985c8fdd41288a.nq.gz
│   ├── 6ce5959f662beecfd9e72d78fd24ef166875896f.nq.gz
│   ├── 6f94cded4fec60283aa42d48789f2f779e32bb9a.nq.gz
│   ├── 70ee48c01c821fe8bc7d1d7b0fc20c1d39ea18c5.nq.gz
│   ├── 73de58d6aa0c0610c2ea8f98d434b32dbae1d979.nq.gz
│   ├── 744ed45068a134cea22d78d6cfe4bba68151b902.nq.gz
│   ├── 753c8e5c9b998572f9b24d710f8e8ce7eea1024f.nq.gz
│   ├── 75c896f8a7aac4ab2c0cc7a01dd92ccb11dc7139.nq.gz
│   ├── 769704f8719df584ab6a67f7fa28342e51dadbc9.nq.gz
│   ├── 7803194d63844e0a4382b04f654321dbeb63d397.nq.gz
│   ├── 7d5623d5ceae85c6a6c937e713256456ae7bf9c7.nq.gz
│   ├── 7fafd0ac573a4925975e3e4b23cc660e4dd7784f.nq.gz
│   ├── 8078cc43e010d7c4a0405c9c58f6bcf43bad2eb3.nq.gz
│   ├── 814c39436092186358d00dca8347740ef7b5389f.nq.gz
│   ├── 81c69957fa42eab63329cce6bbf516360f1fdc80.nq.gz
│   ├── 852fc305b994a48410925642ba37339791182ed4.nq.gz
│   ├── 8cbafc5e7d6ced11228c21efa9f952f6afce875d.nq.gz
│   ├── 8dd8e2fa165f49d1dac71d5e61103e173bdab856.nq.gz
│   ├── 8ddb3e7d5daeb480f334c56596499fc7ecd48c65.nq.gz
│   ├── 8e25a6ffdd0308185e1c2883e860a218f79669cb.nq.gz
│   ├── 8e65ab0d414d5c209a886b4201b830f230c1f36f.nq.gz
│   ├── 930c880276e3d97347998e3ddc112ad03777f37d.nq.gz
│   ├── 930d2e600da574f4765393b5ddc4542a678f82e6.nq.gz
│   ├── 93432d715e2ce61d360073aba151819464930aa3.nq.gz
│   ├── 94288844048508285114210d3d07a9fc6e358e4f.nq.gz
│   ├── 94cad2dd0db947e748071f1ca3ba9f8f4c9bfa68.nq.gz
│   ├── 9858c44319fcf4fa33cc8a2f7f32bbe519e8eea4.nq.gz
│   ├── 99a810dc24a7fce5c1292072667326f755046038.nq.gz
│   ├── 99fd5c559a7d8f80765d07cf0c518be3e05cfa0f.nq.gz
│   ├── 9bb5ab0bdc5772b30fec84340433459e8b1dcf97.nq.gz
│   ├── 9faae765b00be283787a2cec692e2acdc7de49ca.nq.gz
│   ├── a1c62893a79bf9eb00c04c507a7823b9ab1e84ca.nq.gz
│   ├── a24058f9a33198698e8efdad5b0ce31ce8690a8f.nq.gz
│   ├── a4d2efa1b23c32ee22b513dad6b6289076af92fc.nq.gz
│   ├── a6a52edcbdc68e7d1a04a5487cbe2d32af4c2c63.nq.gz
│   ├── a8a1a8b229d6c126b3711f6efe5628a0e9a0511a.nq.gz
│   ├── a9c8d8a78926d2f45db33bea3bb7b5c434a5091c.nq.gz
│   ├── aa5fc58db4296267b6e32bda616d46d88cc70e59.nq.gz
│   ├── adc0241ccacdcbeb7fea51aa9ded6eb8c765ab9d.nq.gz
│   ├── aeb6af6c459616967dde617b5065a5bb0ddf6087.nq.gz
│   ├── b16bda17b90a8d3698325c3ac5806f2f97597f07.nq.gz
│   ├── b2ecc78a9bed6e627c5a7de007464ae67d883b69.nq.gz
│   ├── b40d0fbc76ab06f576ccdca5c3559cd161857aa8.nq.gz
│   ├── b5114126da188f8af6ba6ee0b48be71120042bec.nq.gz
│   ├── b7f78fbe33918cfd0d3f9327ffcc5a63cbcf3ffb.nq.gz
│   ├── b88290190e1ae960feb36074c2306f7b6a948aae.nq.gz
│   ├── b93b946b574775bbce2947512476a10bb4e4c4a3.nq.gz
│   ├── ba5ec97d85312f0519895f7a08c908189112077c.nq.gz
│   ├── bb3ba7d6b09d5159851a9f5aab7c98d84fafe0f5.nq.gz
│   ├── bb623f6a0db64107e459b8c5c80f492e3ed43f30.nq.gz
│   ├── be2535e7ea1bea49ca6e3f2e549ed88d8ffde157.nq.gz
│   ├── be46b1c1ed354a4a67c779877b68406e3c78f56e.nq.gz
│   ├── c4b2cb5b9ef93669da1fc63ba3a6d5f332f0de05.nq.gz
│   ├── c8c3748bb63c17d884b35c3cb967c2f2d1faf5e1.nq.gz
│   ├── ca22bdc37f567c4ba4fe831427043ac3221fb856.nq.gz
│   ├── d01c107f30775e6918fb856f3e33b44edc0730ca.nq.gz
│   ├── d07a76bfd122a4b047d54ed9b86b34ac3b11e9d5.nq.gz
│   ├── da1e2049eb420c5e26c46849af0ee747a58fabcb.nq.gz
│   ├── dddb292a2c1698851f1fe7d4eae27a5c284b55e2.nq.gz
│   ├── de6e0dbfaf18615b8930d706251660b56f9fd902.nq.gz
│   ├── df541556b4c8b8d1d2040a3acdf1aa8872e9c1a7.nq.gz
│   ├── e3004871f70cf6d5987906260417cb642cab4995.nq.gz
│   ├── e44ecd9e18bea79b9e6718901827a96a3a949fca.nq.gz
│   ├── e5f0ff67f0d6a8578a1a470ba9b600dd02d81bb3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9e37b443f283dc7526088111450aa4911f4d79c.nq.gz
│   ├── eae2ca5a0992e5e91886946b58acfc3b514fca58.nq.gz
│   ├── eb675fa04ebd453e1d2567b1a473db59df18dd14.nq.gz
│   ├── ebfeb61db8de34226af2a81c0c04eb5fe8277107.nq.gz
│   ├── f3fd1badb6efc442c722473ec6c454e59ba0b943.nq.gz
│   ├── f4a65fdd7c0714cb6e6d8696295f9c0110a5e870.nq.gz
│   ├── f4e30c56a97efe41bb7baa39ac822b3e4b4d694c.nq.gz
│   ├── f615889a29105fb8110043f415c409876e4c5072.nq.gz
│   ├── fa89e9d7f0a34f12feec51eb28b9208c96d0494e.nq.gz
│   ├── fbfaa1b638639203bb0e3f8eab60ec92c0e6d7d3.nq.gz
│   ├── fe6468e8d0a1957aba024423c38b9eac57f996f6.nq.gz
│   ├── fe7c999f764e53093ad10891f6e1870b27bee5cc.nq.gz
│   └── ff8a9601433f69320f5fb465b10b2df6fa246aba.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 61c27ce6224a4bac58978dec151dcb7bdfe57737.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 153 files
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

[canonical/wazuh-server-operator](https://github.com/canonical/wazuh-server-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
