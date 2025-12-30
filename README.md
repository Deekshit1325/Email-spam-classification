# Email-spam-classification
Email Spam Detection using Machine Learning with TF-IDF, Naive Bayes, and Logistic Regression

##  Project Overview
This project focuses on building a machine learning model to automatically classify emails as **Spam** or **Ham (Not Spam)**.  
The system uses text vectorization techniques and supervised learning algorithms to achieve high classification accuracy.

## Problem Statement
Email spam is a major issue in digital communication. The goal of this project is to develop a reliable spam detection system that can identify unwanted emails based on their content.

## Dataset Information
- **Dataset Name:** Email Spam Dataset
- **Source:** Public Dataset (Kaggle)
- **Features:**
  - `text` – Email content
  - `spam` – Target label (1 = Spam, 0 = Ham)

## Technologies & Tools Used
- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## Machine Learning Techniques Used

### Text Vectorization
- **TF-IDF (Term Frequency–Inverse Document Frequency)**

### Algorithms
- **Naive Bayes (MultinomialNB)**
- **Logistic Regression**

## Why These Algorithms?
- **Naive Bayes** is fast and effective for text classification tasks.
- **Logistic Regression** performs well on high-dimensional TF-IDF features and provides better decision boundaries.
- Logistic Regression achieved better performance compared to Naive Bayes.

## 📈 Model Evaluation Metrics
- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-Score

## Results Summary
| Model | Accuracy |
| Naive Bayes | 89% |
| Logistic Regression | 97% |

Logistic Regression showed higher accuracy and better precision-recall balance.

## Visualizations Included
- Model Accuracy Comparison Chart
- Confusion Matrix
- Precision, Recall & F1-Score Report
- Important Words Influencing Spam and Ham Classification

## Conclusion
The Email Spam Detection system successfully classifies emails using machine learning techniques. Logistic Regression outperformed Naive Bayes with higher accuracy and better evaluation metrics. This project demonstrates effective text preprocessing, model comparison, and result interpretation.


