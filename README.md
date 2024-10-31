# numbers classfication with Dense Neural Network & mnist dataset

- The reason why this model has errors in execution even with 98% accuracy on some new data is that only the Dense network is used and when we import the image directly into the Dense network, the neighborhoods of the pixels are not considered.
- So, the models used for the image must first use the convolutional network to extract the features and then give the extracted features to the Dense network for classifier.
