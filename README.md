# AI-Image-Classification-Base-CNN-ResNet50

This project demonstrates image classification using two models: a custom CNN and a pretrained ResNet50. The goal is to classify images into two classes: `Real`, `AI`.


## Overview

- **Models**:  
  1. **Base CNN** – trained from scratch  
  2. **ResNet50** – pretrained on ImageNet, fine-tuned on this dataset  

- **Dataset**:  
  - 2 classes  
  - Images resized to 128x128 
  - Split into train, validation, and test sets  

- **Results (Validation Accuracy)**:  
  - Base CNN: ~94–95%  
  - ResNet50: ~97–98%  

- **Test Set Performance**:  
  - Base CNN: ~92–94%  
  - ResNet50: ~97%  
  - Confusion matrices included in the notebook for detailed analytics 

