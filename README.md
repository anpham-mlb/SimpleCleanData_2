## Purpose
Using Python Tokenizers to clean the data file
- Normalise tokens to lowercase except the capital tokens appeared in the middle of a sentence/line.
- Tokenize words by using the regular expression "\w+(?:-'\w+)?".
- Return a set of vocabulary with first 200 meaningfull bigrams included in.
- Remove the context-independent and context-dependent stopwords from the vocabulary.
- Remove rare tokens from the vocabulary.
- Stem tokens by using Porter stemmer.
- Remove tokens with the length less than 3 from the vocabulary.
