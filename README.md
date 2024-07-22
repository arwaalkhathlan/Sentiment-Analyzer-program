
# Sentiment Analysis Project

This project performs sentiment analysis on customer reviews using Python, Pandas, TextBlob, and NLTK. The sentiment analysis categorizes the reviews as positive, negative, or neutral based on the sentiment polarity.

## Installation

To get started, you need to install the required Python libraries. Open your terminal or command prompt and run:

```bash
pip install pandas textblob nltk
```

After installing the libraries, download the necessary NLTK corpora by running the following Python code:

```python
import nltk
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('wordnet')
nltk.download('brown')
```

## Usage

1. Place your `data.csv` file in the same directory as your script or Jupyter notebook. The CSV file should contain the following columns:
    - `id`: Unique identifier for each review
    - `name`: Name of the product or reviewer
    - `reviews.title`: Title of the review
    - `reviews.text`: Text of the review

2. Run the provided script or Jupyter notebook to perform sentiment analysis on the reviews. The notebook will categorize each review as positive, negative, or neutral based on the sentiment polarity and display the results.

## Project Structure

- `data.csv`: The CSV file containing the reviews.
- `sentiment_analysis.ipynb`: The Jupyter notebook containing the code for sentiment analysis.
