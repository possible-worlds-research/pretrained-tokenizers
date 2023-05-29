# Wikipedia-trained tokenizers

This repository contains SentencePiece tokenizers trained over Wikipedia snapshots using the wikiloader package. The vocabulary size is held constant across languages, at 10000 wordpieces. Models are trained over the first 5M words of the snapshot.

For each language, you will need:

* a .vocab file containing the list of the 10000 wordpieces used by the model
* a .model file containing the actual SentencePiece model

Those are stored in the respective *vocab/* and *model/* directory, under the relevant language code.
