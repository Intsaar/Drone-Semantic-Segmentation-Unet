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
 


