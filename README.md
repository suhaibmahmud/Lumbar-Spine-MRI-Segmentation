# Lumbar-Spine-MRI-Segmentation
## Overview
This project focuses on automatic segmentation of vertebrae and discs from Lumbar Spine MRI scans using deep learning. A CNN-based model, specifically U-Net and ResNet, is implemented using TensorFlow to achieve precise segmentation for medical image analysis.
## Features
- **Deep Learning Model**: U-Net and ResNet architecture for segmentation
- **Dataset**: Preprocessed Lumbar Spine MRI images
- **Implementation**: TensorFlow-based training and inference pipeline
- **Performance**: Evaluated using Dice coefficient and IoU metrics
## Installation
```bash
# Clone the repository
git clone https://github.com/suhaibmahmud/Lumbar-Spine-MRI-Segmentation.git
cd Lumbar-Spine-MRI-Segmentation
```
## Dataset 
### 1. Lumbar Spine MRI 
This data set contains anonymised clinical MRI study, or a set of scans, of 90-100 patients with symptomatic back pains. Each patient data can have one or more MRI studies associated with it.  Each study contains slices, i.e., axial view, of the lowest three vertebrae and the lowest three IVDs. The axial view slices are mainly taken from the last three IVDs – including the one between the last vertebrae and the sacrum. The orientation of the slices of the last IVD are made to follow the spine curve whereas those of the other IVDs are usually made in blocks – i.e., parallel to each other. There are between four to five slices per IVD and they begin from the top of the IVD towards its bottom. Many of the top and bottom slices cut through the vertebrae leaving between one to three slices that cut the IVD cleanly and show purely the image of that IVD. In most cases, the total number of slices in axial view ranges from 12 to 15. However, in some cases, there may be up to 20 slices because the study contains slices of more than last three vertebrae.
### 2. Ground Truth Labels Data
We have accessed datasets of "lumbar spine MRI" from mendely datasets. This dataset contains the raw label images and ground truth label images of axial view slices of lumbar spine MRI used to train SegNet to detect lumbar spinal stenosis. The four labelled Regions of Interest namely 1) Intervertebral Disc (IVD), 2) Posterior Element (PE), 3) Thecal Sac (TS) and 4) the Area between Anterior and Posterior (AAP) vertebrae elements.
## Evaluation Metrics
- **Dice Coefficient**: Measures the overlap between predicted and ground truth masks.
- **IoU (Intersection over Union)**: Evaluates segmentation accuracy.
![mean_iou](https://github.com/user-attachments/assets/64455946-df38-43b0-814b-75b7b30b3bf9)
![Resnet roc](https://github.com/user-attachments/assets/c800f9c4-a94c-4a7d-9125-fd9fb98cc00c)
## Contact
For any queries, reach out via [LinkedIn](https://www.linkedin.com/in/suhaib-mahmood-511a7326b/) or [GitHub](https://github.com/suhaibmahmud).

