# Module_19_Challenge

## The Purpose of the Analysis

The purpose of the data analysis was to predict where to make investments with a foundation called “Alphabet Soup.”  The goal was to predict if applicants will be successful if funded by “Alphabet Soup” using machine learning and neural networks.  The original file contained over 30,000 organizations.  Also in the file were a number of columns which captured metadata about each organization from previous successful findings.

## Results

# Data Processing

What variable(s) are considered the target(s) for your model?

•	The variable which is being targeted is the IS_SUCCESSFUL column.

What variable(s) are considered to be the features for your model?

•	Every column will be utilized except the columns which will be dropped.

What variable(s) are neither targets nor features, and should be removed from the input data?

•	The EIN and NAME columns will be removed because neither will increase the accuracy of the model.  They will also be removed to improve the efficiency of the code.

# Compiling, Training and Evaluating the Model

How many neurons, layers and activation functions did you select for your neural network model and why?

Four hidden layers and One output layer to the optimal accuracy.  80 neurons were used in the First hidden layer, 60 neurons were used in the Second hidden layer, 40were used in the Third hidden layer and 20 neurons were used in the Fourth Hidden layer.  The relu activation was used for the First and Second hidden layers and the sigmoid activation was used for the Third and Fourth hidden layers.  The sigmoid activation was used because it seemed to give a higher accuracy.

Were you able to achieve the target model performance?

Unfortunately, the target performance was not achieved using a different number of neurons or different activations.  The highest percentage achieved was 72.5%.

What steps did you take to try and increase model performance?

Some steps which were taken to improve the accuracy is that more hidden layers were added and neurons were increased or decreased.
## Summary

The activations which showed the highest accuracy (72.6%) were used to produce the accuracy number.  These two activations proved to produce the best model for the data using a various number of neurons and hidden layers.
