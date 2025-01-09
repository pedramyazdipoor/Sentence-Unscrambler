## Sentence Unscrambler

In this project we use 560k pairs of persian sentences. We only use sentences which have a maximum of 10 words.\
We scrambled them randomly as inputs of our model.\
Our model is a sequence to sequence model in which the encoder is 1-D CNN and the decoder is GRU.\
We used teacher forcing during the training phase.\
During Inference, the words that are present in the input are not considered.
