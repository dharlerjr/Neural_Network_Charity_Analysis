# Neural_Network_Charity_Analysis

## Overview of Analysis
The goal of our analysis is to create a binary classifier to predict how successful applicants will be if funded by Alphabet Soup.

## Results
Data Preprocessing...
* Target Variable: IS_SUCCESSFUL
* Feature Variables: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, ASK_AMT, SPECIAL_CONSIDERATIONS
* Neither Targets nor Features: In our analysis, we removed the EIN & NAME variables

Compiling, Training, & Evaluating the Model
* For our base neural network model, we used...
    * First Hidden Layer with 80 neurons & a ReLu Activation Function
    * Second Hidden Layer with 30 neurons & a ReLu Activation Function
    * Output Layer with a Sigmoid Activation Function
* I was not able to achieve the target model performance
* To try to increase our model's performance, I...
    1. Decreased the number of Epochs
    2. Added a 3rd Hidden Layer
    3. Added More Neurons to the 2nd Hidden Layer

## Summary
In summary, our model was able to predict whether or not an applicant was successful 72% of the time. While this metric may be sufficient, it's nowhere near perfection. Thus, there is still work to be done. Other potential optimizations include further adjusting the input data or using different activation functions for one or more of our hidden layers. 