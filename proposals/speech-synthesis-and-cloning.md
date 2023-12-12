### Text-to-Speech and Voice Cloning

This masters thesis aims to address the challenging tasks of text-to-speech (TTS) voice cloning. 
It will involve developing a novel approaches that leverages recent advances in deep neural networks.
While current methods have made progress, there is still room for improvement in synthesizing naturally sounding voices that can be personalized to match target speakers. 
This work will explore designing a new model architecture and training methodology to better capture both speaker identity and enhance prosody in the generated speech.
The thesis will also investigate how to integrate the use of specialized markup languages (e.g., [SSML](https://en.wikipedia.org/wiki/Speech_Synthesis_Markup_Language)) into current architectures to enable fine-grained control over the generated speech (e.g., emphasis, pauses, etc.)

A comprehensive literature review will identify open challenges and help select a promising research direction. 
The model will be rigorously evaluated on standard datasets using objective and, if possible, subjective metrics. 
Its capabilities, such as how closely it can match new voices, will be systematically compared to state-of-the-art baselines.

**Objectives:**

The main objectives of this thesis are:
- **O1:** Perform a literature review on TTS and voice cloning.
- **O2:** Design a new model architecture and training methodology. It will leverages pre-trained or self-supervised speech representations and will be able to generate speech with a specific speaker identity.
- **O3:** Evaluate the model on standard datasets using objective and subjective metrics. Compare its capabilities to state-of-the-art baselines.
- **O4:** Write a thesis report and present the results.
- **O5:** (Optional) Implement a working demo.

**📚 Suggested Readings:**

- Tools:
  - **WhisperSpeech** - open source framework for TTS - [[access](https://collabora.github.io/WhisperSpeech/)]
  - **Coqui TTS** - open source framework for TTS - [[access](https://coqui.ai/)]
- Technical reports:
  - **TorToiSe TTS technical report** by James Betker [[paper access](https://arxiv.org/abs/2305.07243)]
  - **SSML: A Speech Synthesis Markup Language** by Taylor and Isard [[paper access](https://era.ed.ac.uk/bitstream/handle/1842/1242/Taylor_1997_a.pdf;jsessionid=38271D006919DF04A297152AD70F8DE5?sequence=1)]

- Research papers
  - **Zero-shot text-to-speech synthesis conditioned using self-supervised speech representation model** by Fujita et al. [[paper access](https://arxiv.org/abs/2304.11976)]
  - **Voicebox: Text-Guided Multilingual Universal Speech Generation at Scale** by Le et al. [[paper access](https://arxiv.org/abs/2306.15687)]
  - **Robust Speech Recognition via Large-Scale Weak Supervision** by Radford et al. [[paper access](https://cdn.openai.com/papers/whisper.pdf)]

This research has the potential to advance both TTS and voice cloning techniques. It also aims to help foster more natural and personalized speech technologies for Italian, which could benefit applications in education, accessibility, and entertainment.

**📝 Notes:**
- 💻 The thesis involves developing new deep learning models and requires a strong background in audio-related topics and Python programming.
- 🗺️ The research will primarily center on languages rooted in Latin and Germanic origins (such as English and Italian).
- 💼 This thesis is in collaboration with [AudioBoost](https://www.audioboost.it/), a startup focusing on speech technologies.
- 🤖 The lab has recently acquired two [Ameca robots](https://www.engineeredarts.co.uk/robot/ameca/). Depending on the progress of the thesis, it may be possible to create a working demo to give the robot a more natural voice.