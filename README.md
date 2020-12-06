# Class_TwoLayerNN_and_Data_Classification

- In "OneHiddenLayerNN.ipynb" we build a class for an " input layer/vector - hidden layer - output" neural network.
The cost function considered is the sum of squared errors and the network is trained with a "minibatch SGD" optimizer.

- The "dataset_classification_1" and "dataset_classification_2" files contain applications of the network in circular and moon-shaped datasets respectively.

- ( **to be added in the future** )
In order to use the network in more complicated cases we will : 
1. Equip the network with 2 more dense layers
2. Reformulate the "backpropagation" method so that a regularizer term can also be considered for the network training (the regularizer choice will be optional for the user)
3. Build a separate class for optimizers and make the network class a child-class of the optimizers class. In that way we will be able to consider more optimizers for training.
