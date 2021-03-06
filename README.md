# Restaurant Reviews Topic Analysis

This project focused on utilizing restaurant reviews to provide completitive intelligence and restaurant recommendations for stakeholders in existing or perspective new restaurants in Bangaluru, India. Those considering opening a new restaurant in the area as well as existing restaurant managers could benefit from the insights that were generated in this work.

My individual contribution to the group project was creating topic models using the free-form text in the reviews. Topic models are probabilistic algorithms for discovering the main themes in a large and otherwise unstructured collection of documents. They can help cluster similar groups of documents according to the discovered themes in an unsupervised way. Many algorithms can be used for topic modeling, for this project we focused on Latent Dirichlet Allocation (LDA). LDA models each document in a corpus as a mixture of a fixed number of topics. A topic has a probability of generating various words taken from a dictionary comprised of all the words observed in the corpus. Intuitively, the LDA model tries to find groups of words that appear together frequently.

Preprocessing of the data for input into the LDA model included tokenization and removing stop words, creation of bigrams, and lemmatization. Tokenization splits the text into sentences and the sentences into words. Bigrams allow us to capture two words frequently occurring together. 

Full code can be found [here.](Topic_Model1.ipynb)
