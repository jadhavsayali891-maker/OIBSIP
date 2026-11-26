# Email Spam Detection with Machine Learning

## About the Project

This project is part of my **Oasis Infobyte Data Science Internship (OIBSIP)**.

The main aim of this project is to identify whether an SMS message is spam or genuine (ham) using machine learning. I used the SMS Spam Collection dataset, which contains messages labelled as spam or ham.

## Objective

To build a machine learning model that can classify SMS messages into two categories:

- **Spam:** Unwanted or promotional messages.
- **Ham:** Genuine messages.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Regular Expressions (re)
- WordCloud

## Dataset

I used the SMS Spam Collection dataset.

The dataset contains **5,572 messages**:

- Ham messages: 4,825
- Spam messages: 747

## Project Steps

1. Loaded the SMS Spam Collection dataset.
2. Checked the number and percentage of spam and ham messages.
3. Cleaned the text by converting it to lowercase and removing punctuation, numbers and selected common words.
4. Used TF-IDF to convert text messages into numerical features.
5. Divided the dataset into 80% training data and 20% testing data.
6. Trained two machine learning models:
   - Multinomial Naive Bayes
   - Logistic Regression
7. Evaluated both models using accuracy, precision, recall and F1-score.
8. Created confusion matrices and WordCloud visualisations.

## Model Performance

The following results were obtained on the test dataset:

| Model | Accuracy | Precision (Spam) | Recall (Spam) | F1-Score (Spam) |
|---|---:|---:|---:|---:|
| Multinomial Naive Bayes | 96% | 1.00 | 0.70 | 0.83 |
| Logistic Regression | 97% | 1.00 | 0.74 | 0.85 |

## Conclusion

In this project, I successfully developed a machine learning system to identify spam and genuine SMS messages.

Both models performed well, but Logistic Regression gave slightly better results with 97% accuracy and a spam F1-score of 0.85.

Through this project, I learned about text preprocessing, TF-IDF feature extraction, model training and evaluation. I also understood why recall is important when identifying spam messages.

## Internship

**Oasis Infobyte – Data Science Internship (OIBSIP)**

**Task 4: Email Spam Detection with Machine Learning**
