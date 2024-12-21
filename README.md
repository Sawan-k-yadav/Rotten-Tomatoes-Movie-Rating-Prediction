# Audience Rating Prediction Project from Rotten-Tomatoes-Movie dataset
### Introduction
This project focuses on predicting audience ratings for movies using a dataset from Rotten Tomatoes. The goal is to leverage machine learning techniques to analyze various features related to movies and provide accurate predictions of how audiences rate them. This can be useful for filmmakers, studios, and marketers to understand audience preferences.

### Dataset Description
The dataset used in this project contains multiple features for each movie, which are crucial for predicting audience ratings. The key columns include:

+ movie_title: The title of the movie.
+ genre: The genre of the movie (e.g., Action, Drama, Comedy).
+ directors: Names of the directors involved in the film.
+ writers: Names of the writers who contributed to the script.
+ runtime_in_minutes: The total duration of the movie in minutes.
+ studio_name: The production company responsible for the movie.
+ tomatometer_rating: The critics' score on Rotten Tomatoes.
+ tomatometer_count: The number of reviews that contributed to the tomatometer rating.
+ G, NC17, NR, PG, PG-13, R: Dummy variables representing various film ratings.
+ tomatometer_status: Indicates whether the movie is "Fresh" or "Rotten".
+ audience_rating: The target variable that we aim to predict.

### Objectives
The main objectives of this project are:

1. To explore and preprocess the dataset, ensuring data quality and consistency.
2. To implement various regression algorithms to predict audience ratings.
3. To evaluate and compare the performance of these models to identify the most effective approach.

### Methodology
1. Data Exploration: Analyze the dataset to understand distributions, correlations, and identify missing values.
2. Data Preprocessing: Handle missing values, encode categorical variables, and scale numerical features.
3. Model Selection: Implement the following regression algorithms:
    + Linear Regression
    + Ridge Regression
    + Lasso Regression
    + ElasticNet Regression
    + Decision Tree Regression
    + Random Forest Regression
    + Gradient Boosting Regression
    + Support Vector Regression
4. Model Evaluation: Use metrics such as Mean Squared Error (MSE) and R² Score to evaluate model performance.

## Results
After training and validating the models, the following R² scores were achieved:

+ Ridge Regression: R² Score: 0.52
+ Linear Regression: R² Score: 0.50
+ Random Forest Regression: R² Score: 0.48

(** More improvement need to do )

The Ridge Regression model performed the best, indicating that it effectively captures the relationship between the features and audience ratings.

### Usage
To run this project:

1. Clone the repository:

    ```
    git clone https://github.com/Sawan-k-yadav/Rotten-Tomatoes-Movie-Rating-Prediction.git
    ```
2. Navigate to the project directory:

    ```
    cd Rotten-Tomatoes-Movie-Rating-Prediction
    ```
3. Install the required dependencies if you are creating inside vscode:

    ```
    pip install -r requirements.txt
    ```
4. Open the Jupyter notebook:

    ```
    jupyter notebook
    ```

### Conclusion:

This project demonstrates how machine learning can be applied to predict audience ratings for movies. By analyzing various factors, we can gain insights into audience preferences, which can aid in decision-making for filmmakers and marketers.