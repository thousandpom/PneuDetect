# PneuDetect: An Algorithm to Detect the Presence of Pneumonia from Chest X-Ray Scans
*This is part of the Udaciy AI for Healthcare Nanodegree course projects.*

### Key Words:
`NIH_ChestX-ray_Dataset`, `Object_Dection`, `Keras`, `Image_Augmentation`, `Transfer_Learning`, `DICOM`, `Pneumonia`, `FDA_Software_Validation`

## Project Overview
The project consists of four parts:
- Exploratory Data Analysis of ChestX-Ray8 dataset
- Train a Keras-based CNN model, with weights pretrained on `ImageNet` dataset to classify chest x-rays to detect the presence of pneumonia. 
- Create a DICOM wrapper and predict the presence of pneumonia using DICOM files.
- Document the algorithm with a report following the FDA's official guidance. 

## Dataset
The dataset is from the NIH Chest X-ray Dataset, which consists of 112,120 X-ray scans from 30,805 patients. The labels include a `No Finding` label and 14 common thoracic pathologies, including `pneumonia`.      
The dataset can be downloaded from [kaggle website](https://www.kaggle.com/nih-chest-xrays/data). The details on the labeling process of the original radiology reports can be found in [this paper](https://arxiv.org/abs/1705.02315). 

### Dataset Contents: 

1. 112,120 frontal-view chest X-ray PNG images in 1024*1024 resolution (under images folder)
2. Meta data for all images (Data_Entry_2017.csv): Image Index, Finding Labels, Follow-up #,
Patient ID, Patient Age, Patient Gender, View Position, Original Image Size and Original Image
Pixel Spacing.
