# Fake News Detection Using NLP and Machine Learning

## Author
Vishnu Varadhan Murali  
Rutgers University  
NetID: vm562

---

## Project Overview

This project uses Natural Language Processing (NLP) and machine learning techniques to classify news articles as fake or real based on textual content.

The project compares multiple supervised machine learning models and evaluates their performance using standard classification metrics.

---

## Models Used

- Naive Bayes
- Logistic Regression
- Random Forest

---

## Final Results

| Model | Accuracy |
|---|---|
| Naive Bayes | 93.68% |
| Logistic Regression | 98.80% |
| Random Forest | 99.68% |

Best Model: **Random Forest**

---

## Dataset

This project uses the Kaggle Fake and Real News Dataset:

https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

### Required Files
After downloading and extracting the dataset, place these files in the same folder as the notebook:

- `Fake.csv`
- `True.csv`

---

## Project Workflow

1. Load and combine datasets
2. Clean article text
3. Apply TF-IDF vectorization
4. Split data into training and testing sets
5. Train machine learning models
6. Compare model performance
7. Visualize results using charts and confusion matrices

---

## Technologies Used

- Python
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Vishnum11/FakeNewsDetectionNLP.git