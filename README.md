# Spam - Ham Detection using Natural Language Processing (NLP)

## Introduction
This project aims to classify SMS messages as spam or ham (non-spam) using Natural Language Processing (NLP) techniques. The project utilizes machine learning algorithms and NLP libraries to preprocess text data, extract relevant features, and build predictive models for accurate spam detection.

## Dataset
The dataset used in this project is the SMSSpamCollection, which consists of labeled SMS messages categorized as spam or ham. The dataset is provided in the file 'SMSSpamCollection.tsv'.

## Preprocessing
The preprocessing steps include:
- Removing punctuation marks
- Tokenization
- Removing stopwords
- Stemming
- Lemmatization

## Feature Engineering
Feature engineering involves:
- Creating features for text message length and punctuation percentage
- Creating a document-term matrix using Count Vectorization and TF-IDF Vectorization

## Machine Learning Models
Two approaches are used for building machine learning classifiers:
1. **KFold Cross Validation**: The dataset is split into K folds, and a Random Forest Classifier is trained and evaluated on each fold.
2. **Train-Test Split**: The dataset is split into training and testing sets, and a Random Forest Classifier is trained on the training set and evaluated on the testing set.

## Usage
1. Clone the repository: `https://github.com/Naveen2701/Spam-Ham-Detection-using-NLP.git`

2. Install the required dependencies: `pip install -r requirements.txt`

3. Run the Jupyter notebook provided in the repository to execute the preprocessing steps, feature engineering, and machine learning models.

## Authors
This project was developed by [Naveen KM](https://github.com/Naveen2701) and [Guruakash P](https://github.com/guruakash-7788).

## License
This project is licensed under the Apache 2.0 License. See the LICENSE file for details.