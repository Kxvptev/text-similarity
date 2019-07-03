# text-similarity
Code based on this IPython notebook will analyse a set of sentences and find numbers of sentences, which are most similar to the 0 sentence (numeration from 0).  Presented sentences are transformed to vector space and then cosine distances are calculated. Vector space is stored in a matrix, where number of rows conforms to number of sentences and number of columns conforms to number of all words met in .txt file. i, j - cell of matrix stores number of j-word appearing in i-sentence.
Two sentences, which have the smallest cosine distance with 0 sentence appear in answer.
