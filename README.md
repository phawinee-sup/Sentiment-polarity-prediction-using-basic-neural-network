# Sentiment Polarity Prediction using Basic Neural Network

This project focuses on building a basic neural network model to predict sentiment polarity (positive, negative, and neutral) based on text data. The dataset used for training the model is `SenticNet2_Thai.txt`, which contains columns that describe the sentiment attributes of each text.

## Dataset

The dataset `SenticNet2_Thai.txt` has the following columns:
- **id**: Unique identifier for each entry.
- **text**: The text content (in Thai) that will be used to predict sentiment.
- **Pleasantness**: A score indicating how pleasant the text is.
- **Attention**: A score indicating the level of attention the text demands.
- **Sensitivity**: A score indicating the emotional sensitivity of the text.
- **Aptitude**: A score indicating how apt or suitable the text is in conveying information.
- **Polarity**: The target variable (label), which indicates the sentiment polarity of the text. It can be one of the following:
  - **positive**
  - **negative**
  - **neutral**

## Objective

The goal of this project is to build and train a neural network model that predicts the sentiment polarity of a given text. The model will classify the text into one of the three sentiment categories: **positive**, **negative**, or **neutral**.