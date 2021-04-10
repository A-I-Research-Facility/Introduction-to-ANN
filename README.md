# ANN_declassified
Artificial neural network creation in raw python from scratch<br>
***

### Requirements :<br>
<br>
<img align="left" alt="Python" width="40px" src="https://img.icons8.com/color/72/python.png">
<img align="left" alt="numpy" width="90px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NumPy_logo_2020.svg/640px-NumPy_logo_2020.svg.png">
<br>
<br>
<br>
Installing nnfs -
      
      python3 -m pip install nnfs
      
***
For any query, please reach us at cserveairf@gmail.com or create a pull request regarding your issue.
***

This repository goes from coding a simple neuron without using any data manipulation tools, to advanced coding of neural networks involving batches, layers, etc. This repo is a concise form of https://github.com/Sentdex/NNfSiX which is an overall guide on how to create a neural network from scratch in almost any language by SentDex. Be sure to check it out.

## p1.py -->
This is a simple neuron which takes 3 inputs, has 3 respective weights, and 1 bias. It produces a single output.

## p2.py -->
This is a layer consisting of 3 neurons. Each neuron takes 4 inputs and produces 1 output. So, we have total of 4 inputs, but as output, we have a list of 3 results because of 3 neurons.

## p3.py -->
This is a layer of 3 neurons developed using numpy. Numpy makes it easier to calculate dot product of matrices.

## p4.py -->
Creation and modification of batches

## p5.py -->
Hidden layers and activation functions including the use of rectified linear function

## p6.py -->
Using the softmax activation function 

**p6-1.py** => Understand the internal working of a softmax function 

**p6-2.py** => Implement softmax function
