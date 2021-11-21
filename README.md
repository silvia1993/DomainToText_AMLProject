# Advanced Machine Learning Project - Domain-To-Text 

Basic code to reproduce the baselines (point 1 of the project). 

## Dataset

1 - Download PACS dataset from here https://domaingeneralization.github.io/

2 - Place the dataset in the DomainToText_AMLProject folder making sure that the images are organized in this way:

```
PACS/kfold/art_painting/dog/pic_001.jpg
PACS/kfold/art_painting/dog/pic_002.jpg
PACS/kfold/art_painting/dog/pic_003.jpg
...
```

## Pretrained models

In order to reproduce the values reported in the table, you have to download:

1.  The models trained on each source domain from this link: 

    
2.  The pretrained model provided by Chenyun Wu et al. from this link: https://umass-my.sharepoint.com/personal/chenyunwu_umass_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fchenyunwu%5Fumass%5Fedu%2FDocuments%2Fprojects%2FTexture%2Fmy%5Frepo%2Foutput%2Ftriplet%5Fmatch%2Fda3%5Fbert%5Flr0%2E00001%2Fcheckpoints
  
    Then, you have to put it into 

    ```
    /DomainToText_AMLProject/outputs/triplet_match/
    ```
  

## Environment

To run the code you have to install all the required libraries listed in the "requirements.txt" file.

For example, if you read

```
torch==1.4.0
```

you have to execute the command:

```
pip install torch==1.4.0

```

