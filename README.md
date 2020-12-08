# Sequence-Classification-on-IMDB-dataset-using-LSTM  
A sequence-to-sequence LSTM network enables you to make different predictions for each individual time step of the sequence data.  
The dataset is IMDB movie review sentiment classification dataset, it can be downloaded from: https://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz  
This is a dataset of 25,000 movies reviews from IMDB, labeled by sentiment (positive/negative). Reviews have been preprocessed, and each review is encoded as a list of word indexes (integers).    

Strategy:  
 1. Data loading : (load the dataset and keep the top n words, rest make zero)  
 2. Padding : (pad sequences to a preferred length)  
 3. Model Creation: (create sequential model with 1 LSTM layer)  
