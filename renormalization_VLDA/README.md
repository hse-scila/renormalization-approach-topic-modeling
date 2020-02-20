The file Renormalization_VLDA.ipynb contains an algorithm of renormalization with three types of selecting topics for merging.

To run the program, one needs to upload the results of topic modeling with LDA (variational E-M algorithm).
Matrix Phi (distribution of words by topics) and vector alpha (T-dimensional parameter of the Dirichlet prior on distribution of topics by documents) should be stored in csv-files. Examples of such csv-files are provided: `lenta_vlda_100topics_alpha.csv` contains the values of vector parameter alpha; `lenta_vlda_100topics_phi.csv` contains matrix Phi. 
 
By default, pairs of topics with minimal local Renyi entropy are selected.
To use another principle of merging, one needs to uncomment the necessary method.  
