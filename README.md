# Amazon-Product-Review-Sentiment-Analysis-
This repository hosts a sentiment analysis project that examines customer reviews of video games on Amazon. The goal is to automatically categorize these reviews into distinct sentiment classes: positive, negative, and neutral. This project is particularly useful for businesses and analysts looking to gain insights into customer opinions and preferences in the gaming industry.

**The project can be utilized to:**
- Analyze customer feedback for video game products on Amazon.
- Understand market trends and customer satisfaction.
- Assist businesses in making data-driven decisions based on customer sentiment.
- Provide insights for game developers and publishers on customer preferences.

**How the project was conducted:**
Data Preprocessing: The project starts with cleaning and preprocessing Amazon video game reviews. This includes text normalization, removing non-alphabetic characters, and filtering out stopwords.
Model Training with AutoGluon: The core of the project involves using AutoGluon, an automated machine learning tool, to train models capable of sentiment analysis. AutoGluon simplifies the model selection and hyperparameter tuning process.
Dataset Splitting: The dataset is split into training, validation, and testing subsets to ensure robust model training and evaluation.

**Results:**
Training Data Performance: The model achieved impressive results on the training data, with an overall accuracy of 92%. It demonstrated high precision and recall across all sentiment classes, particularly excelling in identifying negative sentiments (Precision: 0.93, Recall: 0.95, F1-score: 0.94) and positive sentiments (Precision: 0.89, Recall: 0.96, F1-score: 0.92). Neutral sentiments also saw strong precision (0.96) but slightly lower recall (0.86).
Test Data Performance: On the test dataset, the model's accuracy was 70%, a notable decrease from the training performance but still a respectable score for a real-world application. The model's ability to identify negative (Precision: 0.72, Recall: 0.76, F1-score: 0.74) and positive sentiments (Precision: 0.73, Recall: 0.76, F1-score: 0.75) remained relatively strong, though with reduced precision and recall compared to the training data. Neutral sentiment detection was the most challenging for the model, with lower precision (0.63) and recall (0.56).
General Observations: The model demonstrated a high degree of effectiveness in classifying sentiments in Amazon video game reviews. However, the drop in performance metrics (especially precision and recall) on the test data suggests potential overfitting to the training data. This highlights the need for further model refinement to improve its generalization capabilities, particularly for neutral sentiment detection.
