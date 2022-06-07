# Morpho-syntactic parsing / Морфо-синтаксический парсинг

В этом разделе объединены задачи по морфологическому и синтаксическому анализу.

## GramEval-2020

GramEval 2020 — дорожка по оценке методов и технических решений для **полного морфологического и синтаксического анализа** текстов на русском языке. Данные представлены в формате UD и охватывают 5 жанров современного русского языка:  новости, сообщения из социальных сетей и электронную коммуникацию, энциклопедические статьи, художественную литературу, поэзию (+ исторические тексты 17 века). Метрика: среднее accuracy по лемме, PoS, features и LAS.

[GramEval-2020 GITHUB](https://github.com/dialogue-evaluation/GramEval2020)
[Статья организаторов GramEval-2020](https://www.dialog-21.ru/media/5109/lyashevskayaonplusetal-181.pdf)

### Датасет:

- [Train](https://github.com/dialogue-evaluation/GramEval2020/tree/master/dataTrain)
- [Validation](https://github.com/dialogue-evaluation/GramEval2020/tree/master/dataOpenTest)


### Лидерборд


| Model                                                                        |  Avg Acc  | Paper                                                                                                                     | Code                                                                           |
| ---------------------------------------------------------------------------- | :---: | :---: | :---: | --------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| qbic: RuBERT + LSTM (+various other models) (Anastasyev, 2020)                    | 91.60 | [Exploring Pretrained Models For Joint Morpho-Syntactic Parsing of Russian](https://www.dialog-21.ru/media/5069/anastasyevdg-147.pdf) | [Github](https://github.com/DanAnastasyev/GramEval2020)                          |
| ADVance: RuBERT + fine-tuning + post-processing (Sorokin et al., 2020) | 90.76 | [Tagging and Parsing of Multidomain Collections](https://www.dialog-21.ru/media/5118/sorokinaaplusetal-162.pdf) | [Github](https://github.com/AlexeySorokin/GramEval2020)|
| lima: Fasttext + LSTM + FF (Bocharov et al, 2020)                            | 87.87  | [The Russian Language Pipeline in the Lima Multilingual Analyzer](https://www.dialog-21.ru/media/5075/bocharovvvplusdechalendarg-158.pdf)                        | [Github](https://github.com/aymara/lima/tree/grameval-2020)                     |


## MorphoRuEval-2017

[MorphoRuEval-2017 GITHUB](https://github.com/dialogue-evaluation/morphoRuEval-2017)

| Model                                                                        |  POS  |  UAS  |  LAS  | Paper / Source                                                                                                                    | Code                                                                           |
| ---------------------------------------------------------------------------- | :---: | :---: | :---: | --------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| Label Attention Layer + HPSG + XLNet (Mrini et al., 2019)                    | 97.3  | 97.42 | 96.26 | [Rethinking Self-Attention: Towards Interpretability for Neural Parsing](https://khalilmrini.github.io/Label_Attention_Layer.pdf) | [Official](https://github.com/KhalilMrini/LAL-Parser)                          |
| ACE + fine-tune (Wang et al., 2020) | - | 97.20 | 95.80 | [Automated Concatenation of Embeddings for Structured Prediction](https://arxiv.org/pdf/2010.05006.pdf) | [Official](https://github.com/Alibaba-NLP/ACE)|
| HPSG Parser (Joint) + XLNet (Zhou et al, 2020)                            | 97.3  | 97.20 | 95.72 | [Head-Driven Phrase Structure Grammar Parsing on Penn Treebank](https://www.aclweb.org/anthology/2020.findings-emnlp.398.pdf)                        | [Official](https://github.com/DoodleJZ/HPSG-Neural-Parser)                     |
