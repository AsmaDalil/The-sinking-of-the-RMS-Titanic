# The-sinking-of-the-RMS-Titanic
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew.  Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this homework, you are asked to complete the analysis of what sorts of people were likely to survive. In particular, you are asked to build a deep neural network to predict which passengers survived the tragedy.

 # Dataset

The data has been split into two groups:

training set (train.csv Download train.csv): The training set should be used to build your model. For the training set, the outcome (also known as the “ground truth”) is provided for each passenger. Your model will be based on  “features” like passengers’ gender and class.

test set (test.csv Download test.csv): The test set should be used to see how well your model performs on unseen data. For the  test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

titanic full.csv Download titanic full.csvcontains the whole dataset and is provided for you to extract the label for the test set to compute accuracy.

