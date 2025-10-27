# heart_disease_prediction
this is project is about predicting the heart disease of a person based on the given data.
the data set consistof 16 columns including target varible.
we read the data set and preprocess the data to handle missing value.
we perform EDA (Exploratory Data analysis) to inspect the data and understand the features and their behaviour.
we desgin various plots to understand the data better.
detect the outliers and handle them.
we check the correlationand and understand importance of the features.
select the features on the EDA and correlation.
X,y are split into the train,test data.
model trining on the train data.
evaluate the model performance
tune hyperparameters
select the best performing model
create the example dataset to test.
save the model as pickle file 

## API
load the model pickle file
create fastAPI to expose the predictions.
test the API endpoint in the postman or swagger ui.

## Streamlit ui
create a streamlit ui.
call the API predictions to display in ui.
test the application.
