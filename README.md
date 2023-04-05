# Improving News Headline Text Generation Quality Through Frequent POS-Tag Patterns Analysis

This repository contains the code and data for the research paper "Improving News Headline Text Generation Quality Through Frequent POS-Tag Patterns Analysis". The paper presents a method for enhancing the quality of generated news headlines by analyzing the frequent POS-tag patterns in the training data and integrating them into the text generation model.

The repository includes the following components:

- `data`: Preprocessed training data used in the paper
- `models`: Source code for the text generation model, implemented in Python with PyTorch
- `HPPE`: Headline post-processing script for selecting generated headlines based on POS Tags matching.
- `examples`: Generated headlines and their corresponding POS-tag patterns


## Executing Code
### Cloning repository
- Clone this repository using following command:
```
git clone https://github.com/saifhassan/Headline-Generationg-using-POS.git
```

### Downloading Dataset
The dataset which is used for Urdu News Headlines is taken from [here](https://data.mendeley.com/public-files/datasets/834vsxnb99/files/60d1e75f-7d9a-4b24-99df-33174cd49094/file_downloaded). There are two ways to produce same results as mentioned in paper. 

1. First, Download original dataset and process through [Notebook](https://github.com/saifhassan/Headline-Generationg-using-POS/blob/main/post-processing.ipynb).

OR

2. Another way is, we have already pre-processed dataset. You can download pre-processed dataset with POS Tags from [here](https://drive.google.com/file/d/1cZFm_JoBv7nE7-LfitRcNMf7OLhgcsEo/view?usp=sharing)

3. Put downloaded dataset in data folder.

### Running notebook

- Go to HPPE directory within main directory and open notebook using terminal and execute code.


The repository is open-source and welcomes contributions from the community.

Note: This repository is provided for research purposes only and is not intended for commercial use.
