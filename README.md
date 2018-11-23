# Text classification with PyTorch and torchtext

This notebook shows how to use [torchtext](https://github.com/pytorch/text) and [PyTorch](https://pytorch.org/) libraries to retrieve a dataset and build a simple RNN model to classify text.

It is based on the TREC-6 dataset, which consists on 5,952 questions written in English, classified in the following categories, depending on their answer:

* HUM: Human
* DESC: Description
* ABBR: Abbreviation
* LOC: Location
* NUM: Number
* ENTY: Entity

### Further exercises
Try improving the performance of the model by:

* Adding more complexity (RNN layers, other layers)
* Add regularisation (L1, L2, dropout)
* Make the model a bidirectional RNN
* Use pretrained embeddings such as word2vec or GLOVE. Note that you can use: nn.Embedding.from_pretrained(...)
