# Neologisms
INFO 256 Applied NLP class final project

## TODO:
1. Cleaning 
* Filter only-in-text neologisms
* Spacy(): depunctuation, stemming, tokenization
* Masking

2. Calculate entropy for each neologism
* Take top 500 most frequent vocabularies in whole corpus
* p = frequency of token X in tweets of neologism A / total number of tokens in tweets of neoglogism A
* entropy = -sum(p x log(p)) over all 500 vocabularies

3. Labels
* clustering on the time pattern of tweets

4. Model
* biLstm + attention
* concatenate entropy with attention scalar for final prediction
 
