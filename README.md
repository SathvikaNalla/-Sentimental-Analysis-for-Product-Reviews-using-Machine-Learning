# -Sentimental-Analysis-for-Product-Reviews-using-Machine-Learning
This code performs sentiment analysis on Amazon product reviews. 

1. **Data Loading & Pre-processing:**
   - It loads a CSV dataset containing Amazon product reviews.
   - It creates a new DataFrame with only the 'reviews.rating' and 'reviews.title' columns.
   - It removes rows with missing values.
   - It creates a new column 'label' to categorize reviews as positive (1) or negative (0) based on the rating.

2. **Data Visualization:**
   - It displays a heatmap to visualize the cleaned data and check for missing values.
   - It shows the distribution of labels (positive vs. negative) using a bar chart.
