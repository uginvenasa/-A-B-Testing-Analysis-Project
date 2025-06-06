# Amazon Reviews Sentiment Analysis
This project performs sentiment analysis on real Amazon product reviews using TextBlob and Python.
# Files
- `amazon_reviews.csv`: Amazon review dataset (from Kaggle)
- `sentiment_analysis.ipynb`: Notebook to process and analyze sentiment
- `sentiment_output.csv`: Output with sentiment scores and labels
# Workflow
1. Load the Amazon review dataset
2. Use TextBlob to calculate the sentiment polarity
3. Label reviews as:
   - Positive (score > 0.1)
   - Neutral (between -0.1 and 0.1)
   - Negative (score < -0.1)
#Example Output
| Review | Sentiment |
|--------|-----------|
| Love this phone, battery lasts long! | Positive |
| It's okay, nothing special. | Neutral |
| Terrible build quality. | Negative |

