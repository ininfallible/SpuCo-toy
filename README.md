# Toy implementation reducing spurious correlation using GEORGE on the SpuCoMNIST Dataset.\
Written as part of a lab application to BigML@UCLA.\
Heavily referenced code from [SpuCo's Sample Notebook](https://github.com/BigML-CS-UCLA/SpuCo/blob/master/quickstart/spuco_mnist/spuco_mnist_cluster.ipynb)
## The method (George) we'd like you to implement has a 3 step pipeline:
1. Train a model using ERM
2. Cluster inputs based on the output they produce for ERM
3. Retrain using "Group-Balancing" to ensure in each batch each group appears equally.
