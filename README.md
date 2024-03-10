# Sci-Bert
Novel Machine Learning algorithm "Sci-Bert", for generating BERT based embedding to check temporal evolution of linguistics in Academia.

Sci-Bert, uses BERT, a transformer based word embedding approach, to investigate the changing dynamism of keywords with contextual awareness. The main contribution of this report is to examine the contextual dependence/independence of keywords in scientific literature.


The embeddings are generated in such a way that, each sentence (context), a word appears in, is taken into consideration. This helps to generate contextual embeddings, in a manner that preserves the semantic information of the keyword of interest. 

The generated embeddings are modelled using K-nearest neighbour (K-NN) to explore the changing neighbourhoods. The changing neighbourhood of words over time helps to identify the dynamism of the domain of interest (keyword) in a temporal fashion.
