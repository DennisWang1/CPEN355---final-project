# Predicting Car Prices With ML

## Overview

Our team developed a machine learning model to accurately predict used car prices solely from vehicle images using Convolutional Neural Networks (CNNs). By utilizing the extensive DVM-CAR dataset of over 1.4 million images, we addressed class imbalance and reduced training times through resizing, normalizing, and filtering the dataset to create a balanced set of 225,206 images across approximately 400 car models. Our optimized CNN architecture, which includes two convolutional layers followed by dense layers for regression, achieved a Mean Absolute Error (MAE) of 8,882.9 and an R² score of 0.936, significantly outperforming a Support Vector Machine (SVM) regressor that had an MAE of 21,567. We overcame initial challenges in model design and computational efficiency by adopting an end-to-end CNN approach and strategically reducing the dataset size. This project demonstrates that a well-designed CNN can effectively predict used car prices from images, providing a robust and efficient solution for the used car market.

## Breakdown of what each folder contains

DataAnalysis: contains scripts we use to find the distribution of our data set 

TraininedModels: these are some of the best performant models that we trained, with best_cnn_model.h5 being the main focus

TrainingScripts: Scripts that we use to filter data and train models. Including CNN, classifier, and SVM

### For More Info, please checkout Project Report.pdf
