# 🎬 Content-Based Movie Recommendation System

This project implements a **Content-Based Movie Recommendation System** that suggests movies similar to a given movie based on their genres.  
The system uses **TF-IDF vectorization** and **Cosine Similarity** to measure similarity between movies and generate recommendations.

---

##  Project Overview

Recommendation systems are widely used by platforms like **Netflix, Amazon, and Spotify**.  
This project demonstrates how a **content-based recommender** works by analyzing movie metadata (genres) rather than user ratings.

The system recommends movies by identifying similarities in movie content.

---

## How It Works

1. Movie genres are converted into numerical vectors using **TF-IDF Vectorizer**
2. **Cosine Similarity** is calculated between all movies
3. When a user selects a movie, the system:
   - Finds the most similar movies
   - Ranks them based on similarity score
   - Returns the top recommendations

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab / Jupyter Notebook











