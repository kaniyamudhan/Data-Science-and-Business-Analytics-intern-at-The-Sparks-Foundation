I'm grateful to The Sparks Foundation for providing me with this fantastic internship opportunity.
Hello, everyone! I'm excited to share that I've successfully completed Task 1 as a Data Science and Business Analytics Intern. Let's dive into the details.
Task Details: Objective: Prediction using Supervised ML. Task: Predict the percentage of a student based on the number of study hours. Method: Simple linear regression, involving just two variables. Dataset: Dataset Link
Problem Statement: The challenge is to predict the score a student is likely to achieve if they study for 9.25 hours a day.
Steps I Followed:
1. Data Collection:
I downloaded the dataset from the provided URL (Dataset Link).
The dataset comprises two columns: one for study hours and another for corresponding scores.
2. Data Exploration:
I loaded the dataset into Python, using libraries like pandas, matplotlib, and scikit-learn.
I thoroughly explored the dataset, checking for missing values, outliers, and other data-related issues.
3. Data Preprocessing:
I handled missing values appropriately, using methods like imputing the mean or median.
Outliers were assessed and treated based on domain knowledge.
I divided the dataset into feature (X) and target variable (y). 'Hours' became the feature, and 'Scores' was designated as the target variable.
4. Data Visualization:
I created visualizations such as scatter plots to depict the relationship between study hours and scores, confirming the existence of a linear relationship.
5. Splitting Data into Training and Testing Sets:
The dataset was split into a training set (80%) and a testing set (20%).
6. Model Selection and Training:
Given the simplicity of the problem, I opted for a simple linear regression model.
I imported the linear regression model from scikit-learn and trained it using 'Hours' as input (X_train) and 'Scores' as the target (y_train).
7. Model Evaluation:
I used the trained model to make predictions on the testing data (X_test).
Model performance was assessed using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
8. Making Predictions:
Using the trained model, I predicted the percentage of a student who studies for 9.25 hours/day by creating a new data point with 'Hours' set to 9.25.
9. Interpreting Results:
The prediction provided an estimated score for a student who studies for 9.25 hours/day, addressing the problem statement.
10. Conclusion and Visualization:
I wrapped up the analysis by summarizing the results.
Optionally, I could visualize the predicted score alongside the actual data points on a scatter plot to assess the model's fit to the data.

