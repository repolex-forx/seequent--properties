# Repolex Knowledge Graph of seequent/properties

RDF knowledge graph data for [seequent/properties](https://github.com/seequent/properties), parsed by [repolex](https://repolex.ai).

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
lexq download seequent/properties
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 85dccbbd5455e4a34a255f18fbf1db6f71311868
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 85dccbbd5455e4a34a255f18fbf1db6f71311868.nq.gz
│   └── repolex
│       └── 85dccbbd5455e4a34a255f18fbf1db6f71311868
│           └── chunk-001.nq.gz
├── blob
│   ├── 02ae700331cff5750f3c7a90f3149bbd6bb2fc9d.nq.gz
│   ├── 064b7798ac058879580b47899211ea0da0f23836.nq.gz
│   ├── 06fc59a0266d194a0133834d063ccd6d7a379f49.nq.gz
│   ├── 08a1136245c5703c5c908edb30209e02721f6a68.nq.gz
│   ├── 08c053f26dc7cce1d84ecd3023cdb4e3e997c938.nq.gz
│   ├── 0bdeb54a6c26b4f256d55f6eb6746780167218c7.nq.gz
│   ├── 11c5cd882fb7eb67d90a96a5254d8edf152c349c.nq.gz
│   ├── 123ed086c80b7f499a6fd45834c82bee42c8dd29.nq.gz
│   ├── 1377ae3f1533551e773125961222221b8b5b5e20.nq.gz
│   ├── 1624a9db9ade6e652e5d627b5c9b1a65af1f20f7.nq.gz
│   ├── 1b7b9b2fe765576c56fd514cbec418d262980ce6.nq.gz
│   ├── 1ba6141c4db3b1f590df292bdb2131378468edfa.nq.gz
│   ├── 1c7c3719af36a5d5766cad8d917e949a439cd824.nq.gz
│   ├── 1c800c3463647444d901b49423abb0f328256c0a.nq.gz
│   ├── 20feeace8dd0648adeb93fc8cecfe0827b247dc4.nq.gz
│   ├── 258278ccea34a690b2bbdf208116836ad384e536.nq.gz
│   ├── 2881a8793ed29fe6b0cd1565033e945398b2810e.nq.gz
│   ├── 2b622fc1c124b07f771e1f9860f59dbbcd7ef0fb.nq.gz
│   ├── 3716560cef29e750554ac69041eb60944f4c752e.nq.gz
│   ├── 3ea5b5dcd5e807b231af672a2fe11f9626823f3c.nq.gz
│   ├── 4125e0fdc6b9bc971fa2c0028e9802d28f09a431.nq.gz
│   ├── 4263dfa8b3ca5cdab72b3e39786e3f13b272711f.nq.gz
│   ├── 485ed992157c7ce9d95f103e319ccef853688e40.nq.gz
│   ├── 556491704260719022bc2ef7ea87add074730219.nq.gz
│   ├── 560f852378753f18583a8649425d12f378fb4440.nq.gz
│   ├── 56f8871b57b97ed1342c973e6d01530e50c6c66c.nq.gz
│   ├── 5aef279b98f5a38ea748ea502fe13c2a1c6d811e.nq.gz
│   ├── 60a9c0ce8e45b181998fee4a8276e9a9301bec98.nq.gz
│   ├── 61facb6ed3a7627febf8bcac8cc3600c774c2231.nq.gz
│   ├── 673b198cf9fb05ede3aee94604f4ceb3051ee3bf.nq.gz
│   ├── 6afaa502e0cb8b1c862868f40d9928c680128b78.nq.gz
│   ├── 6c68cb7593d045b730b2b10f1361f3a566f6c2fb.nq.gz
│   ├── 6c8f40de422d854ccbcef6cee6d981eae433868f.nq.gz
│   ├── 6f53a679f125ec8dd5e66e1e36e16fd1a830d92d.nq.gz
│   ├── 72e6bc5380c1db8b0f7a0b24a71bce1f51c1bd0b.nq.gz
│   ├── 7466c2663a5bd3054e885b80be6946c368e7e73b.nq.gz
│   ├── 75757470619281eb5cc3649db8f80baae8b847f7.nq.gz
│   ├── 7bf8fb685f957053df0aebd6fa23d62727d1a110.nq.gz
│   ├── 7e5d2382e14d0a178b66518e888d775b986bcb5b.nq.gz
│   ├── 7f525bed247610ba405d6d7954d09fe0f76457ef.nq.gz
│   ├── 82e5264fa08434c57e97b22bdf8a3685e57b6529.nq.gz
│   ├── 844467bda629943f0489b70fc1bf4870b948035e.nq.gz
│   ├── 85a0ab35b1a2362e2732ff153dda0f68fb9cb1ef.nq.gz
│   ├── 8663c86d27a4945d0356a5011aaff7ea71a9bcb6.nq.gz
│   ├── 88715df549802e2b41074bfc120901dfc946cc12.nq.gz
│   ├── 8a58b1a983543ef0a8562dead51f4922a34162f2.nq.gz
│   ├── 8d85b54cc9ab8675fdb3fe7a150d2a029592b3fb.nq.gz
│   ├── 9a36cd3d96f449f765a39a110682084f41ac5233.nq.gz
│   ├── 9c59fd19188b3ff86eddbcd12514603665e98fc6.nq.gz
│   ├── 9f4a1e5c8299e6a8243a132fcc9bfd27308673ac.nq.gz
│   ├── a244b317cd3a4f9cd668445edbee482bbd32b726.nq.gz
│   ├── a5021c60e36ae085d1ef96c1fed9d88c2f65dd53.nq.gz
│   ├── aef744adf490e523e317852534d0b7865feb273e.nq.gz
│   ├── b121e3d91a54122247a936354b9b9edece86824a.nq.gz
│   ├── b20b93504564772dfeaba57f01f35cf8f683a012.nq.gz
│   ├── b33ab23f2ad94169c7a63c6f92cb818fba6b7591.nq.gz
│   ├── b5035057bae953e5cf1854e94d432fc65134e3c3.nq.gz
│   ├── b67d6c7861481b288ecd23c7da3654908e24de7b.nq.gz
│   ├── b7811d113083de193de4b6e78c9c5f11c17796a0.nq.gz
│   ├── bad960d76967a78413e936ca647adb2519023d8f.nq.gz
│   ├── bcb688d110bd43d656062c4cc36c8095a61ce6c7.nq.gz
│   ├── bd44fa27f875a703af292dd3f9141ec1559dbcd6.nq.gz
│   ├── be429f4fdc5643a0697003e132a51e06cc9ab4a6.nq.gz
│   ├── c016f3a5f326697bb7938ceb34cfab5e5e2c728f.nq.gz
│   ├── c32b23f66bbe95c7e46d4d0b8bf461bb1cda4858.nq.gz
│   ├── c3f64834d6f17c3a457c1b5bfe7f2fa709c81c3a.nq.gz
│   ├── c693a534d7b3087d036851db9056ad58e7f8f601.nq.gz
│   ├── cbfccc3e29b4af912f5b45e769306c86c1d6bc3b.nq.gz
│   ├── d2229c6af64d38e350b5aab722fd196ce5650071.nq.gz
│   ├── d3149368f8c863956317c7b5f9125b7981a42b9d.nq.gz
│   ├── d62cbed53393ee7d6116b737c187c9518a23fd77.nq.gz
│   ├── decb01c69fdc608224e1add688b364c97edbceb3.nq.gz
│   ├── e5bf348b6f6051ef28f527cc033538cd4ef2244a.nq.gz
│   ├── e84774152ae42805d05b868c13f111e0dbbda2bd.nq.gz
│   ├── e9a00fbf86e53c70d745a3e9ce681d3202b284c4.nq.gz
│   ├── ec222851f10f46bdeba37f8520e52acb32e1e764.nq.gz
│   ├── edb8fbf29f3717cf3200a5b5d5459c2cc9ef23b6.nq.gz
│   ├── ee313efd37acde2e3b7862606d133c4a5d9218d0.nq.gz
│   ├── ef963cef5284018d082efea63fbbdb63d362bfef.nq.gz
│   └── fbfa318ebd559b13fce4d4e651eb53e0e154208f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 85dccbbd5455e4a34a255f18fbf1db6f71311868.nq.gz
├── filetree
│   └── 85dccbbd5455e4a34a255f18fbf1db6f71311868.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 90 files
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

[seequent/properties](https://github.com/seequent/properties)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
