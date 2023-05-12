# Spoiler Classification in Book Reviews
This project is for the course `CIS5200: Machine Learning (Fall 2022)`.

## Abstract
Book spoilers on review websites can detract from a user's experience consuming 
media. In this project we seek to build a system that automatically detects 
spoiler sentences. We frame the problem as a sentence-level binary 
classification task and experiment with different machine learning models 
(logistic regression, perceptrons, random forests) and transfer learning with 
large-language models. We address a class imbalance problem in our dataset by 
using Area Under Curve (AUC) as our primary evaluation metric, and 
experimenting with different class weightings, sampling strategies, and loss 
functions. Our best performing model proves to be logistic regression, which 
achieves a test AUC of 0.785.

## Contributors
- Akash Sundar
- Rohan Saraogi
- Shikha Reddy