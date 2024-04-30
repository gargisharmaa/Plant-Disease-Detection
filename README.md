# Plant Disease Detection

This project aims to develop a plant disease recognition model based on leaf image classification using deep convolutional networks. The model is designed to recognize 38 different types of plant diseases across 14 different plants.

## Introduction

The objective of this project is to create a robust model that can accurately identify plant diseases from images of their leaves. This is achieved by leveraging deep learning techniques and convolutional neural networks (CNNs) to learn features from the input images and classify them into various disease categories.

## Dataset

The dataset used in this project consists of:
- 70,295 training images
- 17,572 testing images

The dataset covers 14 different plants, including:
- Tomato
- Apple
- Blueberry
- Grape
- Peach
- Corn
- Cherry
- Squash
- Strawberry
- Pepper
- Orange
- Potato
- Raspberry
- Soybean

## Workflow

1. **Data Preprocessing**
    - Load images from the folder, resize them to 128x128 pixels (256x256 takes longer for processing), and convert them to tensors.
    - Build a validation dataset using 30% of the total dataset.
  
2. **Model Architecture**
    - Experiment with various CNN architectures, including:
        - Multilayer CNN with Linear Layers
        - VGG16 using Transfer Learning
        - Resnet34 using Transfer Learning
  
3. **Data Loading and Batching**
    - Load the data using batches to efficiently train the model.

4. **Model Training**
    - Select the device (e.g., GPU) and load the data onto the device.
    - Train the model on the training data and evaluate its performance on the test data.

5. **Model Evaluation**
    - Assess the model's accuracy and performance on the test data.

6. **Model Saving**
    - Save the trained model for future use.

## Results

The model achieves satisfactory accuracy in recognizing plant diseases across various plant species. The performance metrics and evaluation results are provided in the project documentation.

## Future Work

Future updates to this project may include:
- Fine-tuning the model architecture for improved performance.
- Exploring additional CNN architectures and transfer learning approaches.
- Scaling up the dataset and training the model on larger datasets for better generalization.
