# Neural_Network_Charity_Analysis
## Overview of the Analysis

A hypothetical nonprofit foundation, Alphabet Soup, needs help analyzing the impact of their donations and vetting potential recipients by predicting which organizations are worth donating to and which are too high risk. I designed a deep learning neural network that evaluates all types of input data and produces a clear decision making result using the Python TensorFlow library.

## Data Preprocessing
* Variable that was considered as the target for my model: IS_SUCCESSFUL Column
* Variables that were considered features for my model: Every Column except for IS_SUCCESSFUL which is our target and the ones we will drop
* Variable that were neither targets or features for the dataset: Columns that I dropeed are EIN, NAME because they will have little to no impact om our outcome

## Compiling, Training and Evaluating the Model
The number of neurons, layers, and activation functions I selected for my neural network model:

I had 2 hidden layers. My first layer had 80 neurons, the second has 30 there is also an output layer. The first and second hidden layer have the "relu" activation function and the activation function for the output layer is "sigmoid."

![1](https://user-images.githubusercontent.com/90945875/152032425-889b966a-8f34-48a6-b405-9b885df49759.PNG)

## Evaluate the model using the test data

![2](https://user-images.githubusercontent.com/90945875/152032991-a4876a92-3ec0-411e-b0bf-2bd9e47e49ac.PNG)

The model was not able to reach the target 75%. The accuracy for my model was 52%.
## Improving the model 
Removed additional feature, that is the 'USE_CASE' column. Rest of the model stayed the same

![3](https://user-images.githubusercontent.com/90945875/152034113-fc046e6c-b671-4119-8f0b-9a400529efc7.PNG)

![4](https://user-images.githubusercontent.com/90945875/152034519-bbff391e-aa2b-4e7b-90e1-27d3840ceace.PNG)

![5](https://user-images.githubusercontent.com/90945875/152034833-28cebee0-2b94-4679-bebc-7784f1400d81.PNG)

the model reach the accuracy of 64% after we drop useless Column  


