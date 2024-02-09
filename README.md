# Image-Segmentation-using-CNN-


# Overview
This repository contains a basic implementation of an image segmentation algorithm using Convolutional Neural Networks (CNN). The implemented code is designed for a synthetic dataset with simple shapes on a contrasting background. The CNN architecture is a U-Net-like model, and the project includes dataset preparation, model design, training, and validation steps.

# Dataset Preparation
The synthetic dataset can be generated using the data/synthetic_dataset.py script. Adjust the parameters in the script for the number of samples, image size, and shape complexity.

# Model Training
Run the script to train the CNN model on the synthetic dataset. The script includes model initialization, loss function, optimizer, and training loop. We can adjust the hyperparameters as needed.

# Validation
The script performs segmentation on a few images from the validation set and reports key metrics such as accuracy, precision, recall, and F1 score.

# Model Architecture
It consists of an encoder-decoder structure similar to U-Net. The model is designed for binary image segmentation, with the output representing the segmented region.

# Results
A few examples are visualized, showing the input image, ground truth mask, and predicted mask.

# Future Improvements
Extend the code for real-world datasets<br>
Experiment with more complex CNN architectures<br>
Fine-tuning hyperparameters for better performance<br>

