# Search Engine with NLP

Building a custom search engine that’s capable of quickly and accurately sourcing documents from a document database. This search engine improve the ability to handle future pandemics, with the capability to aggregate and search unstructured text data from records of earlier outbreaks. 

- **Part 1: Text Search with spaCy and scikit-learn:**
In this part, we'll explore and assess essential methods for unstructured text search in order to identify which is the best for building a search engine. We’ll preprocess the data for this task using the spaCy library, and then experiment with implementing both a TF-IDF search and an inverted index search to find relevant information.

- **Part 2 Implement Semantic Search with ML and BERT:**
In this part, we’ll apply premade transfer learning models to improve the context understanding of your search. We’ll implement BERT (Bidirectional Encoder Representations from Transformers) to create a semantic search engine. BERT excels in many traditional NLP tasks, like search, summarization and question answering. It will allow your search engine to find documents with terms that are contextually related to what your user is searching for, rather than just exact word occurrence.

- **Part 3 Building a Search API with Elasticsearch and BERT:**
In this part, we’ll bring together multiple tools and models to construct a production-grade smart search engine. We’ll combine off-the-shelf Elasticsearch models for keyword search with your own semantic search API using transformers. We start by setting up and indexing an Elasticsearch Docker container, then quickly move on to boosting search relevance with BERT. Finally, we’ll set up a Flask API to serve a BERT model and look into customizing your search engine for your own particular topics of interest.


- **Part 4 UI for a Search API with Flask and Bootstrap:**
In this part, we’ll use Docker, the Docker compose command line, and Bootstrap to construct an easy-to-use UI for your search engine. You’ll work to set up a single node Elasticsearch cluster, before putting together your Bootstrap UI, and then create a customized Docker image of the Flask API that serves your transformers model and frontend.


