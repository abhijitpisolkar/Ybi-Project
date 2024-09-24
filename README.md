# Movie Recommendation System

## Objective
To build a movie recommendation system that suggests similar movies based on a user’s favorite movie using content-based filtering.

## Data Source
The dataset used for this project is sourced from [this link](https://raw.githubusercontent.com/Lorddhaval/Dataset/main/Movies%20Recommendation.csv).

## Approach
This project uses content-based filtering, which relies on movie features such as genre, keywords, tagline, cast, and director to recommend movies that are similar to a given movie.

## Steps Involved:
1. **Data Import:** The movie dataset is loaded and inspected.
2. **Data Preprocessing:** Missing values in important features are handled.
3. **Feature Engineering:** Text-based features are combined to create a composite feature for similarity calculations.
4. **Modeling:** A TF-IDF vectorizer is used to convert text into vectors. Cosine similarity is computed to find the closest movies based on feature similarity.
5. **Recommendation System:** The user inputs a favorite movie, and the system suggests top 30 movies similar to the chosen movie.

## Tools & Libraries
- **Python**: Core programming language used.
- **Pandas**: Data manipulation and analysis.
- **Scikit-learn**: TF-IDF vectorizer and cosine similarity.
- **Numpy**: Support for array operations.

## How to Use
To run this project:
1. Clone the repository.
2. Run the `Movie_Recommendation.ipynb` Jupyter notebook on your local machine or Google Colab.
3. Input a favorite movie name and get a list of recommended movies.

## Future Enhancements
- Adding collaborative filtering for user-based recommendations.
- Improving movie data by including more features, like user ratings and reviews.
