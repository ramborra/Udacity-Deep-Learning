# Deep-Learning

## Assignment 1: notMNIST
Preprocess notMNIST data and train a simple logistic regression model on it
### Achieved a Test Accuracy of 85.85%

## Assignment 2
Previously in 1_notmnist.ipynb, we created a pickle with formatted datasets for training, development and testing on the notMNIST dataset.

The goal of this assignment is to progressively train deeper and more accurate models using TensorFlow.
### Achieved a Test Accuracy of 94.1% using single hidden layer and 94.2% using two hidden layers

## Assignment 3
Previously in 2_fullyconnected.ipynb, you trained a logistic regression and a neural network model.
The goal of this assignment is to explore regularization techniques.

 ### Achieved a Test Accuracy of 90.2% using two hidden layers using Loss Regularization, Dropout and Exponential Decay.
 
## Assignment 4
The goal of this assignment is make the neural network convolutional. 
 
 ### Achieved a Test Accuracy of 90.3% using Dropout in CNN and 94.9% using Dropout, Regularization and Learning Rate Decay.
 
 ## Assignment 5
 
n gram vs CBOW : 

To create a model that will assign a probability to a sequence of tokens. Let us start with an example: "The cat jumped over the puddle."

One approach is to treat {"The", "cat", ’over", "the’, "puddle"} as a context and from these words, be able to predict or generate the center word "jumped". This type of model we call a Continuous Bag of Words (CBOW) Model.

Another approach is to create a model such that given the center word "jumped", the model will be able to predict or generate the surrounding words "The", "cat", "over", "the", "puddle". Here we call the word "jumped" the context. We call this type of model a SkipGram model. 

 The goal of this assignment is to train a Word2Vec skip-gram model over Text8 data.
 
 ## Achieved a loss of 3.355148 for 100000 steps.
 
 The goal of this assignment is to train a Word2Vec CBOW model over Text8 data.
 
 ## Achieved a loss of 2.712092 for 100000 steps.
