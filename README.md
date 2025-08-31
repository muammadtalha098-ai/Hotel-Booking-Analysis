# Hotel Booking Analysis

 Beginner data analysis project on hotel booking dataset.

## Project Highlights
- Cleaned dataset
- Explored booking patterns
- Visualized room prices, lead times, and cancellations
- Used Machine learning models to predict cancellation status

## Tools Used
- Python
- Pandas
- Matplotlib & Seaborn
- Scikit learn
- Jupyter Notebook

## Insights
- From the analysis, we can see that **Room Type 6** is the most expensive, while **Room Type 2** is the cheapest. This shows variation in pricing across room categories, which may influence booking status and customer choice. 
- Bookings with longer Lead times are more likely to be cancelled.
- Random Forest Classifier model is performing the best with 89% accuracy and 93% recall score

## Models Performance:
| Models                 |   Accuracy Score |   Precision_score |   F1_score |   Recall_score |
|:-----------------------|-----------------:|------------------:|-----------:|---------------:|
| LogisticRegression     |            75.49 |             88.4  |       81.3 |          75.25 |
| RandomForestClassifier |            89.12 |             91.42 |       92.4 |          93.4  |
| SVC                    |            82.53 |             84.48 |       88.2 |          92.26 |
