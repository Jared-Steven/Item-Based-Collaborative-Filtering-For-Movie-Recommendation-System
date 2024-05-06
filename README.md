# Item Based Collaborative Filtering For Movie Recommendation System

## Overview

This project focuses on building a movie recommendation system using item-based collaborative filtering. The recommendation system suggests movies to users based on the similarity between movies, as determined by user ratings.

## Dataset

The dataset used in this project is sourced from Kaggle and can be found at the following link:
- [MovieLens 100k Dataset](https://www.kaggle.com/prajitdatta/movielens-100k-dataset)

## Code Details

The code is provided in the Jupyter Notebook format (`Item_based_collaborative_filtering_for_movie_recommendation_system.ipynb`). It's developed using Python and relies on libraries such as Pandas, NumPy, and Plotly for data manipulation, analysis, and visualization.

### Dependencies

Ensure you have the necessary dependencies installed to run the code:
- `pandas`
- `numpy`
- `plotly`

### Code Workflow

The notebook follows these key steps:

1. **Data Preparation:**
   - Loading the movie ratings data and movie titles.
   - Merging the datasets to create a unified dataframe.

2. **Data Exploration:**
   - Calculating statistical features of the movies.
   - Analyzing movie ratings and the number of ratings received.

3. **Creating User-Item Interaction Matrix:**
   - Building a matrix representing the ratings given by users to each movie.

4. **Making Recommendations:**
   - Finding movies similar to a selected movie based on user ratings.
   - Establishing a threshold for the minimum number of ratings to filter out less-rated movies.
   - Generating movie recommendations based on correlation with the selected movie and the number of ratings.

## Usage

To run the notebook, follow these steps:
1. Install the required dependencies listed above.
2. Download the dataset from the provided Kaggle link.
3. Update the notebook with the correct file paths to the dataset.
4. Execute each cell in the notebook sequentially to perform data analysis and generate movie recommendations.

## Conclusion

The item-based collaborative filtering approach offers a simple yet effective method for recommending movies to users based on their preferences and ratings. By leveraging correlation between movies, the recommendation system can provide personalized suggestions, enhancing the user experience.

For detailed implementation and results, refer to the notebook.

