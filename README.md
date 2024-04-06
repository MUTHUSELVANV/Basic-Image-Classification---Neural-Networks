# Basic-Image-Classification---Neural-Networks
## Overview<br>
This project focuses on solving a basic image classification problem using Keras with TensorFlow as its backend. The objective is to create, train, and evaluate a neural network model capable of accurately predicting digits from hand-written images.<br>

## Dataset<br>
- **Source**: MNIST database, accessed via the Keras API of the TensorFlow library.<br>
- **Description**: Contains grayscale images of hand-written digits (0 to 9) and their corresponding labels.<br>
## Preprocessing<br>
- **Data Splitting**: Features (pixel values of the images) and target labels are split into training and testing datasets.<br>
- **Label Encoding**: Target labels are encoded to facilitate model training.<br>
## Model Architecture<br>
- **Input Layer**: 784 values corresponding to the initial 28x28 pixel values of the images.<br>
- **Hidden Layers**: Two hidden layers, each with 128 activations to process a single output value.<br>
## Training and Evaluation<br>
- **Training**: Model is trained using the training dataset.<br>
- **Evaluation**: Performance is evaluated using the testing dataset.<br>
## Results<br>
- **Visualization**: Predicted results for the first 25 images in the testing dataset are plotted to visualize the model's performance.<br>
## Conclusion<br>
- Demonstrates the successful creation of a model for handwritten digit recognition.<br>
- High accuracy achieved in predicting digits from hand-written images, showcasing the effectiveness of deep learning approaches in image classification tasks.<br>
