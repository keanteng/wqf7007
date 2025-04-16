what is part of speech
- words grouped into categories based on their function

the main parts of speech
- noun
- verb
- adverb
- adjective
- preposition
- interjection
- pronoun
- conjunction

what is pos tagging
- assign a part of speech to each word in a sentence
- to improve accuracy of other nlp tasks
- used in text classification and information extraction

why pos tagging
- label named entities like people or organization
- reveal about relationship between words
- support syntactic parsing (analyze sentence structure)

opened class example
- adjective, adverb, noun, verb, proper noun, interjection

closed class example
- adposition, auxiliary, coordinating conjunction, determiner, numeral, particle, pronoun, subordinating conjunction

other class example
- punctuation
- symbols

what is open class words
- content words
- word that carry meaning

what is closed class words
- function words
- words that serve a grammatical purpose

pos-labeled corpora
- brown corpus
- wsj corpus
- switchboard corpus

why tagging is challenging
- word are ambiguous may have more than one possible part of speech
- need to determine the correct tag for a specific word in context

pos tagging
- generative approach (hmm tagging)
    - hidden markov model
    - learn probability of tag sequence, use algorithm to find best tag sequence and probabilities and memory of what came before
- discriminative approach (crf tagging)
    - conditional random field
    - learn how to distinguish correct and incorrect tags directly
    - use many features like current words, surrounding words, previous tags and so on