# Assignment 3: Binary Segmentation of Synthetic Geometric Shapes Using U-Net

| Files | Purpose |
|---|---|
|`Generated_Data.m`| MatLAB code used to generate data of three geometrical shapes 1,000 training images and 67 test images |
|`U-net_Performance.ipynb`| Python Google Colab notebook that trains the U-net based on the generated data and evaluates the performance |

1. Description
The objective of this project was to develop and evaluate the U-net for binary segmentation of synthetic grayscale images with different geometrical shapes. The geometrical shapes are placed randomly placed, rotated, and differ in size. The model is trained on the generated dataset and performance is evaluated using a metrics TP, TN, FP, FN.

2. Requirements & How to Run 

- MatLAB is required to run the file Generated_Data.m code to obtain the generated data. After running the code the data set will be placed into a folder named "data" where subfolders will be located labeled "train" and "test". This provides the images needed to train a U-Net.
- From the repository copy the code from file U-net_Performance.ipynb into Google Colab and ensure the dataset from the MatLAB code is available. If ran on a local environment the path in which the code is located in, such as google drive, change the path to the directory in which the MatLAB dataset was downloaded in. The U-net code can be ran as normal. 
