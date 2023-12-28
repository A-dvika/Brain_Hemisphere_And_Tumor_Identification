# Brain_Hemisphere_And_Tumor_Identification

# Brain Hemisphere Classification and Tumor Detection

This repository contains an implementation of brain hemisphere classification using SWIN Transformer and YOLOv8 for tumor detection within each hemisphere.
![image](https://github.com/A-dvika/Brain_Hemisphere_And_Tumor_Identification/assets/115079077/c73f3999-93cf-4006-9eb5-3d1e95e81965)


## Overview

This project aims to classify brain hemispheres and detect tumors within MRI images using a combination of SWIN Transformer, a state-of-the-art architecture for image processing, and YOLOv8, a robust object detection algorithm.

## Features

- **Brain Hemisphere Classification:** Utilizes SWIN Transformer to classify brain hemispheres from MRI scans.
- **Tumor Detection:** Employs YOLOv8 for precise tumor detection within each classified hemisphere.
- **Data Preprocessing:** Includes data preprocessing steps for image augmentation, normalization, and preparation.
- **Evaluation Metrics:** Provides evaluation metrics for both hemisphere classification and tumor detection accuracy.

'''The app is yet to be deployed to see how it works'''


# Overview  of architecture

![image](https://github.com/A-dvika/Brain_Hemisphere_And_Tumor_Identification/assets/115079077/a0521340-fda5-48c4-80bb-a0fa14e66b87)

### Swin Transformer

Swin Transformer, derived from "Shifted window," revolutionizes computer vision by introducing a hierarchical Transformer architecture. This model computes representations using shifted windows, optimizing efficiency through localized, non-overlapping self-attention computation. Additionally, it enables seamless cross-window connections.

#### Key Features:
- **Efficient Windowing:** Limiting self-attention computation to localized windows enhances computational efficiency.
- **Cross-Window Connectivity:** Allows seamless connections between windows for improved representation.

#### Performance:
Swin Transformer showcases remarkable performance:
- **COCO Object Detection:** Achieves 58.7 box AP and 51.1 mask AP on test-dev, surpassing previous models.
- **ADE20K Semantic Segmentation:** Delivers 53.5 mIoU on validation, demonstrating a substantial performance leap.

This repository aims to provide an accessible implementation and exploration of the Swin Transformer for computer vision tasks. Discover its capabilities and empower your vision-based projects.

For more details, check out the original [arXiv paper](link_to_paper_here).

### YOLOv8 by Ultralytics
![image](https://github.com/A-dvika/Brain_Hemisphere_And_Tumor_Identification/assets/115079077/c6a9248b-4399-40b0-82ff-56d29c774222)


Ultralytics YOLOv8 represents the pinnacle of object detection technology, refining and advancing the capabilities of previous YOLO versions. This state-of-the-art (SOTA) model introduces groundbreaking features and enhancements aimed at significantly improving performance and versatility.

#### Key Features:
- **Speed and Accuracy:** YOLOv8 is optimized for both speed and accuracy, ensuring swift yet precise object detection.
- **Ease of Use:** Designed with user-friendliness in mind, making it accessible for a variety of tasks.
- **Versatility:** Suitable for a wide range of computer vision tasks:
  - Object detection and tracking
  - Instance segmentation
  - Image classification
  - Pose estimation

YOLOv8 empowers users with a powerful tool for tackling various vision-based challenges, offering a compelling blend of speed, accuracy, and ease of implementation.

For more detailed information and usage guidelines, refer to the official Ultralytics documentation or repository.

