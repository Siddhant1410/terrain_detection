# TensorFlow Terrain Detection 

A Tensorflow based Terrain Recgnition Program.

![alt text](https://github.com/Siddhant1410/terrain_detection/blob/main/Output.jpg)

# Description

Terrain Recognition programs as such can be used along with self-driving cars to better adjust the driving, by identifying the type of terrain.
This model is made with the help of Tensorflow object detection by Google.

# Setup

Download the pre-trained model from this drive link:
https://drive.google.com/file/d/1KKpDZZZ8rPr2RrCEIKuzVCxLmZdVG2JM/view?usp=sharing

Unzip this folder in the main folder.
Create 2 new folders: "training_images" and "test_images".

# Dependencies

It is advised to use anaconda virtual environment with python v3.5

use: "pip install -r requirements.txt" to install dependencies.

Create folders named as different terrain types (offroad, freeway etc.) in /training_images folder.
Add at least 10 images in the corresponding folders.
Then add Images to test on, outside of the training dataset in the /test_images folder.

# Training

execute: python retrain.py

# Testing

execute: python test.py
The test images will be classified as per the training.

# Retrain

You can add a larger image dataset to obtain better accuracy for detection.
Run the Retrain script everytime you expand the dataset.

