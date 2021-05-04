---
layout: default
---

## <a name="lucia" id="lucia"></a>Lucia Specia: Disagreement in human evaluation: blame the task not the annotators.

**Imperial College London**

<block class="image"><img width="300px" src="images/Lucia_Specia.jpg" alt="" /></block>

<b>Abstract:</b><br>
It is well known that human evaluators are prone to disagreement and that this is a problem for reliability and reproducibility of evaluation experiments. The reasons for disagreement can fall into two broad categories: (1) human evaluator, including under-trained, under-incentivised, lacking expertise, or ill-intended individuals, e.g., cheaters; and (2) task, including ill-definition, poor guidelines, suboptimal setup, or inherent complexity or subjectivity. While in an ideal evaluation experiment many of these elements will be controlled for, in this talk I will argue that task complexity and subjectivity are much harder issues and that in some cases agreement cannot and should not be expected. I will cover several evaluation experiments on tasks with variable degrees of complexity and subjectivity, discuss their levels of disagreement along with other issues. I hope this will lead to an open discussion on possible strategies and directions to address this problem.


<b>Bio:</b><br>
Lucia Specia is Professor of Natural Language Processing at Imperial College London, with part-time appointments at the University of Sheffield and Dublin City University. Her research focuses on various aspects of data-driven approaches to language processing, with a particular interest in multimodal and multilingual context models and work at the intersection of language and vision. Her work has been applied to various tasks such as machine translation, image captioning, text adaptation and quality estimation. She is also interested in making machine translation useful for end-users, where tools like quality estimation and automatic post-editing play a big role. She is the recipient of the MultiMT ERC Starting Grant on Multimodal Machine Translation (2016-2021) and is also currently involved in research projects on in-browser machine translation and quality estimation, as well as multilingual referential grounding. In the past she worked as Senior Lecturer at the University of Wolverhampton (2010-2011), and research engineer at the Xerox Research Centre, France (2008-2009, now Naver Labs). She received a PhD in Computer Science from the University of São Paulo, Brazil, in 2008.

## <a name="adina" id="adina"></a>Adina Williams: For Matters Word Order Little MLM.

**Facebook AI Research**

<block class="image"><img width="300px" src="images/AdinaHeadshot.jpg" alt="" /></block>

<b>Abstract:</b><br>
One possible explanation for the impressive performance of masked language models (MLMs) is that they can learn to represent the syntactic structures prevalent in classical NLP pipelines. Were this correct, we would expect that fine-tuning such models on tasks requiring syntactic structure would lead them to be sensitive to word order at inference time. To address this question, we permute example word order at several steps in the pipeline---during fine-tuning, evaluation, and/or pre-training---and measure the results. We find that permuting word order during fine-tuning has remarkably little effect on downstream performance for several purportedly syntax sensitive NLU tasks (including NLI). Next, we pre-train MLMs on examples with randomly shuffled word order, and find that these models still achieve high accuracy (even after unpermuted fine-tuning) on many downstream tasks—including tasks specifically designed to be challenging for models that ignore word order. Our results show that the success of MLM pre-training is largely due to distributional information not any knowledge of word order per se, and underscores the importance of curating challenging evaluation datasets that require deeper syntactic knowledge.

<b>Bio:</b><br>
Adina Williams is a Research Scientist at Facebook AI Research in New York City. Her recent projects focus on trying to understand the behavior of deep neural networks from an interdisciplinary perspective that draws from linguistics, cognitive science, and natural language processing. Her current projects focus on combinations of natural language inference, evaluating model performance and explaining model behaviors, dynamic adversarial dataset collection, and information theoretic approaches to computational morphology. Previously, she earned her PhD at New York University in the Department of Linguistics, where she investigated the brain basis of syntactic and semantic processing.
 


