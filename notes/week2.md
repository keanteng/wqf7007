what is tokenization
- break up a stream of text into words, phrases or symbols and other meaningful elements

the types
- tokenization
- sentence segmentation
- word tokenization

what problems will we face
- punctuation >>> Phd.
- compound words >>> James Bond
- abbraviations >>> MAGA

how to preprocess
- lower case
- remove noise
- remove stopwords
    - remove low information words from text
    - save computing time and efforts in large volume text processing
- stemming and lemmatization

what is stemming
- converts a word into its stem
- process of obtaining the root word from a given word by elimiting its affixes

what is lemmatization
- consider the context and converts the word to tis meaningful base form

what is morphology
- study of word structure and word formation processes

what is morpheme
- small meaningful units that make up words -- minimal unit of meaning
- un happy ness
    - un (prefix) + happy (root) + ness (suffix)

types
- inflectional morphology
    - predictable changes a word undergoes as a result of syntax like singular to plural
- derivational morphology
    - may and may not affect a word parts of speeech of meaning like add suffix
    - active to activity
- non cancatenative morphology
    - morphemes are combines in more complex ways through non linear process by modifying internal structure of morphemes
    - Arabic language

why we need morphological analysis
- large vocabulary system has problem in representing lexion
- large number of words
- inflectional forms of a word
- derivational forms of a word
- open clas words >>> nouns, verbs, adjectives, adverbs
- closed class words >>> pronouns, prepositions, conjunctions, determiners, auxiliary verbs

stemmer
- s stemmer >>> convert plural to singular
- porter stemmer >>> remove suffixes from words

text normalization
- replace non standard tokens that carry significant menaings with context appropriate standard words
- 2morr, 2morrow >>> tomorrow
- 2day, 2day >>> today

two ways to normalize
- dictionary based
- statistical machine translation