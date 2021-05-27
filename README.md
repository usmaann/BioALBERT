# BioALBERT
BioALBERT- A simple and effective pre-trained biomedical language representation model


This repository provides the pre-trained BioALBERT models, a biomedical language representation model trained on large domain specific (biomedical) corpora for designed for biomedical text mining tasks. Please refer to our paper [title of the paper](links) for more details.


## Download

We provide eight versions of pre-trained weights. Pre-training was based on the original ALBERT code, and training details are described in our paper (To be Published). Currently available versions of pre-trained weights are as follows:

1) *[BioALBERT-Base v1.0 (PubMed)](https://drive.google.com/file/d/1sCU1vvSOWoWVAkOoWGUC3ZKraItLIoXD/view?usp=sharing) - based on ALBERT-base Model*

2) *[BioALBERT-Base v1.0 (PubMed + PMC)](https://drive.google.com/file/d/1N2UekXKNqhbjQLbtipsm8rNPcaFEG-2I/view?usp=sharing) - based on ALBERT-base Model*
 
3) *[BioALBERT-Base v1.0 (PubMed + MIMIC-III)](https://drive.google.com/file/d/1t9XUVMxEfRzVYU0M99NB9PIPSZWAFX4V/view?usp=sharing) - based on ALBERT-base Model*

4) *[BioALBERT-Base v1.0 (PubMed + PMC + MIMIC-III)](https://drive.google.com/file/d/1SIBd_-GETHhMiZ7BgMdDPEUDjOjtN_bH/view?usp=sharing) - based on ALBERT-base Model*

5) *[BioALBERT-Large v1.1 (PubMed)](https://drive.google.com/file/d/1uX5w8yaMyJta3Nit_3ayrL16tE-dO8Ew/view?usp=sharing) - based on ALBERT-Large Model*

6) *[BioALBERT-Large v1.1 (PubMed + PMC)](https://drive.google.com/file/d/1WJp7KbWXPa-3QWpsXcN95smY6V2RRbcX/view?usp=sharing) - based on ALBERT-Large Model*

7) *[BioALBERT-Large v1.1 (PubMed + MIMIC-III)](https://drive.google.com/file/d/1mZeW_0iQsCSIn86cW_XduaGnVtNGGXYp/view?usp=sharing) - based on ALBERT-Large Model*

8) *[BioALBERT-Large v1.1 (PubMed + PMC + MIMIC-III)](https://drive.google.com/file/d/16KRtHf8Meze2Hcc4vK_GUNhG-9LY6_6P/view?usp=sharing) - based on ALBERT-Large Model*

Alternately, you can download pre-trained weights from [here]()

Make sure to specify the version of the pre-trained weights used in your work. 


## Installation

The following sections introduce the installation and fine-tuning process of BioALBERT based on PyTorch (python version <= 3.7).

To fine-tune BioALBERT, you need to download BioALBERT pre-training weights. After downloading the pre-trained weights, install BioALBERT using requirements.txt as follows:

```
git clone https://github.com/usmaann/BioALBERT.git
cd BioALBERT; pip install -r requirements.txt

```
Note that this repository is based on the [ALBERT](https://github.com/google-research/albert) repository by Google. See requirements.txt for other details.

## Quick Links

| Link | Detail |
| --- | --- |
| Paper | Paper link with [BibTex]() |


## Datasets

We provide a pre-processed version of benchmark datasets for each task as follows:

* Share/Clefe
* BC5CDR (Disease)
* BC5CDR (Chenical)
* JNLPBA
* LINNAEUS
* NCBI (Disease)
* Species-800 (S800)
* BC2GM
* DDI
* ChemProt
* i2b2
* Euadr
* GAD
* BIOSSES
* MedSTS
* MedNLI
* HoC
* BioASQ 4b
* BioASQ 5b
* BioASQ 6b

You can simply run `download.sh` to download all the datasets at once. The folder called `datasets` has all the data you need.


## Fine-tuning BioBERT

###several datasets



