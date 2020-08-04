# Shopee Code League 2020 - Product Detection

## Overview
Shopee Code League is a 2-month online coding challenge consisting of a series of competitions, online algorithm questions and online training workshops open to all students and professionals across the region. The Product Detection competition was opened for two weeks and the main goal is to correctly categorize product images. 

## Task
Shopee provided us with ~100k images with 42 different categories (with the categoray names being desensitized for confidentiality purposes). Images are not very clean (e.g. some are in wrong categories, there are varieties of image sizes, and multiple images in one image file, etc.). The test data contains ~12k images. 

## Approach
I tried using two different existing models:
- EfficientNet B4 (used TPU via Kaggle notebook)
- MobileNet V2 (used GPU via Google Colab) 

## Result
EfficientNet B4 is much faster to train and produce a significantly higher accuracy (79.56%) than MobileNet V2, EfficientNet B4 model was used for the submission.
