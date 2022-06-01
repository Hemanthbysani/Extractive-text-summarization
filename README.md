# Extractive-Summarisation
## This project was done as a part of Innovator Incubator Advisory Hackathon
### We recieved 3rd prize for the same
Synopsis Derived using Extractive Summarisation for Patient Notes

Implemented a model that performs extractive summarization on Doctor-Patient notes using various models from different libraries. 
The model uses Cosine similarity matrix and graph-based Lexical Centrality to achieve the aforementioned, Bert model from Google and Sumy Summarization model to perform the summarization.

The model has been developed keeping in mind medical professionals' convenience and thus, shortens extracts, keeping important recognised data and corrects existing data using tokenized lemmatization and converting the tokenized words into vectors so that they can be fed into the models for analysis.

Entity Recognition has also been implemented to provide a means to categorize words according to their meaning and roots.

We have found out that Sumy summarization and Bert model work best for extractive summarization, further tests have to be done on GPT-3's model too, but that would be a later project.

We will not be attaching any data as the data is protected by an NDA clause.
