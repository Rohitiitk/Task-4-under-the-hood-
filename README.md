# Task-4-under-the-hood-
first I take the data and clean it by dropping the rows having NAN values.
And in the second line I rescale the values to between 0 and 1 by dividing every element of it by the maxima of that column.
After that I divide the data randomly in training set and test set and then reshape the data matrix as per the need in the model.
In the defination of model, I first initialise the weight and bias to 0 ,then define z and applied sigmoid function to that so that it can give output between 0 and 1 so that we can easily classify the output between 0 and 1.After that I write the cost function and it is defined in such a way that it gives the minima smoothly during gradient decent.W and B is then updated as shown in the code.
after defining the model I have defined the accuracy by the given formula, and find the accuracy by passing test dataset.
