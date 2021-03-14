# Neural_Network_Charity_Analysis

## Overview of the analysis: 
The purpose of the analysis is to help the Alphabet Soup's business team predict whether applicants will be successful if funded by Alphabet Soup. Alphabet Soup has donated to more than 34,000 organizations. The Alphabet Soup's business team wants to use the data they have on 34,000 organizations to predict future succucess of applicats.

## Results: 
Using bulleted lists and images to support your answers, address the following questions.
Data Preprocessing

#### Target
What variable(s) are considered the target(s) for your model?
- The variable IS_SUCCESSFUL was used at the target for the model.
What variable(s) are considered to be the features for your model?
#### Features
- Variables APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, and SPECIAL_CONSIDERATIONS were used as the features for the model.

What variable(s) are neither targets nor features, and should be removed from the input data?
- Variables NAME, STATUS, and ASK_AMT should be removed from the input data.

Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?

- There were 5 hidden layers used to provide the highes accurary percentage (0.7371). The first hidden layer has 20 nodes, the seconds hidden layer has 15 nodes, the third hidden layer has 10 nodes, the fourth hidden layer has 5 nodes, and the fifth hidden layer has 1 node. Also, the activation function is sigmoid and epochs is set to 10. There was multiple tests to find what provided the highest accurary percentage. After reducing the noise, using 5 hidden layers, distributing neurons amongst the 5 layers, using sigmoid, and increasing epochs to 10 the highest accuracy percentage acheived is 0.737. It did not meet the target model performance but it did improve from the previous highest accuracy percentage 0.72.

## Summary:
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
