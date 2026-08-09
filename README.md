Final Project: Conspiracy Discourse Analysis & Classification
Overview
This repository contains the code and research for our Final Project in Information Systems. The project focuses on identifying and classifying conspiratorial discourse on social media, utilizing a specific case study on political influencer Charlie Kirk.

By leveraging advanced Natural Language Processing (NLP) and machine learning techniques, we developed a hybrid computational model designed to distinguish between legitimate political criticism and manipulative conspiracy theories. Our custom model successfully overcomes the over-classification and conservatism biases often found in generic Zero-Shot Large Language Models (LLMs).

Key Achievements
Hybrid Machine Learning Architecture: Developed an ensemble model combining BERT (for deep semantic embeddings) with a Random Forest classifier.

High Accuracy: Achieved a classification accuracy rate of over 80%, outperforming generic commercial models.

Semantic & Emotional Profiling: Engineered features such as "emotional entropy" to prove that viral conspiracy discourse often relies on positive, mobilizing rhetoric rather than strictly negative sentiment.

Project Structure & Execution Order
The repository consists of several Jupyter Notebooks. To review the code or reproduce the workflow, please follow this specific order of execution:

1. Sentiment_1.ipynb
Sentiment & Emotional Analysis
This notebook calculates the emotional profile of the texts. It extracts semantic features and analyzes the sentiment (positive vs. negative) to identify the unique "mobilizing rhetoric" and emotional entropy characteristic of the dataset.

2. Bert_Model.ipynb
Model Training & Classification
The core algorithmic pipeline of the project. This notebook utilizes BERT to generate contextual text embeddings and trains a Random Forest classifier on these features to accurately predict and classify conspiratorial discourse.

3. API יוטיוב API ו מידע נוסף...
API Integration & Data Fetching
Contains the scripts used to interact with various social media APIs (including YouTube). This section handles the extraction of external metadata and supplementary engagement metrics.

4. בדיקות על לינקים.ipynb
Link Verification & Analysis
This script validates and analyzes the outbound URLs found within the text. The presence and type of external links serve as crucial structural features for identifying institutional vs. non-institutional media sources.

5. עיבוד נתונים.ipynb
Data Processing & Cleaning
The final phase of the pipeline, which includes the ultimate data cleaning, normalization of text features (removing HTML tags, handling slang), and organizing the final datasets for presentation and visualization.

Authors:

Sarit Failayev

Gabriel Gabai

College of Law and Business - Department of Computer Science and Information Systems
