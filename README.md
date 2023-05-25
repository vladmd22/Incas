#  ![](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white) Vesuvius Challenge - Ink Detection 

This Skoltech Deep Learning Course 2023 final project "Ink detection of Herculaneum scrolls"


## Problem statement

The Kaggle competition hosts the Ink Detection Progress Prize ($100,000 in prizes) of Vesuvius challenge, which focuses on the sub-problem of detecting ink from 3d x-ray scans of fragments of papyrus (figure 2) which became detached from some of the excavated scrolls.
The goal is to detecting ink from 3D X-ray scans and reading the contents.
Due to the heat of the volcano, the scrolls were carbonized, and are now impossible to open without breaking them.
We will try to find the best model to get the maximum accuracy.

For kaggle data 3D X-ray scans (54keV) were transformed into “surface volumes” and then infrared photos were aligned with these surface volumes, and binary ink masks were created to denote the presence of ink

## Our results

## Further improvement...

To enhance the model and the metric-score we want to train on full dataset
Compare different models such as Unet, Unet++, DeepLabV3+
Define the optimal augmentations for our dataset

## Installation

You can download this repo simply by cloning:

        git clone https://github.com/vladmd22/Incas

The data is given via the link:

        https://drive.google.com/drive/folders/1R8uubGEevPI9ao0tikSnQSt17e4LOtJv?usp=share_link
       
All dependencies are solved inside notebooks via !pip install.

## Team

+ Bari Khairullin
+ Yunseok Park
+ Nikita Vasilev
+ Anastasia Gavrish
+ Vladislav Mityukov
