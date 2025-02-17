# homeassignment

1)
Creating Tensors: A random tensor of shape (4,6) is generated using a normal distribution.
Inspecting Tensors: The rank (number of dimensions) and shape of the tensor are retrieved.
Reshaping and Transposing: The tensor is reshaped into a (2,3,4) shape, and then transposed to swap dimensions.
Broadcasting: A smaller (1,4) tensor is added to a subset of the original tensor using broadcasting, allowing element-wise addition without explicit replication.

2)
Data Preparation: The Iris dataset is loaded and split into training and testing sets.
Model Architecture: A sequential neural network is defined with three dense layers using ReLU and softmax activations.
Compilation: The model is compiled with the Adam optimizer and sparse categorical cross-entropy loss for multi-class classification.
Training: The model is trained for 10 epochs using mini-batches and validated on the test set.

3)
Load and Prepare Data: The Iris dataset is loaded and split into training and testing sets.
Define Neural Network: A sequential model with three dense layers is created, using ReLU for hidden layers and softmax for the output layer.
Compile the Model: The model is compiled with the Adam optimizer and sparse categorical cross-entropy loss for multi-class classification.
Train the Model: The model is trained for 10 epochs using mini-batches and evaluated on the test set.

4)
Builds and trains a neural network to classify flowers in the Iris dataset. It first loads and splits the data into training and testing sets. A sequential neural network is then defined with three layers: two hidden layers using ReLU activation and an output layer with softmax activation for multi-class classification. The model is compiled with the Adam optimizer and a categorical loss function. Finally, it is trained over multiple epochs and validated on test data to assess its performance.
