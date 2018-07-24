# Text-Scrapping-and-Classification
  The objective of this assignment is to scrape a corpus of news articles from a set of web pages, pre-process the corpus, and evaluate the performance of automated classification of these articles in a supervised learning context. 

  The assignment should be implemented as a single IPython Notebook (not a script). The code was required to be clearly documented, using comments and Markdown cells to explain your code and results.

# The Tasks that were assigned are as follows:

## Part 1. Data Collection

The goal here is to collect a labelled news corpus. Tasks to be completed: 
  1. Identify the URLs and category labels for all news articles listed on the website: http://mlg.ucd.ie/modules/COMP41680/archive/index.html
  2. Retrieve all web pages corresponding to these article URLs. From the web pages, extract the main body text containing the content of each news article. Save the body of each article as plain text.
  3. Save the category labels for all articles in a separate file.
  
## Part 2. Text Classification

The goal here is to analyse the corpus of documents from Part 1 in a text classification context. Tasks to be completed:
  1. From the files created in Part 1, load the set of raw documents into your notebook. Ensure that each document has a class label, based on the original category label that you identified.
  2. From the raw documents, create a document-term matrix, using appropriate text pre-processing and term weighting steps.
  3. Build two multi-class classification models using two different classifiers of your choice.
  4. Compare the predictions of the two classification models using an appropriate evaluation strategy. Report and discuss the evaluation results in your notebook.

# Tasks Completed

  1. Collected a labelled news corpus: Identified the URLs and category labels for all news articles listed on the website provided, retrieved all web pages corresponding to the article URLs.
  2. Loaded the set of raw documents, added a class label to each document using Pandas Library, created a Document-Term Matrix from the raw documents after performing text pre-processing.
  3. Built multi-class classification models using Scikit-learn Library, compared the predictions and performed Cross-Validation Evaluation Strategy.
