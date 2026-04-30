# Image Caption Generator using CNN + RNN

## Project Overview

This project is an Image Caption Generator built using Deep Learning.

The system takes an input image and automatically generates a meaningful text caption describing the image.

The project uses:

* CNN for image feature extraction
* RNN (SimpleRNN) for sequence generation
* VGG16 for image understanding
* Flickr8k Dataset for training

This project is developed using Google Colab and Python.

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Pillow
* tqdm

---

## Deep Learning Model

### CNN + RNN Architecture

### CNN Part

VGG16 is used as the Convolutional Neural Network (CNN) model.

It extracts important image features from the input image.

Image → Feature Vector

---

### RNN Part

SimpleRNN is used for caption generation.

It generates words one by one based on the image features.

Feature Vector + Word Sequence → Caption

---

## Dataset Used

### Flickr8k Dataset

The Flickr8k dataset contains:

* 8,000 images
* 5 captions for each image
* Real-world image descriptions

It is commonly used for Image Captioning projects.

---

## Project Workflow

1. Upload Dataset
2. Load Captions File
3. Clean Text Data
4. Extract Image Features using VGG16
5. Create Tokenizer
6. Build Vocabulary
7. Create RNN Model
8. Train the Model
9. Save the Model
10. Upload New Test Image
11. Generate Caption

---

## Example Output

### Input Image

Dog playing with a ball

### Generated Caption

A dog is playing with a ball

---

## Why RNN?

RNN is used because image caption generation is a sequential problem.

Words are generated one after another, so RNN helps learn sequence dependency between words.

---

## Why VGG16?

VGG16 is a powerful pre-trained CNN model.

It helps extract strong image features and improves caption generation performance.

---

## Training Details

* Optimizer: Adam
* Loss Function: Categorical Crossentropy
* Epochs: 30
* Dataset: Flickr8k
* Model Type: CNN + RNN

---

## Future Improvements

The project can be improved using:

* LSTM
* GRU
* Attention Mechanism
* Transformer Models
* Larger datasets like MS COCO

---

## Author

Third Year Deep Learning Project

Image Caption Generator using CNN + RNN

---

## GitHub Repository Name

image-caption-generator-rnn
