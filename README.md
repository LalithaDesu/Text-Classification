# Text-Classification
This project implements multi-class text classification on the Consumer Complaint Dataset provided by the U.S. Government (data.gov). The goal is to classify consumer complaints into one of the following categories:  0 → Credit reporting, repair, or other  1 → Debt collection  2 → Consumer Loan  3 → Mortgage
Steps Performed

1.Exploratory Data Analysis (EDA)

Analyzed complaint text length, word frequency, and class distribution.

Checked for missing and imbalanced data.

2.Text Pre-processing

Converted text to lowercase.

Removed punctuation, numbers, and URLs.

Removed stop words.

Cleaned and tokenized complaint narratives.

3.Feature Engineering

Used TF-IDF Vectorization to transform text into numerical features.

Limited vocabulary size to reduce dimensionality.

4.Model Selection

Trained multiple machine learning models:

Naive Bayes

Logistic Regression

Random Forest

Support Vector Machine (SVM)

5.Model Comparison

Compared models based on accuracy, precision, recall, and F1-score.

Selected the best-performing model for final deployment.

6.Model Evaluation

Generated confusion matrix and classification report.

Visualized performance metrics.

7.Prediction

Saved the trained model and TF-IDF vectorizer.

Demonstrated predictions on new complaint text samples.
