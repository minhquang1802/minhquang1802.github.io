---
title: "DUCK Net"
date: 2024-11-01T15:45:47+07:00
draft: true
author: "WanWan"
authorLink: "https://minhquang1802.github.io"
description: "An introduction of U-Net architecture"

tags: ["Blog", "Computer Vision", "Image Segmentation", "English"]
categories: ["Blog"]

lightgallery: true
---

## Motivation
This blog is a continuation of the **U-Net** model post. If you haven’t read it yet, you may want to do so first to better understand the **DUCK-Net** model, as it is based on the U-Net architecture. The purpose of this blog is to deepen my understanding of the DUCK-Net model and to summarize its role in the field of **Medical Image Segmentation**. 
>Please note that the information may not be entirely precise, as it reflects my personal perspective. I welcome any feedback and corrections, which I would greatly appreciate.

## Introduction
DUCK-Net, a supervised convolutional neural network architecture, can effectively learn and generalize from small amounts of medical images to perform accurate segmentation tasks.

While DUCK-Net’s architecture is versatile and applicable to various segmentation tasks, the paper proposed by Razvan-Gabriel Dumitru specifically demonstrates its capabilities for polyp segmentation in colonoscopy images. 

Before DUCK-Net, several models and architectures were used for polyp segmentation, such as U-Net, Fully Convolutional Network (FCN), and their variants like U-Net++, Modified U-Net (mU-Net), ResNet++, and H-DenseUNet. Although these methods achieve precise segmentation results, their performance may be less robust when faced with a wide range of polyp characteristics.

## Methodology
The key feature of DUCK-Net architecture consists of two main components. The first component is a convolutional block called **DUCK** and the second component keeps the low-level details by adding a secondary U-Net **downscaling layer** that does not process the image.
We will look more detail about this two components in the next section.

### Model architecture
DUCK-Net architecture is based on Encoder-Decoder architecture. Most of the architecture is resemble with the U-Net architecture with three significant differences.

Firstly, 

### Block components

#### Residual Block

#### Midscope Block

#### Widescope Block

#### Separated Block

#### DUCK Block

### Model evaluation

## Data Augmentation

## Result

## Reference

