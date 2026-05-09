# Handwritten Digit Recognition – Neural Network Model

## Overview

**What was the goal?**
Built and trained a fully-connected neural network to recognize handwritten 
digits (0-9) from images. The model was trained on the MNIST dataset and tested 
on two custom handwritten digit test sets, one easier and one harder to read.

**What tools and model were used?**
Python, PyTorch, torchvision. Built a fully-connected network (no CNN) with 
three linear layers (784 -> 128 -> 64 -> 10), trained using SGD optimizer and 
CrossEntropyLoss over 10 epochs on 60,000 MNIST training images.

**What was achieved?**
Achieved over 80% accuracy on the MNIST training set. Applied data 
augmentation techniques including random affine transformations, rotation, 
translation, and scaling to improve the model's ability to generalize to 
real handwriting. Normalized inputs using MNIST mean (0.1307) and standard 
deviation (0.3081) for stable training.

## Tools Used
Python, PyTorch, torchvision, numpy, matplotlib

## Files
- Fatima_Afzal_Day_3_IOAI_Take_Home_Challenge.ipynb — main notebook
- trained_model.pth — saved model weights