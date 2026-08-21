# 🌐 Language Identification: Traditional Models vs. LLMs (ALLaM)

A comparative natural language processing project evaluating traditional machine learning pipelines against pre-trained Large Language Models (LLMs) for multi-language text classification.

## 👥 Project Team
- Course: Natural Language Processing[span_0](start_span)[span_0](end_span)
- Instructor: Dr. Ghada Alharbi[span_1](start_span)[span_1](end_span)
- Team Members: Nada Alsuhaimi, Rama Hamed Alhasainy, Raneem Almukhlifi, Rehab Alharbi[span_2](start_span)[span_2](end_span)

## 📊 Overview
The goal of this project is to identify the language of a given text input across five target languages: **English, Spanish, French, Japanese, and Russian**[span_3](start_span)[span_3](end_span). We compared two distinct approaches using a 22,000-instance dataset sourced from WiLI-2018 (Wikipedia via Kaggle)[span_4](start_span)[span_4](end_span):
1. Traditional Machine Learning: Evaluated Bag-of-Words with Naive Bayes as a baseline, moving to **TF-IDF with an SVM classifier**[span_5](start_span)[span_5](end_span).
2. LLM-Based Approach: Leveraged the ALLaM-7B-Instruct model via prompt engineering without additional fine-tuning[span_6](start_span)[span_6](end_span).

## 📈 Key Results
- TF-IDF + SVM: Achieved an outstanding accuracy of 99.20% due to its stability in statistical weighting across the entire text[span_7](start_span)[span_7](end_span).
- ALLaM-7B-Instruct: Achieved 96.20% accuracy, demonstrating strong zero-shot linguistic understanding while showing minor biases toward initial words, diacritics, and scientific terms[span_8](start_span)[span_8](end_span).

## 🛠 Tech Stack
- Languages & Libraries: Python, Scikit-learn (CountVectorizer, TfidfVectorizer, MultinomialNB, LinearSVC)[span_9](start_span)[span_9](end_span)
- Models: ALLaM-7B-Instruct (Hugging Face), Naive Bayes, Linear Support Vector Classification[span_10](start_span)[span_10](end_span)
- Dataset: WiLI-2018 Multilingual Corpus[span_11](start_span)[span_11](end_span)
