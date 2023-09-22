# Kannada-MNIST-Classification-Problem
## Problem Statement
The task is to build a machine learning model capable of correctly classifying grayscale images of handwritten digits (0 to 9) and this is an extension to the classic MNIST dataset where we deal with the Kannada Numerals. The goal is to achieve high accuracy in correctly identifying the digits using various classification algorithms and techniques. The dataset that is used can be referred from: https://www.kaggle.com/datasets/higgstachyon/kannada-mnist

## Approach
1. Data Collection and Preprocessing:
- Extracting the dataset from the provided npz file, containing 60,000 training and 10,000 test images, each with a size of 28x28 pixels.
- Normalizing the pixel values to a range of 0 to 1 and reshape the images for further processing.

2. Dimensionality Reduction with PCA:
- Performing PCA (Principal Component Analysis) to reduce the image dimensions from 28x28 to a compact 10-dimensional representation.
- Retaining the most important features while reducing computational complexity.

3. Model Selection and Training:
- Implementing five powerful classification models: Decision Trees, Random Forest, Naive Bayes, K-NN Classifier, and SVM.
- Train each model using the transformed training data in 10 dimensions.

4. Model Evaluation and Metrics:
- Evaluating the performance of each model using essential metrics like Precision, Recall, and F1-Score.
- Generating Confusion Matrix to analyze the accuracy of predictions for all classes.
- Visualizing the Receiver Operating Characteristic (RoC) curve to gauge model performance.

## Conclusion
By following the steps outlined in the Jupyter Notebook, you will be able to preprocess the Kannada MNIST dataset, apply various classification models, and evaluate their performance using different metrics. The results obtained will help understand each model's effectiveness for the given classification problem.


# Toxic-Tweets-Dataset-NLP-Problem
This dataset has a collection of Tweets. Its labelled as Toxic - 1, Non toxic - 0. Apply the NLP methods to predict the toxicity of the tweets.

## Libraries Used:
- pandas: Used for data manipulation and analysis.
- scikit-learn: Used for implementing machine learning models, preprocessing, and metrics evaluation.
- matplotlib: Used for data visualization.
- seaborn: Used for enhanced data visualization.
- nltk: Used for natural language processing tasks like tokenization, lemmatization, and stop words removal.

## Data:
- The dataset was downloaded from the following Kaggle Com- pitation https://www.kaggle.com/datasets/ashwiniyer176/toxic-tweets-dataset.

The script assumes that the tweet data is available in a pandas DataFrame named df with two columns:
- 'tweet': Contains the raw tweet text.
- 'Toxicity': Contains the binary label (0 for non-toxic and 1 for toxic) indicating the toxicity of each tweet.

## Conclusion
By following the steps outlined in the Jupyter Notebook, you will be able to preprocess the Toxic Tweets dataset, apply NLP methods for feature extraction, and train various classification models to predict the toxicity of tweets. The evaluation metrics obtained will help in understanding the performance of each model and selecting the most suitable one for the given classification problem.
