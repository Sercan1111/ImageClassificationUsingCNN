# Image Classification using CNN

## Overview
This project uses Convolutional Neural Networks (CNN) to classify images as either happy or sad. The solution is implemented in Python and utilizes libraries such as TensorFlow, Keras, OpenCV, and Matplotlib for data preprocessing, model building, and visualization.

## Dataset
The dataset used in this project consists of images categorized into two classes: happy and sad. The images are stored in directories that represent their respective classes.

## Preprocessing Steps
1. Load and preprocess the images from the dataset directory.
2. Remove any images that are not in the specified formats (jpeg, jpg, bmp, png).
3. Normalize the image pixel values to the range [0, 1].
4.Split the dataset into training, validation, and test sets.

## Visualization
- Display sample images from the dataset.
- Plot the training and validation loss over epochs.
- Plot the training and validation accuracy over epochs.

## Classification Model
A Convolutional Neural Network (CNN) model is built to classify the images. The architecture includes:

- Convolutional layers with ReLU activation.
- MaxPooling layers to reduce spatial dimensions.
- Dense layers with ReLU and sigmoid activation for the final output.

## Files in the Repository
- image_classification.py: The main Python script with all the preprocessing, modeling, and evaluation steps.
- requirements.txt: Lists all the dependencies to run the script.

## Results
The model was trained for 20 epochs, and the performance was evaluated on the validation set. The accuracy and loss metrics for both training and validation were plotted to visualize the model's performance over time.
## Future Work
- Explore data augmentation techniques to increase the diversity of the training dataset.
- Experiment with deeper and more complex CNN architectures to improve accuracy.
- Implement real-time image classification using a webcam feed.

## Contributions
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.
