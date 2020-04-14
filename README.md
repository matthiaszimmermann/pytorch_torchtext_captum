# pytorch torchtext captum
sentiment classification with text model interpretation

## basic environment
captum tutorial run through on macbook pro with anaconda installed.
some additional installations/changes necessary as noted in IMDB_TorchText_Interpret.ipynb

## component versions
* anaconda [anaconda.com](https://www.anaconda.com/distribution/) (python 3.7)
* pytorch 1.4.0 [pytorch.org](https://pytorch.org/)
* captum 0.2.0 [captum.ai](https://captum.ai/)
* torchtext 0.5.0 [torchtext](https://pytorch.org/text/)
* spacy 2.1.8 ([spacy.io](https://spacy.io/) for sentiment classification)
* sentencepiece ([sentencepiece](https://pypi.org/project/sentencepiece/) for sentiment classification, pip installation only)

## goal of experiment
get to the graphic with colored words to indicate which words did contribute how much to movie review sentiment classification.

## steps
* open IMDB_TorchText_Interpret.ipynb
* run through steps
* get to output as shown below

![word level contributions](https://github.com/matthiaszimmermann/pytorch_torchtext_captum/blob/master/img/sentiment_analysis.png)
