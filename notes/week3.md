why vectorization
- computers can only process numbers
- converting to numbers support analysis by ML models

how do we do that
- traditional count based method >>> BOW, TFIDF
- prediction based word embeddings >>> Word2Vec, GloVe
- contextualized word embeddings >>> ELMO, BERT

word vectorization
- bag of words
    - represent text doc as vector of word counts
- tf idf
    - stat method to evaluate the importance of a word in a document relative to a collection like corpus
    - adjust the word weigth based on how frequently appears across multiple documents

limitation of count based methods
- lack semantics and do not consider relationship between words
- ignores word order
- high dimensional vectors as vocab size grows, vectors become sparse and inefficient

predictive based word embeddings (static)
- word 2 vec
    - learn word meanings based on context
    - predict the target word based on surrounding context words >>> continuous BoW
    - predict surrounding context words given target words >>> skip-gram
- glove (global vectors for word representation)
    - unsupervised approach to obtain vector representation of words
- fasttext
    - extension of word2vec developed by fb
    - incorporates subword info for more effective morphologically rich language

> assign a fixed vector to each word

contextualized word embeddings
- generate different representations for a word based on its context
- generate embeddings dynamically during inference
- capture semantic relationship more effectively

example
- elmo (embeddings from language models)
    - generate word representation that change based on sentence context
- transformer based model
    - self attention mechanisms to process entire sequences at once
    - handle complex linguistic patterns more effectively
    - flexible for different nlp applications
- bert (bidirectional encoder representations from transformers)
    - learns word representations by looking at both left and right context


what can we learn
- Contextualized word embeddings have transformed NLP by 
allowing models to understand words in their correct context.
- ELMo introduced bidirectional LSTMs, improving performance on 
various linguistic tasks. 
- Transformer-based models like BERT further advanced NLP by capturing deeper semantic meanings and handling long-range dependencies