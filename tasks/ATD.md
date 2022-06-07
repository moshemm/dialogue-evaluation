# Artificial Text Detection


## RuATD-2022

Experiments are conducted on the data of the [CoNLL-2012 shared task](http://www.aclweb.org/anthology/W12-4501), which
uses OntoNotes coreference annotations. Papers
report the precision, recall, and F1 of the MUC, B3, and CEAFφ4 metrics using the official
CoNLL-2012 evaluation scripts. The main evaluation metric is the average F1 of the three metrics.

| Model           | Avg F1 |  Paper / Source | Code |
| ------------- | :-----:| --- | --- |
| wl-coref + RoBERTa | 81.0 | [Word-Level Coreference Resolution](https://arxiv.org/abs/2109.04127) | [Official](https://github.com/vdobrovolskii/wl-coref) |
| s2e+Longformer-Large | 80.3 | [Coreference Resolution without Span Representations](https://arxiv.org/abs/2101.00434) | [Official](https://github.com/yuvalkirstain/s2e-coref) |
| Xu et al. (2020) | 80.2 | [Revealing the Myth of Higher-Order Inference in Coreference Resolution](https://arxiv.org/abs/2009.12013) |[Official](https://github.com/emorynlp/coref-hoi) |
