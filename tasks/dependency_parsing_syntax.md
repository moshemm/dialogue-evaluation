# Dependency parcing & Syntax

This page contains classical **Dependency Parsing** task as well as less classical once that also relates to **Syntax**: a **Gapping (Ellipsis) resolution**.

## Dependency parcing
The task of extracting a dependency parse of a sentence that represents its grammatical structure and defines binary grammatical relations between the words: heads and dependents.

| Model                                                                        |  POS  |  UAS  |  LAS  | Paper / Source                                                                                                                    | Code                                                                           |
| ---------------------------------------------------------------------------- | :---: | :---: | :---: | --------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| Label Attention Layer + HPSG + XLNet (Mrini et al., 2019)                    | 97.3  | 97.42 | 96.26 | [Rethinking Self-Attention: Towards Interpretability for Neural Parsing](https://khalilmrini.github.io/Label_Attention_Layer.pdf) | [Official](https://github.com/KhalilMrini/LAL-Parser)                          |
| ACE + fine-tune (Wang et al., 2020) | - | 97.20 | 95.80 | [Automated Concatenation of Embeddings for Structured Prediction](https://arxiv.org/pdf/2010.05006.pdf) | [Official](https://github.com/Alibaba-NLP/ACE)|
| HPSG Parser (Joint) + XLNet (Zhou et al, 2020)                            | 97.3  | 97.20 | 95.72 | [Head-Driven Phrase Structure Grammar Parsing on Penn Treebank](https://www.aclweb.org/anthology/2020.findings-emnlp.398.pdf)                        | [Official](https://github.com/DoodleJZ/HPSG-Neural-Parser)                     |
