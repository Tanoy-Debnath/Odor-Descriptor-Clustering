This Repository is a part of the below paper that was published in Plos One (2020) and it was related to odor Descriptors Clustering using odor descriptors of chemical mixtures such as essential oils.


Debnath T, Nakamoto T (2020) Predicting human odor perception represented by continuous values from mass spectra of essential oils resembling chemical mixtures. PLoS ONE 15(6): e0234688. https://doi.org/10.1371/journal.pone.0234688


1) Pretrained FastText model was used to make cosine similarity matrix of odor descriptors.
2) Odor Descriptor Hierarchical clustering using cosine similarity matrix from Fast-Text model --MATLAB Code
Descriptions: After creating the cosine similarity matrix (adj file) using Fast-Text, then use that one to load in this MATLAB code (I renames it as Fast_text_similarity_matrix.csv) to create the hierarchical clustering. It will provide you a vertical Dendrogram of Hierarchical clustering.
