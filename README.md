# Project-Artemis
Machine learning project for Course Introduction to Machine Learning.

You need a Python version lower than 3.8 for TensorFlow 1

Packages: pip3 install tensorflow==1.15.5 pip3 install gpt-2-simple

How to train:

Put text processing and other helper scripts in the Toolbox folder.
Put processed text files (novels) in the Authors folder.
Train models with AI_Author_Train.py (it will take very long, don't let the computer go to sleep).
Test the result with AI_Author_Test.py, put the question you want to ask in it.
NOTE: If you have finished training with one author and want to start with another one, move "checkpoint" and "samples" folders somewhere else before starting another training.
