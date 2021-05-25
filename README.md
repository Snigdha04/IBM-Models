# IBM-Models

1.	‘assgn3_1.py’ implements the IBM Model 1 and the EM Algorithm.
The alignments are taken as an intersection of the alignments from English to foreign language and from the foreign language to English. As a result, a word can be aligned to multiple words.
2.	 ‘assgn3_2.py’ is used for comparing the alignments obtained from the results of ‘assgn3_1.py’ with the nltk implementations of IBM Model 1 and Model 2.
The alignments from ‘assgn3_1.py’ are used, and the alignments from nltk IBM models are directly obtained using the get_alignment method for each sentence pair.
3.	‘assgn3_3.py’ has the code to extract phrases using the alignments from ‘assgn3_1.py’ and the phrased based translation module from nltk, and then ranks the phrases in decreasing order of probability.
In the end, the corresponding translated word is printed for each extracted phrase.
