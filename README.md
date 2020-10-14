# Name Prediction with RNN using PyTorch

## The Problem

Let’s take a problem of identifying the Country of a person based on their name.

We’ll use RNN for approaching the problem; But instead of word level RNN, we’ll use character level RNN. A character-level RNN reads words as a series of characters – outputting a prediction and “hidden state” at each step like normal RNN architecture.

It’s previous hidden state is fed into each next step. Once all the letters are fed into the network, we take the final hidden state as the output. This output is fed into softmax function to restrict the output values between 0 and 1.

Specifically, we’ll train on a few thousand surnames from different languages of origin, and predict which language a name is from based on the spelling. 

Read the <a href="http://sushtend.com/machine-learning/name-prediction-with-rnn-using-pytorch-part-i/">full blog post</a>
