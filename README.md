# fasttext Demonstration

This is a demonstration on how to train word vectors using Python's fasttext library.

There are 4 notebooks.
* 01_grab_pdfs fetches the last week's submissions in the machine learning category of arxiv.org
* 02_convert_to_text pulls the texts for all pdfs and outputs to a single text file
* 03_make_word_vectors creates fasttext vectors out of the pdf text
* 04_load_model demonstrates using the model to find the nearest neighbors to certain words
