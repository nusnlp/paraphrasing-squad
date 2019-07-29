# Datasets of Paraphrased SQuAD Questions

This repository contains the datasets used in the [paper]() 

```
@InProceedings{gan2019parasquad,
  author    = {Gan, Wee Chung and Ng, Hwee Tou},
  title     = {Improving the Robustness of Question Answering Systems to Question Paraphrasing},
  booktitle = {Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics},
  year      = {2019},
}
```

The datasets are organised according to the original .json format of SQuAD v1.1. Hence, models can be evaluated on these datasets in the exact same manner as the original development set. There are a total of 4 .json files in this repository:

**Non-adversarial paraphrased dataset** used to evaluate models' over-sensitivity to small paraphrasing in the questions:
1. `dev_para.json`: Dataset containing paraphrased SQuAD questions.
2. `dev_orig.json`: Dataset containing the corresponding original SQuAD questions for performance comparison.

**Adversarial paraphrased dataset** used to evaluate models' over-reliance on string matching to obtain the answer:
1. `adv_para.json`: Dataset containing paraphrased SQuAD questions.
2. `adv_orig.json`: Dataset containing the corresponding original SQuAD questions for performance comparison.
