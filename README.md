Tensorflow Chatbot
===============

#Summary
-------------------
Python3

#Imports
numpy
scipy
six
tensorflow (==0.12.0 due to breaking change in seq2seq path)

#Getting Started
-------------------
You will first need to create the /data directory, where you will store your training and testing .enc and .dec files.

To obtain these files, visit https://github.com/suriyadeepan/datasets/tree/master/seq2seq/cornell_movie_corpus/

To train the bot, edit the seq2seq.ini file so that mode is set to train like so
```
mode = train
```
then run the code like so
```
python execute.py
```
To test the bot during or after training, edit the seq2seq.ini file so that mode is set to test like so
```
mode = test
```
then run the code like so
```
python execute.py
```

Note: this project was inspired by https://github.com/llSourcell
