# Zomato_restaurant_sentiment_analysis
AI/ML project analyzing Zomato restaurant reviews and metadata to understand customer experiences, identify business insights, and classify reviews as Positive, Neutral, or Negative using NLP, TF-IDF, feature selection, and machine learning models.
# Zomato Restaurant Review Sentiment Analysis

An end-to-end AI/ML project that analyzes Zomato restaurant reviews and metadata to understand customer experience and classify reviews into Negative, Neutral, and Positive sentiment.

## Project Overview

This project uses Zomato restaurant review data along with restaurant metadata. The objective is to analyze customer feedback, identify useful business insights, and build a machine learning model for sentiment classification.

## Dataset

The project uses two datasets:

1. Restaurant Reviews Dataset
   - Restaurant
   - Reviewer
   - Review
   - Rating
   - Metadata
   - Time
   - Pictures

2. Restaurant Metadata Dataset
   - Restaurant Name
   - Cost
   - Collections
   - Cuisines
   - Timings
   - Zomato Link

The datasets are merged using the restaurant name.

## Project Workflow

Data Collection
↓
Data Cleaning
↓
Exploratory Data Analysis
↓
Feature Engineering
↓
NLP Preprocessing
↓
TF-IDF Vectorization
↓
Feature Selection
↓
Machine Learning
↓
Model Evaluation
↓
Prediction

## Exploratory Data Analysis

The project includes:

- Rating distribution
- Sentiment distribution
- Restaurant-wise ratings
- Cost analysis
- Review length analysis
- Cuisine analysis
- Collection analysis
- Correlation analysis
- Customer engagement analysis

## NLP Techniques

The review text is processed using:

- Lowercasing
- Contraction expansion
- Punctuation removal
- URL removal
- Stopword removal
- Tokenization
- Text normalization
- TF-IDF
- Unigrams and bigrams

## Machine Learning Models

Three classification algorithms were compared:

- Logistic Regression
- Linear SVC
- Multinomial Naive Bayes

Hyperparameters were optimized using GridSearchCV.

## Final Model

The tuned Linear SVC was selected as the final model based on its overall performance and macro F1-score.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- SciPy
- Joblib
- Jupyter Notebook

## Project Structure

```text
zomato-restaurant-sentiment-analysis/
│
├── notebooks/
├── data/
├── presentation/
├── models/
├── requirements.txt
└── README.md

## Author

**Ashitosh Wankhede**  
B.Tech - Artificial Intelligence and Data Science  
Vishwakarma Institute of Technology, Pune

- LinkedIn: https://www.linkedin.com/in/ashitoshwankhede
- GitHub: https://github.com/ashu170
