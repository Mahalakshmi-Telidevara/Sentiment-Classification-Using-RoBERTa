# Sentiment-Classification-Using-RoBERTa
This project aims to classify Twitter sentiments into multiple categories using machine learning models. It leverages the power of RoBERTa, SVM, and Random Forest models to predict the sentiment of tweets. A Streamlit application has been developed to deploy the RoBERTa-based sentiment classification model. The final model classifies tweets into one of the following emotions: Joy, Love, Surprise, Anger, Fear, and Sadness.

## Dataset
The dataset used in this project is a Twitter Multi-Class Sentiment Dataset sourced from GitHub, with additional records added to enhance the dataset for training and testing. The dataset contains various features that help classify sentiments into categories.

## Models Used
    1. SVM (Support Vector Machine): Initially tested for sentiment classification.
    2. Random Forest: Another classical machine learning model tested for sentiment analysis.
    3. RoBERTa (Robustly Optimized BERT Pretraining Approach): A transformer-based model fine-tuned for sentiment classification based on its superior accuracy over SVM and Random Forest.

## Technology Stack
    1. Python: The core programming language for this project.
    2. Streamlit: Used to build an interactive web application for real-time sentiment analysis.
    3. RoBERTa: A transformer-based model for natural language understanding and classification.
    4. SVM & Random Forest: Classical machine learning models used for comparison.
    5. Google Colab (T4 GPU): Used for training the models, leveraging the power of the T4 GPU for faster computations.

## Steps to Run
  # Download the Dataset:
      Download the dataset.
  # Clone the Repository:
      git clone https://github.com/Mahalakshmi-Telidevara/Sentiment-Classification-Using-RoBERTa.git
      cd Sentiment-Classification-Using-RoBERTa
  # Open the Google Colab Notebook:
      1. Import the downloaded dataset.
      2. Open the Sentiment_classification_Using_RoBERTa.ipynb file in Google Colab.
      3. Run the notebook to execute the sentiment analysis using the RoBERTa model.
      
## Conclusion
This project demonstrates how to build and deploy a sentiment classification application using RoBERTa. The application classifies sentiments into multiple categories based on a dataset of Twitter sentiments. The fine-tuning of RoBERTa provides the best performance for sentiment classification compared to traditional machine learning models like SVM and Random Forest.
