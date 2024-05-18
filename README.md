# Activity-Preference-Classifier

# Practical Data Science with Python

## Project Overview

This project provides a comprehensive analysis of the BuddyMove dataset, focusing on classifying users based on their activity preferences using machine learning models. The primary goal is to predict user preferences across different activity categories, enhancing user engagement through data-driven insights.

## Key Features

- **Data Retrieval and Preprocessing**: The dataset was sourced from the UCI Machine Learning Repository. The preprocessing steps included handling missing values and normalizing numerical features to ensure data quality and reliability.
- **Exploratory Data Analysis (EDA)**: Descriptive statistics and visualizations were used to explore each activity category, revealing user preferences and behaviors. Scatter plots helped in understanding the relationships between different activity ratings.
- **Classification Models**: Decision Tree and Random Forest classifiers were implemented to categorize users based on their activity preferences. The models were evaluated using accuracy, precision, recall, F1 score, and confusion matrices.
- **Model Comparison**: A comparative analysis of the models highlighted their strengths and weaknesses, providing recommendations for model selection and further research.

## Methodology

1. **Data Retrieval and Preprocessing**:
    - Retrieved the BuddyMove dataset.
    - Handled missing values.
    - Normalized numerical features using StandardScaler from scikit-learn.

2. **Exploratory Data Analysis**:
    - Conducted descriptive statistics for each activity category.
    - Used histograms and scatter plots to visualize data distributions and attribute relationships.

3. **Data Modelling**:
    - Implemented Decision Tree and Random Forest classifiers.
    - Evaluated models using accuracy, precision, recall, F1 score, and confusion matrices.

4. **Model Comparison**:
    - Compared models based on evaluation metrics.
    - Analyzed confusion matrices to understand classification errors.

## Results

- The **Decision Tree** classifier achieved an accuracy of 48%, with precision and recall around 48% and an F1 score of 46.95%.
- The **Random Forest** classifier also achieved an accuracy of 48%, with precision of 49.45%, recall of 48%, and an F1 score of 44.66%.
- Both models showed similar accuracy but varied in precision and F1 scores, indicating room for improvement.

## Conclusion

The study demonstrates the effectiveness of data preprocessing and model selection in classification tasks. While the models provided valuable insights into user preferences, future work could focus on improving model performance through more extensive data collection, feature development, and hyperparameter tuning.

## Technologies Used

- **Programming Language**: Python
- **Libraries**: pandas, scikit-learn, matplotlib, seaborn

## References

- [BuddyMove Data Set](https://doi.org/10.24432/C5N316) - UCI Machine Learning Repository
- Breiman, L. (2001). Random forests. Machine Learning, 45(1), 5-32.
- Quinlan, J. R. (1986). Induction of decision trees. Machine Learning, 1(1), 81-106.
- Han, J., Kamber, M., & Pei, J. (2011). Data mining: concepts and techniques. Elsevier.
- Tukey, J. W. (1977). Exploratory data analysis. Addison-Wesley.
- Alpaydin, E. (2020). Introduction to machine learning. MIT Press.
