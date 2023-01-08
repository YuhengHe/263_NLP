# 263_NLP
We realized the importance to cluster different news of the same topics together, especially in a multilingual setting. In this project, we designed a model that can rate the similarities of two pieces of news, regardless of the languages used, in a 4-point scale. This model is trained on the data we crawled from different websites and is fine-tuned using a corresponding pre-labeled score sets. The main tasks of our projects are data crawling, data cleaning, word embedding, model training, and predicting. We also fine-tuned our model for better performance.
##Network
1. Convolutional Neural Network (CNN)
2. Recurrent Neural network (RNN)
3. Support Vector Machine (SVM) poorly performed.
##Functions
1. Data Crawling - extract a large amount of data using news links from different websites
2. Data Pruning - clean the dataset and eliminate unwanted entries such as HTML artifacts and spam links
3. Word Embedding - transform textual data to vector-like data for similarity processing
4. Neural network Classification
