# A Multi-task Learning Framework for Opinion Triplet Extraction

## Requirements

* Python 3.6
* PyTorch 1.0.0
* numpy 1.15.4

## Usage

* Download pretrained GloVe embeddings with this [link](http://nlp.stanford.edu/data/wordvecs/glove.840B.300d.zip) and extract `glove.840B.300d.txt` into `glove/`.
* Train with command, optional arguments could be found in [train.py](/train.py), **--v2** denotes whether test on datav2
```bash
python train.py --model mtl --dataset rest14 [--v2]
```
* Infer with [infer.ipynb](/infer.ipynb)

