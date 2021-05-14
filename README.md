Master Thesis Instructions
=================
Contact Points:

- Luca Cagliero: luca.cagliero@polito.it 
- Moreno La Quatra: moreno.laquatra@polito.it

This repository contains the information used for the development a master thesis in the NLP domain at PoliTO.


Table of contents
=================

   * [Instructions and templates](#instructions-and-templates)
   * [Thesis proposals](#thesis-proposals)
     * [AL meets NLP](#al-meets-nlp-)
     * [Temporal Summarization](#temporal-summarization-)
     * [Generative Sentiment Analysis](#generative-sentiment-analysis-)
   * [Ongoing Topics](#ongoing-topics)
   * [Published Theisis](#published-thesis)

Instructions and templates
============

The latex template to write the master thesis is avaiable in [Overleaf](https://it.overleaf.com/latex/templates/master-thesis-template-polito/jvfrbmxqkscw)

The first step is to create a GitHub Educational account and create an ad-hoc repository containing all relevant code and information for the master thesis.

The research work expected during the development of the master thesis will cover the following steps.

### State-of-the-art exploration
Collect, read and analyze the most recent and relevant publications in the proposed application field. Related works could be summarized and presented by using the Markdown Template available [here](/RW_template.md). Publication could be searched by using the following services:
- [Google Scholar](https://scholar.google.com/)
- [Arxiv](https://arxiv.org/multi?group=grp_stat&%2Ffind=Search)

### Data collection and finding
The majority of the thesis requires a step of data collection or data search. 
During the exploration of the state of the art the student is asked to collect and organize the data used by each publication.
Dataset must be presented in an organized way by expoiting the Markdown template available [here](/DS_template.md)
If a new data collection is created/parsed please create a specific Markdown file (template available [here](/NEWDS_template.md)) explaining both the data collection procedure and the statistics of the data collection.


A video tutorial explaining how to create a Python package is available here: [YouTube](https://www.youtube.com/watch?v=GIF3LaRqgXo) .

Thesis proposals
============

### AL meets NLP <a href="mailto:moreno.laquatra@polito.it?subject=AL meets NLP - YOUR NAME HERE"><img src="https://shields.io/badge/-available-green" alt="Available"></a>
<a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><img src="https://img.shields.io/badge/AL-Active%20Learning-red" alt="Active Learning"></a>
<a href="https://en.wikipedia.org/wiki/Natural_language_processing"><img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-yellow" alt="Natural Language Processing"></a>

Active Learning is a subfield of machine learning that aims at reducing the number of supervised samples needed to train a machine learning model. 
It include an human-in-the-loop procedure aimed at selecting the most relevant examples for model's learning.

The **main objectives** of this thesis are:

- Explore the state of the art in Active Learning
- Define and propose an Active Learning approach for the fine-tuning of *deep* neural language models.
- Simulate the process on existing benchmark dataset

**References :books::**

Peshterliev, S., Kearney, J., Jagannatha, A., Kiss, I., & Matsoukas, S. (2019, June). Active Learning for New Domains in Natural Language Understanding. In Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 2 (Industry Papers) (pp. 90-96). [article](https://www.aclweb.org/anthology/N19-2012.pdf)

Schröder, C., & Niekler, A. (2020). A Survey of Active Learning for Text Classification using Deep Neural Networks. arXiv preprint arXiv:2008.07267. [article](https://arxiv.org/pdf/2008.07267.pdf)


**Interesting projects :computer::**

- [modAL](https://github.com/modAL-python/modAL)
- [libact](https://github.com/ntucllab/libact)


**Additional Material:**

Active Learning: Algorithmically Selecting Training Data to Improve Alexa’s Natural-Language Understanding [post](https://www.amazon.science/blog/active-learning-algorithmically-selecting-training-data-to-improve-alexas-natural-language-understanding)

Active Learning for Natural Language Processing. [post](https://crowintelligence.org/2020/06/04/active-learning-for-natural-language-processing/)


### Temporal Summarization <a href="mailto:moreno.laquatra@polito.it?subject=Temporal summarizaion - YOUR NAME HERE"><img src="https://shields.io/badge/-available-green" alt="Available"></a>

<a href="https://en.wikipedia.org/wiki/Information_retrieval"><img src="https://img.shields.io/badge/IR-Information%20Retrieval-blue" alt="Information Retrieval"></a>
<a href="https://en.wikipedia.org/wiki/Natural_language_processing"><img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-yellow" alt="Natural Language Processing"></a>

News events such as protests, accidents or natural disasters represent a unique information access problem where traditional approaches fail. For example, immediately after an event, the corpus may be sparsely populated with relevant content. Even when, after a few hours, relevant content becomes available, it is often inaccurate or highly redundant. At the same time, crisis events demonstrate a scenario where users urgently need information, especially if they are directly affected by the event. The goal of the TREC Temporal Summarization Track is to develop systems for efficiently monitoring the information associated with an event over time. [source TREC Temporal Summarization Track](https://sites.google.com/site/temporalsummarization)

The **main objectives** of this thesis are:

- Define and explore the state of the art in Temporal Summarization.
- Design a new temporal summarization framework able to process data streams from different sources.
- Simulate the process on existing benchmark dataset
- Create a web-based dashboard to present live updates about ongoing events.

### Generative Sentiment Analysis <a href="mailto:moreno.laquatra@polito.it?subject=Temporal summarizaion - YOUR NAME HERE"><img src="https://shields.io/badge/-available-green" alt="Available"></a>

<a href="https://en.wikipedia.org/wiki/Natural_language_processing"><img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-yellow" alt="Natural Language Processing"></a>

Sentiment analysis is one of the most important task in several NLP pipelines.
It consists in the analysis of text for classifying its sentiment being both positive or negative.
Generative models such as [GPT3]() open a large set of possibilities in this scenario.
This master thesis will cover both generative language and sentiment analysis.

The **main objectives** of this thesis are:

- Define and explore the state of the art in Language Generation.
- Analyze state of the art methodologies in Sentiment Anaysis.
- Simulate an innovative pipeline on existing benchmark dataset.

**References :books::**
Wang, H., & Zhai, C. (2017). Generative models for sentiment analysis and opinion mining. In A practical guide to sentiment analysis (pp. 107-134). Springer, Cham. [article](https://link.springer.com/chapter/10.1007/978-3-319-55394-8_6)

Gupta, R. (2019, May). Data augmentation for low resource sentiment analysis using generative adversarial networks. In ICASSP 2019-2019 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (pp. 7380-7384). IEEE. [article](https://arxiv.org/abs/1902.06818)



Ongoing Topics
============

### Text Summarization <a href="https://en.wikipedia.org/wiki/Natural_language_processing"><img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-yellow" alt="Natural Language Processing"></a> <a href="https://en.wikipedia.org/wiki/Automatic_summarization"><img src="https://img.shields.io/badge/ATS-Automatic%20Text%20Summarization-blue" alt="Automatic Text Summarization"></a>
