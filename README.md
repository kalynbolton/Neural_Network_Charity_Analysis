# Neural_Network_Charity_Analysis

## Overview 
With our knowledge of machine learning and neural networks, we used the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. From Alphabet Soup’s business team, we received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization.

## Results
For our Data Preprocessing, we divided our feautures and target arrays. The features were all columns except for the IS_SUCCESSFUL column, which is our target. We removed the EIN and NAME column as they were not applicable to our model.

For Compiling, Training, and Evaluating the Model we first got an accuracy score of 69%. While trying to optimize the model I changed the number of neurons to 165, added a hidden layer, and tried out a different activation function to possibly increase the score. I was unable to reach my target of 75%.

![Capture](https://user-images.githubusercontent.com/97268254/181937551-e3e87e6b-2a0d-4e30-be2b-408ad93d7aae.PNG)

## Summary
Overall running the model with th inital parameters seemed to give a better result. In the future, I think a supervsed classification model could also solve this question. 
