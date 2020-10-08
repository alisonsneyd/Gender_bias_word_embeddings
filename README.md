# Gender_bias_word_embeddings

The repository contains code to replicate the experiments in the paper "Robustness and Reliability of Gender Bias Assessment in Word Embeddings: The Role of Base Pairs", by Haiyang Zhang, Alison Sneyd and Mark Stevenson, AACL 2020 (https://arxiv.org/abs/2010.02847v1).

To run the notebook bias_embeddings_paper_code.ipynb, a copy of the word2vec embeddings GoogleNews-vectors-negative300.bin (available at https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit) should be placed in the input_data folder.
Some of the files in the input_data folder were sourced from https://github.com/tolga-b/debiaswe and http://www.fit.vutbr.cz/~imikolov/rnnlm/word-test.v1.txt.


Requirements: \
Python=3.7.6\
pandas=1.0.1\
numpy=1.18.1\
sklearn=0.22.1\
gensim=3.8.3\
json=2.0.9\
matplotlib=3.1.3\
re=2.2.1
