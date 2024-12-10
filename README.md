# Sentiment Analysis of Tweets on Autonomous Vehicles from 2012 to 2021

This repository contains the research and analysis conducted in our study on the comparative performance of various sentiment analysis models applied to the classification of tweets related to autonomous vehicles (AVs). 
Our work explores a range of sentiment analysis models including Support Vector Machines (SVM), Long Short-Term Memory networks (LSTM), BERTweet(base), RoBERTa(base), and RoBERTa(base-latest).

#### Objectives

The main objectives of this study were to:

* Evaluate the performance of different sentiment analysis models in classifying tweets about AVs.
* Compare the effectiveness of these models in multi-label and multi-class classification tasks.
* Assess the impact of augmenting models with additional layers on their performance.

#### Repository Organization
The project is divided into several folders:
* Data sets: This folder contains several files with the 1,198 randomly selected tweet IDs used for manual labeling, training, validating, and testing models.
* Multiclass Classification: This folder contains complete code, manually labeled data, and tweet IDs.
* Multilabel Classification: This folder includes complete code, manually labeled data, and tweet IDs.
* Emotional and valence dictionary: This resource was utilized to filter the textual data.

Full Changelog: https://github.com/adam-aalah/Tweet-Sentiment-Classification/commits/v.1.0.0

#### Findings

Our comprehensive analysis revealed that:

* RoBERTa (base-latest) outperforms other models in multi-label classification tasks, demonstrating superior accuracy, precision, recall, and F1-score metrics.
* The addition of extra layers to RoBERTa models does not consistently enhance performance, suggesting potential overfitting issues.
* In multi-class classification, RoBERTa (base) emerged as the most effective model for classifying tweets in multi-class tasks.
* Non-transformer models such as SVMs and LSTMs exhibited lower performance in both multi-class and multi-label classifications, highlighting the challenges they encounter in nuanced sentiment analysis tasks.



