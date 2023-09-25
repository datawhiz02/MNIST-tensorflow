# MNIST-tensorflow
Building classical ML models using MNIST dataset

## Task 1
- The images are 28 x 28 pixels in gray scale. The categories are 0, 1, ... 9
- Concatenated the image rows into a 784-dimensional (784 = 28 x 28) vector and treated this as our feature.
- Assuming the feature vectors in each category in the training data have Gaussian distribution, mean and standard deviation of those features for the 10 categories as 28 x 28 images are drawn using the training images. There are be 2 images for each of the 10 digits, one for mean and one for standard deviation. We call those ”mean digits” and ”standard deviation digits.”

## Task 2
- Classified the images in the testing data set using 0-1 loss function and Bayesian Decision Rule to report the performance by assuming that the class-conditional 784-dimensional image vector has Gaussian distribution. The confusion matrix is shown to summarize the prediciton summary. 
- Printed out some correctly and incorrectly classified images for each label, together with the output of the discriminant functions

## task 3
- Trained a multi-class logistic regression model using tensorflow and included confusion matrix to summarize the performance of the model.
- Printed out some correctly and incorrectly classified images for each label, together with the output of the discriminant functions.
- Used Rectified Linear unit(relu) activation function, Stochastic Gradient Descent(SDE) for optimizing the model and Mean squared error(MSE) loss function.
