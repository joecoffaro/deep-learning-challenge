# deep-learning-challenge

## Overview
### 
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Using my knowledge of machine learning and neural networks, the features in the provided dataset will create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.


## Results

## Data Preprocessing

What variable(s) are the target(s) for your model? Target Variable for the model is "IS_SUCCESSFUL" this determins if the investment in a venture is worth investing in.

What variable(s) are the features for your model?
NAME
APPLICATION_TYPE
AFFILIATION
CLASSIFICATION
USE_CASE
ORGANIZATION
INCOME_AMT
SPECIAL_CONSIDERATIONS 
STATUS
ASK_AMT

What variable(s) should be removed from the input data because they are neither targets nor features? EIN (Employer ID number) was removed


## Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

I was able to achieve the models desiered acuracy of 75% by using 3 hidden layers and each layer had a modification to the neurons. I also used output functions and changed relu to sigmoid, I did this to increase accuracy and hold Epoch. 

Were you able to achieve the target model performance? yes. 

What steps did you take in your attempts to increase model performance? I Changed the "CLASSIFICATION" from "NAME" and added a hidden layer. 

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

The updated model demonstrates improved classification performance, achieving an average accuracy of over 75% for predicting successful outcomes.

Key Success Indicators:

Application Type: Applicants with application types in the range [T3 to T8, T10, T19] have a significantly higher likelihood of success.

Application Frequency: Applicants who have applied 10 or more times show an over 80% chance of success based on recent model results.

Another alternative model to consider is the Random Forest Classifier. A Random Forest Classifier could be used because it combines multiple decision trees to improve accuracy and reduce overfitting. It works well for complex datasets and can handle both numerical and categorical data effectively. It’s also good at identifying important features that influence predictions.
