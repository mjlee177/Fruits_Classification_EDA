# Fruits_Classification_EDA

This repository is for the UC Berkeley ML & AI Capston Project Assignment 20.1: Exploratory Data Analysis.  Also included in this assignment is a baseline model, EfficientNetV2B0.

The selected project is for image classification of fruits into 5 categories: 
- Apples
- Bananas
- Grapes
- Mangoes
- Strawberries.

The dataset can be found on Kaggle here: https://www.kaggle.com/datasets/utkarshsaxenadn/fruits-classification/data

## Observations of the data
The pictures are of various shapes, sizes, colors, and lighting conditions. Some are pictures taken with a camera, some are computer generated, and some are drawn by hand. 
All types of scenes and angles are taken of the fruits, including whole, sliced, peeled, bitten, plucked, on the tree/ vine, and arranged on dishes. 
Some pictures even have false colors (like a blue apple) or are in black-and-white. 
What is consistent among these images is that the fruits are true to shape, meaning there's no mashed banana, apple sauce, grape juice, or other byproducts. If there is a picture of a byproduct (e.g. strawberry cake), the fruit is there as well. 
Some images are of the full fruit, some are in bunches, some are only partially on the image or some of the fruit is not exactly true to shape because it's dipped in chocolate or something similar.

## EDA and plots
The EDA portion first takes a look at the resolution of the existing images and plots frequencies for width and height so that we can get a quickly visual.  
The next portion has code to confirm uploads were of the numbers (1940 train, 40 validation, 20 test for each category) and percentages expected (20% for each of the 5 categories).
Please note that anaconda online would not allow for successful uploading of all images, so these plots do not match the provided data.
I will try to switch to Colab or something else for the final project.

## Modeling
The modeling portion applies the EfficiencyV2B0 model as a baseline.  The initial results (without hypertuning) were bad with a maximum accuracy of 0.2559 on training data and 0.2450 on validation data. 
Further methods could be tested, but it will be better to try more models and then focus on which ones have produced the best initial accuracies.
