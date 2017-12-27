# Convolutional-Neural-Network
A single hidden layer neural network to solve a computer vision problem

Determine orientation of an image in computer vision using Neural Networks

To run the problem, simply type:

python3 orient.py **\<mode> \<test OR train-file.txt> \<model-file.txt> \<model>**

where,

* **mode** = train or test (you have to train before testing for custom data sets)
* **test/train file** - a .txt file that contains vectors(192 dimensions) for the images we're training on.
* **model-file** - Using pickle we store the trained model in this file (used when classifying testing data)
* **model** - enter 'nnet' here

#### Note
This program stores the trained model in a temporary file (using pickle) called model-file.txt
