# Small Step Toward Image Generation Models
## Overview:
This repository contains a simple image generation model built using the MNIST dataset. The goal of this project is to provide a basic introduction to image generation models with a straightforward architecture.

## Project Description:
The project demonstrates a basic generative model implemented with TensorFlow and Keras. The model uses a simple architecture of dense layers and dropout to generate images from MNIST digits. The dataset used includes handwritten digits from the MNIST dataset, which is widely used for image classification tasks.

## Model Architecture:

### The generative model consists of:
 * __Dense Layers:__ Five dense layers with ReLU and Sigmoid activations to learn and generate image features.  
 * __Dropout Layer:__ Applied to reduce overfitting.  
 * __Layer Normalization:__ Used to normalize activations and improve training stability.  
The model is trained to minimize the Mean Absolute Error (MAE) between generated images and input images.

## Sample outputs:
![Screenshot (168)](https://github.com/user-attachments/assets/e15402e7-91aa-4dd2-8096-b502e1d1bc40)![Screenshot (169)](https://github.com/user-attachments/assets/809515bb-1ddd-441a-b3cc-810f71f8b588)![Screenshot (170)](https://github.com/user-attachments/assets/20561bbc-cbdc-43b7-a7bc-567c22bf921b)![Screenshot (171)](https://github.com/user-attachments/assets/1bab6e8e-46c0-4d29-a6e5-2f122fb462ad)![Screenshot (172)](https://github.com/user-attachments/assets/ecb75748-8b39-4040-ab3e-19274f8c70f1)




