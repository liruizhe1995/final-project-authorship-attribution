# Authorship Attribution

This is a project inspired by the question "Are works from Bronte sisters and Austen similar to each other on writing styles?". We tend to analyze the syles of each author and build models to identify the actual author given a piece of text.

## Installation

This project uses Python as prgramming language in Jupyter Notebook. We use nltk and spacy packages for processing the text data. Sklearn package is used for training and testing our models in the project. We also use matplotlib, seaborn and plotly for plotting and graphing. 

For using nltk model from spacy in the notebook, we need to download language model from spacy in the terminal by inputting "python -m spacy download en_core_web_sm"

Warning: While using the spacy in the notebook, it will take a long time run the code, therefore we also put the result images in the folder.

## Project Description
1. Input 13 novels from 4 differenct authors including:
1. Item 1
1. Item 2
1. Item 3
   1. Jane Austen ("Sense & Sensibility (1811)", "Pride and Prejudice (1813)", "Emma (1815)"
   2. Charlotte Bronte ("The Professor", "Jane Eyre (1847)", "Shirley (1849)", "Villette (1853)"
   3. Charles Dickens ("Bleak House (1852)", "David Copperfield (1849)", "Hard Times (1854)"
   4. George Eliot ("Adam Bede (1859)", "The Mill on the Floss (1860)", "Middlemarch (1872-1872)"
2. Calculate term frequency of each book
3. Document preprocessing
   1. tokenization
   2. lower-casing 
   3. lemmatization
4. Analysis and Visualization 
   1. Common words used by each author
   2. sentence length
   3. lexical richness 
   4. word length
   5. top 10 words 
   6. part of speech used by each author
   7. most common adj and adv used by author
5. Model Building (Delta Method, Naive Bayes, Logistic Regressions)
6. Conclusions

## File Description

1. The folder "data" includes all 13 books in txt fomats used by the projects.
2. The file "document_term_matrix.csv" prints out the top 20 highest relative frequency words in each book.
3. The file "580_Final_Project.ipynb" is the jupyter notebook that contains our code and analysis of the project.
4. The image "lexical_richness.png" describes the lexical richness of each book used in the project.
5. The image "top10_words.png" describes the relative frequency of 10 most common words used in each book.
6. The image "POS.png" describes the relative frequenncy of part-of-speech taggings including noun, adjective, verb, adverb and pronoun.
7. The file "adj.csv" prints out the most common adjectives used by each author.
8. The file "adv.csv" prints out the most common adverbs used by each author.

