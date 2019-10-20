# Project 1 Generative Text

Christina Ho, cgh003@ucsd.edu

## Abstract

*Friends* is an iconic show from the 90s that ran for over 10 years. Ever since it ended, the show has had a huge influence on pop culture and many fans of the show have called for a reboot or a reunion of the cast. For this project, we are going to use ML to attempt to create scenes with the same lovable elements of the show. We will use a GPT-2 model that will be finetuned on all the scripts of *Friends* from the internet. Then the training parameters will be changed to generate a script that makes sense.

## Model/Data

Briefly describe the files that are included with your repository:
- training data: scripts.txt scraped from https://fangj.github.io/friends/
- One model was trained on the scripts by finetuning with gpt-2-simple-library

## Code

Your code for generating your project:
- Text_Generation_GPT2-Friends.ipynb

## Results

- Documentation of your generative text in an effective form. A file with your generated text (.pdf, .doc, .txt). 

## Technical Notes

Any implementation details or notes we need to repeat your work. 
- This code requires gpt-2-simple

## Reference

References to any papers, techniques, repositories you used:
- https://minimaxir.com/2019/09/howto-gpt2/
