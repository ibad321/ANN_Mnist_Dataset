# ANN on MNIST Dataset

This repository contains the implementation of an Artificial Neural Network (ANN) on the MNIST dataset using Google Colab. The project involves data preprocessing, model training, and evaluation of the ANN to classify handwritten digits.

## Project Workflow

1. **Data Acquisition**
   - The MNIST dataset is used, which is a large database of handwritten digits commonly used for training various image processing systems.

2. **Data Preprocessing**
   - Loading the dataset.
   - Normalizing the images to scale the pixel values to the range [0, 1].
   - Reshaping the data to fit the model requirements.

3. **Model Architecture**
   - Building an Artificial Neural Network (ANN) with the following layers:
     - Input layer
     - Hidden layers with activation functions
     - Output layer with softmax activation

4. **Model Training**
   - Compiling the model with appropriate loss function and optimizer.
   - Training the model on the training data.

5. **Model Evaluation**
   - Evaluating the model on the test data to determine its accuracy and performance.

## Tools and Technologies

- **Google Colab:** The Integrated Development Environment (IDE) used for this project.
- **Python Libraries:** 
  - TensorFlow and Keras for building and training the ANN.
  - NumPy for data manipulation.
  - Matplotlib for data visualization.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ann-mnist.git
