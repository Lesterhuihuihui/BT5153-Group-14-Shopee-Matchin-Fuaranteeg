## BT5153-Group-14-Shopee-Matching-Guarantee
This project is one for BT5153 module of NUS, which was conducted by Ji Lincheng, Li Qiaojun, Liu Binghui, Zhao Heng and Patrick Ye Li.

## Conpetition Description
<img width="576" alt="1650618774(1)" src="https://user-images.githubusercontent.com/92854200/164675738-926038bf-0624-4e0b-877a-81d16af04982.png">
The aim of this competition is to predict which items are the same products. This is source code/solution to get the Silver Medal in Shopee - Price Match Guarantee.

## Our working pipeline
For 1st model clustering methods:
![caa5c2cf6207d7358cf011a8d12d742](https://user-images.githubusercontent.com/92854200/164971975-bc218c4d-c0b3-49d5-8729-3676ae7eb6f5.png)

For 2rd deep learning and NLP model:

<img width="619" alt="1650796000(1)" src="https://user-images.githubusercontent.com/92854200/164972068-7f87082f-6b59-491f-a318-9fbe361c73f8.png">

For 3rd model with fine tune
![image](https://user-images.githubusercontent.com/92854200/164682981-8716b678-9693-416a-b93e-3a3ada0ea8dd.png)
![image](https://user-images.githubusercontent.com/92854200/164682961-73d9e0e9-3ce4-4bef-ac1d-54e49d8719ed.png)

## Our F1 Score
For ML Models: 0.63
For NLP Baseline: 0.73
For NLP with Fine tuned: 0.83

## Disclaimer
This is our work, we DO NOT represent any organization except our BT5153 project
There's no reproducibility guarantee for notebook which uses GPU and TPU
Dataset and generated dataset falls under Shopee Terms and Conditions which can be seen on Kaggle related competition

## Reproducibility Guide
This guide assume you have necessary files (full dataset provided by Shopee and dependency datasets), move it to correct directory path and run it on Kaggle Notebook.
For EDA: You can run All EDA notebook within the EDA files.
For Our First Model: Install related libraries, and then run them in notebook
For Our NLP Baseline: Install related libraries, and then run them in notebook or colab or Kaggle.
For Our Final (3rd) model: You need to run Data Augmentation notebook, Image Feature Notebook and then run the final model to get best results.
