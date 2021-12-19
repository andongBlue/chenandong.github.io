---
title: "Improving Low-resource Question Answering by Augmenting Question Information"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-2
excerpt: 'In this paper, aiming at scarcity of Tibetan knowledge graphs, we extend the Tibetan knowledge graph by using the triples of the high- resource language knowledge graphs and POI (Point of Information) map information. To improve the representation learning of the Tibetan knowledge graph, we propose a joint model to merge structure and entity description information based on the TransE and CNN model. '
date: 2021-01-11
venue: 'The Transactions on Asian and Low-Resource Language Information Processing'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3447248'
---
**Andong Chen**, Yuan Sun, Xiaobing Zhao, Rosella P. Galindo Esparza

### Abstract
Question Generation is already a common way to augment QA data. The Question Answering model can improve the performance and increase the robustness by augmenting the variety of questions. However, the traditional way of question generation, which paraphrases declarative sentences into questions, makes the generated questions highly repetitive from the declarative sentences and introduces trivial additional information. Subsequently, Neural seq2seq models have come to dominate QG tasks. Although the seq2seq models can generate a variety of questions based on the passage, the type of questions generated is limited to the training dataset and the performance of the question generation model is determined by the amount of data. To overcome these shortcomings, we propose a QA data augmentation method (PQQ: Prompt Answer, Question Generation and Question Filter). We design a prompting template through <passage, question> pair in the QA dataset as an input and use a large-scale pre-trained language model (PLM) to output the prompted answers. The question generation (QG) model then outputs generated questions based on the prompted answer and the corresponding passage. Finally, the question filter intrinsically evaluates generated questions based on the Natural Language Inference (NLI) task: this model focuses on the relevance of the generated questions to the original dataset. The experimental results show that we exceed the baseline in two general QA datasets (SQUAD1.1 and TriviaQA); the best results are obtained in the low resource QA tasks (PolicyQA and TechQA).

### My contributions:
- Built the QA model and PQQ data augmenation Pipeline
- Wrote the whole paper

[Download paper here](https://drive.google.com/file/d/1zM3qz6xojg2ou5Jx13YNAEuA6s-HTCm8/view?usp=sharing)


