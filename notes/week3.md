word vectorization
- bag of words
    - represent text doc as vector of word counts
- tf idf
    - stat method to evaluate the importance of a word in a document relative to a collection like corpus

limitation of count based methods
- lack semantics
- ignores word order
- high dimensional vectors

predictive based word embeddings (static)
- word 2 vec
    - learn word meanings based on context
- glove
    - unsupervised approach to obtain vector representation of words
- fasttext
    - extension of word2vec developed by fb

> assign a fixed vector to each word

contextualized word embeddings
- generate embeddings dynamically during inference

example
- elmo
    - generate word representation that change based on sentence context
- transformer based model
    - self attention mechanisms to process entire sequences at once
- bert
    - learns word representations by looking at both left and right context


what can we learn
- Contextualized word embeddings have transformed NLP by 
allowing models to understand words in their correct context.
- ELMo introduced bidirectional LSTMs, improving performance on 
various linguistic tasks. 
- Transformer-based models like BERT further advanced NLP by capturing deeper semantic meanings and handling long-range dependencies