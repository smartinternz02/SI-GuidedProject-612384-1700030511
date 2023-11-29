# Fake Logo Detection

## Team Information

- **Team ID:** Team-592815
- **Team Size:** 4
- **Team Members:**
  - Devesh B
  - Challa Anudeep Reddy
  - Vitta Vishnu Datta
  - Praneeth Kasanagottu

# Fake/Real Logo Detection using Deep Learning

## Overview

The purpose of this project is to develop a system that can automatically analyze visual characteristics and patterns in logo images, enabling the classification of logos as either genuine or fake. The project utilizes Convolutional Neural Networks (CNNs), with a focus on the VGG19 architecture. VGG19 comes with pre-trained layers, offering a profound understanding of image features such as shape, color, and structure.

## CNN Architecture

The CNN architecture is a combination of layers designed to transform an image into an output that the model can comprehend. The process of fake/real logo detection involves forward and backward propagation, iterating through all training samples in the network until optimal weights are determined. This ensures that only the most powerful and predictive neurons are activated to make a prediction.

## Deployment

To deploy the model, Flask, a Python web framework, is employed. Flask provides a straightforward way to deploy machine learning models as web applications. The model is loaded into the Flask application, allowing users to upload an image to the web application. The image is then passed through the model, and the result is displayed on the web page. Flask also facilitates hosting the web application on a server, making it accessible from anywhere.

## Usage

- Clone the repository:

  ```bash
  git clone https://github.com/smartinternz02/SI-GuidedProject-612384-1700030511.git

## Demo

Check out a live demo of our Fake/Real Logo Detection system:

[Demo Link](https://drive.google.com/file/d/1vvCi-ACiyc_CWmyXwxyw14GgWTRuEw2G/view)
