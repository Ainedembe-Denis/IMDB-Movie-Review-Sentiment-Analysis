# IMDB Movie Review Sentiment Analysis

This project implements comprehensive sentiment analysis on IMDB movie reviews using traditional machine learning techniques, including EDA, feature engineering, and statistical inference.

- About Dataset: 
The IMDb dataset is a large collection of movie-related data sourced from the Internet Movie Database (IMDb). It includes information about thousands of movies, television shows, and other media, such as cast details, genres, directors, user ratings, and reviews. 

## Dataset
- **Source**: the dataset should be downloaded from https://www.kaggle.com/datasets/mahmoudshaheen1134/imdp-data extract the downloaded zip file and rename it as `IMDB-Dataset.csv` and put it under location as below:
- **Location**: `dataset/IMDB-Dataset.csv`
- **Description**: Contains movie reviews with binary sentiment labels (positive/negative)
- **Dataset Brief**: See `dataset/IMDB-data.docx` for detailed dataset information

## Authors

- **Students**: Ainedembe Denis, Musinguzi Benson
- **Lecturer**: Harriet Sibitenda (PhD)

## Course Assignment Context
This project is part of the Intelligent Systems course assignment, covering:
- **Part A**: Data Loading & Preprocessing 
- **Part B**: First EDA 
- **Part C**: Feature Engineering 
- **Part D**: Second EDA & Statistical Inference
- **Part E**: Machine Learning 
- **Part F**: Presentation & Reflection

### Key Features
- **Data Preprocessing**: Text cleaning, stopword removal, TF-IDF vectorization
- **Exploratory Data Analysis**: Word frequency analysis, word clouds, review length analysis
- **Feature Engineering**: Sentiment lexicon scores, n-grams, readability metrics
- **Statistical Analysis**: Hypothesis testing, confidence intervals
- **Machine Learning Models**: Naive Bayes, Logistic Regression, Linear SVM, Gradient Boosting
- **Model Evaluation**: 5-fold cross-validation with comprehensive metrics (Accuracy, Precision, Recall, F1, ROC-AUC)

## Project Structure
The project structure will be as below:

```
.
├── dataset/
│   ├── IMDB-Dataset.csv
│   └── IMDB-data.docx
├── notebooks/
│   └── sentiment_analysis.ipynb
├── requirements.txt
└── README.md
```
## Setup

### Prerequisites
- Python 3.8+ 
- pip package manager

### Installation

1. Install required packages:
```bash
pip install -r requirements.txt
```

Or install individually:
```bash
pip install notebook ipykernel
pip install pandas numpy matplotlib seaborn scikit-learn scipy nltk wordcloud
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook
```

3. Navigate to `notebooks/sentiment_analysis.ipynb` in the browser

4. Clearing outputs via commandline
```bash
jupyter nbconvert --clear-output --inplace notebooks/sentiment_analysis.ipynb
```