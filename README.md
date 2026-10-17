# Repolex Knowledge Graph of spacetelescope/synphot_refactor

RDF knowledge graph data for [spacetelescope/synphot_refactor](https://github.com/spacetelescope/synphot_refactor), parsed by [repolex](https://repolex.ai).

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
rlex download spacetelescope/synphot_refactor
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a308c5ac1a3e332791f900fc2e51dd274a7afc54
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a308c5ac1a3e332791f900fc2e51dd274a7afc54
│           └── chunk-001.nq.gz
├── blob
│   ├── 00df71c2749bfad6135765bca5ea5f46c06ced62.nq.gz
│   ├── 027e1ee21f197e8e0b0ea6ef48e9bf93ed4845c8.nq.gz
│   ├── 04bc91ba0e20687c965f84126e94e49df51e56cf.nq.gz
│   ├── 05cce74c2bee3a27e614fe38ab7820c3583bf21a.nq.gz
│   ├── 0a53ea75ed41c8d57ea6bf33f427d9ecef530826.nq.gz
│   ├── 0a7947a55c15de7cba0c1119dcd968b6f647293b.nq.gz
│   ├── 0da7d3004493c38ad50e9e13ee1ce65070dcf952.nq.gz
│   ├── 0fb73beb106e5d6ff22ae466c34640ef64b9d48f.nq.gz
│   ├── 108603026f6b5f1195574c36b27cded1d9f14d42.nq.gz
│   ├── 1343240f697f1b5dc0a38a74d28495c66e5614ca.nq.gz
│   ├── 14445784414910df390445e9d560c6b896478619.nq.gz
│   ├── 1815342d62fdff7fb6590cf84a042d984245adb2.nq.gz
│   ├── 182320d6bf20457e7efde7faf15ffbca3bf03b41.nq.gz
│   ├── 18989bffb5cd935c781122f359c7091a59c629e6.nq.gz
│   ├── 1e4163fdad6ef648234d4d0550216f92d7538141.nq.gz
│   ├── 1fa331b4a3782ebe5475b0bed60814d94819a650.nq.gz
│   ├── 22d95b35794c040b3ae149c68a71c6b8e200ad36.nq.gz
│   ├── 257b80745ff8cc5bad13f4141ffd53aadf0017d1.nq.gz
│   ├── 28cae47b872be89cbf87617eb64d8c0ef1ff7096.nq.gz
│   ├── 2c826192eb62810524721ba3b70460953502f7d1.nq.gz
│   ├── 2d02876d4590f1ae433fe33f8f62e9b92e47352b.nq.gz
│   ├── 2ff7e2a6b3f5fd926a79e1a55871d18657ecc96a.nq.gz
│   ├── 3256b4e321ad4f93f6134e06ef2082dad45a541d.nq.gz
│   ├── 3337603f9fee0c181bf312a45b8a342cc2b1dc77.nq.gz
│   ├── 364fb010e29d84c97d0f6a8fbadd513b50ebf8cd.nq.gz
│   ├── 3d4176438ee8b07513df8d27750d03871ed2789f.nq.gz
│   ├── 3da283eb1551338ae26760b7535c98291fae1451.nq.gz
│   ├── 3e87561d2a7e4e4bb153d2b85ec6f616859b0abb.nq.gz
│   ├── 3f16c5b6db18d3fe12063de7a097e1887c4c7ab0.nq.gz
│   ├── 493d8b66b4a33611a7fd5f2f3286e3c0abf880bd.nq.gz
│   ├── 4944973c3d7a7b5731f558c5840f54925e744dc0.nq.gz
│   ├── 4c92f914edf67df054f45504bc2871a3ff199aba.nq.gz
│   ├── 4cf1a0c2caf583050a9786217975f0a2989fc70f.nq.gz
│   ├── 4e85d57bc6f45ff7a4695c1d66ba860315e531e6.nq.gz
│   ├── 52e78a4fa768fdd73ccffd8ba16c74e67f7ac919.nq.gz
│   ├── 53be9b211f25c1cf9c3cd047af26d0a75e765119.nq.gz
│   ├── 59141674e82552647b06e35e6ef6060d2d8d746a.nq.gz
│   ├── 5ac9faf8361cc4a293022e67cfbc9a276e3ace88.nq.gz
│   ├── 5c8f93b89b424f5c01fa451a54ff3d74a97353a9.nq.gz
│   ├── 63f980e05e19cf1cde430817c5e59855835e42a9.nq.gz
│   ├── 659ca281d00a36bd3643b9e1dd5ab1313a399fdd.nq.gz
│   ├── 67cf9ebabdeaccd263e3eac98d5780a92bab8dcb.nq.gz
│   ├── 6884da28d905e0d283f833f124614cc522737aab.nq.gz
│   ├── 6997454bbd5e8b8754ef9588122834a42e46bac7.nq.gz
│   ├── 69c1ef75dbeafdc7ed889a843b7a6579687b404e.nq.gz
│   ├── 6a3fc282240bf0971f0c8cea75a0c7bb830e1ab8.nq.gz
│   ├── 6b214a5c09d3a2ed5399a65ba6100bdfd0b070ca.nq.gz
│   ├── 6b439622fa9fb23592c22d8cf4454640fd7c47ef.nq.gz
│   ├── 6dd2a1c05f1cdaa8ce3a351ff69f5d7dba42d2f2.nq.gz
│   ├── 703e7b6ff68ad182d145ada2e32d2e643b377f44.nq.gz
│   ├── 761663e5d8f378666160a6940faba620ac3ddefe.nq.gz
│   ├── 7bb1a9584348e08ae4daa187a85947e3948357d3.nq.gz
│   ├── 7d05f9c37ef5cdad78b0dac34998974678fe5cbe.nq.gz
│   ├── 7ecc55b43b0074c08d49af4792dc8e34c08cd858.nq.gz
│   ├── 7efd31a99764b1f78fd50fa2a1ff5b2915624b8d.nq.gz
│   ├── 8228c01d31781ed941c4d89fd77bb1407627de5e.nq.gz
│   ├── 825b9cd4e5e067d11d738c969778070203fd5422.nq.gz
│   ├── 83097b9404164488ab3af35205dc54aca5b6a175.nq.gz
│   ├── 888300fd4ef751bd5707c19c53af357727a8e9a4.nq.gz
│   ├── 8ad4ff783d0ea47b0a0346d45d2435ce00c35733.nq.gz
│   ├── 8b383b7f9deaaca95c0dc7b7e0d0317ce4a5caff.nq.gz
│   ├── 8e9eb797f787835b6194f9a6ea2e43ec7a9140fc.nq.gz
│   ├── 910437d31a06ae4f90cc1f47ca6c3ab3176e7845.nq.gz
│   ├── 9232f7220f24d883d3b7aa06c5cb181718d836d6.nq.gz
│   ├── 93dfe92b9c98e009c2f75b6477817411d3a15585.nq.gz
│   ├── 9532371e8904371c3d55482002300e8f9db527f3.nq.gz
│   ├── 957706486f1bd566c29253e1f5d729a24b24536a.nq.gz
│   ├── 9bcc0f885055fb59473554212627a40bb469f3ef.nq.gz
│   ├── 9cabaf5238d62b16f3ff3c1fd828130815f33324.nq.gz
│   ├── 9e35d31e5e31c79b2aaac7a334f6857191299e76.nq.gz
│   ├── 9e3bc7481ade705cfdbe38c5dde7e899a0099626.nq.gz
│   ├── 9fa5c0af7d6d1ceb28c137c0170039c3ce49e955.nq.gz
│   ├── a48e8e49d9be998b34cb2b521c72e1eac463b483.nq.gz
│   ├── a517febe575bf029c8901b4c7b714ada570f37bc.nq.gz
│   ├── a57e55697a80abafd321c68e32bb25a28b9cd7b6.nq.gz
│   ├── ac1b4fd9208ba3af2e987bc698a249c633f7ca02.nq.gz
│   ├── b326e13b2e3ce216c95fa6cf6560da451200f127.nq.gz
│   ├── b83f013cfc6644f85404aae984fbd74f9c8ac967.nq.gz
│   ├── bc1a937c46b16809afe600c24ed25b9694a24313.nq.gz
│   ├── bd2e2fd7bdc2c8ad564f24bb102c30e0566333b3.nq.gz
│   ├── c4732b306a32728143f0ad0190d7ec83eec0efe9.nq.gz
│   ├── c4a8503d19b953b007fe4b92306259045bba3f45.nq.gz
│   ├── c7979506d6bfcb9819fad6b4955ee871e08eb175.nq.gz
│   ├── c88b94cf2eee9a71a793a89f3c41fc6c68e2f741.nq.gz
│   ├── c893c1be6af1292538a67afc43b5a645028cba49.nq.gz
│   ├── c9376bba0780962ef0fe30c31e988c2567824f12.nq.gz
│   ├── cabf8314b55c4d9b4baf6b1225ae327ac05e0527.nq.gz
│   ├── d1ab79f68731136f211c60083fd357597ea30e9c.nq.gz
│   ├── d341b1395d70e0ef132fb109d271a066a450d188.nq.gz
│   ├── d5cc5f389ce9de8b25039122fe729467c4268597.nq.gz
│   ├── d79ad74390587b9ffc6ab6e2cfbbf7268f52c105.nq.gz
│   ├── ddbf59182d0aacf3991281c7d654e8227ea6d307.nq.gz
│   ├── e0cccf95e4b6fd5bac078f5549ee1b518156e7e4.nq.gz
│   ├── e110b4e65fdefc54db1e1ac45a7854ae2ebbf288.nq.gz
│   ├── e5c631a1ca527eabb4b4856121abd266018d4412.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6d2f11f3370e6cca4b7a6f68f7a0625fd567d6d.nq.gz
│   ├── e807ca3d9453b694cfda304d910ff56684418cdd.nq.gz
│   ├── ebfc6acccab0d10ba8aed9bbd07cb38b0305c113.nq.gz
│   ├── ec44c37e217d985c6898f566687e6386844ec7e7.nq.gz
│   ├── f38315b22a4929c146aebfb5f2671bb16c003fd7.nq.gz
│   └── f84e83628e10389e41e982be653b20ad77645aeb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a308c5ac1a3e332791f900fc2e51dd274a7afc54.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 110 files
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

[spacetelescope/synphot_refactor](https://github.com/spacetelescope/synphot_refactor)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
