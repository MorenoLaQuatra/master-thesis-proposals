Master Thesis Instructions
=================
Contact Point:

- Moreno La Quatra: moreno.laquatra@polito.it


Table of contents
=================

* [Instructions and templates](#instructions-and-templates)
* Natural Language Processing
    * [Unsupervised Representation Learning (Contrastive Learning)](#unsupervised-representation-learning-)
    * [Efficent AI-powered platform for scientific literature](#efficent-ai-powered-platform-for-scientific-literature-) **NEW**
    * [Smart Recycle Bins](#smart-recycle-bins-) **NEW**
* Audio Processing
    * [Music Source Separation](#music-source-separation-) **NEW**
    * [Audio Event Detection](#audio-event-detection-) **NEW**
* [Graduated Students](#graduated-students)

Instructions and templates (PoliTO students only)
============

If you are a student from Politecnico di Torino the latex template to write the master thesis is avaiable in [Overleaf](https://it.overleaf.com/latex/templates/master-thesis-template-polito/jvfrbmxqkscw)

The first step is to create a GitHub Educational account and create an ad-hoc repository containing all relevant code and information for the master thesis.

The research work expected during the development of the master thesis will cover the following steps.

### State-of-the-art exploration
Collect, read and analyze the most recent and relevant publications in the proposed application field. Related works could be summarized and presented by using the Markdown Template available [here](/RW_template.md). Publication could be searched by using the following services:
- [Google Scholar](https://scholar.google.com/)
- [Arxiv](https://arxiv.org/search/)

### Data collection and finding
The majority of the thesis requires a step of data collection or data search. 
During the exploration of the state of the art the student is asked to collect and organize the data used by each publication.
Dataset must be presented in an organized way by expoiting the Markdown template available [here](/DS_template.md)
If a new data collection is created/parsed please create a specific Markdown file (template available [here](/NEWDS_template.md)) explaining both the data collection procedure and the statistics of the data collection.


A video tutorial explaining how to create a Python package is available here: [YouTube](https://www.youtube.com/watch?v=GIF3LaRqgXo) .

Natural Language Processing
============

### Unsupervised Representation Learning <a href="mailto:moreno.laquatra@polito.it?subject=[Master Thesis] Unsupervised Representation Learning  - YOUR NAME HERE"><img src="https://shields.io/badge/Click%20to%20candidate-available-green" alt="Available"></a>

<a href="https://en.wikipedia.org/wiki/Natural_language_processing"><img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-yellow" alt="Natural Language Processing"></a>

![immagine](https://user-images.githubusercontent.com/10062811/138849271-71e64021-1ada-46a1-b4f6-9a1d1838c1ee.png)
_image by: https://arxiv.org/abs/2009.12061_

Learning effective representations of the input data is one of the main challenges of deep learning algorithms. While it is framed as an independent task, effective representations are beneficial in a variety of contexts and domains. **Contrastive Learning** is one of the hot-topics in current research. It allows exploiting un-annotated data to let the model learns by contrastive examples. It all started in the Computer Vision domain with some groundbreaking publications (e.g., [SimCLR](https://arxiv.org/abs/2002.05709)), however, at the time of writing, almost 400 papers have been published both for CV and NLP.

The **main objectives** of this thesis are:

1. Analyze the state-of-the-art in contrastive learning and data augmentation techniques (mainly in NLP).
2. Find interesting spots where Contrastive Learning can be effectively exploited (e.g., structured data representation)
3. Define a novel contrastive learning algorithm and demonstrate its effectiveness in real-world scenarios. The model should be trained and evaluated on benchmark dataset (the Master Thesis could involve also data collection).


**References :books::**

Radford, Alec, et al. "Learning transferable visual models from natural language supervision." arXiv preprint arXiv:2103.00020 (2021). [article](https://arxiv.org/abs/2103.00020)

Chen, Ting, et al. "A simple framework for contrastive learning of visual representations." International conference on machine learning. PMLR, 2020. [article](https://arxiv.org/abs/2002.05709) 

Hosking, T., & Lapata, M. (2021). Factorising Meaning and Form for Intent-Preserving Paraphrasing. arXiv preprint arXiv:2105.15053. [article](https://aclanthology.org/2021.acl-long.112.pdf)

Zhang, Yan, et al. "An unsupervised sentence embedding method by mutual information maximization." arXiv preprint arXiv:2009.12061 (2020). [article](https://arxiv.org/abs/2009.12061)

Lilian Weng - [Contrastive Representation Learning](https://lilianweng.github.io/lil-log/2021/05/31/contrastive-representation-learning.html)

**Interesting projects :computer::**

[solo-learn library](https://github.com/vturrisi/solo-learn)

[TensorFlow Similarity](https://github.com/tensorflow/similarity)



***





### NLP-aided voice cloning <a href="mailto:moreno.laquatra@polito.it?subject=[Master Thesis] NLP-aided Voice Cloning  - YOUR NAME HERE"><img src="https://shields.io/badge/Click%20to%20candidate-not available-red" alt="Not Available"></a>

<a href="https://en.wikipedia.org/wiki/Natural_language_processing"><img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-yellow" alt="Natural Language Processing"></a>
<a href="https://en.wikipedia.org/wiki/Audio_signal_processing"><img src="https://img.shields.io/badge/AP-Audio%20Processing-blue" alt="Audio Processing"></a>

![immagine](https://lh3.googleusercontent.com/XMJlFDtiFU7WtZYnPDMDhT6jTFEXvTpY7c7sY70PtTkzEIDm6DvUv5nvHHwbOrUrDckS34aIu5fiZx0615p1-nf3rFxzhza387ud=w1440)

_image by: https://deepmind.com/blog/article/wavenet-generative-model-raw-audio_

What if you can speak with someone else voice? _Voice imitation_ is usually challenging from an human perspective. It requires both specific training and great voice flexibility. This thesis aims at exploring the intersection of audio and natural language processing domain for the task of voice cloning.

The **main objectives** of this thesis are:

1. Analyze the state-of-the-art voice cloning.
2. Leverage state-of-the-art NLP models.
3. Define a novel approach and demonstrate its effectiveness both using benchmark datasets and real-world data (Master Thesis could involve also data collection).


**References :books::**

Voice Cloning: a Multi-Speaker Text-to-Speech Synthesis Approach based on Transfer Learning [article](https://arxiv.org/abs/2102.05630)

Neural Voice Cloning with a Few Samples [article](https://proceedings.neurips.cc/paper/2018/file/4559912e7a94a9c32b09d894f2bc3c82-Paper.pdf) 

[Blog post](https://towardsdatascience.com/you-can-now-speak-using-someone-elses-voice-with-deep-learning-8be24368fa2b)

**Interesting projects :computer::**

[Real time voice cloning](https://github.com/CorentinJ/Real-Time-Voice-Cloning)






***





### Efficent AI-powered platform for scientific literature <a href="mailto:moreno.laquatra@polito.it?subject=[Master Thesis] Efficent AI-powered platform for scientific literature - YOUR NAME HERE"><img src="https://shields.io/badge/Click%20to%20candidate-available-green" alt="Available"></a>

<a href="https://en.wikipedia.org/wiki/Natural_language_processing"><img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-yellow" alt="Natural Language Processing"></a>
<a href="https://en.wikipedia.org/wiki/Software_design"><img src="https://img.shields.io/badge/SW-Sofware%20Design-purple" alt="SW Design"></a>

![immagine](https://contenthub-static.grammarly.com/blog/wp-content/uploads/2021/09/literature-review.jpeg)

_image by: https://grammarly.com_

The task of reviewing the literature for a scientific project is one of the most crucial steps for its success. This thesis is intented to apply several NLP architecture and tools for generating a platform aimed at helping researchers during the academic literature review.

The **main objectives** of this thesis are:

1. Define the scope and the tools for platform develpment.
2. Leverage state-of-the-art NLP models for classification, summarization, automated scoring, user-item similarity, etc.
3. Implement, train and make efficient relevant DL architectures that can be used in the platform.
4. Platform deployment.


**References :books::**

ArXiv Sanity [platform](https://arxiv-sanity-lite.com/)

Semantic Scholar [platform](https://www.semanticscholar.org/) 

A Web-based Knowledge Hub for Exploration of MultipleResearch Article Collections [paper](https://dl.acm.org/doi/abs/10.1145/3404835.3462780)

**Interesting projects :computer::**

[arxiv scraper](https://github.com/Mahdisadjadi/arxivscraper)


***

### Smart Recycle Bin <a href="mailto:moreno.laquatra@polito.it?subject=[Master Thesis] Smart Recycle Bin - YOUR NAME HERE"><img src="https://shields.io/badge/Click%20to%20candidate-available-green" alt="Available"></a>

<a href="https://en.wikipedia.org/wiki/Natural_language_processing"><img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-yellow" alt="Natural Language Processing"></a>
<a href="https://en.wikipedia.org/wiki/Audio_signal_processing"><img src="https://img.shields.io/badge/AP-Audio%20Processing-blue" alt="Audio Processing"></a>

![immagine](https://www.re-learn.eu/wp-content/uploads/2022/09/Copy-of-SITO-4.0-X-immagini-3-pdf.jpg)

Recycling is a key step for a sustainable future. However, the current recycling process rely on human intervention and can be error-prone. This thesis is a collaboration with [relearn](https://www.re-learn.eu/) and aims at developing a smart recycle bin that can automatically recognize the type of waste and provide the user with the correct recycling instructions.
The goal of this thesis is to jointly optimize NLP and audio processing models for the task of waste classification and recycling instructions generation.

The **main objectives** of this thesis are:
- Analyze state-of-the-art models for automatic speech recognition to detect the spoken utterance by the user.
- Analyze state-of-the-art models for text classification to detect the type of waste and the correct recycling instructions.
- Benchmark state-of-the-art models both for audio and text classification.
- Define a novel approach and demonstrate its effectiveness both using benchmark datasets and real-world data (Master Thesis will involve testing the system in real-world scenarios).

**References :books::**

- [Robust Speech Recognition via Large-Scale Weak Supervision](https://cdn.openai.com/papers/whisper.pdf)
- [Speech Commands: A Dataset for Limited-Vocabulary Speech Recognition](https://arxiv.org/abs/1804.03209)
- [WasteNet: A Deep Learning Approach for Waste Classification](https://arxiv.org/abs/2006.05873)

**Interesting projects :computer::**

- [Whisper from OpenAI](https://github.com/openai/whisper)
- [Sentence-BERT](https://www.sbert.net/)



Audio Processing
============

### Music Source Separation <a href="mailto:moreno.laquatra@polito.it?subject=[Master Thesis] Audio Source Separation - YOUR NAME HERE"><img src="https://shields.io/badge/Click%20to%20candidate-available-green" alt="Available"></a>

<a href="https://en.wikipedia.org/wiki/Audio_signal_processing"><img src="https://img.shields.io/badge/AP-Audio%20Processing-blue" alt="Audio Processing"></a>

![immagine](https://source-separation.github.io/tutorial/_images/source_separation_io.png)

_image by: https://source-separation.github.io/tutorial/landing.html_

Audio source separation is the task of separating a mixture of audio sources into their individual components. Audio recordings usually contain multiple sources, such as speech, music, and environmental sounds. Separating these sources is a fundamental problem in audio signal processing and machine learning. This thesis aims at exploring the state-of-the-art audio source separation techniques.

The **main objectives** of this thesis are:
- Analyze the state-of-the-art audio source separation techniques.
- Leverage modern deep learning architectures to design a novel approach for audio source separation. Specifically, the goal is to apply the proposed approach to the task of separating different musical instruments in a music recording.
- Demonstrate the effectiveness of the proposed approach using benchmark data collections (e.g., [MUSDB18](https://sigsep.github.io/datasets/musdb.html)).
- (Optional) Extend the proposed approach to the task of separating speech and music in a music recording.

**References :books::**

1. [MusDB18 dataset](https://sigsep.github.io/datasets/musdb.html)
2. [Jukebox: A Generative Model for Music](https://arxiv.org/abs/2005.00341)
3. [Music Separation Enhancement with Generative Modeling](https://arxiv.org/abs/2208.12387)



***

### Audio Event Detection <a href="mailto:moreno.laquatra@polito.it?subject=[Master Thesis] Audio Event Detection - YOUR NAME HERE"><img src="https://shields.io/badge/Click%20to%20candidate-available-green" alt="Available"></a>

<a href="https://en.wikipedia.org/wiki/Audio_signal_processing"><img src="https://img.shields.io/badge/AP-Audio%20Processing-blue" alt="Audio Processing"></a>

![immagine](https://dcase.community/images/tasks/challenge2018/task4_sound_event_detection.png)

_image by: https://dcase.community/challenge2018/task-large-scale-weakly-labeled-semi-supervised-sound-event-detection_

Audio event detection is the task of detecting the presence of a specific audio event in a given audio recording. Detecting specific audio events can be useful in many applications, such as audio surveillance, audio indexing, and audio search. Novel transformer-based architectures have recently been proposed for audio event detection but they are usually limited to short audio recordings or to a small number of audio events.

The **main objectives** of this thesis are:
- Analyze the state-of-the-art audio event detection techniques.
- Model the audio event detection task using novel design choices for the transformer-based architectures. Explore the use of restricted self-attention or structured state space models.
- Participate to specific audio event detection challenges (e.g., [DCASE](https://dcase.community/)).
- Demonstrate the effectiveness of the proposed approach using benchmark data collections.

**References :books::**

1. [DCASE workshop](https://dcase.community/)
2. [How Much Attention Should we Pay to Mosquitoes?](https://dl.acm.org/doi/10.1145/3503161.3551594)
3. [Efficiently Modeling Long Sequences with Structured State Spaces](https://arxiv.org/abs/2111.00396)



Graduated Students
============

- Simone Manni (2021) - PoliTO [@simonemanni](https://github.com/simonemanni)
- Sofia Perosin (2021) - PoliTO [@sofiaperosin](https://github.com/sofiaperosin)
- Giuseppe Gallipoli (2022) - PoliTO [@gallipoligiuseppe](https://github.com/gallipoligiuseppe)
