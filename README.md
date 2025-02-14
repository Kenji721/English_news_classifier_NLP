# 📰 NLP-Based English News Classifier

## 📌 Overview
This project explores **Natural Language Processing (NLP)** techniques to classify **English news articles** into different categories using **shallow machine learning models**. The goal is to build an efficient and interpretable classifier that can categorize news articles based on their textual content.

---

## 🔍 What is NLP?
**Natural Language Processing (NLP)** is a branch of artificial intelligence that enables computers to understand, interpret, and generate human language. In this project, we apply **NLP techniques** to preprocess and classify news articles.

---

## 🏗️ Machine Learning Approach

### ✅ **Shallow Machine Learning Models**
We focus on **traditional machine learning** methods for **text classification**, avoiding deep learning techniques. These models are **interpretable, fast, and effective** for structured text data.

#### **Models Implemented:**
1. **Logistic Regression** – A linear model for classification.
2. **Random Forest** – An ensemble method using multiple decision trees.
3. **Support Vector Machine (SVM)** – A strong classifier for text-based problems.

---

## 📂 Dataset Description
- The dataset contains **English news articles** labeled into **different categories**.
- Each news article consists of:
  - **Title**
  - **Body text**
  - **Category (target label)**

The goal is to train a machine learning model that can accurately classify news articles into **predefined categories**.

---

## 🛠️ NLP Pipeline (Text Preprocessing)
Before feeding the text into machine learning models, we apply several **NLP preprocessing steps** to clean and transform the data:

1. **Tokenization** – Splitting text into individual words.
2. **Lowercasing** – Converting all text to lowercase.
3. **Removing Stopwords** – Filtering out common words like *the, and, is, a*.
4. **Stemming/Lemmatization** – Reducing words to their base form (*running → run*).
5. **TF-IDF Vectorization** – Converting text into numerical format for machine learning.

---

## 🤖 Model Training & Evaluation
### **Feature Engineering**
- We use **TF-IDF (Term Frequency-Inverse Document Frequency)** to represent text as numerical vectors.
- The dataset is split into **training (80%)** and **testing (20%)** sets.

### **Model Comparison**
| Model               | Accuracy |
|--------------------|----------|
| **Logistic Regression** | ✅ **Best Performance** |
| **Random Forest** | ⚡ **Good interpretability** |
| **SVM** | 🔥 **High precision for specific categories** |

#### **Evaluation Metrics**
- **Accuracy** – Measures overall model performance.
- **Precision & Recall** – Assesses how well the model classifies different news categories.
- **Confusion Matrix** – Helps visualize correct vs. incorrect predictions.

---

## 📌 Key Insights
- **Logistic Regression** outperformed other models in classification accuracy.
- **Random Forest** provided **interpretable results** but required more computational resources.
- **SVM** excelled in certain categories but was computationally expensive.

---

## 🚀 How to Run the Project

1. **Clone this repository:**
   ```sh
   git clone https://github.com/<your-username>/English-News-Classifier.git
   cd English-News-Classifier
