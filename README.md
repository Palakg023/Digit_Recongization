# Digit_Recongization
# Handwritten Digit Classification using Single-layer and Multi-layer Perceptron
![image](https://github.com/Palakg023/Digit_Recongization/assets/91871427/6543cc1a-7d7d-4826-ad76-4de1290a09b0)
![image](https://github.com/Palakg023/Digit_Recongization/assets/91871427/9aa4a93b-7e7c-4a5f-adb6-35c2a4dd198a)


This project aims to implement handwritten digit classification using deep learning techniques, specifically utilizing both single-layer and multi-layer perceptrons. The goal is to train models that can accurately classify handwritten digits into their respective numeric classes (0 to 9).

## Project Overview

The project consists of the following main components:

1. **Dataset**: The MNIST dataset is used, which is a well-known benchmark dataset for handwritten digit classification. It contains a large collection of labeled images of handwritten digits (28x28 pixels) along with their corresponding numeric labels.

2. **Data Preprocessing**: The dataset is preprocessed to prepare it for training and testing the models. This includes splitting the dataset into training and testing sets, normalizing the pixel values, and potentially applying data augmentation techniques to enhance the model's generalization capabilities.

3. **Single-layer Perceptron**: The first approach involves implementing a single-layer perceptron for digit classification. The pixel values of the images serve as input features, and the model learns a set of weights and biases to make predictions. Suitable activation functions, such as sigmoid or ReLU, are used to introduce non-linearity.

4. **Training and Evaluation**: The single-layer perceptron model is trained on the training dataset using an optimization algorithm such as stochastic gradient descent (SGD). The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1 score.

5. **Multi-layer Perceptron (MLP)**: The second approach involves implementing a multi-layer perceptron (also known as a feed-forward neural network). This model consists of multiple layers of artificial neurons, allowing for more complex representations of the handwritten digits. The MLP incorporates hidden layers with varying numbers of neurons and utilizes suitable activation functions and regularization techniques (e.g., dropout) to improve performance and prevent overfitting.

6. **Training and Evaluation**: Similar to the single-layer perceptron, the MLP model is trained on the training dataset using an optimization algorithm like SGD. The model's performance is evaluated on the testing dataset, and the results are compared with the single-layer perceptron to determine the improvement achieved by the multi-layer architecture.

7. **Model Deployment and Visualization**: Once the models are trained and evaluated, they can be saved and deployed to classify handwritten digits in real-world scenarios. The project can include visualizations to showcase the model's predictions and provide insights into the learned representations.
