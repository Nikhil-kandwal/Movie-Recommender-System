# 🎬 Movie Recommender System

A content-based movie recommendation engine built using TF-IDF and cosine similarity.

## 📌 Features
- Recommends movies similar to a selected title based on tags, overview, and genre.
- Uses TF-IDF vectorization and cosine similarity for finding related movies.
- Precomputes the similarity matrix for fast runtime recommendations.

## 🧠 How It Works
1. Combines movie metadata into a single "tag" field.
2. Applies TF-IDF vectorization to convert text into numerical features.
3. Calculates cosine similarity between all movie vectors.
4. When a user inputs a movie, the top similar movies are returned.

## 📂 Dataset
- Based on [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).
- You'll need `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv` to run the notebook.
- These files are too large to upload to GitHub, so download them from Kaggle and place them in the project directory.

## 🚀 Getting Started

### Prerequisites:
- Python 3.x
- Libraries: `pandas`, `scikit-learn`, `numpy`
