<!-- PROJECT BANNER -->
![Movie Recommender System](assets/movie-recommender-banner.png)

<!-- HEADER with DESCRIPTION -->
## 🎬 Movie Recommender System 🍿

A **content-based movie recommendation web app** built with **Python** and **Streamlit**. Select a movie and it returns the **five most similar titles** with their posters. Each of the ~4,800 TMDB movies is represented by its genres, keywords, top three cast members, director, and plot overview, vectorized with a **bag-of-words** model and ranked by **cosine similarity**.

<br>

## ✨ Features

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)"  srcset="assets/features-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/features-light.svg">
    <img src="assets/features-dark.svg" alt="Features" width="800">
  </picture>
</p>

<br>

## ⚙️ Technologies Used

| Category | Tools |
|---|---|
| **Frontend** | Streamlit |
| **Backend** | Python, Requests |
| **ML & Data Processing** | Pandas, NumPy, scikit-learn (`CountVectorizer`, `cosine_similarity`), NLTK (Porter stemmer) |
| **Data & APIs** | TMDB 5000 dataset, TMDB API (poster images) |
| **Tools & Deployment** | Jupyter Notebook, Pickle, Git LFS, Procfile |

<br>
<hr>

<a href="https://github.com/arinjadhav"><img src="https://img.shields.io/static/v1?style=for-the-badge&label=GITHUB&message=arinjadhav&labelColor=161B22&color=DBDBDB&logo=github&logoColor=FFFFFF" alt="GitHub: arinjadhav"></a>
<a href=""><img src="https://img.shields.io/static/v1?style=for-the-badge&label=LICENSE&message=MIT&labelColor=161B22&color=DBDBDB" alt="MIT License"></a>
