# SMS_spam_prediction_ML

# README

## Introduction
This repository contains code for analyzing and classifying SMS messages as spam or ham (non-spam). The code is divided into different sections to perform data cleaning, exploratory data analysis (EDA), data preprocessing, and model building.

## Contents
1. **Data Cleaning**: In this section, the data cleaning process is described. It involves loading the dataset, dropping unnecessary columns, and handling missing values.

2. **EDA (Exploratory Data Analysis)**: This section explores the dataset to gain insights into its structure and characteristics. It includes analyzing the distribution of spam vs. ham messages, examining the distribution of message lengths, and visualizing word clouds for both spam and ham messages.

3. **Data Preprocessing**: Here, the text data is preprocessed before feeding it into the model. Steps include lowercasing, tokenization, stemming, and vectorization using TF-IDF (Term Frequency-Inverse Document Frequency) representation.

4. **Model Building**: The code for building and evaluating different Naive Bayes classifiers (Gaussian, Multinomial, Bernoulli) is provided in this section. The models are trained on the preprocessed text data and evaluated using accuracy, precision, and confusion matrix.

## Usage
1. **Data**: The dataset used for this analysis is stored in a CSV file named "spam.csv".
2. **Requirements**: Ensure to have the necessary Python libraries installed, including `pandas`, `numpy`, `scikit-learn`, `nltk`, `wordcloud`, and `seaborn`.
3. **Execution**: Run the code cells in a Python environment, such as Jupyter Notebook, sequentially to execute each section and PyCharm to run app.py using streamlit.
4. **Model Deployment**: After building the model, it is saved using pickle for deployment in other applications.

## Example Messages
- **Spam Messages**:
  - "Congratulations! You've won $1 million in the international lottery. Claim now!"
  - "You have been selected to win a free iPhone! Click here to claim your prize."
- **Ham Messages**:
  - "Hey, sorry I missed dinner. Hope you are not mad at me."
  - "Reminder: Meeting tomorrow at 2 PM in the conference room."

## Performance Evaluation
- The model's performance is evaluated using metrics such as accuracy, precision, and ROC curve (Receiver Operating Characteristic).
- The confusion matrix provides insights into the model's performance in classifying spam and ham messages.
