# Classification-Indonesian-Fraud-SMS-using-NaiveBayes-and-IndoBert
Evaluation of  TF-IDF Base Naive Bayes and IndoBERT Models in Indonesian Fraud SMS Classification Daniel Nomolas Wicaksono


📦 Evaluation of Naive Bayes with TF-IDF and IndoBERT Models for Indonesian SMS Fraud Classification
This repository presents the implementation and comparative evaluation of two text classification approaches for detecting fraudulent Indonesian SMS messages:

Naive Bayes with TF-IDF vectorization

IndoBERT, a pre-trained BERT model for the Indonesian language

🎯 Objective
To evaluate and compare the performance of both models in classifying SMS into three categories:

0 - Normal

1 - Fraud

2 - Promotion



🧪 Models Used
Multinomial Naive Bayes with TF-IDF features

IndoBERT from HuggingFace Transformers, fine-tuned for multi-class classification

📊 Evaluation Metrics
Accuracy

Precision

Recall

F1-Score

Confusion Matrix

🛠️ Tools & Libraries
Python (Scikit-learn, Pandas, NumPy)

HuggingFace Transformers, Datasets, and Tokenizers

Matplotlib and Seaborn for visualization

📌 Notes
The dataset used is anonymized and intended solely for academic and research purposes.

IndoBERT was fine-tuned using labeled Indonesian SMS messages for optimal performance.

