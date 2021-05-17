# Neural_Network_Charity_Analysis

### Preprocessing and optimizing data for a neural network model

## Analysis Overview:

We use a classifier to determine whether or not the applicants will be successful using Alphabet Soup.

## Results

Using bulleted lists and images to support your answers, address the following questions:
- Data Preprocessing
  1. What variable(s) are considered the target(s) for your model: The target variable in this module is the IS_SUCCESSFUL column.
  2. What variable(s) are considered to be the features for your model: Every column except the dropped columns are the features.
  3. What variable(s) are neither targets nor features, and should be removed from the input data: 'EIN' & 'NAME'

- Compiling, Training, and Evaluating the Model
  1. How many neurons, layers, and activation functions did you select for your neural network model, and why: This model has input & output features and two hidden layers. The first hidden layer has 80 neurons and the second has 30 neurons. There is an activation function for each of the layers; "relu" for the hidden layers and "sigmoid" for the output feature.

![Deliv_2](https://github.com/awebber00/Neural_Network_Charity_Analysis/blob/main/Resources/Deliv2.png)

 2. Were you able to achieve the target model performance: The target performance for the model was above 75% and it was not achieved.

![Deliv_4](https://github.com/awebber00/Neural_Network_Charity_Analysis/blob/main/Resources/Deliv4.png)

## Summary

The accuracy of the model was hindered by a lack of data. More hidden layers could have been added to possibly get a target model performance result closer to the desired percentage of 75%.
