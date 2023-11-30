# Student Performance Prediction Project

Welcome to the repository for the Student Performance Prediction project! This project is focused on predicting student performance based on various features such as gender, race, parental education, lunch type, and scores in math, reading, and writing.

## Dataset

The dataset used for this project is named `StudentsPerformance.csv` from Kaggle. It contains information about students' demographics and academic scores.

## Data Preprocessing

- **Handling Missing Values**: Checked for missing values in each column; fortunately, no missing values were found.

- **Column Renaming**: Renamed columns for better clarity and ease of understanding.

- **Data Cleaning**: Replaced 'some college' with 'college' and mapped 'none' to 'unprepared' and 'completed' to 'prepared' for better consistency.

- **Duplicate Removal**: Checked and removed any duplicate rows from the dataset.

- **Label Encoding**: Mapped the 'test_performance' column to binary labels ('prepared': 1, 'unprepared': 0) for the target variable.

## Feature Selection

- Selected all available features initially.

## Model Training and Evaluation

Evaluated the performance of various classification algorithms:

- **Naive Bayes**
- **Logistic Regression**
- **Random Forest**
- **Decision Tree**

## Confusion Matrix Visualization

Generated confusion matrices for each model to visualize the true positive, true negative, false positive, and false negative predictions.

## User-Friendly Prediction Algorithm

Thus algorithm is developed using Logistic Rgression Model and can predict the students' preparedness depending on the user's input of the fields: gender, race, lunch, math score, reading score and writing score, during run time.

## Running the Code

1. Ensure you have Python installed on your system.

2. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/mahekdesai/Aacademic-Success-Insight.git
    ```

3. Navigate to the project directory:

    ```bash
    cd Academic-Success-Insight
    ```

4. Run the Jupyter notebook or Python script for your analysis.

## Libraries Used

- pandas
- numpy
- sklearn
- matplotlib
- seaborn

## Note

- Customize the preprocessing steps or feature selection based on your specific use case or dataset.

- Feel free to explore and experiment with different machine learning models to improve prediction accuracy.

Happy coding and predicting student success! 📚✨
