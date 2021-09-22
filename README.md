[![PyPI - Python](https://img.shields.io/badge/python-v3.6+-blue.svg)](https://pypi.org/project/bertopic/)
[![BERTopic](https://img.shields.io/badge/BERtopic-v0.9%20-brightgreen)](https://github.com/MaartenGr/BERTopic)
[![PyPI - License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/mediote/twAnalytics/blob/main/LICENSE)
[![Lattes](https://img.shields.io/badge/Lattes-CNPq-blueviolet)](http://lattes.cnpq.br/2455024624300452)


# Pro/Anti-vaxxers in Brazil: a temporal analysis of COVID vaccination stance in Twitter

## Abstract
Collective imunization is critical to combat COVID, but a large portion of the population in many countries refuses to be vaccinated despite the availability of vaccines. We developed a temporal analysis of pro/against stances towards COVID vaccination in Brazil using Twitter. We summarized the main topics expressed by pro/anti-vaxxers using BERTopic, a dynamic topic modeling technique, and related them to events in the national scenario. The anti-vaxxers were prevalent throughout 2020, expressing concerns about mandatory vaccination with a strong political bias. The pro-vaxxer movement significantly increased by late 2020 with the begging of immunization and became prevalent in 2021. This group expresses joy and anxiety to get vaccinated and criticisms towards the Federal Government. 


## Colab 

| Nome  | Link  |
|---|---|
| Text pre-processing  and data crawling on Twitter API  | [![Open on Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mediote/twAnalytics/blob/main/GetTwitter.ipynb)  |
| Topic modeling whith BERTopic  |  [![Open on Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mediote/twAnalytics/blob/main/BERTopic.ipynb) |


## Datasets

Due to twitter information sharing policies, the data made available is anonymized.

## Citation

To cite this reference in your work, please use the following bibtex reference:

```bibtex
@misc{mediote2021twanalytics,
  author       = {Sousa, Andre and Beacker, Karin},
  title        = {Pro/Anti-vaxxers in Brazil: a temporal analysis of COVID vaccination stance in Twitter},
  year         = 2021,
  booktitle={Symposium on Knowledge Discovery, Mining and Learning},
  organization={SBC}
}
```
