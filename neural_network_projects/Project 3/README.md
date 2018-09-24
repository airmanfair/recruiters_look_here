# Assignment 3 Description
In this assignment, you will learn more about vector space models of semantics (specifically, word embeddings), attention in the context of machine translation, and memory networks. The goals of this assignment are as follows:

- Understand and implement two predictive methods for learning word embeddings.
- Solve two semantic tasks using pretrained word embeddings.
- Implement several methods for attention in neural machine translation.
- Implement an end-to-end memory network for QA.

## Q1: Word Embeddings (30 points)
The Jupyter notebook word_embeddings_tf.ipynb will walk you through implementing two methods for learning word embeddings. You will implement both and test your implementations by visualizing the learned embeddings with t-SNE. The notebook will also present a word similarity task and an analogy task, both of which you will solve using pretrained word embeddings.

## Q2: Attention & Machine Translation (40 points)
The Jupyter notebook machine_translation_and_attention_tf.ipynb will walk you through implementing an LSTM cell that uses attention for the decoder of an NMT model, as well as three different methods for implementing the attention computation. You will test your implementations by training the models.

## Q3: Memory Networks (30 points)
The Jupyter notebook memory_networks_tf.ipynb will walk you through implementing the MemN2N model. You will test your implementation by training the model on the babi question answering (QA) task.