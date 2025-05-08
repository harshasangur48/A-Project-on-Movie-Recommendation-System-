# 🎬 Movie Recommendation System

A personalized movie recommendation system using collaborative filtering techniques (SVD and KNN). The system predicts movie ratings for users and recommends top-rated unseen movies based on selected genres, with optional preference for Indian cinema.

---

## 📌 Features

- Predicts user ratings for movies using SVD and KNN algorithms.
- Provides top-N personalized movie recommendations.
- Allows filtering by genre and prioritization of Indian movies.
- Evaluates models using RMSE and MAE.
- Visualizes rating distribution and top-rated movies.

---

## 🛠️ Tech Stack

- **Language:** Python  
- **IDE:** Jupyter Notebook  
- **Libraries Used:**  
  - pandas, numpy – Data manipulation  
  - matplotlib, seaborn – Visualization  
  - scikit-surprise – Recommendation models

---

## 📂 Dataset

- **Source:** [MovieLens Dataset](https://grouplens.org/datasets/movielens/)  
- **Files Used:**
  - `movies.csv`: Contains movie titles and genres  
  - `ratings.csv`: Contains user-movie ratings  

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git
   cd movie-recommendation-system


   - "Install required libraries:"
    - |
      ```
      pip install pandas numpy matplotlib seaborn scikit-surprise
      ```
    - "Launch the Jupyter Notebook:"
    - |
      ```
      jupyter notebook
      ```
    - "Open the notebook and follow the prompts to select genre and generate recommendations."

example_output: |
    
    Enter your name: Prashanth Neel
    Choose genre: Action
    Prioritize Indian movies? (yes/no): no

    🎥 Prashanth Neel's Top Action Recommendations:
    • The Dark Knight (2008) - ⭐ 4.72
    • Seven Samurai (1954) - ⭐ 4.52
    • Blade Runner (1982) - ⭐ 4.41
    

  future_scope:

  
    - Combine collaborative and content-based filtering for hybrid recommendations.

    
    - Develop a web or mobile app interface using Streamlit or React.

    
    - Integrate real-time movie data from APIs like TMDB or IMDb.

    
    -  Apply sentiment analysis on user reviews.

    
    - Enable explainable and diverse recommendations.

    
    - Add user account support for personalized history tracking.

    
    - Support multi-language and region-based filtering.

  license:
    type: MIT License
   

  contact:
    email: harshasangur048@gmail.com
