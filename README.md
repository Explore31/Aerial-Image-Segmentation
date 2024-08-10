# Aerial Image Segmentation with PyTorch

## Overview

This project demonstrates how to perform aerial image segmentation using PyTorch and various libraries such as `segmentation-models-pytorch` and `albumentations`. The dataset used is a subset of the Massachusetts Roads Dataset, which consists of 200 aerial images with corresponding masks.

## Table of Contents

- [Installation](#installation)
- [Dataset](#dataset)
- [Setup Configurations](#setup-configurations)
- [Data Preparation](#data-preparation)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [References](#references)
- [License](#license)

## Installation

To set up the Colab GPU runtime environment, execute the following commands:

```python
!pip install segmentation-models-pytorch
!pip install -U git+https://github.com/albumentations-team/albumentations
!pip install --upgrade opencv-contrib-python
