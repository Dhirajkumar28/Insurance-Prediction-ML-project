Project Overview:-
This project involves predicting medical insurance expenses based on several factors such as age, sex, BMI, number of children, smoking status, and region. The dataset used contains the following columns:
age: Age of the primary beneficiary, 
sex: Gender of the insurance contractor (female, male)
bmi: Body Mass Index, providing an understanding of body weight relative to height
children: Number of children covered by health insurance
smoker: Smoking status (yes, no)
region: The beneficiary's residential area in the US (northeast, southeast, southwest, northwest)
expenses: Individual medical costs billed by health insurance.

Steps Performed:
Data Cleaning: Checked for missing values and handled them appropriately.
Converted categorical variables into numerical values for model processing.

Data Analysis and Visualization:
Used plotly.express for interactive visualizations.
Analyzed the number of smokers according to sex.
Created a pie chart to visualize the distribution of regions where people live.

Model Training and Prediction:
Split the dataset into training and testing sets using train_test_split from sklearn.model_selection.
Trained a Random Forest Regressor model to predict the insurance expenses.
Evaluated the model by predicting the expenses on the test set.
Stored the predicted values in a DataFrame for further analysis.
