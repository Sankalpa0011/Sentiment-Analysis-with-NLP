# Sentiment Analysis with NLP

This project performs sentiment analysis on airline tweets to classify them as positive, negative, or neutral. It was developed in a Google Colab notebook.

## Steps

1. Load the Tweets dataset 
2. Preprocess the text
   - Convert to lower case
   - Remove URLs  
   - Remove stop words
   - Stem words
3. Extract features using TF-IDF vectorizer
4. Split data into training and test sets 
5. Train models
   - Multinomial Naive Bayes
   - Random Forest
6. Evaluate models on test set

## Models 

The following models are trained and evaluated:

- **Multinomial Naive Bayes**: Accuracy = 72.2%
- **Random Forest**: Accuracy = 74.9%

Random Forest performs better for this dataset.

## Usage

To run the code:

1. Open the [Sentiment_Analysis.ipynb](https://colab.research.google.com/github/user/repo/blob/master/Sentiment_Analysis.ipynb) notebook in Google Colab
2. Run the cells

Feel free to tune the models and try other approaches!

## References

The Tweets dataset is loaded from /content/Tweets.csv in the Colab runtime.
