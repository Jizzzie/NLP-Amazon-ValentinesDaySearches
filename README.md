# NLP-Amazon-ValentinesDaySearches
The project aimes to implement NLP techniques on searches in Valentine's Day on Amazon; hence increasing user interaction and providing more meaningful suggestions

Following are the steps involved:

**Objective 1: Dealing with Data**
- > Develop a program that cleans the reviews by converting them to lowercase for consistency and removing unnecessary symbols like punctuation and special characters.
- > Once the data is cleaned, your task is to tokenize the reviews into individual words and calculate the total number of words across all reviews.
- > Identify and report the most frequently mentioned word along with its frequency.

**Objective 2: Edit Distance for Product Name Correction**
Customers often misspell product names while searching. Write a program to compute the edit distance between a customer’s search query and the correct product name. Suggest the correct product name if the edit distance is below a certain threshold. We intend to take a list of product titles and based on that do autocorrection as comparing with existing reviews might give wrong suggestions as users might have texted wrong input already.

**Objective 3: N-gram Language Model for Product Recommendations**
Build a bigram language model using the product descriptions dataset. Use the model to calculate the probability of a sequence of product-related terms. Also, predict the next word for a given product search query using the bigram probabilities.

**Objective 4: Named Entity Recognition (NER) for Reviews**
Implement NER to extract product names, brands, and other important entities from customer reviews. For example, identify which reviews mention the brand “AAA" or the product category "QQQ". The brand we chose is Ferrero Rocher and for doing this we call en_core_web_sm module from spacy

**Objective 5: Cosine Similarity and Word Embeddings for Similar Products**
Build word embeddings from the product descriptions and reviews. Compute the cosine similarity between product names to identify the most similar products based on their descriptions. Visualize the word embeddings to show how similar products cluster together. TF-IDF (Term Frequency-Inverse Document Frequency) is a statistical measure used to evaluate the importance of a word in a document relative to a collection of documents (corpus). It's commonly used for tasks like document similarity, text classification, and information retrieval. TF-IDF embeddings represent documents as vectors, where each dimension corresponds to a word, and the value in that dimension is its TF-IDF score. Cosine similarity is a metric used to measure the similarity between two vectors. It calculates the cosine of the angle between the vectors, which gives a value between -1 (completely dissimilar) and 1 (completely similar). In the context of text embeddings, like TF-IDF vectors, cosine similarity can be used to determine how similar two documents are.

