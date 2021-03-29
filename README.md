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
     * [Multimodal Learning](#multimodal-learning-)
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

News events such as protests, accidents or natural disasters represent a unique information access problem where traditional approaches fail. For example, immediately after an event, the corpus may be sparsely populated with relevant content. Even when, after a few hours, relevant content becomes available, it is often inaccurate or highly redundant. At the same time, crisis events demonstrate a scenario where users urgently need information, especially if they are directly affected by the event. The goal of the TREC Temporal Summarization Track is to develop systems for efficiently monitoring the information associated with an event over time. (source TREC Temporal Summarization Track)[https://sites.google.com/site/temporalsummarization]

The **main objectives** of this thesis are:

- Define and explore the state of the art in Temporal Summarization.
- Design a new temporal summarization framework able to process data streams from different sources.
- Simulate the process on existing benchmark dataset
- Create a web-based dashboard to present live updates about ongoing events.

**References :books::**

McCreadie, R., Santos, R. L., Macdonald, C., & Ounis, I. (2018). Explicit diversification of event aspects for temporal summarization. ACM Transactions on Information Systems (TOIS), 36(3), 1-31. [article](https://core.ac.uk/download/pdf/111557739.pdf)

Aslam, J., Diaz, F., Ekstrand-Abueg, M., McCreadie, R., Pavlu, V., & Sakai, T. (2015). TREC 2014 temporal summarization track overview. [article](https://apps.dtic.mil/sti/pdfs/ADA618947.pdf)

### Multimodal Learning <a href="mailto:moreno.laquatra@polito.it?subject=Multimodal Learning - YOUR NAME HERE"><img src="https://shields.io/badge/-available-green" alt="Available"></a>

<a href="https://en.wikipedia.org/wiki/Natural_language_processing"><img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-yellow" alt="Natural Language Processing"></a> 
<a href="https://en.wikipedia.org/wiki/Computer_Vision"><img src="https://img.shields.io/badge/CV-Computer%20Vision-green" alt="Computer Vision"></a>

You can find an explaination of Multimodal learning in videos, schemes, images, podcasts. This is multimodal learning, it consists of several techniques that are able to combine the input from different modalities (images, videos, audio, text, etc.) at _the same time_. 
**Multi** refers to the simultaneous process.
**Modal** refers to the modalities (images, audios, videos, etc.).
**Learning** refers to the automated process involved (machine or deep learning).

The **main objectives** of this thesis are:

- Define and explore the state of the art in Multimodal learning.
- Investigate the deep learning techniques that can be designed or adapted for a multimodal scenario. 
- Simulate the process on existing multimodal benchmark dataset to prove the effectiveness of the designed methodology.

**References :books::**

Hu, R., & Singh, A. (2021). Transformer is All You Need: Multimodal Multitask Learning with a Unified Transformer. arXiv preprint arXiv:2102.10772. [article](https://arxiv.org/abs/2102.10772)

Lu, J., Batra, D., Parikh, D., & Lee, S. (2019). Vilbert: Pretraining task-agnostic visiolinguistic representations for vision-and-language tasks. arXiv preprint arXiv:1908.02265. [article](https://arxiv.org/abs/1908.02265)

Lin, X., Bertasius, G., Wang, J., Chang, S. F., Parikh, D., & Torresani, L. (2021). Vx2Text: End-to-End Learning of Video-Based Text Generation From Multimodal Inputs. arXiv preprint arXiv:2101.12059. [article](https://arxiv.org/abs/2101.12059)

**Interesting projects :computer::**
- [List of updated references](https://github.com/pliang279/awesome-multimodal-ml)
- [MMF: multimodal framework](https://mmf.sh/)

**Additional Material:**

- [BERT Can See Out of the Box](https://www.youtube.com/watch?v=K2ho2zoulT4)
- [Learning Visiolinguistic Representations with ViLBERT w/ Stefan Lee - Podcast](https://www.youtube.com/watch?v=LDrQgIhXlk8)
- [Vilbert talk](https://www.youtube.com/watch?v=hFVM1PylYZI) [demo](https://vilbert.cloudcv.org/)


Ongoing Topics
============

### Text Summarization <a href="https://en.wikipedia.org/wiki/Natural_language_processing"><img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-yellow" alt="Natural Language Processing"></a> <a href="https://en.wikipedia.org/wiki/Automatic_summarization"><img src="https://img.shields.io/badge/ATS-Automatic%20Text%20Summarization-blue" alt="Automatic Text Summarization"></a>
### Multimodal Learning <a href="https://en.wikipedia.org/wiki/Natural_language_processing"><img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-yellow" alt="Natural Language Processing"></a> <a href="https://en.wikipedia.org/wiki/Computer_Vision"><img src="https://img.shields.io/badge/CV-Computer%20Vision-green" alt="Computer Vision"></a>


Published Thesis
============
