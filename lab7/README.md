## Neural Networks Part 2 

### Goals 
1. Understanding PyTorch neural network data preparation, network definition, training and evaluation. 
2. Saving a NN weights.

### Submission
Copy and paste the answers in each text cells at the end of the notebook [MNIST_with_GPU.ipynb](MNIST_with_GPU.ipynb) with code changes. Submit it to the TAs responsible for the lab attendance to get the grade.



### Exercise 1
Read the code from [MNIST_with_GPU.ipynb](MNIST_with_GPU.ipynb) and answer the following questions and paste the answers in the notebook you are submitting.

1. What batch size is used for training the neural network?
2. How many epochs the network is trained?
3. How many layers are there in the network?
4. Describe each layers by the type of the layer, number of neurons in that layer (for fully connected layer), the type of activation function used in that layer. If it is a Convolutional Layer describe its filter size and stride length.
5. What algorithm is used for training and describe the prameters used.
6. Will the network improve with epoch for training why or why not?

### Exercise 2
Improve the performance of the the NN accuracy slightly by adjusting parameters such as number of epoches and different learning rates. Note that there wont be any drastic improvements as there is not much room to improve after 98.9% accuracy.

### Exercise 3
Note the accuracy after each epoch and save it. Now use SGD for training the NN.

### Exercise 4
Training a NN is expensive, time consuming and in larger datasets it is hard to converge. Therefore after you have trained your network find a way to save the weights. After the weights are saved, reload the model from the weights saved and feed the sample here through the NN.