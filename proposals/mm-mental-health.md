# Master Thesis Proposal: Depression Detection from Speech Using SSL & Multimodal Models

## 📌 Research Goal
Evaluate and compare **self-supervised learning (SSL) speech models** (e.g., Wav2Vec2, HuBERT, Whisper) and **multimodal (speech + text) models** for **depression detection**.  
Investigate:
- Performance of **speech-only** SSL models in detecting depression.
- **Multimodal fusion** of speech and text (BERT + SSL models).
- The role of **prosody** and paralinguistic cues.
- **Generalizability** across different datasets.

## 📚 Datasets
- **[DAIC-WOZ](https://dcapswoz.ict.usc.edu/)**: Depression diagnosis dataset with speech, text, and PHQ-8 labels.
- **[E-DAIC](https://dcapswoz.ict.usc.edu/extended-daic-database-download/)**: Extended DAIC-WOZ with additional annotations.

## 🏗️ Methodology
1. **SSL Model Benchmarking**
   - Evaluate **Wav2Vec2, HuBERT, Whisper, SpeechT5** for depression detection.
   - Train classifiers (MLP, LSTMs, transformers) on extracted embeddings.
   - Compare zero-shot vs. fine-tuned performance.

2. **Multimodal Fusion (Speech + Text)**
   - Extract text embeddings (BERT/RoBERTa) and speech embeddings (SSL models).
   - Test different fusion strategies (concatenation, attention-based, late fusion).
   - Analyze whether text improves speech-based models.

3. **Prosody & Paralinguistics**
   - Extract features like pitch, energy, pauses.
   - Fuse with SSL embeddings for classification.
   - Evaluate their importance in depression detection.

4. **Explainability & Bias Analysis**
   - Use **SHAP, attention visualization** to interpret model predictions.
   - Test for **demographic biases** (gender, age, accent).

## 📅 Timeline (5 Months)
1. **Month 1**: Literature review, dataset preprocessing.
2. **Month 2**: SSL model benchmarking.
3. **Month 3**: Multimodal fusion experiments.
4. **Month 4**: Prosody integration, explainability study.
5. **Month 5**: Final evaluation, write thesis & paper.

## 🔍 Expected Outcomes
- A **benchmark** of SSL models for depression detection.
- A **multimodal speech-text fusion** approach.
- Insights into **prosody & explainability**.
- Potential submission to **Computer Speech and Language**.

---

### **🔹 Notes:**
- The project can be simplified to focus **only on SSL benchmarking**.
- Can be extended with **few-shot learning** for low-resource adaptation.
