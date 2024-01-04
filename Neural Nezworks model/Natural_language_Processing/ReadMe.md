
# Disaster Tweets Classification Project



## Overview

This project focuses on classifying tweets as either related to a disaster or not. The primary goal is to explore various Natural Language Processing (NLP) techniques and deep learning models to achieve accurate classification. The dataset used for this project is sourced from Kaggle and revolves around tweets related to disasters.

## Table of Contents

    Tokenization and Embedding

    Models
    Baseline Model
    LSTM RNN
    GRU RNN
    1D Convolutional Neural Network
    Transfer Learning with Universal Sentence Encoder
    BERT Model (In Progress)

    Identifying Labeling Issues
    Results and Comparison

## Models

*Baseline Model*

The initial model is a simple baseline utilizing a Naive Bayes approach.

*LSTM RNN*
Following the baseline, Long Short-Term Memory (LSTM) Recurrent Neural Network (RNN) models are explored.

*GRU RNN*
Gated Recurrent Unit (GRU) RNN is implemented to compare performance with LSTM.

*1D Convolutional Neural Network*
A 1D Convolutional Neural Network is experimented with to assess its effectiveness for tweet classification.

*Transfer Learning with Universal Sentence Encoder*
Transfer learning is employed using TensorFlow Hub's Universal Sentence Encoder, comparing its performance against baseline and traditional neural networks.

*BERT Model (In Progress)*
The README is under construction, and a BERT model is currently being implemented to further improve classification results.

*Identifying Labeling Issues*
During the course of the project, it was discovered that labeling issues existed within the dataset. Some tweets were mislabeled, contributing to unexpected model performance.

Results and Comparison
A comprehensive comparison of model performance is presented, highlighting the strengths and weaknesses of each approach. Notably, transfer learning with Universal Sentence Encoder outperformed other models, including advanced neural networks.



## Software and Packages Used

Python: The code is written in Python programming language.

TensorFlow: Deep learning library used for building and training neural network models. Make sure to install TensorFlow using the following
## References 
1. https://github.com/mrdbourke/tensorflow-deep-learning

2. https://chat.openai.com/c/ce49e82a-d775-4ac6-80d9-3bb9efcdf80c

3.https://raw.githubusercontent.com/mrdbourke/tensorflow-deep-learning/main/extras/helper_functions.py

## License

[MIT](https://choosealicense.com/licenses/mit/)

Copyright (c) 2023 JEEVA SAM

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
