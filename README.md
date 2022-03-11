# Multi-Layer-Perceptron-Algorithm
## Multi Layer Perceptron
The multi layer perceptron (MLP) is a feed forward neural network supplement. It has three layers: an input layer, an output layer, and a hidden layer. <br/>
![mlp](https://user-images.githubusercontent.com/78887209/157832855-226eafc8-d317-4960-a350-e24039027ac0.png)  <br/>
The input signal to be processed is received by the input layer. The output layer is responsible for tasks such as prediction and categorization. The true computational engine of the MLP is an arbitrary number of hidden layers inserted between the input and output layers.In an MLP, data flows from input to output layer in the forward direction, similar to a feed forward network. The back propagation learning algorithm is used to train the neurons in the MLP. MLPs can tackle issues that aren't linearly separable and are designed to approximate any continuous function. Pattern categorization, recognition, prediction, and approximation are some of MLP's most common applications. <br/>
## PROBLEM 1: Pattern Classification with Multi Layer Perceptron
A multi-layered network of 4 classes, each of which can separate black and white patterns with a resolution of 10x5, will be designed.What is expected from the designed network is to be able to recognize clean and broken patterns and specify which class they belong to. <br/>
While creating our dataset, we created 4 10x5 matrices that look like 0,2,4,7 as digital numbers. <br/>
![image](https://user-images.githubusercontent.com/78887209/157834792-c2b9fe73-aef7-4d8d-8f9e-bb7f072713b8.png) <br/>
We defined two functions to add noise and provide distortion that makes a black point white and a white point black. For each data, we produced 6 noise added data and 6 distorted data.In the first place, we made a 2% deterioration in the data.After this stage, we have 13 data for each class, 6 of which are corrupted, 6 are changed and 1 is the data itself.
