# 🧠 Aspect-Based Sentiment Analysis using Transformer Models

This repository contains the final project for the **Text Analytics** course in the Master's program in Informatics. The project focuses on **Aspect-Based Sentiment Analysis (ABSA)** using transformer-based models, implemented in a single, well-documented Jupyter Notebook.

## 🎯 Project Objective

The main objective of this project is to evaluate how different pre-trained transformer models perform in fine-tuning for text classification tasks, particularly in the tourism domain. The task involves classifying sentiment on a per-aspect basis, rather than assigning a single sentiment to the whole review.

## 🛠️ Models Explored

The following pre-trained models were fine-tuned and evaluated:

- `bert-base-uncased`
- `distilbert-base-uncased`
- `roberta-base`

Each model was assessed using standard classification metrics after hyperparameter tuning and fine-tuning on the labeled dataset.

## 📌 Key Highlights

- Aspect-level sentiment classification  
- Hyperparameter tuning across multiple transformer architectures  
- Evaluation using precision, recall, F1-score, and confusion matrix  
- Clear visualizations of model performance  
- Implemented entirely in one notebook with step-by-step explanations  

## 📈 Result Summary

The models demonstrated high performance, with **DistilBERT** achieving the best F1-score:

| Model      | F1-Score |
|------------|----------|
| DistilBERT | 0.9783   |
| RoBERTa    | 0.9671   |
| BERT       | 0.9612   |

These results indicate that even lighter transformer models can be highly effective for domain-specific ABSA tasks.

## 🚀 Getting Started

The main Jupyter Notebook used in this project is:

- [`final_project_text_analytics.ipynb`](final_project_text_analytics.ipynb) – full version with output (⚠️ **might not render on GitHub** due to large file size)
- [`final_project_text_analytics_without_output.ipynb`](final_project_text_analytics_without_output.ipynb) – stripped-down version without output (✅ can be viewed directly on GitHub)

If the full notebook does not render properly on GitHub, you can open it using Google Colab:

👉 **[Open notebook with output in Google Colab](https://colab.research.google.com/drive/1rO8MDNd-IjB5sPeHrATjnL_-NmGxrOCL?usp=sharing)**

> **Note**: The dataset and model checkpoints are stored in Google Drive and not included in this repository due to size constraints.

## 📚 Academic Context

This project was developed as part of the **Text Analytics** course at the graduate level (Semester 2). It combines natural language processing (NLP), deep learning, and transfer learning to address fine-grained sentiment classification in a real-world setting.

## 🧾 License

This project is intended for academic and educational purposes only.

---

**Eko Ikhwan Saputra**  
_Master’s Student in Informatics_  
Universitas Islam Indonesia – 2025