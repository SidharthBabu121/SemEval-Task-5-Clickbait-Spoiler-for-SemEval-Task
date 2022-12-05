# SemEval Task-5: Clickbait Spoiler



# Webis Clickbait Spoiling Corpus

The Webis Clickbait Spoiling Corpus 2022 (Webis-Clickbait-22) contains 4,000 spoiled clickbait posts crawled from Facebook, Reddit, and Twitter.
This corpus supports the task of clickbait spoiling, which deals with generating a short text that satisfies the curiosity induced by a clickbait post.


## Overview

The dataset comes with predefined train/validation/test splits:

- [3,200 posts for training](training.jsonl)
- [800 posts for validation](validation.jsonl)



## Installation

1) Please refrence this link: https://www.makeuseof.com/tag/install-pip-for-python/, to install pip for Windows, Mac, Linux

2) Please create a virtual enviornment  using venv  (https://docs.python.org/3/library/venv.html)

3) pip install -U pip

4) pip install -r requirements.txt
 
5) After git cloning this project, please go to the data folder and unzip the qa file.


## Details of Importance:

1) The project contains three folder:
    - data       ->  Contains all the raw train and validation data for all models
    - models     ->  Folder where we save the best models for spoiler classification. 
    - notebooks  ->  Folder containing model notebooks

2) In the notebooks folder, there are 5 notebooks for each model we designed and test:
    - nlp_243_project_classification_svm.ipynb 
    - nlp_243_project_classification_bert.ipynb
    - nlp_243_project_classification_bert_lstm.ipynb
    - nlp_243_project_qa_bert.ipynb
    - nlp_243_project_qa_roberta.ipynb
    
3) Execute each of the notebooks sequentially
    - To execute them, please change (in the first cell) the "root_path" to the path of the data folder (please keep in mind of the structure of the code       you download).
    - The results for each will be present in the bottom of the notebook. 
 

 


