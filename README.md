# IR2022_A1_62
 Assignment-1 for the course CSE508:Information Retreival


IR Assignment-1
Samyak Jain (2019098) and Sarthak Johari (2019099)

Q1 
Preprocessing :
After extracting the text from the files we performed the following preprocessing steps on the text to convert them into valid tokens which would be later used in making the unigram inverted index data structure.

First we converted the text to lowercase. 
Text tends to have the shortened form of a combination of two words For Example “I will” is written as “I’ll” to fix this issue we have fixed the contractions from the text.
We then performed tokenization on the text
Only alphanumeric tokens were kept and the rest were discarded.
We then removed all the stopwords from our tokens.
Punctuations were removed from the tokens and finally we had our valid sets of tokens.







