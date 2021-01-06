# facemask_detection

## Overview
The facemask _detection base on SSD training Model

## Requirements

- Tensorflow 2.1.0
- python=3.7
- Kaggle(if you need)


## Getting Started
- 1.Run voc2ssd.py, then changing "xmlfilepath" & "saveBasePath" to the path you'd like

- 2.Run the voc_annotation.py:


            Line6- Changing "classes" to the classes you target. 


            Line9- "in_file"'s path shoulud be the path of your dataset's annotations-set


            Line32- "list_file.write"'s path should be the path of dataset


So far you will get 5 more txtfiles

- 3.Run train.py:


            Line2- Just for the training set up on the Kaggle plateform


            Line25- The path should be target to the 2020_train.txt


            Line27- Changing the num of the NUM_CLASSES to your target's num(the number of your classes + 1 for the background value)


            Line48- You should load your own model or you can use the begining model of mine for your firsr training


            Line70- Line88 For the rough training


            Line90- End For the fine training


## Tips
-  The datas you will need post on https://pan.baidu.com/s/1DCTQCBSdgpaGSMu7QO-HQg and the code is h4a1
Don't forget your dataset and start to TRAINING YOUR MODEL NOW  !!!
