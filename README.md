# Spam_sms_detection



A machine learning-based SMS Spam Detection System built in Python using NLP, data visualization, and classification models to identify spam messages with high accuracy.

---

##  Task Objective

The goal of this project is to develop an intelligent spam detection system that:
- Accurately classifies SMS messages as **spam** or **ham** (not spam)
- Preprocesses and vectorizes text using NLP techniques
- Handles data imbalance using **SMOTE**
- Trains multiple ML models and evaluates performance
- Visualizes message characteristics and results
- Provides an **interactive user interface** using `ipywidgets`

---

##  Tech Stack & Libraries

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- WordCloud
- NLTK (for stopwords and stemming)
- Scikit-learn
- imbalanced-learn (SMOTE)
- ipywidgets (for UI in Jupyter)
- HTML (for custom UI styling)

---

##  Models Used

- Naive Bayes
- Logistic Regression
- Random Forest

Each model is evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

##  Features

-  Data loading, visualization, and preprocessing
-  Text cleaning, stemming, stopword removal
-  TF-IDF vectorization
-  SMOTE to handle class imbalance
-  ML model training and evaluation
-  Interactive prediction with confidence level
-  Intuitive UI for checking messages

---

##  Steps to Run the Project:

Upload the dataset and run the project. 

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/sms-spam-detector.git
cd sms-spam-detector
