# IMDB Sentiment Analysis – Machine Learning

## Project Description
This project performs **sentiment analysis of movie reviews** using classical machine learning algorithms. The data comes from the public **IMDB Dataset** and contains reviews labeled as *positive* or *negative*.

The main objectives of the project are:
- exploratory analysis of textual data,
- text preprocessing using NLP techniques,
- training and comparing multiple classification models,
- evaluating model performance using standard metrics.

---

## Technologies Used
- **Python 3**
- **Pandas**, **NumPy** – data analysis and preprocessing
- **NLTK** – tokenization and stopword removal
- **Scikit-learn** – machine learning models and evaluation metrics
- **Matplotlib** – data visualization

---

## Dataset
- File: `IMDB Dataset.csv`
- Columns:
  - `review` – review text
  - `sentiment` – label (`positive` / `negative`)

Additionally:
- positive and negative reviews are saved into separate CSV files.

---

## Text Preprocessing (NLP)
1. Lowercasing the text  
2. Tokenization  
3. Stopword removal  
4. Removing special characters  
5. Removing duplicate words  
6. Text vectorization using **TF-IDF**
   - unigrams and bigrams
   - up to 5000 features

---

## Machine Learning Models
The following models were implemented and compared:

- **K-Nearest Neighbors (KNN)**
- **Random Forest**
- **Logistic Regression**

The dataset was split into:
- **80% training set**
- **20% test set**

---

## Evaluation Metrics
Each model is evaluated using:
- Accuracy
- Precision (weighted)
- Recall (weighted)
- F1-score (weighted)

The results are:
- presented in a comparison table,
- visualized using bar charts,
- used to select the best-performing model.

---

## New Review Prediction
The project supports sentiment prediction for new, unseen movie reviews using trained models.

---

## Results Visualization
- Metric comparison across models
- Combined plots for all evaluation metrics
- Automatic value annotations on charts

---
