# Neural_Network_Charity_Analysis
Module 19:Neural Networks and Deep Learning Models, Tensorflow v. 2.4.1

## 1) PURPOSE OF THE ANALYSIS:
A foundation, Alphabet Soup, wants to predict where to make investments. The goal is to use machine learning and neural networks to apply features on a provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. The initial file has 34,000 organizations and a number of columns that capture metadata about each organization from past successful fundings.

## 2) RESULTS:
### Data Preprocessing-

  * What variable(s) are considered the target(s) for your model?
  
    The variable we are targeting in this module is the IS_SUCCESSFUL column.

  * What variable(s) are considered to be the features for your model?
    
    The features that we are using are every column except the ones that we will drop.

  * What variable(s) are neither targets nor features, and should be removed from the input data?
    
    The EIN and NAME columns will not increase the accuracy of the model and can be removed to improve code efficiency.
    
### Compiling, Training, and Evaluating the Model-

  * How many neurons, layers, and activation functions did you select for your neural network model, and why?
  
    In the optimized model, layer 1 started with 110 neurons with a relu activation. For layer 2, it dropped to 80 neurons and continued with the relu activation.       From there, the sigmoid activation seemed to be the better fit for layers 3 (40 neurons) and layer 4 (20 neurons).
    
    <img width="1013" alt="Screen Shot 2022-02-25 at 12 12 51 PM" src="https://user-images.githubusercontent.com/91294352/155759059-e5dfe23d-97d6-467e-a761-d561f1b9cc7e.png">

  * Was the model able to achieve the target model performance?

    Although the target for the model was to be 75% or above, but the best the model could produce was 72.7%.
    
  * What steps were taken to try and increase model performance?

    Some of the steps I took to try and make the model more accurate were adding hidden layers, changing the activation type, changing the number of epochs and         changing the number of neurons in each layer.
    
    <img width="778" alt="Screen Shot 2022-02-25 at 12 16 42 PM" src="https://user-images.githubusercontent.com/91294352/155759081-b83dad3f-fb84-447a-b4ce-1e5a2b133e5c.png">
