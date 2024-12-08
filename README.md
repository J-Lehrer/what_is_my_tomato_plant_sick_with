# What Is My Tomato Plant Sick With

This project is a part of the AAI-521 course in the Applied Artificial Intelligence Program at the University of San Diego (USD).

--Project Status: [Completed]

## Installation

To use this project you can either clone the repo on your device using the command below:

git init

git clone https://github.com/J-Lehrer/what_is_my_tomato_plant_sick_with.git

Or you can download and unzip the completed model directly which is called:

tomato_disease_model-20241125T225856Z-001.zip

## Project Intro/Objective

The main purpose of this project is to create code of an image classifier model that will be able to take an image of a tomato plant leaf and give an output of the most likely type of sickness (if any) that the plant has out of 10 sicknesses. 

### Partners/Contributors

* Jeffrey Lehrer
* Gurleen Virk
* Kay Cheung

### Methods Used

* Transfer Learning
* Computer Vision
* Data Visualization
* Data Manipulation
* Machine Learning

### Technologies

* Python
* Jupyter Notebook

## Project Description

The main purpose of this project was to make a lightweight model that would be usable in a mobile application to detect what sickness a tomato plant had based on a picture of a leaf.

### Dataset

Dataset kaggle URL: https://www.kaggle.com/datasets/ashishmotwani/tomato

Description of dataset from kaggle:

Tomato Leaf Disease Classification
Over 20k images of tomato leaves with 10 diseases and 1 healthy class. Images are collected from both lab scenes and in-the-wild scenes. The goal is to develop a lightweight model that can predict tomato leaf diseases & deploy it offline on a mobile app.

Classes:

 * Late_blight
 * healthy
 * Early_blight
 * Septorialeafspot
 * TomatoYellowLeafCurlVirus
 * Bacterial_spot
 * Target_Spot
 * Tomatomosaicvirus
 * Leaf_Mold
 * Spidermites Two-spottedspider_mite
 * Powdery Mildew

## License

MIT License

Copyright (c) [2024] [Jeffrey Lehrer], [Gurleen Virk], [Kay Cheung]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Acknowledgments

We would like to thank Professor Saeed Sardari as well as all of those who contributed to machine learning before us allowing us to complete this project.

Additionally the code to set up the transfer learning base from the MobileNetV2 model was found at:

https://kshitijkutumbe.medium.com/building-an-image-classification-model-with-transfer-learning-in-tensorflow-4ab203783ec9

Similarly the code which was used as reference for the additional model layers was found at:

https://clemsonciti.github.io/rcde_workshops/python_deep_learning/07-Convolution-Neural-Network.html
