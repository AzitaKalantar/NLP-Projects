### version1_embedded_rnn :
in this version of the code I used a pretrained embeddeding named [GloVe](https://nlp.stanford.edu/projects/glove/) as the initial weights for my embedding layer.I also used a GRU layer as my RNN layer to give an importance to the sequence of words rather than just the exsistance of words in each text.

Accuracy : 68.36

### version2_tf_idf_nn : 
In this version, instead of an embedding layer, I use tf-idf to encode the words, Then I pass each text to a simple neural network model

Accuracy : 67.98

### version3_BERT_Transformer : 
In this version, I used a pretrained bert model and fine tuned it for my problem

Accuracy : 71.22
