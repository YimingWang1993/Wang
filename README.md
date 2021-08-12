# Wang
Neural network for time series dataset

Explaination:  
This code is suit for time series dataset. There are two kinds of neual network architectures. One is Fully connected mutli-layer perceptron (FCMLP and FCMLP_R), one is Convolution neural network(CNN and CNN_R). And FCMLP and CNN are used for classifcation and FCMMP_R and CNN_R are used for regression.

"mianFucntion" can be given input dataset and training parameters and sone methods against overfitting. The details about methods can be seen below:
                • early stopping: “0” means without; when > 0, for example: ”3” means stop training when loss don’t decrease in 3 iterations
                • L2: set factor of L2 regularization
                • Dropout [dropout rate of inputlayer,1st,2rd,3rd hidden layer]: set factor of dropout for each layers
                • Downsampling rate: set downsampling rate; “0” means without downsampling
                • data augmentation: set Set augmentation factor. “0” means without data augmentation. For example: “2” means number of samples from N to 2N.

"Napthalene" is an example dataset.

"Methods", "OverFittingExperiments" and "StopLossNotImproveing" are about methods against overfitting. 

