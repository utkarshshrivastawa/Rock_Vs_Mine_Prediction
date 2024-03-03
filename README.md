# Rock_Vs_Mine_Prediction using Logistic Regression
This project aims to accurately classify sonar signals as either a rock or a mine using a Logistic Regression model. The dataset used for this project contains signals bounced off a metal cylinder (mine) and a roughly cylindrical rock collected from different angles.

## Project Overview
1. Objective: Build a binary classifier to identify whether the object is a rock or a mine based on sonar signal returns.
2. Model Used: Logistic Regression, due to its effectiveness in binary classification problems.
3. Libraries and Dependencies: The project utilizes Python along with libraries such as NumPy, Pandas, and Scikit-Learn for data manipulation, analysis, and model building.
   
## Dataset
The dataset comprises 208 entries, each with 60 features representing the energy within a particular frequency band, integrated over a certain period. The last column contains labels (R for rock, M for mine).

## Data Preprocessing
1. Handling Missing Values: The dataset was checked for null values to ensure data integrity.
2. Feature Selection: All features were used as inputs for the model, and the dataset did not require additional feature engineering.

## Model Training and Evaluation
1. The dataset was split into training (90%) and testing (10%) sets to evaluate the model's performance.
2. The Logistic Regression model was trained using the training set.
3. The model achieved an accuracy of ~83.4% on the training set
4. The model achieved an accuracy of ~83.4%~76.2% on the test set, indicating a reasonable performance.

## Predictive System
1. A predictive system was developed to classify new samples as either rocks or mines based on their sonar signatures.
2. The system takes a numpy array of signal values as input, processes it, and outputs the classification along with a message indicating whether the object is a rock or a mine.

## How to Run
1. Clone the repository.
2. Ensure you have Python and all required libraries installed.
3. Run the Jupyter notebook to train the model and make predictions.

## Conclusion
This project demonstrates the capability of Logistic Regression in classifying sonar signals into rocks or mines. Future work could explore more complex models or feature engineering techniques to improve accuracy.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.
