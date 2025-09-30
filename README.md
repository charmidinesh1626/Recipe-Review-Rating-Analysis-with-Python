# Recipe-Review-Rating-Analysis-with-Python
This project explores factors influencing recipe review ratings using machine learning models. By analyzing the recipe_reviews.csv dataset, the study investigates what drives user star ratings, evaluates model performance, and provides business insights to improve review-based decision-making.

🔹 Key Steps

Data Preparation: Encoded categorical variables, scaled numeric features, and included review metadata.

Modeling: Implemented Logistic Regression and Random Forest classifiers.

Evaluation Metrics: Accuracy, Precision, Recall, Macro F1, ROC-AUC, Confusion Matrices.

Visualizations: Class distribution, feature importance, ROC curves, correlation heatmaps.

🔹 Findings

Ratings are highly imbalanced – 77% of reviews are 5-star, biasing predictions.

Random Forest achieved 77.6% accuracy but a very low Macro F1 (0.213), indicating poor performance on minority classes (1–4 stars).

Feature importance revealed data leakage from IDs, while engagement features (likes_score, ranking_value) and contextual features (region, device_type) showed real predictive power.

Review text is valuable but underutilized without preprocessing (sentiment analysis, embeddings).

🔹 Business Insights

Improve models by removing identifiers, addressing class imbalance, and processing review text.

Engagement metrics can help identify influential reviews and filter outliers.

Models can be applied for negative review detection, customer service triaging, and recommendation system enhancement.

🔹 Conclusion

The study highlights the challenges of imbalanced data and leakage, but also shows the potential of engagement and text features in predicting customer satisfaction. With better preprocessing and feature engineering, businesses can leverage review data for customer experience improvement and strategic growth.
