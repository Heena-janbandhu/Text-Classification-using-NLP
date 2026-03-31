
# NLP Preprocessing and Text Classification

## 📌 Objective

The objective of this project is to implement Natural Language Processing (NLP) preprocessing techniques and build a text classification model using machine learning algorithms.

---

## 🎯 Learning Outcomes

* Apply NLP preprocessing techniques:

  * Tokenization
  * Stopword Removal
  * Stemming
  * Lemmatization
* Implement text vectorization:

  * TF-IDF
  * CountVectorizer
* Build machine learning models for text classification
* Evaluate model performance using metrics

---

## 📂 Dataset

* AG News Dataset (CSV format)
* Contains news articles categorized into:

  * World
  * Sports
  * Business
  * Sci/Tech

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn

---

## 🔄 Workflow

### 1. Data Loading

* Upload and read dataset using Pandas

### 2. Data Preprocessing

* Convert text to lowercase
* Remove special characters
* Tokenization
* Stopword removal
* Stemming (PorterStemmer)
* Lemmatization (WordNetLemmatizer)

### 3. Text Vectorization

* TF-IDF Vectorizer
* CountVectorizer

### 4. Model Training

* Logistic Regression
* Naive Bayes
* Support Vector Machine (SVM)

### 5. Model Evaluation

* Accuracy Score
* Classification Report
* Confusion Matrix

### 6. Visualization

* Confusion Matrix Heatmap
* Model Accuracy Comparison Graph

### 7. Custom Prediction

* Predict category for new input text

---

## 📊 Results

* Achieved approximately **90–91% accuracy**
* Best performing model: **SVM**

---

## 🚀 How to Run

1. Clone the repository:

```
git clone https://github.com/Heena-janbandhu/NLP-Preprocessing-and-Text-Classification.git
```

2. Install dependencies:

```
pip install nltk scikit-learn pandas matplotlib seaborn
```

3. Run the notebook:

* Open in Jupyter Notebook / Google Colab
* Execute all cells

---

## 📁 Project Structure

```
├── NLP_Assignment.ipynb
├── train.csv.gz
├── README.md
```

---

## 📌 Conclusion

This project demonstrates how NLP preprocessing and vectorization techniques can significantly improve text classification performance. Among the models tested, SVM and Logistic Regression provided the highest accuracy.

---


