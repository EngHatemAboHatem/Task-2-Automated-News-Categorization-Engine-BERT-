# 📰 Phase 2 - Task 2: Automated News Categorization Engine (BERT)

## 📌 Project Overview
This project demonstrates the application of Transfer Learning in Natural Language Processing (NLP). I developed a text classification pipeline by fine-tuning a pre-trained **BERT (Bidirectional Encoder Representations from Transformers)** model to automatically sort news headlines into four main categories:
1. Global/World News
2. Sports Events
3. Business & Finance
4. Science & Technology

## 🗂️ Dataset
The training process utilized the **AG News Dataset** provided by the Hugging Face library, which contains thousands of news articles categorized into these four specific labels.

## 🛠️ Methodology & Tech Stack
* **Frameworks:** `PyTorch`, Hugging Face `transformers`, and `datasets`.
* **Data Processing:** Applied `BertTokenizer` to transform raw news text into machine-readable formats (input IDs and attention masks).
* **Modeling:** Adapted the `bert-base-uncased` architecture to handle a 4-class sequence classification task.
* **Training Pipeline:** Configured and executed the training loop using the Hugging Face `Trainer` API.
* **User Interface:** Integrated a **Gradio** web interface for real-time, interactive topic prediction.

## 📊 Performance Metrics
After evaluating the fine-tuned model on the test split, it achieved solid predictive performance:
* **Accuracy:** ~83.00%
* **Weighted F1-Score:** ~82.83%

## 🚀 Interactive Demo
The final section of the notebook includes a **Gradio** web application. Once executed, it generates a UI where users can type or paste any news headline and receive an instant category prediction from the trained AI model.

---
**Developer:** Hatem  
**Date:** March 2026
