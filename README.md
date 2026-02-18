# 🎬 Movie Recommendation System

## 📌 Project Overview

This project is a **Content-Based Movie Recommendation System** developed as part of our internship project.
It recommends movies similar to a user’s favorite movie by analyzing movie metadata such as **genres, keywords, tagline, cast, and director**.

The system uses **Natural Language Processing (NLP)** techniques and **Cosine Similarity** to find movies with similar features.

---

## 🚀 Features

* Movie recommendations based on user input
* Uses multiple metadata fields for better accuracy
* Handles spelling mistakes using closest match detection
* Suggests top similar movies ranked by similarity score
* Simple and easy-to-understand implementation

---

## 🛠️ Technologies Used

* **Python**
* **NumPy**
* **Pandas**
* **Scikit-learn**
* **TF-IDF Vectorizer**
* **Cosine Similarity**
* **Difflib** (for closest movie name matching)
* **Jupyter Notebook**

---

## 📂 Dataset

The project uses a movie dataset (`movies.csv`) containing information such as:

* Movie Title
* Genres
* Keywords
* Tagline
* Cast
* Director

---

## ⚙️ How It Works

1. Load movie dataset using Pandas
2. Select important features (genres, keywords, tagline, cast, director)
3. Replace missing values with empty strings
4. Combine selected features into one text column
5. Convert text data into numerical vectors using **TF-IDF**
6. Compute similarity between movies using **Cosine Similarity**
7. Take user input (favorite movie name)
8. Find the closest matching movie title
9. Recommend top similar movies

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
```

### 2️⃣ Navigate to project folder

```bash
cd movie-recommendation-system
```

### 3️⃣ Install required libraries

```bash
pip install numpy pandas scikit-learn
```

### 4️⃣ Run the notebook

Open:

```
Movie_Recommendation_System.ipynb
```

Run all cells and enter your favorite movie when prompted.

---

## 💡 Example

**Input:**

```
Enter your favourite movie name: Avatar
```

**Output:**

```
Movies suggested for you:
1. Guardians of the Galaxy
2. John Carter
3. Star Trek
...
```

---

## 📈 Future Improvements

* Add GUI using Streamlit or Flask
* Deploy as a web app
* Improve recommendation accuracy
* Add collaborative filtering
* Use larger real-world datasets

---

## 👨‍💻 Authors

kalpesh Badujar

Internship Project Team

---

## 📜 License

This project is for educational and internship purposes only.
