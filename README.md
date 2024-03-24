# DS_Hw11

This code snippet performs sentiment analysis on the IMDB movie review dataset using different recurrent neural network (RNN) architectures: Simple RNN, LSTM, Bidirectional LSTM, and Deep RNN. 

1. It loads the IMDB dataset, preprocesses the data, and pads/truncates sequences to a fixed length.
2. Constructs four different RNN models with varying architectures.
3. Trains each model on the training data and evaluates their performance on the validation set.
4. Finally, it visualizes the training and validation accuracy as well as the training and validation loss for each model using matplotlib.