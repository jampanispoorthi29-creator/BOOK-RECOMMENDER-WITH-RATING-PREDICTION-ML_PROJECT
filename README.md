 # 📚 Book Recommender with Rating Prediction

## 📌 Project Overview

**Book Recommender with Rating Prediction** is a Machine Learning-based project that recommends books to users based on their preferences and historical rating patterns. Along with recommending books, the system predicts the rating that a user is likely to give to a particular book.

The project combines **Machine Learning-based rating prediction** with a **recommendation system** to provide personalized book suggestions.

---

## 👥 Team Members

| Roll Number    | Contribution                 |
| -------------- | ---------------------------- |
| **2520030514** | Rating Prediction & ML Model |
| **2520030587** | Book Recommendation System   |

---

## 🎯 Objectives

* Recommend books according to user preferences.
* Predict the rating a user may give to a selected book.
* Analyze historical book-rating data.
* Apply Machine Learning techniques to a real-world recommendation problem.
* Provide personalized book suggestions.

---

## ✨ Features

* 📖 Book recommendation
* ⭐ Rating prediction
* 👤 User preference analysis
* 📊 Exploratory Data Analysis
* 🔍 Similarity-based recommendations
* 📈 Model evaluation using MAE and RMSE
* 🖥️ Simple user interface

---

# 🧠 Project Modules

## Module 1 – Rating Prediction

**Member: 2520030514**

The Rating Prediction module predicts the rating that a user is likely to give to a particular book.

### Tasks

* Dataset loading
* Data cleaning
* Missing-value handling
* Exploratory Data Analysis
* Feature engineering
* Train-test split
* ML model training
* Rating prediction
* Model evaluation

### Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

---

## Module 2 – Book Recommendation

**Member: 2520030587**

The Book Recommendation module recommends books based on user preferences and similarities between books.

### Tasks

* Book data preprocessing
* Feature selection
* Feature vectorization
* Similarity calculation
* Cosine Similarity
* Recommendation function
* Top 5/10 book recommendations

---

# 📓 Google Colab Work

The Machine Learning development and experimentation are performed using **Google Colab**.

### 👤 Colab – Member 1

**Roll Number: 2520030514**

**Work:** Rating Prediction

```text
Dataset
   ↓
Data Preprocessing
   ↓
EDA
   ↓
Feature Engineering
   ↓
Train-Test Split
   ↓
ML Model
   ↓
Rating Prediction
   ↓
MAE & RMSE
```

** **

---

### 👤 Colab – Member 2

**Roll Number: 2520030587**

**Work:** Book Recommendation

```text
Book Dataset
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Feature Vectorization
   ↓
Cosine Similarity
   ↓
Recommendation Function
   ↓
Top Recommended Books
```

** **

---

# 🔄 Complete Project Workflow

```text
                 BOOK DATASET
                      ↓
              Data Preprocessing
                      ↓
             Exploratory Data Analysis
                      ↓
              Feature Engineering
                 ↙           ↘
                ↓             ↓
       Rating Prediction   Recommendation
                ↓             ↓
        Predicted Rating   Similar Books
                 ↘           ↙
                  ↓
            Final Results
```

---

# 🛠️ Technologies Used

| Technology   | Purpose              |
| ------------ | -------------------- |
| Python       | Programming          |
| Pandas       | Data preprocessing   |
| NumPy        | Numerical operations |
| Scikit-learn | Machine Learning     |
| Matplotlib   | Visualization        |
| Seaborn      | Visualization        |
| Google Colab | ML development       |
| Streamlit    | User interface       |

---

# 📊 Dataset

The dataset contains information related to books, users, and ratings.

Possible attributes include:

* Book ID
* Book Title
* Author
* Genre
* User ID
* Rating
* Number of Ratings

The dataset is cleaned and preprocessed before applying Machine Learning algorithms.

---

# 🧪 Model Evaluation

The rating prediction model is evaluated using:

### Mean Absolute Error (MAE)

Measures the average difference between actual and predicted ratings.

### Root Mean Squared Error (RMSE)

Measures prediction error while giving more importance to larger errors.

**Lower MAE and RMSE values indicate better prediction performance.**

---

# 💡 Example

### Input

```text
User: User_101
Selected Book: The Hobbit
```

### Output

```text
Predicted Rating: 4.5 ⭐

Recommended Books:

1. Harry Potter
2. Percy Jackson
3. The Lord of the Rings
4. The Chronicles of Narnia
5. Eragon
```

---

# 📁 Project Structure

```text
Book-Recommender-Rating-Prediction/
│
├── dataset/
│   └── books.csv
│
├── notebooks/
│   ├── rating_prediction.ipynb
│   └── book_recommendation.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── rating_prediction.py
│   └── recommendation.py
│
├── app.py
├── requirements.txt
└── README.md
```

---

# 🚀 Future Enhancements

* Natural Language Processing for book reviews
* Sentiment analysis
* Advanced collaborative filtering
* Deep Learning-based recommendations
* User login and personalized profiles
* Genre-based recommendations
* Book cover images
* Web deployment

---

# 🎓 Learning Outcomes

This project helps demonstrate:

* Data preprocessing
* Exploratory Data Analysis
* Feature engineering
* Regression
* Recommendation systems
* Cosine similarity
* Model evaluation
* Python Machine Learning
* Google Colab development

---

## 📌 Project Type

**Machine Learning | Recommendation System | Rating Prediction | Regression**

 
