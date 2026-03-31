# 🎬 SVD Recommender System (Linear Algebra for ML)

## 📌 Overview

This project implements a **Movie Recommendation System** using **Singular Value Decomposition (SVD)** — a core linear algebra technique widely used in machine learning for dimensionality reduction and matrix factorization.

The system analyzes a sparse user-item rating matrix, learns latent features, and predicts missing values to generate personalized movie recommendations.

---

## 🧠 Core Concepts (Linear Algebra Focus)

* Matrix Factorization: **A = UΣVᵀ**
* Singular Value Decomposition (SVD)
* Dimensionality Reduction
* Mean Centering
* Matrix Reconstruction

---

## 📐 Mathematical Insight

SVD decomposes the user-item matrix into three components:

A = UΣVᵀ

* **U** → User latent feature matrix
* **Σ** → Diagonal matrix of singular values (importance of features)
* **Vᵀ** → Item latent feature matrix

This decomposition captures hidden relationships between users and movies, enabling prediction of missing ratings.

---

## ⚙️ Approach

1. Construct user-item matrix from dataset
2. Apply mean-centering to normalize ratings
3. Perform SVD decomposition
4. Reduce dimensions using top-k singular values
5. Reconstruct matrix to estimate missing ratings
6. Recommend top-N unseen movies

---

## 🤔 Why SVD?

* Handles **sparse data** efficiently
* Captures **latent relationships** between users and items
* Reduces dimensionality while preserving important patterns
* Widely used in real-world recommendation systems

---

## 📊 Dataset

* MovieLens 100K dataset
* 100,000 ratings from 943 users on 1682 movies
* Real-world sparse dataset

---

## 📈 Evaluation

* Metric: **RMSE (Root Mean Squared Error)**
* Measures prediction accuracy between actual and predicted ratings

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

```text
Top Recommendations for User 0:

Star Wars (1977) → ⭐ 4.85  
Toy Story (1995) → ⭐ 4.72  
...
```

---

## 📸 Screenshot

<img width="1204" height="1398" alt="image" src="https://github.com/user-attachments/assets/6122ef95-1807-4c62-bbc0-736e5da77dc9" />


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

Built a Movie Recommendation System using **SVD-based matrix factorization** on real-world data, applying linear algebra concepts for dimensionality reduction and prediction of user preferences.

---

## 🔥 Key Highlight

This project demonstrates **practical application of linear algebra in machine learning**, specifically how SVD is used in real-world recommendation systems like Netflix.

---

## 🚀 Future Improvements

* Use larger datasets (MovieLens 1M / 20M)
* Add cosine similarity
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
