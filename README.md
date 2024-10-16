# -Sentimental-Analysis-for-Product-Reviews-using-Machine-Learning
This code performs sentiment analysis on Amazon product reviews. 

1. Data Loading & Pre-processing:
   - It loads a CSV dataset containing Amazon product reviews.
   - It creates a new DataFrame with only the 'reviews.rating' and 'reviews.title' columns.
   - It removes rows with missing values.
   - It creates a new column 'label' to categorize reviews as positive (1) or negative (0) based on the rating.

2. Data Visualization:
   - It displays a heatmap to visualize the cleaned data and check for missing values.
   - It shows the distribution of labels (positive vs. negative) using a bar chart.
3. Feature Engineering:
   - Split data into features (review text) and target (labels).
   - Split data into training and testing sets.
   - Use TF-IDF vectorizer to convert text data into numerical representations for model training.
4. Model Training and Evaluation:
   - Train a Logistic Regression model.
   - Make predictions on the test set.
   - Evaluate the model using accuracy and a classification report.
   - Train a Multinomial Naive Bayes model and evaluate similarly.
   - Compare the accuracies of both models using a bar chart.
5. Model Testing:
   - Select random rows from the dataset.
   - Use the trained model to predict the sentiment of these random reviews.
   - Compare the predicted labels to the actual labels for each review.
