# Grapevine Leaves Classification

## Overview
This project is focused on classifying different types of grapevine leaves using deep learning techniques. We use the [Grapevine Leaves Image Dataset](https://www.muratkoklu.com/datasets/Grapevine_Leaves_Image_Dataset.zip) for training and evaluation. The primary objectives of this project include:

1. Data Preprocessing:
   - Divide the data into training and test sets with an 80-20 split.
   - Apply data augmentation to increase the dataset size while ensuring that the test data remains unaffected.
   - Implement a 10-fold cross-validation strategy.

2. Model Architectures:
   - Utilize various pre-trained Convolutional Neural Network (CNN) architectures such as VGG16, VGG19, ResNet101, and InceptionV3.
   - Fine-tune these models for grapevine leaves classification.

3. Autoencoder Networks:
   - Implement autoencoder networks for tasks like denoising or dimensionality reduction.
   - Evaluate the impact of autoencoders on model performance.

4. Evaluation and Reporting:
   - Perform 10 iterations of model training with different random seeds and report average results.
   - Present the results in the form of a table, confusion matrix, and diagrams.
   - Compare the model's performance with relevant articles or benchmarks.

## Project Structure
The project structure includes the following components:

### Dataset
The dataset consists of grapevine leaf images categorized into different classes such as 'Ak', 'Ala_Idris', 'Buzgulu', 'Dimnit', and 'Nazli'. You can download the dataset from [here](https://www.muratkoklu.com/datasets/Grapevine_Leaves_Image_Dataset.zip) and place it in the appropriate directory.

### Code
The code is organized into Python scripts or Jupyter notebooks that cover different aspects of the project, including data preprocessing, model training, and evaluation.

### Models
This directory contains pre-trained model weights and configurations for VGG16, VGG19, ResNet101, and InceptionV3.

### Results
This directory stores the results of model training and evaluation, including performance metrics, confusion matrices, and visualizations.

## Instructions
1. Download the Grapevine Leaves Image Dataset and place it in the appropriate directory.
2. Run the code provided in the project's Python scripts or Jupyter notebooks.
3. Adjust hyperparameters, model architectures, and training settings as needed.
4. Refer to the Results directory for the project's outcomes and performance metrics.

Please note that this project involves extensive deep learning model training, which may require a suitable computing environment and significant computational resources.
