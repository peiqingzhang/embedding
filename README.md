# Embedding

Finding the nearest neighbours for the song tracks and visualize their given embeddings, based on two datasets:

- embeddings.txt: the raw embeddings track embeddings from a Word2Vec model. The first row contains the number of the rows in the file and the dimensionality of the embeddings. For the remaining rows the first item contains the trackId and the remaining elements make up the embeddings

- metadata.csv: metadata for each track in embeddings.txt
