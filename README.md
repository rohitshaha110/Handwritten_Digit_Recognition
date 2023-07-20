# Handwritten_Digit_Recognition

This is a deep learning project that implements Convolutional Neural Network (CNN) for digit recognition. The goal of this project is to accurately recognize hand-drawn digits from 0 to 9.

## Dataset
This project uses the MNIST dataset, which is included in Keras. The dataset consists of 28x28 grayscale images of handwritten digits and their corresponding labels. It is split into training and test sets.

## Usage
Run the application:

'''python app.py'''

Once the application starts, a window will open where you can draw digits using the mouse. After drawing, release the mouse button to process the drawing. The predicted digit will be displayed above the drawing.

## Model
The CNN model used for digit recognition is defined in the model.ipynb file. The architecture consists of convolutional layers, max-pooling layers, and fully connected layers.
