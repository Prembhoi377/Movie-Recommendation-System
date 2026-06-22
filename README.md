# 🎬 Movie Recommendation System

A **Content-Based Movie Recommendation System** built using **Python**, **Pandas**, and **Scikit-Learn**. This project recommends movies based on their content (overview, genres, and keywords) using **TF-IDF Vectorization** and **Cosine Similarity**.

---

## 📌 Project Overview

The system analyzes movie descriptions and metadata to identify similar movies. When a user enters a movie title, the application recommends the **Top 5 most similar movies** based on textual similarity.

---

## ✨ Features

* 🎥 Content-Based Movie Recommendation
* 📄 Text Preprocessing
* 🏷️ Genre & Keyword Extraction
* 🧠 TF-IDF Vectorization
* 📊 Cosine Similarity Calculation
* 🔍 Top 5 Similar Movie Recommendations
* ⚡ Fast and Simple Recommendation Engine

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* JupyterLab

---

## 📂 Dataset

**TMDB 5000 Movies Dataset**

The dataset contains movie information such as:

* Movie Title
* Overview
* Genres
* Keywords

---

## ⚙️ Workflow

1. Load the TMDB dataset
2. Select required features
3. Handle missing values
4. Preprocess text data
5. Combine overview, genres, and keywords
6. Apply TF-IDF Vectorization
7. Calculate Cosine Similarity
8. Recommend Top 5 similar movies

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Movie-Recommendation-System.git
```

Move to the project folder:

```bash
cd Movie-Recommendation-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Open the Jupyter Notebook:

```bash
jupyter lab
```

Run all notebook cells and execute:

```python
recommend("Avatar")
```

---

## 📁 Project Structure

```text
Movie-Recommendation-System/
│── Movie_Recommendation.ipynb
│── tmdb_5000_movies.csv
│── README.md
│── requirements.txt
└── .gitignore
```

---

## 📌 Future Improvements

* Streamlit Web Application
* Movie Posters using TMDB API
* Search Autocomplete
* IMDb Ratings Integration
* User-Friendly Interface

---

## 👨‍💻 Author

Developed as part of the **CodeAlpha Internship** to demonstrate the implementation of a Content-Based Movie Recommendation System using Machine Learning techniques.
