# Flower Classification with GoogleNet and Transfer Learning

This project uses **GoogleNet** with **transfer learning** to classify flower images from a custom dataset. The model leverages pre-trained weights from **ImageNet** and fine-tunes them for flower classification.

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/SobanAhmedK/FlowerClassification.git
    ```
2. Open the project in **MATLAB**.
3. Make sure the required toolboxes (Deep Learning Toolbox) are installed.

## Dataset

The dataset contains flower images organized into folders for each flower type. It is split into `train` and `val` folders for training and validation sets.

## Training

Fine-tune the pre-trained **GoogleNet** model using the custom dataset by running the provided training script in MATLAB.

## Prediction

After training, use the model to predict flower types by passing new images to the trained model.



