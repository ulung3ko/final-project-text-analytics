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

To reproduce this project:

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Run the first cell to install dependencies.
3. Mount your Google Drive where the dataset and output folders are stored.
4. Run the notebook cells sequentially for training, evaluation, and analysis.

> **Note**: The dataset and model checkpoints are stored in Google Drive and not included in this repository due to size constraints.

## 📚 Academic Context

This project was developed as part of the **Text Analytics** course at the graduate level (Semester 2). It combines natural language processing (NLP), deep learning, and transfer learning to address fine-grained sentiment classification in a real-world setting.

## 🧾 License

This project is intended for academic and educational purposes only.

---

**Eko Ikhwan Saputra**  
_Master’s Student in Informatics_  
Universitas Islam Indonesia – 2025