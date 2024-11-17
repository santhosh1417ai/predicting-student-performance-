# predicting-student-performance-
This project aims to predict student performance (GPA) based on various factors including demographics, parental level of education, test preparation course completion, and more. It leverages machine learning models such as Linear Regression to analyze student data and make predictions.

## Project Structure

- **Student_performance.csv**: Contains the dataset used for analysis and model training.
- **[Notebook Name].ipynb**: Jupyter Notebook containing the data analysis, preprocessing, model training, and evaluation steps.
- **README.md**: This file providing an overview of the project.

## Data
The dataset used in this project includes information about students, such as:
- Gender
- Race/ethnicity
- Parental level of education
- Lunch type
- Test preparation course completion
- Math score
- Reading score
- Writing score
- GPA (target variable)

## Methodology

1. **Data Loading and Exploration**: Load the student data from the CSV file and perform exploratory data analysis to understand the data's structure and characteristics.
2. **Data Preprocessing**:
    - Handle missing values using imputation techniques (e.g., SimpleImputer).
    - Encode categorical features using one-hot encoding (OneHotEncoder).
    - Split the data into training and testing sets.
3. **Model Training**:
    - Utilize a Linear Regression model to learn the relationship between features and GPA.
    - Train the model on the training data.
4. **Model Evaluation**:
    - Evaluate the model's performance on the testing data using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2).
5. **Prediction**: Use the trained model to make predictions on new data.

## Dependencies

- pandas
- scikit-learn
