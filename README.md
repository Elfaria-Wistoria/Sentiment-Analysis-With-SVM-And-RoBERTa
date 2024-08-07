# 🎉 Sentiment Analysis on YouTube Comments using RoBERTa and SVM 🚀

![Sentiment Analysis](https://media.giphy.com/media/3o6Mb5Cy8Xb3N6L5u0/giphy.gif)

## 📚 Overview

Welcome to the **Sentiment Analysis on YouTube Comments** project! This project aims to analyze and predict the sentiment of comments on YouTube videos using advanced machine learning techniques. We leverage the power of the RoBERTa transformer model for feature extraction and Support Vector Machine (SVM) for sentiment classification. 🎯

## 📈 Project Highlights

- **High Accuracy**: Achieved a mean cross-validation accuracy of 98.83% across 5 folds.
- **Cutting-edge Technology**: Utilizes RoBERTa, a state-of-the-art transformer model for text representation.
- **Robust Pipeline**: From data scraping to sentiment prediction, the entire pipeline is automated and efficient.
- **Cross-validation**: Ensures consistency and reliability of the model across the dataset.

## 🌟 Features

- **Scraping Comments**: Automatically fetch comments from YouTube using YouTube Data API.
- **Data Cleaning**: Preprocess comments to remove noise and irrelevant characters.
- **Feature Extraction**: Extracts rich semantic features using RoBERTa embeddings.
- **Sentiment Classification**: Classifies comments as **Negative**, **Neutral**, or **Positive** using SVM.
- **Model Persistence**: Saves trained models for future predictions on new data.

## 🛠️ Installation

To run this project, clone the repository and install the required packages:

```bash
git clone https://github.com/yourusername/sentiment-analysis-youtube.git
cd sentiment-analysis-youtube
pip install -r requirements.txt
