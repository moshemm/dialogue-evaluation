# Artificial Text Detection / Распознавание сгенерированных текстов

Современные модели генерации текстов показывают впечатляющие результаты: они могут сочинить стихотворение, изменить стиль текстов и даже написать осмысленное эссе на свободную тематику. Однако такие модели могут быть использованы в злонамеренных целях, например, для генерации фейковых новостей, отзывов на продукты и политического контента. Так, возникает новая задача: **научиться отличать тексты, написанные человеком, от текстов, сгенерированных нейросетевыми языковыми моделями**.

## RuATD-2022

[RuATD GITHUB](https://github.com/dialogue-evaluation/RuATD)

- Бинарная постановка: [kaggle](https://www.kaggle.com/c/ruatd-2022-bi/)
- Мультиклассовая постановка: [kaggle](https://www.kaggle.com/c/ruatd-2022-multi-task/)
- Группа в телеграм: [tg](https://t.me/ruatd)

### Датасет
- [Бинарная постановка](https://www.kaggle.com/competitions/ruatd-2022-bi/data) (H-human / M-machine)
- [Мультиклассовая постановка](https://www.kaggle.com/competitions/ruatd-2022-multi-task/data)

### Лидерборд. Бинарная постановка

| Model           | Avg F1 |  Paper / Source | Code |
| ------------- | :-----:| --- | --- |
| wl-coref + RoBERTa | 81.0 | [Word-Level Coreference Resolution](https://arxiv.org/abs/2109.04127) | [Official](https://github.com/vdobrovolskii/wl-coref) |
| s2e+Longformer-Large | 80.3 | [Coreference Resolution without Span Representations](https://arxiv.org/abs/2101.00434) | [Official](https://github.com/yuvalkirstain/s2e-coref) |
| Xu et al. (2020) | 80.2 | [Revealing the Myth of Higher-Order Inference in Coreference Resolution](https://arxiv.org/abs/2009.12013) |[Official](https://github.com/emorynlp/coref-hoi) |

### Лидерборд. Мультиклассовая постановка

| Model           | Avg F1 |  Paper / Source | Code |
| ------------- | :-----:| --- | --- |
| wl-coref + RoBERTa | 81.0 | [Word-Level Coreference Resolution](https://arxiv.org/abs/2109.04127) | [Official](https://github.com/vdobrovolskii/wl-coref) |
| s2e+Longformer-Large | 80.3 | [Coreference Resolution without Span Representations](https://arxiv.org/abs/2101.00434) | [Official](https://github.com/yuvalkirstain/s2e-coref) |
| Xu et al. (2020) | 80.2 | [Revealing the Myth of Higher-Order Inference in Coreference Resolution](https://arxiv.org/abs/2009.12013) |[Official](https://github.com/emorynlp/coref-hoi) |
