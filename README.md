# Autocorrect Peter Novig python imlementation : 


![alt text](https://github.com/BheZelmat/Autocorrect-Peter-Norvig-python-implementation/blob/main/autocorrect-ft.JPEG?raw=true)

## Overview
This notebook demonstrates the implementation of an autocorrect system similar to those used in smartphones and word processing software. It delves into the key concepts of natural language processing, including tokenization, probability distributions, and edit distance algorithms, to correct typographical errors in English text. The implementation draws inspiration from Peter Norvig's seminal work on spell correction.

## Dependencies
Python 3.x
re (regular expression library)
collections
numpy
pandas
Dataset
The autocorrect system utilizes a corpus from Shakespeare's works to compute word frequencies and probabilities. The dataset should be a plain text file with a collection of English words. Users must ensure the file 'shakespeare.txt' or similar is placed in the correct directory or modify the file path in the notebook accordingly.

## Installation and Setup
Ensure you have Python installed on your system. You can install the necessary Python libraries using pip:

* Copy code
* pip install numpy pandas
* Clone the repository or download the notebook file to your local machine. Ensure the dataset (e.g., 'shakespeare.txt') is in the same directory as the notebook or update the file path in the notebook's code to point to the location of your dataset.

## Usage
Open the notebook in Jupyter Notebook or JupyterLab:

* Copy code
* jupyter notebook Auto_Corrector.ipynb
* Execute the cells sequentially to observe the autocorrect system's development and operation. The notebook includes detailed comments explaining each step and its purpose.

## Functionality Overview
The notebook implements several key functions:

* process_data(file_name): Processes the input text file to create a list of words.
* Edit distance functions: Implement algorithms to compute the minimum number of edits required to transform one word into another.
* Autocorrect functions: Suggest corrections for misspelled words based on edit distance and word probability derived from the dataset.

## References
Peter Norvig's article on spell correction: [How to Write a Spelling Corrector](https://norvig.com/spell-correct.html)
Bayes' Theorem: [Wikipedia page](https://en.wikipedia.org/wiki/Bayes'_theorem)https://en.wikipedia.org/wiki/Bayes'_theorem

## Author 
B Houssem E Zelmat 
