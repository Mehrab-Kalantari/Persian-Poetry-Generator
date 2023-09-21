# Persian Poetry Generator using GRU Model
In this notebook we create a model to generate Persian Khayyam poetry

[Dataset](https://ganjoor.net/khayyam/robaee)

## About Dataset
The dataset contains 16376 hemistichs of Khayyam's poetry.

Hemistichs are divided by **|**

## Encoding Text
At first, we extract all vocabularies and assign a number to each of them. 
* char2index: for encoding purposes
* index2char: for text generation purposes


Before modeling, we create sequences of data.

## Modeling
We use GRU model with 1024 units and a dense layer to predict probability of each character.


## Prediction
At the end, we use our model to generate poems.
