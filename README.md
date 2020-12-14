<h1 align="center">
  MedFilter
</h1>
<h4 align="center">Improving Extraction of Task-relevant Utterances through Integration of Discourse Structure and Ontological Knowledge</h4>
<p align="center">
  <a href="https://2020.emnlp.org/"><img src="http://img.shields.io/badge/EMNLP-2020-4b44ce.svg"></a>
  <a href="https://arxiv.org/abs/2010.02246"><img src="http://img.shields.io/badge/Paper-PDF-red.svg"></a>
    <img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg">
  </a>
</p>

<h2 align="center">
  Overview of MedFilter
  <img align="center"  src="./overview.png" alt="...">
</h2>

*Overview of MedFilter. MedFilter first encodes each utterance of the given conversation using a BERT-based encoder (A). The obtained utterance embedding is concatenated with contextual information like speaker role, position of utterance in the conversation, and ontological knowledge (B). This is then fed to a MS-BiLSTM (C1) for medical relevance identification. MS-BiLSTM leverages speaker role information to learn speaker-specific context for each utterance. This contextual representation is concatenated with the utterance embedding (C2) and passed through another MS-BiLSTM (C3) which focuses on fine-grained categorization. Both tasks are jointly learned. Refer to Section 3 for more details.*

### Code Coming Soon ...

### Citation:

```bibtex
@inproceedings{khosla-etal-2020-medfilter,
    title = "{M}ed{F}ilter: {I}mproving {E}xtraction of {T}ask-relevant {U}tterances through {I}ntegration of {D}iscourse {S}tructure and {O}ntological {K}nowledge",
    author = "Khosla, Sopan  and
      Vashishth, Shikhar  and
      Lehman, Jill Fain  and
      Rose, Carolyn",
    booktitle = "Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP)",
    month = nov,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.emnlp-main.626",
    doi = "10.18653/v1/2020.emnlp-main.626",
    pages = "7781--7797"
}

```

For any clarification, comments, or suggestions please create an issue or contact [Sopan](sopank@cs.cmu.edu).
