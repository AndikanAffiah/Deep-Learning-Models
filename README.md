# Deep Learning Models

Here I will host Deep Learning models I have built and used for various tasks. A quick overview of my models:

### Text Analysis

All the models here use Word Embeddings. One can input their own embeddings, like FastText/GloVe/Word2Vect/etc. After the embeddings layer there is a `SpatialDroupout1D`/`Dropout` layer. Below I note the main model characteristics after the dropout layer:

* `cnn`: A `Conv1D` layer.
* `gru`: A bidirectional GRU layer with poolings (average and max).
* `gru_cnn`: A bidirectional GRU followed by a Convolutional layer poolings (max).
* `gru_double`: Two bi-GRU layers followed by poolings (avg and max).
* `lstm`: An LSTM layer.
* `lstm_cnn`: An LSTM layer followed by a Convolutional layer and a layer of poolings (avg and max).
