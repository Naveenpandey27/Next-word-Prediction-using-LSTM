# Next-word-Prediction-using-LSTM
In this code i have Trained LSTM model for predicting next word

This is a simple Python script for building a Next Word Prediction model using Long Short-Term Memory (LSTM) neural network. The model is trained on a given text file and then used to predict the next words in a sequence based on a seed text.

# Requirements

Python 3.x
TensorFlow 2.x
NumPy
regex

# How to Use
**1** -  Make sure you have all the required libraries installed (you can use pip install tensorflow numpy regex).

**2** - Prepare your text data: Replace the 'pizza.txt' file path with the path to your own text file. The script reads the text file, tokenizes the data, and creates input sequences for the LSTM model.

**3** - Define the model architecture: The script defines a simple LSTM model with an embedding layer and a dense layer with a softmax activation function. Feel free to modify the architecture to suit your needs.

**4** - Train the model: The model is trained on the generated input sequences and target data. You can modify the number of epochs (epochs=500) for training.

**5** - Generate predictions: After training, the script demonstrates how to generate next word predictions given a seed text. Modify the seed_text and next_words variables to customize the predictions.

# Customization

You can customize this script for your own text data and experiment with different model architectures to achieve better performance. Here are some possible improvements:

**1** - Use a larger dataset for training to improve the model's language understanding.
**2** - Tune hyperparameters such as the embedding dimension, LSTM units, and batch size to optimize performance.
**3** - Experiment with more advanced language models like Transformer or GPT-based models.
Please note that this current implementation is for educational purposes and may not be optimized for large-scale or production use. For production-level applications, consider using more advanced language models and preprocessing techniques.
