# sentiment-analysis-task5
 Task 5: Text Classification project using IMDb dataset. Implements preprocessing, TF-IDF, Naive Bayes, Logistic Regression, and Random Forest with evaluation and predictions.
# Task 5 – Sentiment Analysis (IMDb Dataset)

## 📖 Description
This project is part of the **Kaiburr Hiring Assessment – Task 5**.  
It performs **binary text classification** on the **IMDb Movie Reviews dataset**, predicting whether a review is **Positive** or **Negative**.  

The project demonstrates:
- Text preprocessing  
- TF-IDF feature extraction  
- Model training with **Naive Bayes, Logistic Regression, and Random Forest**  
- Performance evaluation (accuracy, classification report, confusion matrix)  
- Predictions on new sample reviews  

---

## ⚙️ Steps Followed
1. Load dataset (`IMDB Dataset.csv` from [Kaggle IMDb dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews))  
2. Preprocess text (remove stopwords, lowercase)  
3. Convert text into **TF-IDF vectors**  
4. Train models:
   - Multinomial Naive Bayes  
   - Logistic Regression  
   - Random Forest  
5. Compare model accuracy  
6. Generate **confusion matrix** for best model  
7. Run predictions on custom sample reviews  

---

## 📦 Requirements
- Python 3.8+
- pandas
- scikit-learn
- matplotlib
- seaborn

Install dependencies:
```bash
pip install -r requirements.txt
