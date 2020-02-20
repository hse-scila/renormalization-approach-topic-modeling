The file Renormalization_plsa.ipynb contains an algorithm of renormalization with three types of selecting topics for merging.

To run the program, one needs to upload the results of topic modeling with pLSA.
Matrix Phi (distribution of words by topics) should be stored in a txt-file. An example of such txt-file is provided: `Lenta_100topics_plsa.txt` contains matrix Phi. 
 
By default, pairs of topics with minimal local Renyi entropy are selected.
To use another principle of merging, one needs to uncomment the necessary method.  
