---
title: "Improving Low-resource Question Answering by Augmenting Question Information"
collection: Conference
permalink: /publication/2015-10-01-paper-title-number-2
excerpt: ''
date: 2021-12-19
venue: 'Under Review *ACL 2022*'
paperurl: ''
---
**Andong Chen**, Yuan Sun, Xiaobing Zhao, Rosella P. Galindo Esparza

### Abstract
Question Generation is already a common way to augment QA data. The Question Answering model can improve the performance and increase the robustness by augmenting the variety of questions. However, the traditional way of question generation, which paraphrases declarative sentences into questions, makes the generated questions highly repetitive from the declarative sentences and introduces trivial additional information. Subsequently, Neural seq2seq models have come to dominate QG tasks. Although the seq2seq models can generate a variety of questions based on the passage, the type of questions generated is limited to the training dataset and the performance of the question generation model is determined by the amount of data. To overcome these shortcomings, we propose a QA data augmentation method (PQQ: Prompt Answer, Question Generation and Question Filter). We design a prompting template through <passage, question> pair in the QA dataset as an input and use a large-scale pre-trained language model (PLM) to output the prompted answers. The question generation (QG) model then outputs generated questions based on the prompted answer and the corresponding passage. Finally, the question filter intrinsically evaluates generated questions based on the Natural Language Inference (NLI) task: this model focuses on the relevance of the generated questions to the original dataset. The experimental results show that we exceed the baseline in two general QA datasets (SQUAD1.1 and TriviaQA); the best results are obtained in the low resource QA tasks (PolicyQA and TechQA).

### My contributions:
- Built the QA model and PQQ data augmenation Pipeline
- Wrote the whole paper

[Download paper here](https://drive.google.com/file/d/1zM3qz6xojg2ou5Jx13YNAEuA6s-HTCm8/view?usp=sharing)


