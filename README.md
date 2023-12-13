# Mushroom Classification Tutorial

This tutorial guides you through the process of classifying different types of mushrooms using a deep learning model. The dataset pipeline involves downloading mushroom images, creating a data.json file, resizing images, and splitting the dataset into training, validation, and test sets.

## Dataset Pipeline

### Step 1: Download Mushroom Images
Use the "Download All Images" Chrome extension tool to download 100 images of each mushroom type into separate folders.

### Step 2: Create data.json File
Run the provided Python script to create a data.json file containing mushroom types and labels.

### Step 3: Resize Images
Run the provided Python script to resize images to (600 x 800), (300 x 500), and (200 x 200) pixels.

### Step 4: Split Datasets
Run the provided Python script to split the dataset into training, validation, and test sets.

## Model Training

Train a deep learning model using PyTorch, transfer learning with a pre-trained VGG16 model, and a custom classifier. The training script includes code for data augmentation, learning rate scheduling, and model evaluation.

## Test the Model

Evaluate the trained model on the test set to measure accuracy.

## Save the Model

Save the trained model, optimizer, and other necessary information as a checkpoint file named "VGGNet.pth".

## Load the Model

Use the provided function to load a saved checkpoint and rebuild the model for future use.

## Inference

Use the model for inference on new mushroom images. The provided functions help with image processing and visualization.

## Dependencies

- Python 3.x
- PyTorch
- torchvision
- Pillow (PIL)
- Matplotlib
- splitfolders

Follow the instructions in the tutorial steps to set up the environment and run the code. Have fun exploring and classifying mushrooms!
