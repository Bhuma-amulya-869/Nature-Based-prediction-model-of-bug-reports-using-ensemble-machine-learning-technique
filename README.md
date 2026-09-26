# Nature-Based Prediction Model of Bug Reports Using Ensemble Machine Learning

## 📌 Project Overview

The **Nature-Based Prediction Model of Bug Reports Using Ensemble Machine Learning** is a machine learning-based system designed to automatically identify and classify the nature of software bug reports.

The system uses **Natural Language Processing (NLP)** techniques to process bug report descriptions and extracts meaningful features using **TF-IDF and Bigram** techniques. Multiple machine learning algorithms are used to improve prediction performance through an **ensemble learning approach**.

## 🎯 Objectives

- Automatically classify software bug reports.
- Identify the nature/category of bugs from their descriptions.
- Reduce manual bug report analysis.
- Improve prediction accuracy and reliability.
- Process large numbers of bug reports efficiently.
- Support developers and testers in software maintenance.

## 🛠️ Technologies Used

- **Python**
- **Django**
- **Natural Language Processing (NLP)**
- **NLTK**
- **Scikit-learn**
- **Pandas**
- **NumPy**
- **HTML**
- **CSS**
- **JavaScript**
- **SQLite**

## 🤖 Machine Learning Algorithms

The project uses multiple machine learning algorithms:

1. **Support Vector Machine (SVM)**
2. **Decision Tree**
3. **Naive Bayes**
4. **Random Forest**

The predictions from multiple models are combined using an **ensemble learning approach** to obtain more reliable classification results.

## 🧠 NLP Techniques

The bug report text is processed using the following techniques:

- Text Cleaning
- Tokenization
- Stop-word Removal
- Lemmatization
- TF-IDF Feature Extraction
- Bigram Feature Extraction
- Text Augmentation

## 📊 Bug Nature Categories

The system can classify bug reports into predefined categories such as:

- Program Anomaly
- GUI
- Network/Security
- Configuration
- Performance
- Test-Code

## ⚙️ System Workflow

```text
Bug Report
     ↓
Text Preprocessing
     ↓
Tokenization
     ↓
Stop-word Removal
     ↓
Lemmatization
     ↓
TF-IDF + Bigram Feature Extraction
     ↓
Text Augmentation
     ↓
Machine Learning Models
     ↓
SVM + Decision Tree + Naive Bayes + Random Forest
     ↓
Ensemble Learning
     ↓
Bug Nature Prediction
