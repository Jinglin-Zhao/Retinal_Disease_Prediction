# Retinal_Disease_Prediction
Utilizing machine learning to classify retinal diseases, improving diagnosis and treatment outcomes for patients.
## Overview
This repository contains the implementation of a U-Net model for classifying retinal diseases. The U-Net architecture is widely used for tasks like semantic segmentation and medical image analysis, making it suitable for our classification task.

## Data Source
The dataset used for training, testing, and evaluation was obtained from Kaggle and is provided in three zip files: Test_Set.zip, Training_Set.zip, and Evaluation_Set.zip. The dataset contains retinal fundus images with various retinal diseases, including diabetic retinopathy, age-related macular degeneration, myopia, and many others.

## Model Evaluation Metric
To evaluate the model's performance, we utilize the area under the curve (AUC) of the receiving operator characteristic (ROC). AUC-ROC is a suggested metric for multilabel classification tasks, and it is an appropriate choice for assessing our U-Net model's accuracy.

## Domain Knowledge
To better understand the results and interpretations, it is essential to have some domain knowledge about retinal disease abbreviations. All abbreviations used in the classification correspond to the definitions found in the source paper "Retinal Fundus Multi-Disease Image Dataset (RFMiD): A Dataset for Multi-Disease Detection Research."

## Abbreviations 
include DR (Diabetic retinopathy), ARMD (Age-related macular degeneration), MH (Media haze), DN (Drusen), MYA (Myopia), BRVO (Branch retinal vein occlusion), and many others.

## References
Retinal Disease Classification in TensorFlow - Kaggle Notebook： 
https://www.kaggle.com/code/anthodata/retinal-disease-classification/notebook
Retinal Disease Classification - Kaggle Notebook：
https://www.kaggle.com/code/nicholasmcelroy/retinal-disease-classification-in-tf#Retinal-Disease-Classification:-Multiclass-Classification

For more details and code implementation, please refer to the notebooks and files in this repository.




