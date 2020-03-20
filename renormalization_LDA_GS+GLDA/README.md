# Renormalization LDA GS + GLDA

The program contains a procedure of renormalization with three types of selecting topics for merging. To select the type one has to set the value of variable `col_rem_alg`, where

1. Merging of random columns
2. Merging of columns with minimum Kullback-Leibler divergence
3. Merging of coumns with minima local Renyi entropy

To run the program on your data, one needs to upload the results of topic modeling with LDA (Gibbs sampling algorithm) or GLDA (LDA with granulated sampling) in the following format:
Binary file `nw` contains W\*K matrix of counters showing how many times word "w" was assigned to topic "k"; W is the number of unique words and K is the number of topics.
Binary file `nwsum` is a K-vector containing counters which show how many tokens were assigned to topic "k".

Examples of such files are provided for Lenta dataset in the folder `pyRenormalize_Lenta`. 

