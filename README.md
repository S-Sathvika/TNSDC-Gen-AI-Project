# TNSDC-Gen-AI-Project
This repository contains code for training a Generative Adversarial Network (GAN) to generate new images based on a provided dataset.


Project Goal:

The goal is to train a GAN model to create novel and realistic images within a specific category. The code allows you to customize the training process for your desired image category.


Key Features:

Image Preprocessing: The code includes functionalities to load and preprocess image data for training the GAN.
Model Architecture: Separate functions define the architectures for both the Generator and Discriminator models. You can modify these functions to experiment with different network configurations.
Training Loop: The script implements a training loop that iteratively updates the Generator and Discriminator models based on the provided dataset.
Loss Functions: The code utilizes binary cross-entropy loss functions for both the Generator and Discriminator.
Image Generation: The script includes a function to generate sample images during training for visualization purposes.

Requirements:

TensorFlow 2.x
NumPy
Pillow (PIL Fork)
tqdm (optional, for progress bar)
Matplotlib (optional, for image visualization)

Outputs:

The script will generate and save sample images periodically during training in the final directory within the DATA_PATH. These images demonstrate the model's progress in creating new images.
The training process will also print logs indicating the epoch number, generator loss, discriminator loss, and estimated time remaining for each epoch.
