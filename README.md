This is a simple Python script that compares two text files to detect similarity and determine the likelihood of plagiarism. It uses the SequenceMatcher class from Python's difflib module to calculate a similarity ratio and classify the result into different categories.

Features
File Comparison: Compares the content of two text files (1.txt and 2.txt).
Similarity Detection: Calculates a similarity percentage using the SequenceMatcher algorithm.
Plagiarism Analysis: Categorizes the similarity level into three levels:
High probability of plagiarism: Similarity >= 90%.
Moderate similarity: Similarity between 70% and 89%.
Low similarity: Similarity < 70%.
Error Handling: Detects if the files are missing and provides appropriate error messages.
Tech Stack
Language: Python
Module: difflib
Requirements
Python 3.x
Text files to compare (1.txt and 2.txt).

