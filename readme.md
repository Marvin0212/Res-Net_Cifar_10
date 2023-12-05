## ResNet CIFAR-10 Classifier

**Project Description:**

This repository contains a TensorFlow implementation of a Residual Network (ResNet) trained on the CIFAR-10 dataset. The CIFAR-10 dataset comprises 60,000 32x32 color images in 10 classes, with 6,000 images per class. This project demonstrates the implementation and training of a deep learning model using ResNet architecture to classify images into these 10 classes.

### Key Features:

1. **Data Preprocessing and Visualization**: The project begins with loading the CIFAR-10 dataset and visualizing random images from each class, providing an intuitive understanding of the data we're working with.

2. **Custom ResNet Architecture**: The core of this project is a custom-built ResNet model. The architecture is defined using TensorFlow and Keras, with a series of residual blocks to learn from the image data effectively.

3. **Model Training and Optimization**: The model is compiled and trained with Adam optimizer, categorical cross-entropy loss, and a focus on accuracy as the performance metric. Training includes the use of a `ModelCheckpoint` callback to save the best model based on validation accuracy.

4. **Performance Evaluation**: After training, the model's performance is evaluated using accuracy and loss metrics on the test dataset. A confusion matrix is also generated to provide deeper insights into the model's classification capabilities.

### Repository Structure:

- `ResNet_CIFAR10.ipynb`: The main Jupyter notebook containing the complete code for loading data, building the ResNet model, training, and evaluating its performance.
- `model/`: Directory containing the saved model checkpoint at the epoch with the highest validation accuracy.
- `images/`: Sample images from the CIFAR-10 dataset used for visualization.
- `requirements.txt`: List of Python packages required to run the project.

### Conclusion:

This project serves as a practical application of ResNet architecture in image classification. The CIFAR-10 dataset provides a diverse set of images to train and test the model, allowing for a comprehensive understanding of deep learning techniques in computer vision.
