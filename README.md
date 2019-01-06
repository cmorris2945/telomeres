# telomeres
CNN for discovery of telomere lemgth
Neural Network Architecture
The model is built using Keras, utilizing TensorFlow as the backend. TensorFlow was chosen as the backend due to better performance over Theano, and the ability to visualize the neural network using TensorBoard.

For predicting two categories, EyeNet utilizes three convolutional layers, each having a depth of 32. A Max Pooling layer is applied after all three convolutional layers with size (2,2).

After pooling, the data is fed through a single dense layer of size 128, and finally to the output layer, consisting of 2 softmax nodes.

TensorBoard CNN


