# Persian Poetry Generator Using GRU Units
In this notebook a language model was developed to generate Persian Khayyam poetry.

[Dataset](https://ganjoor.net/khayyam/robaee)

## About Dataset
The dataset contains 16376 hemistichs of Khayyam's poetry.

Hemistichs are divided by **|**

## Preprocessing
At first, we extract all vocabularies and assign a number to each of them. 
* char2index array is used for encoding
* index2char array is used for generating text  


Before feeding data to model, text is converted into consecutive sequences.

## Modeling
A large model with 1024 GRU units was created with a dense layer to predict the probability of each character.


## Prediction
At the end, the model can generate poems from a prompt.
