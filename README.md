
# SKIN CANCER DETECTION
The "SKIN CANCER DETECTION" project integrates dermatoscopy with advanced neural networks to enhance automated diagnosis of skin conditions. Drawing inspiration from a 1994 study on melanoma-mole differentiation, our project overcomes limitations by utilizing a more diverse dataset and modern deep learning techniques, especially convolutional neural networks (CNNs). Despite technological advancements, the project highlights the critical challenge of a limited supply of high-quality images for training precise diagnostic computer programs in the realm of skin diseases.

![img alt](https://github.com/NihaalChowdary/Skin-cancer-detection/blob/53a9ae0c1b5f9e4c96b0d76d5b6d535c67991a4b/skin%20images.png)

## Table of Contents
1. [Introduction](#introduction)
   - [overview](#overview)
   - [objective](#objective)
   - [significance](#significance)
2. [Dataset](#dataset)
   - [Data Quality and Ground Truth](#Quality)
3. [Features](#features)
4. [Model Architecture](#architecture)

   
## Introduction

### Overview

Our **Skin Cancer Detection** project involves integrating dermatoscopy, a technique for detailed skin lesion examination, with advanced neural networks to automate diagnosis. Dermatoscopy offers high-quality images crucial for machine learning training. This project aims to overcome existing limitations by using a more diverse dataset and modern deep learning techniques, particularly convolutional neural networks (CNNs).

### Background

In 1994, a study utilized dermatoscopic images for melanoma-mole differentiation, but it was limited by a small dataset. Despite technological advancements, the scarcity of high-quality images representing varied skin diseases remains a significant challenge in training computer programs for precise diagnosis. This project addresses this critical issue by expanding the dataset and leveraging CNNs to improve diagnostic accuracy.

### Objective

The primary objective of the **Skin Cancer Detection** project is to develop a robust, automated diagnostic system that can accurately differentiate between various skin conditions using dermatoscopic images. By enhancing the dataset diversity and employing state-of-the-art deep learning models, we aim to create a reliable tool for early skin cancer detection.

### Significance

By integrating dermatoscopy with advanced neural networks and utilizing a diverse dataset, this project aims to significantly improve the accuracy and reliability of automated skin cancer diagnosis. This has the potential to enhance early detection, reduce diagnostic errors, and ultimately improve patient outcomes in dermatology.


### Dataset

To tackle the challenge of limited and homogeneous dermatoscopic image datasets, we utilize the **HAM10000** ("Human Against Machine with 10000 training images") dataset. This dataset comprises 10,015 diverse images sourced from varied populations and acquisition modalities. It covers essential diagnostic categories, including:

- Actinic keratoses
- Basal cell carcinoma
- Melanoma

https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T  

### Data Quality and Ground Truth

The HAM10000 dataset includes over 50% of lesions confirmed through histopathology. For other cases, ground truth is determined by follow-up examinations, expert consensus, or in-vivo confocal microscopy confirmation. This ensures high data quality and reliable ground truth for training and validation.


### Evaluation

While the test set remains non-public, an evaluation server ensures fair method comparisons using the official test set on the challenge website. This fosters standardized assessments in the development of automated pigmented skin lesion diagnosis, promoting transparency and comparability of different methodologies.


## Features

- Integration of dermatoscopy with advanced neural networks
- Utilization of convolutional neural networks (CNNs) for automated diagnosis
- Extensive and diverse dataset (HAM10000) with over 10,000 images
- Coverage of essential diagnostic categories like actinic keratoses, basal cell carcinoma, and melanoma
- Ground truth for lesions confirmed through various methods, including histopathology

## Architecture
![Image](https://github.com/NihaalChowdary/Skin-cancer-detection/blob/main/Architecture-of-Inception-v3.png)
