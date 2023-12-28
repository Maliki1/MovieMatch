# MovieMatch (Elevating Viewing with Smart Recommendations)

## Project Overview


This project focuses on creating a sophisticated Movie Recommendation System. Our goal is to enhance user engagement and retention by offering personalized movie suggestions, maximizing content value, and boosting potential revenue.

## Process or Methodology
### Data Mining Process

Our approach follows a structured data mining process, encompassing:
- Business Understanding: Recognizing the need for a recommendation system in the fast-growing streaming industry.
- Data Understanding: Analyzing a dataset with 19 columns and 4803 instances, focusing on crucial attributes like budget, revenue, popularity, and vote count.
- Data Preparation: Involves data cleaning (handling missing values, formatting, indexing), feature engineering, and data transformation (normalization, encoding).
- Modeling: We used k-NN (k-Nearest Neighbors), Decision Tree, and Linear Regression models. The process included baseline model creation, hyperparameter tuning via nested cross-validation, and combining feature transformation with hyperparameter tuning.
- Evaluation: Models were evaluated based on Mean Absolute Error (MAE), with nested and non-nested performance assessments.


### Algorithm Choices and Insights

- k-NN: Effective for smaller datasets and faster operation.
- Decision Tree: Offers in-depth analysis and better performance, suitable for scenarios where response time is less critical.
- Linear Regression: A baseline model for performance comparison.

## Results and Findings
### Model Performance

- The Regressor Tree showed the best performance, achieving the lowest MAE on both training and testing sets.
- k-NN ranked second, performing better with an increased number of examples.
- Linear Regression served as a comparative baseline.

## Recommendations

1. Integrate k-NN into the movie search engine for fast response times.
2. Implement the Regressor Tree for post-viewing recommendations, where more sophisticated analysis is viable.


## Conclusions

Our findings suggest that while k-NN and Decision Tree are both viable, their application depends on the specific user interaction scenario. k-NN is preferable for instant recommendations during searches, while the Decision Tree fits better for detailed analysis post-viewing.
