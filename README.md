# 📰 Explainable Fake News Detection Using NLP and Deep Learning

## 📌 Overview
This project implements a Fake News Detection system using advanced transformer-based language models. The system classifies news articles as real or fake by leveraging contextual embeddings learned through deep neural architectures.

Multiple transformer models were evaluated and compared to analyze performance across approaches.

---

## 🚀 Features

✅ Fake vs Real news classification  
✅ Transformer-based NLP models  
✅ Comparative model evaluation  
✅ Explainable AI with LIME  
✅ High-accuracy detection system  

---

## 🧠 Models Implemented

The following models were trained and evaluated:

- **XLM-RoBERTa**
- **ABERT**
- **STODL-FNDC**

---

## 📊 Final Results

| Model            | Accuracy |
|------------------|----------|
| XLM-RoBERTa      | **0.9976** |
| ABERT            | 0.9208 |
| STODL-FNDC       | 0.9891 |

XLM-RoBERTa achieved the highest classification accuracy, demonstrating strong generalization capability.

---

## 📂 Dataset

This project uses the **ISOT Fake News Dataset**.

- **Description:** Contains labeled real and fake news articles  
- **Task:** Binary text classification  
- **Domain:** News articles  

The dataset is widely used for benchmarking fake news detection systems.

---

## 🔍 Explainable AI (XAI)

To improve model interpretability, **LIME (Local Interpretable Model-Agnostic Explanations)** was used.

LIME provides:

✅ Feature-level explanations  
✅ Insight into model predictions  
✅ Transparency for classification decisions  

This helps understand which words or phrases influenced predictions.

---

## 🛠 Technologies Used

- **Python**
- **Transformers / Hugging Face**
- **Deep Learning**
- **LIME (Explainable AI)**
- **NumPy / Pandas / Scikit-learn** *(edit if needed)*

---

## ⚙️ Methodology

The system pipeline includes:

1. Text preprocessing  
2. Transformer-based embedding generation  
3. Model training & fine-tuning  
4. Prediction & evaluation  
5. Model explanation using LIME  

---

## 🎯 Applications

Fake News Detection systems can be applied in:

- Misinformation filtering  
- Social media monitoring  
- Media credibility analysis  
- Fact-checking systems  

---

## 📌 Notes

Model performance depends on:

- Dataset quality & diversity  
- Training configuration  
- Text domain  

---

## 👨‍💻 Author

Developed as part of an NLP / Deep Learning project.
