# CIFAR10
Machine Learning on CIFAR10 dataset

Date - 11.06.2020

first attempt on CIFAR10 data set with own built convolutional model resulted in
train_accuracy of 94.43% and validation accuracy od 72.48%
Test result are really bad, with loss - 568.41, and accuracy of - 52.3%.

Date - 12.06.2020

Second attempt on CIFAR10 data set using VGG16 architechture.
Serious issue of overfitting is evident between train and valuation dataset.
Test result are better than first attempt but overall they are bad
loss - 1.72 & accuracy - 59.25%
Need to try data augmentations.

Date - 13.06.2020

Third attempt on CIFAR10 dataset using VGG16 architechture.
To overcome overfitting L2 Regularization (Weight Decay), Dropout and Batch Normalization was used.
Also VGG achitecture was used but not VGG16 with imagenet weights.
Train reults - accuracy of 97.17% and loss - 0.2956
Validation results - Accuracy - 93.00 and loss - 0.4631
Test results - Accuracy - 92.10% and loss - 0.5064
I also took help from Arivx especially for optimization, as Adam was not giving good results.
