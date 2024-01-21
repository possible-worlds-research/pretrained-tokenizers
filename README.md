# Wikipedia-trained tokenizers

This repository contains SentencePiece tokenizers trained over Wikipedia snapshots using the [WikiLoader](https://github.com/possible-worlds-research/wikiloader) package. At the moment, this repository is maintained for our friends at the [PeARS project](https://github.com/PeARSearch), who are developing a multilingual, decentralised search engine. But you can of course use the models for whichever purposes you need. We will keep adding languages.

The vocabulary size is held constant across languages, at 8000 or 16000 wordpieces. Models are trained over the first 5M words of the snapshot.

For each language, you will need:

* a .vocab file containing the list of the 8000/16000 wordpieces used by the model
* a .model file containing the actual SentencePiece model

Those are stored in the respective *vocabs/* and *models/* directory, under the relevant language code.
