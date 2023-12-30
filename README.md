# Sentiment Analysis of Cryptocurrency News Articles

Welcome to the "CryptoNewsSentiment" project, a deep dive into machine learning with a focus on sentiment analysis of cryptocurrency news articles.

## Dataset

This project utilizes the "SahandNZ/cryptonews-articles-with-price-momentum-labels" dataset from Hugging Face Datasets. Comprising articles from Cryptonews.com and Binance.com, it's designed to analyze the impact of news on cryptocurrency prices and market sentiment. The dataset includes a range of features which are explored and analyzed in our Jupyter notebook.

## Jupyter Notebook Progress

### Exploratory Data Analysis (EDA)
- Conducted an extensive EDA to gain deeper insights into our dataset.
- Key focus areas included sentiment distribution, article length analysis, common words and phrases, and temporal trends in the cryptocurrency news domain.

### Feature Engineering
- Applied comprehensive feature engineering to enhance the dataset's representation of sentiments in cryptocurrency news articles.
- Steps included text preprocessing, tokenization, TF-IDF vectorization, word embeddings, sentiment-specific keyword extraction, N-grams analysis, and polarity scores using tools like TextBlob or VADER.

### Upcoming Phases (In Progress)
- **DateTime Feature Engineering**: Extracting date components from the 'datetime' column.
- **URL Feature Engineering**: Parsing domain information from the 'url' column.
- **Re-splitting Dataset**: Post feature engineering, the combined dataset will be re-split into separate training and validation sets.
- **Feature Scaling and Transformation**: Necessary for models sensitive to data scale.
- Future steps will involve model selection, implementation, evaluation, and hyperparameter tuning.

## Conclusion
We are currently in the midst of the project, with substantial progress made in data analysis and feature engineering. The upcoming phases will focus on model building and evaluation. This project aims to provide valuable insights into the sentiment of cryptocurrency news articles and their impact on market dynamics. Stay tuned for further updates as we continue to advance in our analysis.

*Note: This README will be updated regularly to reflect the latest developments in the project.*


## Usage

Run the Jupyter Notebook `ML_CryptoNews.ipynb` to follow our EDA steps and view the visualizations, analyses, and feature engineering conducted.

## Model Development

(Currently in progress) - Details about model building, training, and validation will be elaborated here.

## Results and Interpretation

(To be added) - We will discuss our findings and interpretations from the sentiment analysis of the news articles.

## Contact

For questions or discussions about this project, feel free to reach out at [adr83440@gmail.com](mailto:adr83440@gmail.com).

## Acknowledgements

Gratitude to the dataset sources and the machine learning community for their invaluable contributions to the field of sentiment analysis.



