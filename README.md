# FedAD: Federated Learning with Generative Data Augmentation and Adaptive Parameter Decomposition for Rice Pest and Disease Identification

## Abstract

Rice serves as a primary global food source, yet its production is severely threatened by various pests and diseases, leading to substantial yield losses and economic instability. Traditional manual identification is labor-intensive, while emerging centralized deep learning solutions struggle with data privacy concerns and high transmission costs in rural areas.

Federated Learning (FL) offers a promising privacy-preserving alternative, but its deployment in the Internet of Agricultural Things (IoAT) is hindered by the statistical heterogeneity of pest and disease distributions (Non-IID) and strict edge resource constraints. To address these obstacles, we propose **Adaptive Parameter Decomposition Federated Learning (FedAD)**, a novel personalized federated learning framework, and introduce the **RP15** dataset.

## RP15 Dataset Overview

The **RP15** dataset was constructed to facilitate research and development in rice pest and disease identification, particularly in a federated learning context where data heterogeneity is common.

*   **Size:** Contains **12,239** images.
*   **Categories:** Covers **15** different rice pest and disease categories.

### Repository Structure

The current file structure shows the organization of the RP15 dataset:
```
RP15/
├── 00/
├── 01/
├── 02/
...
├── 14/
└── classes.docx
```

The folders named `00` through `14` represent the 15 distinct pest and disease classes.


## Code and Dataset Availability

The RP15 dataset is available in this repository.

The source code will be released upon the acceptance of the paper.
