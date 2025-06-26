# Task 4: Recommendation System using Collaborative Filtering

## Description
This task involves building a recommendation system using collaborative filtering with matrix factorization techniques on the MovieLens 100k dataset.

## Files
- `Recommendation_System_Collaborative_Filtering.ipynb`: Jupyter notebook containing the implementation, training, prediction, and evaluation of the recommendation system.

## Dataset
The MovieLens 100k dataset is used, which is built-in to the Surprise library and automatically downloaded.

## How to Run
1. Install the required Python packages if not already installed:
   ```
   pip install scikit-surprise pandas
   ```
2. Open the Jupyter notebook `Recommendation_System_Collaborative_Filtering.ipynb`.
3. Run the cells sequentially to train the recommendation model and evaluate its performance.

## Notes
- The notebook includes detailed comments and explanations for better understanding.
- The model uses SVD for matrix factorization and achieves good RMSE on the test set.
