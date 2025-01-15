# Image-recognition-cifar10
 Image recognition project using cifar10 dataset from Tensorflow.

# The Purpose of the Application
Our application purpose is to convert images into digital image that can be edited,
stored, searched, or transmitted electronically.
Identifying and categorizing objects within images. This can include everyday objects,
animals, landmarks, or specific items within a defined context.
This application allow users to digitize images, objects making them easier to store,
organize, and share electronically.
Overall, ourmapplication enhance productivity, facilitate information management,
and improve accessibility to digital content.
# Which dataset was used and how it was obtained?
We used CIFAR-10 dataset. It includes 10 different objects category, 50000 train
images and 10000 test images. We obtained this dataset from tensorflow tutorial.
# Training, testing, and validation set distributions
The CIFAR-10 dataset typically consists of 60,000 32x32 color images in 10 classes,
with 6,000 images per class. These 60,000 images are usually divided into a training
set and a test set.
In the case of CIFAR-10, the original dataset doesn't come with a predefined
validation set.
# Which models were used?
We used Sequential model and Convolutional Neural Network (CNN) in our
application.
We also used Dense, Activation, Flatten, Conv2D, MaxPooling2D methods in
convolution layers.
# Which evaluation metrics were used?
When we compile our model, we used “sparse_categorical_crossentropy” for loss,
“adam” for optimizer, “accuracy” for evaluation metrics.
There are many loss, optimizer and, metrics types but these ones that mostly used.
