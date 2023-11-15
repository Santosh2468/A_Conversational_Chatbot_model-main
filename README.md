# Building A Conversational Chatbot by Seq2Seq Approache

*Seq2seq* turns one sequence into another sequence (sequence transformation). It does so by use of a recurrent neural network (RNN) or more often LSTM or GRU to avoid the problem of vanishing gradient. The context for each item is the output from the previous step. The primary components are one encoder and one decoder network. The encoder turns each item into a corresponding hidden vector containing the item and its context. The decoder reverses the process, turning the vector into an output item, using the previous output as the input context.[[wikipedia]](https://en.wikipedia.org/wiki/Seq2seq)

## Aim of the project 
is to build an intelligent conversational chatbot, Riki, that can understand complex queries from the user and intelligently respond.

## the dataset used 

[Cornell Movie-Dialogs Corpus](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html) is a large metadata-rich collection of fictional conversations extracted from raw movie scripts. (220,579 conversational exchanges between 10,292 pairs of movie characters in 617 movies).


## References 
- https://blog.keras.io/a-ten-minute-introduction-to-sequence-to-sequence-learning-in-keras.html
- https://arxiv.org/pdf/1508.04025.pdf
