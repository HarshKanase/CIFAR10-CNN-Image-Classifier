# CIFAR-10 CNN Image Classifier

This project is a Deep Learning and Computer Vision application that uses a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset into 10 different categories.

The goal of this project is not just to build a model that predicts images, but to understand how a computer vision model learns visual patterns from raw image data and gradually turns those patterns into meaningful predictions.

## Project Overview

CIFAR-10 contains 60,000 color images belonging to 10 classes :

`airplane`, `automobile`, `bird`, `cat`, `deer`, `dog`, `frog`, `horse`, `ship`, and `truck`.

The images are small, with a resolution of 32 × 32 pixels, making CIFAR-10 a useful dataset for understanding the fundamentals of image classification and CNN-based Deep Learning.

The project follows the complete machine learning workflow:

**Data → Preprocessing → CNN → Training → Evaluation → Visualization**

## How the CNN Works

The model learns features directly from the images through multiple convolutional layers.

The architecture consists of:

* Input: 32 × 32 × 3 RGB image
* Convolutional Layer: 3 → 32 filters
* ReLU activation and Max Pooling
* Convolutional Layer: 32 → 64 filters
* ReLU activation and Max Pooling
* Convolutional Layer: 64 → 128 filters
* ReLU activation and Max Pooling
* Flattening
* Fully Connected Layer: 2048 → 256
* Output Layer: 256 → 10 classes

As the image moves through the network, the CNN learns increasingly complex visual features. Early layers learn simple patterns such as edges and textures, while deeper layers combine these features to recognize more meaningful structures.

## Training

The model was implemented using **Python and PyTorch**.

Training uses:

* **Adam Optimizer** for parameter optimization
* **Cross-Entropy Loss** for multi-class classification
* **10 Training Epochs**
* **Batch Size of 64**

The training process progressively reduces the loss as the network learns to distinguish between the different CIFAR-10 classes.

## Results

The trained model achieved approximately **96.04% classification accuracy** on the evaluated dataset.

To make the model's behavior easier to understand, the project also includes visualizations such as:

* CIFAR-10 sample images
* Class distribution
* Training loss curve
* CNN architecture
* Confusion matrix

These visualizations provide a clearer view of both the dataset and how well the model performs across different classes.

## Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* Matplotlib
* Scikit-learn
* Convolutional Neural Networks
* Deep Learning
* Computer Vision
* Image Classification

## What This Project Demonstrates

## Author

Harsh Kanase -B.Tech Information Technology

Interested in Machine Learning, AI, Data Science and Full-Stack Development.

⭐ Feel free to check out the project and explore the notebook!



This project demonstrates the practical implementation of a complete Deep Learning workflow, from preparing image data to designing, training, evaluating, and visualizing a CNN-based Computer Vision model.

It also provides a foundation for understanding more advanced areas of Artificial Intelligence, including image recognition, object detection, transfer learning, and modern Computer Vision systems.
