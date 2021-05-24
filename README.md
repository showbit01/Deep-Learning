# Deep-Learning

1.Autoencoder:
Implement a simple encoder-decoder neural network with one hidden layer using the following images:
Dataset: http://vis-www.cs.umass.edu/lfw/lfw-bush.tgz

2.Graph convolution Network:

Implementation of Graph Convolutional Network for binary classification. 
Dataset: https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.data

GCNs are a powerful neural network architecture for machine learning on graphs.
A randomly initiated 2-layer GCN can produce useful feature representations of nodes in net- works.
The GCN has been fed the data with one layer of graph node aggregation.

You can see that as the number of iteration increases, the training accuracy increases.It becomes constant after it reaches more than 800 iterations. Similarly, the test accuracy decreases when training accuracy increases, resulting in over-fitting.
I have received maximum training accuracy of 95.7% and test accuracy of 89.6% around 800 epochs.
When I used the KNN, SVM and Logistic Regression using library functions, I have received 86.36% accuracy. We can easily see that GCN is performing better than traditional binary classification algorithms as it uses its neighbour’s information during aggregation.
