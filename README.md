# Next Word Prediction using Recurrent Neural Networks (RNN)

## Assignment Project

---

## Project Description

This project focuses on building a **Next Word Prediction Model** using a Recurrent Neural Network (RNN).
The model learns from a text dataset and predicts the next word based on the previous words in a sentence.

Next-word prediction is an important task in **Natural Language Processing (NLP)** and is used in applications like:

* Text suggestion
* Chatbots
* Search engines
* Smart keyboards

---

## Objective

The main objectives of this project are:

* To understand how sequential data works
* To implement an RNN model
* To preprocess text data
* To train the model for prediction
* To study long-term dependency problems

---

## Dataset

The dataset used in this project is a **Shakespeare text dataset**.
It contains many lines of English text that help the model learn word patterns.

Example:

```
To be or not to be
```

---

## Steps Involved in the Project

1. Download the dataset
2. Load the dataset
3. Convert text into tokens
4. Create input sequences
5. Apply padding
6. Split data into input and output
7. Build the RNN model
8. Train the model
9. Predict the next word

---

## Tools and Technologies

* Python
* TensorFlow / Keras
* NumPy
* Google Colab / Jupyter Notebook

---

## Model Architecture

The model consists of the following layers:

* Embedding Layer
* SimpleRNN Layer
* Dense Layer

These layers help the model understand the sequence of words.

---

## Example Prediction

Input:

```
to be or
```

Output:

```
not
```

---

## Project Files

```
next-word-prediction-rnn
│
├── README.md
├── next_word_prediction.ipynb
├── input.txt
└── report.pdf
```

---

## Future Improvements

* Implement LSTM model
* Implement GRU model
* Improve accuracy
* Train the model on larger datasets

---

## Conclusion

This project demonstrates how a Recurrent Neural Network can be used to predict the next word in a sentence. It also helps in understanding how deep learning models handle sequential text data.

---



