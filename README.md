# GloVe (BEST OF TWO WORDLS)
Here we draw co-occurance matrix but the issue with it was very sparse so we need to sort of reduce the dimension of this matrix. 
now here comes the concept of dimensionality reduction technique --- we can use SINGULAR VALUE DECOMPOSITION
A PhD student from CMU, United States, did these experiments-
He used SVD where the matrix is sort of spplited in 3 parts - U, sigma, and (V)transpose. this technique was initialy very famous in the field of Latent Semantic Analysis and Latent Semantic Indexing. In the later part of his experiment he used PEARSON CORELATION. 
HE SHOWED THAT we can get very usefull word out of this technique- he said that there is semantic vectors which are basically linear components in my carefully constructed space.
# Count based vs Direct prediction
# LSA, HAL    -----     skip gram/CBOW
# COALS, Hellinger-PCA                   -----                 NNLM, HLBL, RNN
# fast training                            -----               scales with corpus size 
# efficient usage of statistics           -----                inefficient usage
# primarily used to capture word similarity  -----             generate improved performance on other task
# Disproportionate importance given to large counts   -----    can capture complex patterns beyond word similarity
