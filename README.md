# Handwritten-digit-and-character-recognition

The objective of this project is to build a image-classifier using Convolutional Neural Networks to accurately categorize the handwritten digits. The data for this project can be found here and the files are expected to be stored in the folder "/data/" relative to the repository.


# Network Architecture
We use three types of layers, in this model. They are the convolutional layer, pooling layer and fully connected layer. For this problem, I have defined the following network architecture.

Note: The input is a sample set of 60,000 images, where each image is 28x28 pixels with 1 channel.

The first layer is a Convolutional layer with 20 filters each of size (6,6) followed by another Convolutional layer with 20 filters each of size (3,3). Then, we have a Max Pooling layer of size (4,4).

Similarly, I have defined same set of layers with Convolutional layer having only 10 filters this time. All the Convolutional layers defined above have ReLU as activation function.

Then there are fully connected layers with 30 units in the first and 10 (no. of o/p units) in the second. The first layer uses tanh as activation function and the second one uses softmax.
