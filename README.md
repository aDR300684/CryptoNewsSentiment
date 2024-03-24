# Sentiment Analysis on Cryptocurrency News Articles and Price Momentum Prediction: A Machine Learning Workflow

Welcome to the GitHub repository for our project, where we've developed a comprehensive machine learning workflow culminating in the `ML_CryptoNews_Pipeline`. This pipeline is designed for detailed analysis of cryptocurrency news articles to predict price momentum by employing advanced Natural Language Processing (NLP) techniques and sentiment analysis with FinBERT.

## Project Structure

The project is organized into several Jupyter notebooks, each dedicated to specific stages of the machine learning workflow, including Exploratory Data Analysis (EDA), Feature Engineering, Feature Selection, Model Training and Evaluation, Addressing Overfitting and Pipeline Development.

## Dataset

Our analysis is based on the "cryptonews-articles-with-price-momentum-labels" dataset from Hugging Face Datasets, comprising articles from prominent cryptocurrency news websites. The dataset includes features like article text, publication date, and price momentum labels, enabling us to assess the impact of news sentiment on cryptocurrency market behavior.

## Workflow Overview

### Exploratory Data Analysis (EDA)

- Initial exploration to understand dataset characteristics.
- Price momentum distribution analysis and identification of key textual patterns.

### Feature Engineering

- Text preprocessing and transformation into structured formats using TF-IDF and Word2Vec.
- Sentiment scoring with FinBERT and aspect-based sentiment analysis to enrich feature set.
- Topic Modeling with Latent Dirichlet Allocation (LDA), identifying and mapping dominant topics and themes.
  
### Feature Selection

- Application of various feature selection techniques to refine the dataset, focusing on predictive accuracy for "price_momentums".
- Utilization of SelectKBest for identifying statistically significant features, and experimentation with feature inclusion and exclusion to optimize the predictive model.

### Model Exploration and Selection

- Evaluation of Random Forest, SVM, GBM, and DNN models.
- GBM model selected based on superior performance on the test set.

### Addressing Overfitting

- Implementation of regularization techniques and hyperparameter optimization to enhance model generalization.
- Utilization of dimensionality reduction techniques, like PCA, to identify the most informative features and minimize overfitting risks.
- Exploration of model adjustments, including alternative kernels and class weight adjustments, to improve model robustness.

### Pipeline Development

- Integration of preprocessing, feature engineering, sentiment analysis, and model prediction into a streamlined workflow.
- The pipeline processes new articles, providing sentiment analysis and price momentum predictions.

## Usage

To replicate our analysis or apply the pipeline to new data:
1. Run the Jupyter notebooks in sequence, starting with `ML_CryptoNews_EDA.ipynb` through to `ML_CryptoNews_Pipeline.ipynb`.
2. Ensure all dependencies are installed and data files are located in the specified directories.

## Results and Interpretation

The final model within our pipeline demonstrates the capability to predict price momentum from cryptocurrency news with an accuracy of approximately 61%. While showing promise, this accuracy level suggests caution in application for real-world financial decisions. Do not use it at the current state !

## Conclusion and Future Work

This project exemplifies a complete machine learning project workflow, from data preprocessing to the development of a predictive pipeline. Future directions include refining the models, exploring additional data sources, and incorporating more sophisticated NLP techniques to enhance predictive accuracy and insights.

## Contact

For inquiries or discussion about this project, feel free to reach out at [email](mailto:adr83440@gmail.com).

## Acknowledgements

Our thanks go to the dataset providers and the broader machine learning community for the resources and support that made this project possible.

