# BioALBERT
BioALBERT- A simple and effective pre-trained biomedical language representation model


This repository provides the pre-trained BioALBERT models, a biomedical language representation model trained on large domain specific (biomedical) corpora for designed for biomedical text mining tasks. Please refer to our [papers](links) for more details.


## Download

We provide four versions of pre-trained weights. Pre-training was based on the original ALBERT code, and training details are described in our paper (To be Published). Currently available versions of pre-trained weights are as follows:

1) *BioALBERT-Base v1.0 (PubMed) - based on ALBERT-base Model*

2) *BioALBERT-Base v1.0 (PubMed + PMC) - based on ALBERT-base Model*

3) *BioALBERT-Large v1.1 (PubMed) - based on ALBERT-Large Model*

4) *BioALBERT-Large v1.1 (PubMed + PMC) - based on ALBERT-Large Model*

Make sure to specify the version of the pre-trained weights used in your work. If you have difficulty choosing which one to use, we recommend using BioALBERT-Base v1.1 (+ PubMed 1M) or BioALBERT-Large v1.1 (+ PubMed 1M) according to your GPU resources. Please note that for BioALBERT-Base, we use the WordPiece vocabulary (vocab.txt) provided by Google, because any new word in the biomedical corpus can be represented by subwords


## Installation

The following sections introduce the installation and fine-tuning process of BioAlBERT based on PyTorch (python version <= 3.7).

To fine-tune BioALBERT, you need to download BioALBERT pre-training weights. After downloading the pre-trained weights, install BioALBERT using requirements.txt as follows:

```
git clone https://github.com/usmaann/BioALBERT.git
cd BioALBERT; pip install -r requirements.txt

```

## Quick Links

| Link | Detail |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |

## Datasets

## Fine-tuning BioBERT

###several datasets



