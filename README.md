
## Overview of the analysis:

For this project, I used my understanding of machine learning and neural networks to develop a binary classifier that would notify the client whether or not the applicants will be successful using alphabet soup. Over 34,000 groups have been sponsored via alphabet soup, according to the database. Each organization's metadata is captured in a number of fields, including the type of organisation and how funds is used, among other things. There are three phases to this project: Data preprocessing for the neural network Compile, train, and assess the model, and then optimise it.

## Results:

## Data Preprocessing

variable(s) that are regarded the model's target(s)?
- The IS_SUCCESSFUL column is the variable we're after in this module.
variable(s) that are regarded to be features for your model?
- We are utilising every column except the ones that we will delete as features.
What variable(s) were deleted since they are neither targets nor characteristics?
- The 'EIN' and 'NAME' are the first features we remove since we expect these characteristics to have little impact on our final result.

## Compiling, Training, and Evaluating the Model

For your neural network model, how many neurons, layers, and activation functions did you choose?
-This model has two hidden layers and an input feature. There are 80 neurons in the first hidden layer, 30 in the second, and an output layer. There is an activation function for each layer. The activation function "relu" is used in the first and second hidden layers, while the output layer is "sigmoid."
<img width="1150" alt="Screen Shot 2020-12-06 at 7 36 03 PM" src="https://user-images.githubusercontent.com/67278193/101298129-776e4880-37fa-11eb-9009-3b64f2bb942b.png">

What measures were made to improve model performance?
- Adding hidden layers, altering the activation type, changing the number of epochs, and modifying the number of neurons in each layer were some of the measures I took to improve the model's accuracy.

<img width="1118" alt="adds" src="https://user-images.githubusercontent.com/67278193/101298133-79d0a280-37fa-11eb-9f44-f42358ba1894.png">

## Summary: 

The model's accuracy was 72.8 percent - we started with a data set and tried to forecast whether or not the project would be successful based on all of the features we used after removing two that we deemed unnecessary. Although I could not get the accuracy of 75% that I desired, it is probable that the reason for this is that we had to exclude more features, lowering the neural network's overall performance. More data is the greatest approach to improve the accuracy of your model. The correctness of this model will be considerably more tangible if solid data is contributed to it.
