# Image Caption Generator

## Project Overview
This project is an **Image Caption Generator** that utilizes deep learning techniques, including **Convolutional Neural Networks (CNNs)** and **Long Short-Term Memory (LSTM) networks**, to automatically generate descriptive captions for images. The system is implemented using Python and leverages pre-trained models for feature extraction and caption generation.

## Features
- Extracts features from images using **Xception CNN model**.
- Generates captions using an **LSTM-based RNN**.
- Utilizes **Flickr8K dataset** for training.
- Implements **data preprocessing and tokenization**.
- Uses **TensorFlow and Keras** for deep learning.

## Technologies Used
- **Programming Language**: Python
- **Deep Learning Frameworks**: TensorFlow, Keras
- **Image Processing**: PIL (Python Image Library)
- **Data Handling**: NumPy, Pandas
- **Dataset**: Flickr8K

## Project Structure
├── dataset/ # Contains training images ├── models/ # Trained models ├── captions.txt # Processed image captions ├── features.p # Extracted image features ├── tokenizer.p # Tokenized vocabulary ├── training_caption_generator.ipynb # Jupyter notebook for training ├── testing_caption_generator.py # Script for caption generation ├── README.md # Project documentation

