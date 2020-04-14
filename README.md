# pytorch torchtext captum
sentiment classification with text model interpretation

## basic environment
captum tutorial run through on macbook pro with anaconda installed.
some additional installations/changes necessary as noted in IMDB_TorchText_Interpret.ipynb

## component versions
* pytorch 1.4.0
* captum 0.2.0
* torchtext 0.5.0
* spacy 2.1.8 (for sentiment classification)
* sentencepiece (pip installation only)

## goal of experiment
get to the graphic with colored words to indicate which words did contribute how much to movie review sentiment classification.

## steps
* open IMDB_TorchText_Interpret.ipynb
* run through steps
* get to output as shown below

![word level contributions](https://github.com/matthiaszimmermann/pytorch_torchtext_captum/blob/master/img/sentiment_analysis.png)
