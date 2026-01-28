# 🎬 Movie Recommender System

A **Python-based Movie Recommendation System** that suggests similar movies using **content-based filtering** and displays movie posters using the **TMDB API**. The application is built with **Streamlit**, handles large model files using **Git LFS**, and is deployed live on **Render**.

---

## 🚀 Live Demo
👉 **[Click here to try the app](https://movie-recommender-system-qtwy.onrender.com/)**

---

## ✨ Features
- 🔍 Recommends movies based on content similarity
- 🧠 Uses cosine similarity on precomputed vectors
- 🎞️ Fetches movie posters dynamically via TMDB API
- 🖥️ Clean and interactive Streamlit UI
- ☁️ Fully deployed on Render (cloud)

---

## 🛠️ Tech Stack
- **Python 3.10**
- **Streamlit** – Web UI
- **Pandas, NumPy** – Data processing
- **Scikit-learn** – Similarity computation
- **TMDB API** – Movie posters & metadata
- **Git & Git LFS** – Version control & large files
- **Render** – Deployment

---

## ⚙️ How It Works
1. Movie metadata is vectorized using content features
2. Cosine similarity is computed between movies
3. A similarity matrix is stored using pickle
4. User selects a movie from the dropdown
5. The system recommends similar movies with posters

---

## 📂 Project Structure
```
Movie-Recommender-System/
│
├── app.py                  # Streamlit application
├── movie_dict.pkl          # Movie metadata
├── similarity.pkl          # Similarity matrix (Git LFS)
├── movie-recommender.ipynb # Model creation notebook
├── requirements.txt        # Python dependencies
├── runtime.txt             # Python version for Render
├── Procfile                # Render process file
├── setup.sh                # Deployment setup
└── README.md
```

---

## 🔐 Environment Variables
Set the following variable in Render:
```
TMDB_API_KEY=your_tmdb_api_key
```

---

## ▶️ Run Locally
```bash
pip install -r requirements.txt
streamlit run app.py
```

---

## 👨‍💻 Author
**Panchal Priyansh**

---

## ⭐ Acknowledgements
- TMDB for movie data and posters
- Streamlit for the amazing UI framework

---

⭐ If you found this project useful, please consider giving it a star!

