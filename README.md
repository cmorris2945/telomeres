# telomeres
CNN for discovery of telomere lemgth
Neural Network Architecture
The model is built using Keras, utilizing TensorFlow as the backend. TensorFlow was chosen as the backend due to better performance over Theano, and the ability to visualize the neural network using TensorBoard.

For predicting two categories, OLD or YOUNG

After pooling, the data is fed through a single dense layer of size 128, and finally to the output layer, consisting of 2 softmax nodes.

TensorBoard CNN


