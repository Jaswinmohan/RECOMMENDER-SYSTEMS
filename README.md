# RECOMMENDER-SYSTEMS
Build a Recommender System: Create personalized recommendations using data science techniques to enhance user experiences.
# RECOMMENDER SYSTEM

This Python notebook provides a Movie Recommendation System with three main parts:

1. **Exploring and preparing data**: This section involves data preprocessing and cleaning. It explores the dataset, drops unnecessary columns, and combines data from different sources to create a comprehensive movie dataset.

2. **Collaborative Filtering**: In this part, an item-based collaborative filtering approach is implemented using the K-nearest neighbors (KNN) algorithm. It generates movie recommendations based on user ratings and movie similarities.

3. **Enhancing the Recommender**: The recommender system is further enhanced by considering movie overviews and keywords/tags. Sentence embeddings are used to capture movie overview similarities, and keyword information is used to improve the recommendations. Recommendations are filtered based on both overview and keyword similarities.

### Prerequisites
- Python
- Libraries: numpy, pandas, matplotlib, scikit-learn, sentence-transformers

### Usage
1. Ensure you have the required libraries installed.
2. Run the code sections sequentially.
3. Use the `movieRecommenderEnhanced` function to get movie recommendations based on a selected movie.

### Note
- The dataset used in this project contains ratings and movie information up until mid-2017.
- Recommendations are based on movie similarities, overview, and keywords.
