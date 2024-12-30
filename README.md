Tool Wear Prediction —— CdualTAL

CdualTAL: A Research on Tool Wear Prediction Based on Multi-domain Principal Feature Enhancement

# Data
The PHM 2010 dataset consists of six parts, where C1, C4, and C6 are the tool wear datasets for three different tools with labeled data, and C2, C3, and C5 are the datasets for the same three tools without labels. 
This research selects the labeled C1, C4, and C6 datasets as experimental data. Each dataset has a dimension of 315×7, containing milling force signals in the Z, Y, and X directions, vibration signals, and acoustic emission signals collected from 315 tool passes. Download the dataset at https://www.kaggle.com/datasets/rabahba/phm-data-challenge-2010

The experimental environment is shown below：
![Experimental Conditions](https://github.com/user-attachments/assets/794f785d-218d-470b-89b8-199615f39a20)

Considering the zero drift phenomenon in the C1, C4, and C6 datasets, the tool exhibits continuous wear during actual use. Therefore, the X, Y, and Z sensor signals from all three datasets were preprocessed to mitigate the effects of this issue. Twenty-four time-domain, frequency-domain, and time-frequency-domain features were extracted from the original signal samples of C1, C4, and C6.The cross-validation method iterates through alternating training and validation sets. 
# CdualTAL file
The files, **CdualTAL-C1.ipynb**, **CdualTAL-C4.ipynb** and **CdualTAL-C6.ipynb** document the experimental procedure and experimental results of the CdualTAL model on the C1, C4, and C6 tool wear data sets.
**Data process.ipynb** documents the data feature extraction process and visualisation.

# Experiments

The following figure shows the prediction results of the CdualTAL model on the PHM 2010 dataset.
![Prediction Results of CdualTAL Model](https://github.com/user-attachments/assets/7b14331c-4a09-45d8-a5db-d617a59d66f4)
