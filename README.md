🛍️ Amazon Review Sentiment Analysis
A Machine Learning and Natural Language Processing (NLP) project that analyzes Amazon customer reviews using TF-IDF, Logistic Regression, Naive Bayes, and VADER Sentiment Analysis. The project includes data cleaning, exploratory data analysis (EDA), sentiment classification, model comparison, word cloud visualization, and performance evaluation to generate actionable customer insights.

📌 Project Overview
This project analyzes Amazon product reviews from multiple product categories to identify customer sentiment as Positive, Neutral, or Negative.

The project also compares two machine learning models and a lexicon-based sentiment analyzer (VADER) to evaluate sentiment prediction performance.

🚀 Features
Data Cleaning & Text Preprocessing
Exploratory Data Analysis (EDA)
TF-IDF Feature Extraction
Logistic Regression Model
Naive Bayes Model
Model Performance Comparison
Confusion Matrix
Positive & Negative Word Clouds
VADER Sentiment Analysis
Category-wise Sentiment Analysis
🛠️ Technologies Used
Python
Google Colab
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
WordCloud
VADER Sentiment
📊 Exploratory Data Analysis
The project includes visualizations such as:

Review Volume by Category
Sentiment Distribution
Star Rating Distribution
Sentiment Mix by Category
Review Length vs Star Rating
Confusion Matrix
Positive Review Word Cloud
Negative Review Word Cloud
🤖 Machine Learning Models
Logistic Regression
Naive Bayes
📈 Model Performance
Logistic Regression
Accuracy: 80.0%
Precision: 86.4%
Recall: 80.0%
F1-score: 82.5%
Naive Bayes
Accuracy: 87.2%
Precision: 84.8%
Recall: 87.2%
F1-score: 84.1%
📖 VADER Sentiment Analysis
The project compares VADER sentiment predictions with the dataset labels.

VADER Agreement: 82.6%
📂 Project Structure
Amazon-Review-Sentiment-Analysis/
│
├── Amazon_Review_Sentiment_Analysis.ipynb
├── Amazon_reviews_dataset.csv
├── requirements.txt
├── README.md
├── category_volume.png
├── sentiment_distribution.png
├── rating_distribution.png
├── sentiment_by_category.png
├── review_length_vs_rating.png
├── confusion_matrix.png
├── wordcloud_positive.png
├── wordcloud_negative.png
├── eda_summary.png
├── model_comparison.png
└── vader_comparison.png
▶️ How to Run
Clone this repository.
Install the required libraries:
pip install -r requirements.txt
Open the notebook:
Amazon_Review_Sentiment_Analysis.ipynb
Update the dataset path if required.

Run all cells.

📌 Key Insights
Positive reviews dominate the dataset.
Naive Bayes achieved the highest overall accuracy (87.2%).
Mobile Accessories had the highest percentage of negative reviews.
Books received the highest percentage of positive reviews.
Lower-rated reviews tend to be longer than higher-rated reviews.
VADER achieved an agreement score of 82.6%.
