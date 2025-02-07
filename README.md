# embeddings
### What are embeddings ?
Embeddings are representations of values or objects like text, images, and audio that are designed to be consumed by machine learning models and semantic search algorithms. They translate objects like these into a mathematical form according to the factors or traits each one may or may not have, and the categories they belong to.

### What types they can be ?
**Text Embeddings**:
* Word Embeddings (words to vectors)
* Sentence Embeddings (sentences to vectors. more subtle nuances of language can be captured)
**Image Embeddings**:
* CNN (images to vectors. e. g. can be used for classification problems or to generate a new one)
* Autoencoders (compress image to dense vector representation)
**Other types of Embeddings**:
* Graph Embeddings (recommendation systems)
* Sequence Embeddings (for sequence analysis, for example, in time series)

### Key terms used for Embedding
* Vector - is a mathematical object that represents a quantity with both magnitude and direction. In machine learning, a vector typically refers to an ordered set of numerical values representing a data point or features in a multi-dimensional space.
* Dense Vector - is a type of vector where most of its elements are non-zero. In the context of embeddings, dense vectors are used to represent discrete objects or values within a continuous multi-dimensional vector space. Dense vectors contain information about the attributes or features of the represented objects, and they are often utilized in machine learning tasks for their ability to capture intricate relationships and patterns within data.
* Cosine Similarity - the most popular metrics to see the distance between two vectorized objects

### What Object can be embedded ? (and which algorithms used for it)
* Words (Word2Vec; GloVe (Global Vectors for Word Representation); FastText; BERT (Bidirectional Encoder Representations from Transformers))
* Text Document (Doc2Vec; Universal Sentence Encoder (USE); BERT; ELMO)
* Audio Data (VGGish; OpenL3; Wav2Vec) etc.

### How do they work ? (briefly)
Embeddings work by transforming high-dimensional and sparse data into dense, low-dimensional representations in a continuous vector space

### Which algorithms were used in this project ?
* Word2Vec to vectorize sample data and to look for similar word
* GloVe to test this algoritm and also to look for similar word in sentence
* SentenceTransformer to use embeddings for news titles
* KMeans to cluster those embedded news articles
* Elbow method and Silhouette Score to calculate most powerful k-value for k-clusters
* PCA for visualization of Word Embeddings
