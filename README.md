# RNN-CLASSIFYING-NAMES-WITH-A-CHARACTER-LEVEL-
CLASSIFYING NAMES WITH A CHARACTER-LEVEL  using Recurrent Neural Network

I am building and training a basic character-level RNN to classify words. 
A character-level RNN reads words as a series of characters - outputting a prediction and “hidden state” at each step, feeding its previous hidden state into each next step. We take the final prediction to be the output, i.e. which class the word belongs to.

Specifically, The model is trained on a few thousand surnames from 18 languages of origin, and predict which language a name is from based on the spelling.
You can also check https://pytorch.org/tutorials/intermediate/char_rnn_classification_tutorial.html.

It would also be useful to know about RNNs and how they work:

[The Unreasonable Effectiveness of Recurrent Neural Networks](https://karpathy.github.io/2015/05/21/rnn-effectiveness/) shows a bunch of real life examples

[Understanding LSTM Networks](https://colah.github.io/posts/2015-08-Understanding-LSTMs/) is about LSTMs specifically but also informative about RNNs in general
