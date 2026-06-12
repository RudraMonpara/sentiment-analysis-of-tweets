# Sentiment Analysis of Tweets

A Machine Learning and Natural Language Processing (NLP) project that classifies tweets into sentiment categories by analyzing textual content. The project applies text preprocessing, feature engineering, and supervised learning algorithms to automatically determine the sentiment expressed in Twitter posts.

##  Overview

Social media platforms generate massive amounts of textual data every day. Understanding public opinion from this data is valuable for businesses, researchers, and policymakers.

This project builds an end-to-end sentiment analysis pipeline that:

* Cleans and preprocesses raw tweet data
* Converts text into numerical features using TF-IDF
* Trains multiple machine learning models
* Evaluates model performance using standard classification metrics
* Predicts sentiment from unseen tweets

---

##  Dataset

The project uses a labeled Twitter dataset containing tweets categorized by sentiment.

### Data Preprocessing

The following NLP preprocessing techniques were applied:

* Lowercase conversion
* Removal of URLs, mentions, hashtags, and special characters
* Tokenization
* Stopword removal
* Lemmatization
* Text normalization

---

##  Tech Stack

### Languages & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Matplotlib
* Seaborn

### Machine Learning Models

* Logistic Regression
* Multinomial Naive Bayes
* Linear Support Vector Machine (SVM)

### Feature Engineering

* TF-IDF Vectorization

---

##  Project Workflow

1. Load and explore tweet dataset
2. Clean and preprocess text data
3. Convert text into TF-IDF vectors
4. Split data into training and testing sets
5. Train multiple classification models
6. Evaluate model performance
7. Compare results and select the best-performing model

---

##  Model Evaluation

Models were evaluated using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

### Results

| Model                   | Accuracy  |
| ----------------------- | --------- |
| Logistic Regression     | 77.2%     |
| Multinomial Naive Bayes | Evaluated |
| Linear SVM              | Evaluated |

The comparison demonstrates the effectiveness of traditional machine learning approaches for sentiment classification on social media text.

---

##  Project Structure

```bash
sentiment-analysis-of-tweets/
│
├── TweetUsingSKNB.ipynb      # Main notebook
├── dataset/                  # Dataset files
├── models/                   # Saved models (optional)
├── images/                   # Visualizations
└── README.md
```

---

##  Key Features

* End-to-end NLP pipeline
* Automated tweet sentiment prediction
* TF-IDF feature extraction
* Multiple model comparison
* Performance visualization
* Reproducible machine learning workflow

---

##  Sample Use Cases

* Brand sentiment monitoring
* Product review analysis
* Public opinion tracking
* Social media trend analysis
* Market research

---

##  Learning Outcomes

Through this project, I gained hands-on experience in:

* Natural Language Processing (NLP)
* Text preprocessing techniques
* Feature engineering with TF-IDF
* Supervised Machine Learning
* Model evaluation and comparison
* Data visualization and analysis

---

##  Author

**Rudresh Monpara**

* GitHub: https://github.com/RudraMonpara
* LinkedIn: https://www.linkedin.com/in/rudresh-monpara-a1a605319

If you found this project useful, feel free to ⭐ the repository.
