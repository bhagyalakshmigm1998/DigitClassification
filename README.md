# DigitClassification
Problem Statement 
# Implement a Multi Layer ( One Input, One Output and One or more Hidden Layers) ANN or CNN for handwritten digit classification using MNIST dataset

Overview:
In this project, Handwritten Digit Classifier, we will try build a neural network from scratch by using the required algorithms and mathematical functions in order to classify handwritten digit.

The dataset is provided by MNIST(Modified National Institute of Standards and Technology). MNIST dataset is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning.


Neural Network's Architecture:
We all know that a basic neural network has three parts:-

#an i/p layer: The leftmost layer in the network is called the input layer, and the neurons within the layer are called input neurons.

#hidden layers: Can be one or more than one in number. It is the middle layer, and all the computation or processing in the neural network is done by the hidden layers.

#an o/p layer: The rightmost layer in the network is called the output layer, and the neurons within the layer are called output neurons.


So, as we know how a basic neural network looks like, let's now see how our neural network architecture for classifying handwritten digits looks like:-

To recognize individual digits we will be using a three-layer neural network.

The input layer of the network contains neurons encoding the values of the input pixels. Our training data will consist of 28 by 28 pixel images of scanned handwritten digits, so the input layer contains 784 = 28x28 neurons.

The second layer of the netwrok is a hidden layer. We denote the number of neurons in this hidden layer by n, and we'll experiment with different values of n.

The output layer of the network contains 10 neurons, having representing values from 0 to 9.

NOTE: The input pixels are greyscales, with value 0.0 for white and 1.0 for black, and in between values representing gradually darkening shades of grey.

Training on 60,000 smaples of MNIST handwritten dataset n Testing on 10,000 smaples.
*Using one of the most powerful supervised deep learning techniques is the Convolutional Neural Networks
*To visualize these numbers, we can get help from matplotlib.
*To be able to use the dataset in Keras API, we need 4-dims NumPy arrays. However, as we see above, our array is 3-dims. In addition, we must normalize our data as it is always required in neural network models.
*I will use the most straightforward API which is Keras. Therefore, I will import the Sequential Model from Keras and add Conv2D, MaxPooling, Flatten, Dropout, and Dense layers.
*set an optimizer with a given loss function that uses a metric. Then, we can fit the model by using our train data.
*We achieved 98.5% accuracy with such a basic model.

Images for testing
five.png and eigth.png

