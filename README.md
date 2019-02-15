# DeepTranslate

A simple neural translation model that functions on an encoder-decoder architecture. The goal of this project was to create a neural network that can translate between multiple languages with acceptable accuracy. I plan to create an application that will use the model to translate text on a page, specifically my school's home website. I decided to undertake this endaevor because I wanted to garner experience in programming neural networks.

The model is programmed in python

My general procedure is as follows:

* retrieve text file
* tokenize text
* create text index
  * create dictionary
* create word embeddings -> vectorize text


* create encoder-decoder model
 *  connected lstm (RNN)
 * pass vector representations through the model
