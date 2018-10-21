# Rhetorical Structure - PubMed Abstracts

This respository contains the abstracts used in the paper "Using LSTM Encoder-Decoder for Rhetorical Structure Prediction"
For the construction of this corpus we used the PubMed Baseline Data from 2017.

**Check the [PubMed license](PUBMED_README.txt) before using this data.**

## abstracts.pickle.xz
[Download](https://github.com/dead/rhetorical-structure-pubmed-abstracts/releases/download/v0.1/abstracts.pickle.xz)

Data Structure:
```python
[
  [ # Abstract
    (SENTENCE_TEXT, LABEL),
    ...
  ],
  ...
]
```


## Usage

Decompress the downloaded file and you can open it using Python.

Example:
```python
import pickle
with open('abstracts.pickle', 'rb') as f:
  data = pickle.load(f)
```


## Contact

If you have any questions feel free to contact me via e-mail: gustavobenn@gmail.com
