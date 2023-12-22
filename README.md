# Unet-VGG16_BrainTumorMRI_Segmentation
kaggle Notebook: https://www.kaggle.com/athulnair8101/unet-vgg16-braintumormri-segmentation

![image](https://github.com/athulnairrr/Unet-VGG16_BrainTumorMRI_Segmentation/assets/132225542/219dd182-cd03-4620-b69f-43bf94d9cebc)

# Brain Tumor Segmentation Project

## Overview

This repository contains code for a brain tumor segmentation project using MRI images. The project involves building and training a U-Net model with a VGG16 encoder for accurate tumor segmentation.

## Table of Contents

- [Dataset Preparation](#dataset-preparation)
- [Data Loading](#data-loading)
- [Model Architecture](#model-architecture)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Visualizing Model Results](#visualizing-model-results)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)

## Dataset Preparation

- Organized brain MRI images and corresponding masks.
- Split the dataset into training and validation sets.
- kaggle Dataset: https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation/data

## Data Loading

- Developed code to load and preprocess data.
- Loaded and normalized images and masks.

## Model Architecture

- Implemented a U-Net model with a pre-trained VGG16 encoder.
- Combined encoder and decoder for segmentation.

## Model Training

- Trained the segmentation model using the training set.
- Implemented callbacks for model checkpointing, early stopping, and learning rate reduction.

## Model Evaluation

- Evaluated the model on the validation set for performance monitoring.

## Visualizing Model Results

- Loaded the trained model using an HDF5 file.
- Visualized predictions on sample images, comparing them with original masks.

## Exploratory Data Analysis (EDA)

- Explored the dataset using visualizations for better understanding.


