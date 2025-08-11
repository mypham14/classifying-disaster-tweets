# Classifying Disaster-Related Tweets as Real or Fake

## Overview

In this project, we work as a data scientist for a news analytics company interested in monitoring and analyzing news on social media platforms to look for misinformation. Our task is to build a deep learning text classification model that predicts which Tweets are about real disasters and which aren’t. The dataset comes from Kaggle.

## Data Description

We'll be using the `train.csv` and `test.csv` datasets that contain five columns:
- `id`: a unique identifier for each tweet
- `keyword`: a particular keyword from the tweet (may be blank)
- `location`: the location the tweet was sent from (may be blank)
- `text`: the text of the tweet
- `target`: denotes whether a tweet is about a real disaster (1) or not (0). This is the target variable.

## Libraries Used

- TensorFlow and Keras for deep learning tools and libraries.
- Pandas and NLTK for data manipulation and text processing.

## Project Structure

1. **Data Collection:**
   - Import the dataset using Pandas and explore its structure.

2. **Data Exploration:**
   - Analyze the dataset to understand the distribution of the target variable and check for missing values.

3. **Text Preprocessing:**
   - Clean and preprocess the text data to prepare it for model training.

4. **Model Building:**
   - Build and evaluate various deep learning models, including a shallow neural network, a multi-layer deep text classification model, a multilayer bidirectional LSTM model, and a Transformer model.

5. **Evaluation:**
   - Evaluate the models using accuracy metrics and visualize the results.

## Usage

To run the project, execute the Jupyter Notebook provided. The notebook will load the dataset, process the data, train the models, and provide predictions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Kaggle for providing the dataset.
- TensorFlow and Keras for deep learning tools and libraries.
- Pandas and NLTK for data manipulation and text processing.
