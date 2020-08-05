# Finger-digit-recognition
A model is built to recognize the hand finger digits using Convolution Neural Network.
* Data set is taken from Kaggle platform which consists of 1800 images.
* Data set is split into training and testing data which consists of 1440 and 360 images.
* ResNet50 is implemented by using Conv2D, MaxPooling2D, AveragePooling2D and Flatten layers.
* Model is trained by considering batch size of 32 for 20 epochs.
* Optimizer used is "adam" and for evaluation of model "accuracy" metrics and
"categorical_crossentropy" loss function is considered.
* Activation functions used are softmax and relu.
Libraries used: Keras, Tensorflow(1.x), numpy, matplotlib, sklearn and h5py
Tools used : Google colob and Jupyter notebook.
Achieved an accuracy of 97%.
