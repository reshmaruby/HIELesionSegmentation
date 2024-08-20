# HIELesionSegmentation
This repository contains the implementation for the segmentation of Hypoxic-Ischemic Encephalopathy (HIE) lesions in neonatal brain MRI scans. 
The project is part of my MSc dissertation aimed at improving the detection and analysis of neonatal brain injuries.

## Dataset
The dataset required for this project can be downloaded from [Zenodo](https://zenodo.org/records/8104103). 
After downloading, place the dataset in the `BONBID2023_Train/` directory within the project folder.

## Files
- `UNet.ipynb`: Jupyter Notebook implementing the U-Net model for HIE lesion segmentation.
- `ResNet18.ipynb`: Jupyter Notebook implementing a U-Net model with a ResNet-18 backbone for HIE lesion segmentation.
- `Vgg19.ipynb`: Jupyter Notebook implementing a U-Net model with a VGG-19 backbone for HIE lesion segmentation.
