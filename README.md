# Neural_Network_Charity_Analysis

## Overview
The purpose of this analysis was to implement machine learning and neural networks by using the features in a provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. Alphabet Soup is a fictional organization that has helped fund over tens of thousands of organizations over the years. They have sent over a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization.
To start, Pandas and Scikit-Learn’s StandardScaler() were used to preprocess the dataset in order to compile, train, and evaluate the neural network model, which is designed with TensorFlow.
A binary classification model was created that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. To do this, first, the numbner of inputs were first decided on before determining the number of neurons and layers in the model. Afterwards, the binary classification model was compiled, trained, and evaluated to calculate the model’s loss and accuracy.
Finally, attempts were made to optimize the model in order to achieve a target predictive accuracy higher than 75%.

## Results

### Data Preprocessing

What variable(s) are considered the target(s) for your model?
What variable(s) are considered to be the features for your model?
What variable(s) are neither targets nor features, and should be removed from the input data?

![balaccsmote](Resources/balaccsmote.png)

![smote](Resources/smote.png)


### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take to try and increase model performance?

![balaccnaive](Resources/balaccnaive.png)

![easy](Resources/easy.png)

## Summary

Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
