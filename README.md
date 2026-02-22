# Drone-Semantic-Segmentation-Unet
Semantic Segmentation of drone imagery using U-Net and EfficientNet-b0 backbone in PyTorch.

 # Project Overview

This project implements Multiclass Semantic Segmentation on aerial drone imagery using the U-Net architecture with a pre-trained EfficientNet-b0 backbone. The goal is to classify various land cover types (roads, buildings, vegetation, etc.) from a bird's-eye view.

# Key Features
- Custom Dataset Class: Handles large-scale drone images and masks with custom remapping for 24 classes.
- SOTA Architecture: Utilizes segmentation_models_pytorch for an efficient U-Net implementation.
- Data Pipeline: Includes robust preprocessing, remapping of non-consecutive labels, and train-test splitting.
- Visualization: Includes a dedicated pipeline to visualize predictions against ground truth.

# Tech Stack
- Framework: PyTorch
- Model: U-Net (Encoder: EfficientNet-b0)
- Library: Segmentation Models PyTorch (SMP)
- Dataset: Semantic Drone Dataset

# Results

<img width="719" height="563" alt="Screenshot 2026-02-23 010858" src="https://github.com/user-attachments/assets/4a6be3ef-464d-4e1a-96e1-597c650444e7" />
<img width="1474" height="495" alt="Screenshot 2026-02-23 011212" src="https://github.com/user-attachments/assets/8926e27f-481a-4adb-bbfa-dd57b9d118f1" />

<img width="1475" height="712" alt="Screenshot 2026-02-23 011308" src="https://github.com/user-attachments/assets/ac40e9cd-0216-4b96-a06e-aeb1c792da93" />
