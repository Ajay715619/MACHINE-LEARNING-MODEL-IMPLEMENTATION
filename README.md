# SMS Spam Classification

## Overview
This Python script implements a Naïve Bayes classifier to detect spam messages using the SMS Spam Collection dataset. It leverages natural language processing (NLP) techniques such as TF-IDF transformation for text feature extraction.

## Features
- Downloads and extracts the SMS Spam Collection dataset.
- Preprocesses and converts text data into numerical format.
- Splits the dataset into training and testing sets.
- Uses a pipeline with `CountVectorizer`, `TfidfTransformer`, and `MultinomialNB` for classification.
- Evaluates model performance using accuracy, classification report, and a confusion matrix.

## Requirements
Ensure you have the following dependencies installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Usage
1. Run the script using Python:

```bash
python spam_classifier.py
```

2. The script will download the dataset, preprocess it, train the model, and evaluate performance.
3. It will output accuracy, a classification report, and a confusion matrix visualization.

## Expected Output
- Accuracy score
- Detailed classification report with precision, recall, and F1-score
- Confusion matrix visualization

## Customization
- Modify the dataset URL to use a different dataset.
- Tune `train_test_split` parameters for different train/test ratios.
- Experiment with different classifiers such as `RandomForestClassifier`.

## License
This project is licensed under the MIT License.

