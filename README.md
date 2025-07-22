# Text Prediction Model

This project implements a simple character-level LSTM model for text prediction. The model is trained on a provided document and can predict the next word based on a given sequence of words.

## Project Structure

The notebook contains the following steps:

1. **Setup:** Installs necessary libraries (nltk).
2. **Data Loading and Preprocessing:**
    - Loads the input text document.
    - Tokenizes the text using NLTK's `word_tokenize`.
    - Builds a vocabulary of unique words in the document.
    - Converts the tokenized text into numerical sequences based on the vocabulary.
    - Pads the numerical sequences to a fixed length.
    - Splits the padded sequences into input (X) and target (y) tensors.
3. **Model Definition:** Defines a simple LSTM model using PyTorch.
4. **Training:**
    - Sets up the training parameters (epochs, learning rate, loss function, optimizer).
    - Trains the LSTM model on the prepared data.
5. **Prediction:**
    - Implements a function to predict the next word given an input text sequence.
    - Demonstrates the prediction function with an example.
6. **Evaluation:**
    - Calculates and prints the accuracy of the trained model on the dataset.

## How to Run the Notebook

1. Ensure you have a Python environment with the required libraries installed.
2. Run each cell in the notebook sequentially.
3. The training process will output the loss per epoch.
4. The prediction section will show an example of how to use the trained model for text prediction.
5. The evaluation section will print the accuracy of the model.

## Dependencies

- torch
- torch.nn
- torch.optim
- numpy
- collections
- nltk

You can install the required libraries using pip:
