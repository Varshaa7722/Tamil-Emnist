# Tamil-Emnist
Handwritten Tamil Character Recognition using CNN


This project focuses on the development of an intelligent system capable of recognizing handwritten Tamil characters using deep learning techniques.

A custom dataset of Tamil letters was created from scratch, consisting of binary (black and white), 64x64 pixel images, with each character augmented to improve generalization.

The dataset was structured in an EMNIST-style format, organized by character class, and preprocessed using image cleaning techniques such as:

1. Background inversion (white to black)
2. Binarization and thresholding
3. Cropping to bounding boxes
4. Centering and resizing characters on a canvas

state-of-the-art model that was trained:

Convolutional Neural Network (CNN) — for fast and efficient recognition


The final system was tested with a live demo interface in Google Colab, allowing real-time image upload and character prediction with high accuracy.


NOTE: This model works only on handwritten dataset
The dataset can be found in https://www.kaggle.com/datasets/varshaa07/tamil-character-dataset

AUTHOR: VARSHAA
