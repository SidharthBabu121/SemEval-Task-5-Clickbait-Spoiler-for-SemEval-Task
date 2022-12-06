# SemEval Task-5: Clickbait Spoiler


# Webis Clickbait Spoiling Corpus

The Webis Clickbait Spoiling Corpus 2022 (Webis-Clickbait-22) contains 4,000 spoiled clickbait posts crawled from Facebook, Reddit, and Twitter.
This corpus supports the task of clickbait spoiling, which deals with generating a short text that satisfies the curiosity induced by a clickbait post.


## Overview

The dataset comes with predefined train/validation/test splits:

- [3,200 posts for training](https://github.com/SidharthBabu121/SemEval-Task-5-Clickbait-Spoiler-for-SemEval-Task/blob/main/data/train.jsonl)
- [800 posts for validation](https://github.com/SidharthBabu121/SemEval-Task-5-Clickbait-Spoiler-for-SemEval-Task/blob/main/data/validation.jsonl)


## Installation of dependencies (to run on colab follow the colab section as the dependencies are already installed in google colab environment)

1) Please refrence this link: https://www.makeuseof.com/tag/install-pip-for-python/, to install pip for Windows, Mac, Linux

2) Please create a virtual enviornment  using venv  (https://docs.python.org/3/library/venv.html)

3) pip install -U pip

4) pip install -r requirements.txt
 
5) After git cloning this project, please go to the data folder and unzip the qa file.

## Setting up data for colab
#setting-up-data-for-colab

1) Before running the notebooks right click folder named "data" and "models" located in "NLP243_2022/Group1" folder of google drive.

2) Select "Add shortcut to Drive"

3) Select "My Drive"

4) Select "ADD SHORTCUT"

This will ensure all the data paths are setup to run in colab.

## Executing Notebooks:

1) The project contains three folder:
    - data       ->  Contains all the raw train and validation data for all models
    - models     ->  Folder where we save the best models for spoiler classification. 
    - notebooks  ->  Folder containing model notebooks

2) In the notebooks folder, there are 5 notebooks for each model we designed and test:
    1. nlp_243_project_classification_svm.ipynb 
    2. nlp_243_project_classification_bert.ipynb
    3. nlp_243_project_classification_bert_lstm.ipynb
    4. nlp_243_project_qa_bert.ipynb
    5. nlp_243_project_qa_roberta.ipynb
    
3) Execute each of the notebooks sequentially (in the same order as shown above):
    - To execute them, please change (in the second cell) the "root_path" to the path of the data folder and execute the notebook.
        - To run in Colab
            1. If you have setup the shortcuts as mentioned in the section ["Setting up data for colab"](#setting-up-data-for-colab) you won't have to change "root_path" as all the paths are already setup.
            2. Select "Runtime"
            3. Select "Change Runtime Type"
                - Select "Hardware Accelerator" as "GPU"
            4. Select "Run All"
            5. Select " Connect to Google Drive" when prompted
            6. Select the Account you want to use
            7. Select "Allow"
    - The results and graphs of each notebook are present at the bottom.
 

 


