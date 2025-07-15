# SMS Spam Classifier

This project implements a machine learning model to classify SMS messages as **ham** (normal) or **spam** (advertisement) using deep learning techniques in Python with TensorFlow and Keras.

---

## Project Overview

- **Dataset:** SMS Spam Collection dataset (train and validation splits)
- **Model:** Bidirectional LSTM neural network with embedding and dropout layers
- **Goal:** Accurately detect spam messages from SMS text data
- **Approach:** 
  - Preprocess text messages with tokenization and vectorization
  - Train the model using binary cross-entropy loss and Adam optimizer
  - Use early stopping to prevent overfitting
  - Evaluate model on sample test messages to verify performance

---

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/sms-spam-classifier.git
   cd sms-spam-classifier
