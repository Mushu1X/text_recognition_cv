# OCRNet - Optical Character Recognition Model

## Project Overview
OCRNet is a deep learning-based Optical Character Recognition (OCR) model developed using PyTorch. This project is designed to recognize alphanumeric characters from images using convolutional neural networks (CNN). The model can recognize 62 different classes, including digits (0-9), uppercase letters (A-Z), and lowercase letters (a-z).


## Prerequisites
- Python 3.x
- PyTorch
- OpenCV
- Matplotlib
- Torchvision

Ensure you have all the required libraries installed. If not, you can install them using:
```bash
pip install torch torchvision opencv-python matplotlib

## Dataset
/data/
    /EnglishFnt/
        /Sample001/
            img001-00001.png
            img001-00002.png
            ...
        ...


Model Architecture
The model architecture for OCRNet consists of the following components:

Two Convolutional Layers: To extract features from the input images.
ReLU Activations: To introduce non-linearities.
Fully Connected Layer: To classify the input features into one of the 62 classes.
