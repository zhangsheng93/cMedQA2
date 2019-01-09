# cMedQA2
This is updated version of the dataset for Chinese community medical question answering. The dataset is in version 2.0 and is available for non-commercial research. We will update and expand the database from time to time. In order to protect the privacy, the data is anonymized and no personal information is included.

The older version of cMedQA is v1.0. You can [click here](https://github.com/zhangsheng93/cMedQA)

# Overview

| DataSet | #Ques | #Ans | Ave. #words per Question |  Ave. #words per Answer| Ave. #characters per Question | Ave. #characters per Answer |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|Train|100,000|188,490|-|-|48|101|
|Dev|4,000|7,527|-|-|49|101|
|Test|4,000|7,552|-|-|49|100|
|Total|108,000|203,569|-|-|49|101|

* **questions.csv**  All Questions and their content.
* **answers.csv**  All Answers and their content.
* **train_candidates.txt** **dev_candidates.txt** **test_candidates.txt** The split of training set, development set and test set respectively.

# Paper
**Multi-Scale Attentive Interaction Networks for Chinese Medical Question Answer Selection.** [link to the paper](https://ieeexplore.ieee.org/abstract/document/8548603)

Please cite our paper when you use the dataset.

```
@ARTICLE{8548603, 
author={S. Zhang and X. Zhang and H. Wang and L. Guo and S. Liu}, 
journal={IEEE Access}, 
title={Multi-Scale Attentive Interaction Networks for Chinese Medical Question Answer Selection}, 
year={2018}, 
volume={6}, 
number={}, 
pages={74061-74071}, 
keywords={Biomedical imaging;Data mining;Semantics;Medical services;Feature extraction;Knowledge discovery;Medical question answering;interactive attention;deep learning;deep neural networks}, 
doi={10.1109/ACCESS.2018.2883637}, 
ISSN={2169-3536}, 
month={},}
```
