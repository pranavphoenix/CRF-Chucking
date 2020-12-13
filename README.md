# CRF-Chucking
## Using Conditional Random Fields to Chunk the words in a sentence 

### Algorithm: Gradient descent using l2 regularization 


## Features used:
- Current Word, Previous Word, Previous to Previous Word (word vectors). 50 dimensional Glove vectors.
- Current POS, Previous POS, Previous to Previous POS.
- Previous chunk labels, previous to the current position.
- Morphological features: word stem and word affixes of current word

