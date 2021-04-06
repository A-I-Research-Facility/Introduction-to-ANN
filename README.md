# ANN_declassified
Artificial neural network creation in raw python from scratch

This repository goes from coding a simple neuron without using data manipulation tools like numpy, to advanced coding of neural networks involving batches, layers, etc. This repo is a concise form of https://github.com/Sentdex/NNfSiX which is an overall guide on how to create a neural network from scratch in almost any language by SentDex. Be sure to check it out.

# _p1.py_ -->
This is a simple neuron which takes 3 inputs, has 3 respective weights, and 1 bias. It produces a single output.

# _p2.py_ -->
This is a layer consisting of 3 neurons. Each neuron takes 4 inputs and produces 1 output. So, we have total of 4 inputs, but as output, we have a list of 3 results because of 3 neurons.

# _p3.py_ -->
This is a layer of 3 neurons developed using numpy. Numpy makes it easier to calculate dot product of matrices.

# _p4.py_ -->
Creation and modification of batches

# _p5.py_ -->
Hidden layers and activation functions including the use of rectified linear function

# _p6.py_ -->
Using the softmax activation function \n
p6-1.py => Understand the internal working of a softmax function \n
p6-2.py => Implement softmax function