This repo is linked to INSERT BLOG POST LINK

You can access the dataset on kaggle [https://www.kaggle.com/datasets/charanpuvvala/company-classification?resource=download]


## Contents

The repo consists of:

- create_kaggle_subset.ipynb which should be run first if you wish to downsample the original dataser. It takes the downloaded kaggle file and creates a subset dataset contianing 10% of each class 

- callibration.ipynb runs some simple eda on the dataset and trains a randfom forest model with and without callibration 


## Setup

To use this repository you will need Jupyter installed (`pip install jupyter`). 

Then install the following dependencies: `pip install spacy numpy pandas matplotlib scikit-learn`

Finally install the spacy model which we use for vectorising the description: `python3 -m spacy download en_core_web_lg`


