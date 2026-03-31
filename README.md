# 🎬 SVD Recommender System (Linear Algebra for ML)

## 📌 Overview

This project implements a **Movie Recommendation System** using **Singular Value Decomposition (SVD)** — a fundamental linear algebra technique widely used in machine learning for dimensionality reduction and matrix factorization.

The system learns latent user and item features from a sparse rating matrix and predicts missing values to generate personalized recommendations.

---

## 🧠 Core Concepts (Linear Algebra Focus)

* Matrix Factorization: **A = UΣVᵀ**
* Singular Value Decomposition (SVD)
* Dimensionality Reduction
* Mean Centering
* Matrix Reconstruction

---

## ⚙️ Approach

1. Construct user-item rating matrix from dataset
2. Normalize data using mean-centering
3. Apply SVD to decompose matrix
4. Reduce dimensions using top-k singular values
5. Reconstruct matrix to predict missing ratings
6. Recommend top-N unseen movies

---

## 📊 Dataset

* MovieLens 100K dataset
* 100,000 ratings from 943 users on 1682 movies
* Sparse real-world user-item interaction data

---

## 📈 Evaluation

* Metric: **RMSE (Root Mean Squared Error)**
* Measures difference between actual and predicted ratings

---

## 🚀 Features

* Predicts missing ratings using matrix reconstruction
* Generates personalized movie recommendations
* Displays movie names (not just IDs)
* Visualizes:

  * Rating matrix (before vs after)
  * Singular values (feature importance)

---

## 🖥️ Sample Output

```
Top Recommendations for User 0:

Star Wars (1977) → ⭐ 4.85  
Toy Story (1995) → ⭐ 4.72  
...
```

---

## ▶️ How to Run

1. Download MovieLens dataset

2. Place files in `data/` folder:

   * `u.data`
   * `u.item`

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Run notebook:

```
jupyter notebook
```

---

## 📦 Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn

---

## 🧾 Resume Highlight

Built a recommendation system using **SVD-based matrix factorization** on real-world data, applying linear algebra concepts for dimensionality reduction and prediction of user preferences.

---

## 🔥 Key Highlight

This project demonstrates **practical application of linear algebra in machine learning**, specifically how SVD is used in real-world recommendation systems like Netflix.

---

## 🚀 Future Improvements

* Use larger datasets (MovieLens 1M / 20M)
* Add cosine similarity for better recommendations
* Build interactive UI (Streamlit)
* Deploy as a web application

---

## 👨‍💻 Author

**Taksh Samirkumar Patel**

* 🎓 Computer Science Engineering Student
* 💡 Interested in AI, ML, Data Science
* 🔗 LinkedIn: https://www.linkedin.com/in/taksh-patel-6a6b97325
* 💻 LeetCode: https://leetcode.com/u/5EWSbJZA6M/

---

⭐ If you found this useful, consider starring the repo!

