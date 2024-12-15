# movie-recommender-system

This repository contains the implementation and analysis of a movie recommendation system. The system utilizes the MovieLens dataset to implement and evaluate multiple recommendation models, such as content-based filtering, Singular Value Decomposition (SVD), Bayesian Parameter Models, and Autoencoders. The project focuses on addressing challenges like data sparsity, scalability, and cold-start problems while maximizing recommendation accuracy.

### Description
The system utilizes the **MovieLens Dataset** containing:

- Metadata for over 45,000 movies.
- 26 million user ratings from more than 270,000 users.

---

## Models Implemented

### 1. Content-Based Filtering
### 2. Singular Value Decomposition (SVD)
### 3. Bayesian Parameter Model
### 4. Autoencoders
---

## How to Run the Code

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo-url
   cd movie-recommendation-system
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook movie_recommender.ipynb
   ```

4. Follow the notebook to train and evaluate different models.

---

## Evaluation Metrics

- **Root Mean Squared Error (RMSE)**: Measures prediction accuracy.
- **Mean Absolute Error (MAE)**: Focuses on the average magnitude of prediction errors.
- **Precision@K**: Proportion of relevant recommendations in the top-K items.
- **Recall@K**: Proportion of relevant items retrieved in the top-K items.

