# Sentiment Analysis of Tweets on Autonomous Vehicles

This repository contains the research and analysis conducted in our study on the comparative performance of various sentiment analysis models applied to the classification of tweets related to autonomous vehicles (AVs). 
Our work delves into a range of sentiment analysis models including Support Vector Machines (SVM), Long Short-Term Memory networks (LSTM), BERTweet(base), RoBERTa(base), and RoBERTa(base-latest), with and without additional layers.

The repository is organized into two main folders, MultiLabelClassification containing notebooks for each model tested in multi-label classification, and MultiClassClassification which contains models tested in the multi-class classification task.

#### Objectives

The main objectives of this study were to:

* Evaluate the performance of different sentiment analysis models in classifying tweets about AVs.
* Compare the effectiveness of these models in multi-label and multi-class classification tasks.
* Assess the impact of augmenting models with additional layers on their performance.


#### Findings

Our comprehensive analysis revealed that:

* RoBERTa(base-latest) outperforms other models in multi-label classification tasks, showcasing superior accuracy, precision, recall, and F1-score metrics.
* The addition of extra layers to RoBERTa models does not consistently enhance performance, hinting at potential overfitting issues.
* In multi-class classification, RoBERTa(base) emerged as the most effective model for multi-class tweet classification tasks.
* Non-transformer models like SVMs and LSTMs displayed lower performance in both multi-class and multi-label classifications, underlining the complexities they face in detailed sentiment analysis tasks.

### Citation


