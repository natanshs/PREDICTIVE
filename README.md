# Personalised Product Recommendation System
## Flipkart GRiD 5.0
This code implements a personalized product recommendation system using collaborative filtering technique and Singular Value Decomposition (SVD) for generating user-specific recommendations. Here's a brief overview of the code:

## Roadmap

### - Importing Libraries:
The necessary libraries for data manipulation, analysis, and visualization are imported.

### - Add more integrations
Reads a CSV file containing user-product ratings data.
Drops the 'timestamp' column and prints descriptive statistics of the DataFrame.

### - Exploratory Data Analysis (EDA):
Generates a histogram of the ratings distribution.

### - Data Filtering and User Ratings:
Filters out users who have rated less than 15 items.
Creates a pivot table with user IDs as rows, product IDs as columns, and ratings as values.

### - Popularity-Based Recommendations:
Generates a list of popular products based on user ratings.

### - Collaborative Filtering and SVD:
Applies Singular Value Decomposition (SVD) on the user-rating matrix to factorize it into U, sigma, and Vt matrices.

### - Generating Recommendations Using SVD:
Defines a function to recommend items to users based on SVD predictions.
Recommends items for specific users and prints the recommendations.

### - Calculating RMSE:
Calculates the Root Mean Square Error (RMSE) to evaluate the performance of the recommendation model.

