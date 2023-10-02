# MNIST Digit Recognition with Convolutional Neural Networks and UI

![MNIST](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

This project combines a Convolutional Neural Network (CNN) for recognizing hand-written digits using the MNIST dataset with a user-friendly UI built using Tkinter. The CNN model is trained to classify digits from 0 to 9, and the UI allows users to draw a digit, recognize it, and display the result.

## Project Overview

In this project, we have two main components:

1. **Convolutional Neural Network (CNN):**
   - The CNN model is trained to recognize hand-written digits using the MNIST dataset.
   - It consists of multiple layers, including Convolutional and Fully Connected layers.
   - The model is compiled, trained on the training data, and evaluated on the test data.
   - After training, the model is saved as `mnist.h5` for future use.

2. **User Interface (UI):**
   - The UI is built using Tkinter, a Python GUI library.
   - Users can draw a digit on a canvas within the UI.
   - When the "Recognise" button is clicked, the drawn digit is captured, preprocessed, and passed to the CNN model for recognition.
   - The recognized digit and the model's confidence score are displayed on the UI.

## Prerequisites

Before running the code, ensure you have the following dependencies installed:

- Python (3.6+ recommended)
- TensorFlow (2.x)
- Keras (2.x)
- NumPy
- Tkinter (usually comes pre-installed with Python)
- Pillow (PIL) for image processing

You can install these dependencies using pip:

    ```bash
    pip install tensorflow keras numpy pillow
# Output 
![WhatsApp Image 2023-10-02 at 14 32 46_a5c6263d](https://github.com/Spraveen8-chary/mnist-digit-classifier/assets/108536707/651a6fc3-26ee-4f7c-8e9b-1742b6004275)


![WhatsApp Image 2023-10-02 at 14 33 38_ad8ab528](https://github.com/Spraveen8-chary/mnist-digit-classifier/assets/108536707/bfa9d160-a7fe-4d5f-9948-8213f9a69075)

