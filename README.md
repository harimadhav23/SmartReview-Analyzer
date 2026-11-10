# SmartReview AI – Customer Sentiment Analysis using NLP and Machine Learning

## 📌 Project Overview

**SmartReview AI** is a Machine Learning and Natural Language Processing (NLP) project that analyzes customer reviews and automatically classifies them into three sentiment categories: Negative, Neutral, and Positive.

The project uses text preprocessing, feature extraction techniques, and multiple Machine Learning classification algorithms to understand customer opinions from textual data.

## 🎯 Project Objectives

- Analyze customer reviews using NLP techniques.
- Clean and preprocess unstructured text data.
- Convert text into numerical features using Bag of Words and TF-IDF.
- Train and compare multiple Machine Learning models.
- Predict the sentiment of new customer reviews.
- Identify the best-performing model using evaluation metrics.

## 📂 Dataset Information

The project uses `sentiment_data.csv`.

The dataset contains customer comments and their corresponding sentiment labels.

| Column      | Description                    |
| ----------- | ------------------------------ |
| `Comment`   | Customer review or feedback    |
| `Sentiment` | Sentiment classification label |

### Sentiment Labels

| Label | Sentiment |
| ----- | --------- |
| 0     | Negative  |
| 1     | Neutral   |
| 2     | Positive  |

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Text Processing:** Regular Expressions (re)
- **NLP Techniques:** CountVectorizer, TF-IDF
- **Machine Learning:** Scikit-learn
- **Model Persistence:** Joblib
- **Application Interface:** Streamlit (planned for deployment)

## ⚙️ Project Workflow

The project follows an end-to-end Machine Learning workflow.

### 1. Data Loading and Exploration

- Loaded the dataset using Pandas.
- Examined dataset dimensions, columns, and data types.
- Analyzed missing values and duplicate records.
- Studied the distribution of sentiment classes.

### 2. Data Preprocessing

- Removed unnecessary columns.
- Handled missing values.
- Removed duplicate records where applicable.
- Converted text into lowercase.
- Removed URLs and unwanted characters.
- Cleaned extra whitespace.

### 3. Train-Test Split

- Separated input features (`Comment`) and target labels (`Sentiment`).
- Split the dataset into training and testing sets.
- Used stratified sampling to preserve class distribution.

### 4. Feature Extraction

Implemented two text vectorization techniques:

**Bag of Words (CountVectorizer)**

- Converts text into numerical word-count features.
- Represents documents using word frequencies.

**TF-IDF (Term Frequency–Inverse Document Frequency)**

- Converts text into numerical feature vectors.
- Assigns importance to words based on their frequency across documents.
- Includes unigram and bigram features.

### 5. Machine Learning Models

Implemented and compared the following classification algorithms:

1. Multinomial Naive Bayes
2. Logistic Regression
3. Linear Support Vector Machine (SVM)

### 6. Model Evaluation

Evaluated model performance using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Compared the models to identify the most suitable classifier for sentiment prediction.

### 7. Sentiment Prediction

Developed a reusable prediction function that accepts a new customer review, applies text preprocessing and TF-IDF transformation, and predicts one of the three sentiment categories.



## 🔮 Future Enhancements

- Develop an interactive Streamlit web application.
- Save and load the best-performing trained model.
- Add real-time sentiment prediction for customer reviews.
- Display sentiment distribution and model evaluation visualizations.
- Explore advanced NLP techniques and transformer-based models.
- Deploy the application for public access.

## 💡 Key Learnings

- Practical implementation of NLP preprocessing techniques.
- Understanding Bag of Words and TF-IDF feature extraction.
- Training multiclass Machine Learning classification models.
- Comparing classification algorithms using evaluation metrics.
- Building reusable sentiment prediction functions.
- Understanding an end-to-end Machine Learning project workflow.

## 👨‍💻 Author

**Hari Madhav**

---

⭐ If you find this project useful, feel free to star the repository!
