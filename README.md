# Stock Market Trend Prediction using News article Sentiment
This repository contains the code and datasets for predicting stock market trends using news articles and ML methods. The contents of this repository are organized as follows:
- Main_source_code.ipynb: This Jupyter Notebook contains the main source code responsible for organizing and pre-processing the news articles, as well as developing and evaluating various machine learning models: Logistic Regression (LR), Random Forest (RF), Support Vector Machines (SVM), Artificial Neural Network (ANN), Gated Recurrent Unit (GRU), and Long Short-Term Memory (LSTM). It also includes the creation of NLP representations (Tf-Idf and GloVe) from the news article data.
- Query_NYT_API.ipynb: This Jupyter Notebook focuses on obtaining the required news articles from the New York Times (NYT) API. It handles the data retrieval process and ensures the news articles are suitable for analysis.
- News_Visualisation.ipynb: This Jupyter Notebook enables exploratory analysis of the news article data by creating word cloud charts to visualize important news terms. It provides insights into the key topics and themes present in the dataset.
- Evaluating_Best_model.ipynb: This Jupyter Notebook utilizes the best-performing model to predict stock market trends for a new unseen time period, from January 1st, 2023 to May 1st, 2023.

The repository also includes the following folders:
- news_dataset: This folder contains the raw news article dataset obtained from the NYT API using the Query_NYT_API.ipynb code.
- preprocessed_datasets: This folder contains the preprocessed NLP representations (Tf-Idf and GloVe) that serve as input for the News-Based models and Hybrid models.

The code and datasets in this repository are used to gain insights into stock market trend prediction using news articles and ML methods.
