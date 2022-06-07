# Morpho-syntactic parsing / морфосинтаксический парсинг

Этот раздел объединяет задачи по морфологии и синтаксису.

## GramEval-2020

[GramEval-2020 GITHUB](https://github.com/dialogue-evaluation/GramEval2020)

GramEval 2020 — дорожка по оценке методов и технических решений для **полного морфологического и синтаксического анализа** текстов на русском языке. Данные представлены в формате UD и охватывают 5 жанров современного русского языка:  новости, сообщения из социальных сетей и электронную коммуникацию, энциклопедические статьи, художественную литературу, поэзию (+ исторические тексты 17 века).

| Model                                                                        |  POS  |  UAS  |  LAS  | Paper / Source                                                                                                                    | Code                                                                           |
| ---------------------------------------------------------------------------- | :---: | :---: | :---: | --------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| Label Attention Layer + HPSG + XLNet (Mrini et al., 2019)                    | 97.3  | 97.42 | 96.26 | [Rethinking Self-Attention: Towards Interpretability for Neural Parsing](https://khalilmrini.github.io/Label_Attention_Layer.pdf) | [Official](https://github.com/KhalilMrini/LAL-Parser)                          |
| ACE + fine-tune (Wang et al., 2020) | - | 97.20 | 95.80 | [Automated Concatenation of Embeddings for Structured Prediction](https://arxiv.org/pdf/2010.05006.pdf) | [Official](https://github.com/Alibaba-NLP/ACE)|
| HPSG Parser (Joint) + XLNet (Zhou et al, 2020)                            | 97.3  | 97.20 | 95.72 | [Head-Driven Phrase Structure Grammar Parsing on Penn Treebank](https://www.aclweb.org/anthology/2020.findings-emnlp.398.pdf)                        | [Official](https://github.com/DoodleJZ/HPSG-Neural-Parser)                     |


## MorphoRuEval-2017

[MorphoRuEval-2017 GITHUB](https://github.com/dialogue-evaluation/morphoRuEval-2017)

Соревнование по морфологической разметке, формат разметки - UD с некоторыми упрощениями организаторов. Данные: НКРЯ, ГИКРЯ (социальные сети), OpenCorpora, SynTagRus.

| Model                                                                        |  POS  |  UAS  |  LAS  | Paper / Source                                                                                                                    | Code                                                                           |
| ---------------------------------------------------------------------------- | :---: | :---: | :---: | --------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| Label Attention Layer + HPSG + XLNet (Mrini et al., 2019)                    | 97.3  | 97.42 | 96.26 | [Rethinking Self-Attention: Towards Interpretability for Neural Parsing](https://khalilmrini.github.io/Label_Attention_Layer.pdf) | [Official](https://github.com/KhalilMrini/LAL-Parser)                          |
| ACE + fine-tune (Wang et al., 2020) | - | 97.20 | 95.80 | [Automated Concatenation of Embeddings for Structured Prediction](https://arxiv.org/pdf/2010.05006.pdf) | [Official](https://github.com/Alibaba-NLP/ACE)|
| HPSG Parser (Joint) + XLNet (Zhou et al, 2020)                            | 97.3  | 97.20 | 95.72 | [Head-Driven Phrase Structure Grammar Parsing on Penn Treebank](https://www.aclweb.org/anthology/2020.findings-emnlp.398.pdf)                        | [Official](https://github.com/DoodleJZ/HPSG-Neural-Parser)                     |
