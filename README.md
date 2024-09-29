# Fake News Detection using Machine Learning

This project addresses the problem of detecting fake news by leveraging various machine learning algorithms. The solution utilizes two datasets—**"Fake"** and **"True"**—sourced from Kaggle.

## Dataset

You can download the dataset from the following link:  
[Fake and Real News Dataset - Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

The dataset contains two types of news articles:
- **Fake**: News that is misleading or incorrect.
- **True**: Authenticated news articles.

---

## Classifiers Used

In this project, five different classifiers are implemented to detect fake news:
1. **Naive Bayes**
2. **Random Forest**
3. **Decision Tree**
4. **Support Vector Machine (SVM)**
5. **Logistic Regression**

---

## Project Workflow

### 1. Collect Data
We use a large dataset of news articles, consisting of both fake and true articles. The data is essential for training machine learning models to differentiate between fake and real news.

### 2. Extract Features
Features are extracted from the text data using techniques like:
- **n-grams**
- **Part-of-speech tagging**

These features are crucial for feeding meaningful inputs into the machine learning model.

### 3. Model Selection
For the classification task, multiple algorithms are evaluated, including:
- **Naive Bayes**: A probabilistic classifier suitable for text-based problems.
- **Support Vector Machine (SVM)**: Finds the hyperplane that best separates the data.
- **Logistic Regression**: A linear model for binary classification.
- **Decision Tree**: A tree-structured algorithm for decision-making.
- **Random Forest**: An ensemble method that builds multiple decision trees and outputs the best prediction.

### 4. Model Training & Testing
Once the models are selected, they are trained using the dataset. Their performance is evaluated based on metrics like accuracy, precision, and recall.

### 5. Deployment
After successful testing, the model is deployed to detect fake news in real-time. It can be further integrated with a user interface for easy usage.

---

## How to Run the Project

1. **Clone the Repository**  
   ```bash
   git clone <repository-link>
   cd Fake-News-Detection-using-Machine-Learning

2. **Install Required Dependencies**
   ```bash
   pip install -r requirements.txt

3. **Run the Code**
   ```bash
   python fake_news_detection.py

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK

---

## Future Enhancements
1. Integration with real-time news APIs to detect and flag fake news instantly.
2. Improvement in model accuracy by exploring advanced techniques such as deep learning.

---

## Dataset Source
[Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)
