# Stastical-Language-Modelling-using-N-gram

Using Natural Language Processing, this model predicts the most probable next word and outputs the correctness of an input English sentence. To achieve the optimum accuracy, a large reliable dataset or corpus is extracted from Wikipedia, preprocessed, and then analyzed before using it to train the model.

The Markov Chain concept can be visualized here. Since the probabilities of each word depends on the previous words, a markov chain can be seen here. To account for edge cases, techniques like Laplace Smoothing or Add-one method.

Analyzing the dataset and its visualization can be an insightful technique to understand the corpus before using it for the model's training. Choosing an appropriate model for any problem is a crucial step. In our case, using a trigram model to train the data proved to be the best trade-of. This trained model is finally used in the code to predict the next word and find the perplexity of a given sentence based on the trigram model. 

