# Persian_NLP_Task
- Data:
"Peykare" is a collection of formal written and spoken Persian language texts that have been labeled and collected from reliable sources like newspapers, websites, and pre-typed documents. The dataset, which was compiled from numerous sources and includes 100 million words, contains a wide range of materials. Each file is categorized according to its subject and source, and 10 million words from this dataset have been manually annotated by linguistics students using 882 syntactic-semantic tags. This dataset, created by the Intelligent Signal Processing Research Center, can be used for natural language processing tasks like language model training.
# Models
- Python-crfsuite (pos-tagger).
- Sklearn-crfsuite (pos-tagger).
- Using LSTM model to Ezafe tags and other tags.
- Testing RNN Models such as Bi-LSTM, Simple RNN, and GRU for all tags.
# Construct Parallel Data with the top-100 similar sentences
- Use laser embeddings to extract one vector per sentence.
- Use pytorch's off-the-shelf cosine similarity function to extract pairwise similarity.
