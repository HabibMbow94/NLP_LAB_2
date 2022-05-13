# LAB 2 NEATURAL LANGUAEG PROCESSING: WORD VECTORS

## CLONE

```
git clone https://github.com/HabibMbow94/NLP_LAB_2.git
```

# COLAB LINK


[NLP_LAB2.](https://colab.research.google.com/drive/1JkEcAVqfXz8Am09UIZetzwFSF-o00-xB#scrollTo=6UpvOsb5_0ap&uniqifier=1)


# STRUCTURES OF THE LAB

* cosine(u,v): function computes the cosine similarity between vectors u and v
* nearest_neighbor(x, word_vectors, exclude_words=[]); function returns the word corresponding to nearest neighbor vector of x
* knn(x, vectors, k): function return the words corresponding to the K nearest neighbors of vector x
* analogy(a, b, c, word_vectors): function return the words d, such that a:b and c:d verifies the same relation
* association_strength(w, A, B, vectors): function compute the association strength between a word w - two sets of attributes A and B
* weat(X, Y, A, B, vectors): fonction compute Perform the word embedding association test between two sets of words X and Y and two sets of attributes A and B
* load_lexicon(filename): function will load the small English-French bilingual lexicon
* align(word_vectors_en, word_vectors_fr, lexicon): function will learn the mapping from English to French
* translate(word, word_vectors_en, word_vectors_fr, mapping): function will translate the English word to French.
* evaluate(valid, word_vectors_en, word_vectors_fr, mapping): function to evaluate this method on the validation lexicon
