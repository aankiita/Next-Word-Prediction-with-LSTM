# Next-Word-Prediction-with-LSTM

This project is a Next Word Prediction application built using an LSTM (Long Short-Term Memory) neural network and Streamlit. The app allows users to enter a sequence of words, and it predicts the most likely next word based on the input. The input text is first converted into numerical tokens using a pre-trained tokenizer, and the sequence is padded or trimmed to match the LSTM model’s input length. The LSTM model then predicts probabilities for the next word, and the word with the highest probability is displayed as output. The system uses a trained model (next_word_lstm.h5) and tokenizer (tokenizer.pickle) to perform predictions. This project provides an interactive web interface for users to experiment with next-word predictions and is a practical demonstration of using LSTM networks for natural language processing tasks.

live demo-- "https://ann-classification-churn-w6c5spkt6srkm5tjpndd9q.streamlit.app/"
