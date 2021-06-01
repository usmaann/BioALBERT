# BioALBERT
Benchmarking for Biomedical Natural Language Processing Tasks with a Domain Specific ALBERT


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

* [Share/Clefe](https://drive.google.com/drive/folders/1zAki8Xuw49QBRWW82w2bXvfjbfDCWrtz?usp=sharing)
* [DDI](https://drive.google.com/drive/folders/1LK1j3oJitxgAUt9W1CkB7IEwY0spePiY?usp=sharing)
* [ChemProt](https://drive.google.com/drive/folders/1iWAgFtAHowflx7_MTA9wttnoKh_W1C5U?usp=sharing)
* [i2b2](https://drive.google.com/drive/folders/1Yv4LioykzMlZoUVo3UuGfunGhiAUwmCr?usp=sharing)
* [BIOSSES](https://drive.google.com/drive/folders/1dJm2cU2hZHlx9-3ZnfJo-dhCvPVYXkcJ?usp=sharing)
* [MedSTS](https://drive.google.com/drive/folders/1X5l2IEYVKGMMQFNwQjlGPEOhzncZl0Lw?usp=sharing)
* [MedNLI](https://drive.google.com/drive/folders/1ej9G-m8ceIaP0INkWsw0rvJNSLso5HzW?usp=sharing)
* [HoC](https://drive.google.com/drive/folders/1_IlZzKnrfnvr2KVoOe40STaqzMRXFd7T?usp=sharing)

### Named Entity Recognition (NER)
* [BC2GM](https://drive.google.com/drive/folders/130ei5___99HkOoaHg9KJhveC7sJM1Zw4?usp=sharing)
* [BC4CHEMD](https://drive.google.com/drive/folders/1gASQyQoDtt7Ss2vXyTvR6EwdGzfFBXuJ?usp=sharing)
* [BC5CDR (Disease)](https://drive.google.com/drive/folders/1BtEDXwj1bwSZfes8w-4S9mIZLdjTC4nj?usp=sharing)
* [BC5CDR (Chemical)](https://drive.google.com/drive/folders/1b_C-vuOZ7ae1qUeuXZJhdyRSrWgygVMS?usp=sharing)
* [JNLPBA](https://drive.google.com/drive/folders/1SMm-cY2XxKsyHvcIR2teNt97N-3zYaXc?usp=sharing)
* [LINNAEUS](https://drive.google.com/drive/folders/1jQEgdQAdRweoh6vHSYeEOwya7w1VDg2p?usp=sharing)
* [NCBI (Disease)](https://drive.google.com/drive/folders/1ESm_CF3cU0ZbKP2N8uXiMHz8wKARm-KW?usp=sharing)
* [Species-800 (S800)](https://drive.google.com/drive/folders/1s2k1e7hnW1f9kHOv2AIEfZyL0c0SIBfT?usp=sharing)

### Relation Extraction (RE)
* [Euadr](https://drive.google.com/drive/folders/1XuiG7W93Nce4cDlD8eAnenB7T4pBoXCs?usp=sharing)
* [GAD](https://drive.google.com/drive/folders/1dFc8eEqrtkf1Nt8etaz3I4WyswUQT9C8?usp=sharing)

### Question Answering (BioASQ)
* BioASQ 4b
* BioASQ 5b
* BioASQ 6b

Open each links and download the datasets you need. For BioASQ datasets, please refer to the [biobert repository](https://github.com/dmis-lab/biobert#datasets)


## Fine-tuning BioBERT

After downloading one of the pre-trained weights, unzip it to any directory you want, we will denote it as ``` $BIOALBERT_DIR ```. For example, when using BioALBERT-Base v1.0 (PubMed), set the BIOALBERT_DIR environment variable to:

```
$ export BIOALBERT_DIR=./BioALBERT_PUBMED_BASE
$ echo $BIOALBERT_DIR
>>> ./BioALBERT_PUBMED_BASE
```

### NER
Each datasets contains four files, which are ```dev.tsv```, ```test.tsv```, ```train_dev.tsv```, and ```train.tsv```. Simply download a dataset from NER and put these files into the directory called ```$NER_DIR```. Also, set ```$OUTPUT_DIR``` as a directory for NER outputs. For example, when fine-tuning on the BC2GM dataset,

```
$ export NER_DIR=./datasets/NER/BC2GM
$ export OUTPUT_DIR=./NER_outputs
```
Following command runs fine-tuning code on NER with default arguments.

```
$ mkdir -p $OUTPUT_DIR
$ python run_ner.py --do_train=true --do_eval=true --vocab_file=$BIOALBERT_DIR/vocab.txt --bert_config_file=$BIOALBERT_DIR/bert_config.json --init_checkpoint=$BIOALBERT_DIR/model.ckpt-1000000 --num_train_epochs=10.0 --data_dir=$NER_DIR --output_dir=$OUTPUT_DIR
```

### RE
Each datasets contains there files, which are ```dev.tsv```, ```test.tsv```, and ```train.tsv```. Let ```$RE_DIR``` denote the folder of a single RE data set, ```$TASK_NAME``` denote the task name (two options: gad, euadr), and ```$OUTPUT_DIR``` denote the RE output directory, take GAD as an example:

```
$ export RE_DIR=./datasets/RE/GAD/1
$ export TASK_NAME=gad
$ export OUTPUT_DIR=./re_outputs_1
```
Following command runs fine-tuning code on RE with default arguments.

```
$ python run_re.py --task_name=$TASK_NAME --do_train=true --do_eval=true --do_predict=true --vocab_file=$BIOBERT_DIR/vocab.txt --bert_config_file=$BIOBERT_DIR/bert_config.json --init_checkpoint=$BIOBERT_DIR/model.ckpt-1000000 --max_seq_length=128 --train_batch_size=32 --learning_rate=2e-5 --num_train_epochs=3.0 --do_lower_case=false --data_dir=$RE_DIR --output_dir=$OUTPUT_DIR
```

### QA

please refer to the [biobert repository](https://github.com/dmis-lab/biobert#question-answering-qa)



