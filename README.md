# Handwritten Text Generation using Character-Level RNN

## 📌 Project Overview

This project focuses on generating text using a **character-level Recurrent Neural Network (RNN)**. The model learns patterns from a text dataset and generates new text based on the learned character sequences.

## 🎯 Objective

The main objective is to implement a character-level neural network that can learn text patterns and generate new text.

## 📂 Dataset

The project uses an English text dataset for training the character-level model.

The text is processed character by character to create input sequences and target characters.

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* TensorFlow
* Keras
* Jupyter Notebook

## 🔄 Project Workflow

1. Load the text dataset
2. Read and preprocess the text
3. Create a character vocabulary
4. Convert characters into numerical representations
5. Create input sequences and target characters
6. Build a character-level RNN/LSTM model
7. Train the model on the text data
8. Generate new text using the trained model

## 🤖 Model

A character-level recurrent neural network is used to learn the patterns and relationships between characters in the training text.

The trained model can generate new text by predicting the next character based on previously generated characters.

## 📊 Result

The trained model is capable of generating new text based on the patterns learned from the training dataset.

## 💾 Saved Model

The trained model is saved as:

`character_lstm_model.h5`

## 💡 Conclusion

This project demonstrates how Recurrent Neural Networks can be used for character-level text generation. The model learns patterns from the provided text and uses them to generate new sequences of text.
