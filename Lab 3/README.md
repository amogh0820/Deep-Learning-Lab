# MNIST Image Classification using CNN

### Aim
To build and evaluate a Convolutional Neural Network (CNN) using Keras and TensorFlow that can automatically recognize and classify handwritten digits (0 through 9).

### Dataset Used
* **Name:** MNIST database of handwritten digits
* **Details:** 60,000 training images and 10,000 testing images of size 28x28 pixels in grayscale.
* **Preprocessing:** Reshaped images to include the single grayscale channel and normalized pixel values from [0, 255] down to [0, 1].

### Brief Note on Results
* The model trained extremely quickly over 5 epochs.
* Hit a final test accuracy of **98.92%** with a very low validation loss (~0.037).
* Using convolutional layers allowed the model to extract spatial features efficiently, making it highly accurate compared to a basic feed-forward network.