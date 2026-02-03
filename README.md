## Amine-Gender-Classification
This is my first Kaggle competition project, focused on classifying gender (male/female) from anime face images using deep learning.
The model is trained using MobileNetV2, a lightweight pretrained CNN, which allows efficient training while maintaining good performance.

### Project Overview
Anime characters often have stylized facial features that make gender classification challenging.
This project applies computer vision to learn gender-related visual patterns from anime faces.

### Model & Method

**Model:** MobileNetV2 (pretrained on ImageNet)

**Task:** Binary classification (Male / Female)

**Framework:** PyTorch

### Approach:

* Load image–label pairs from CSV files

* Apply image transformations and augmentation

* Fine-tune a lightweight pretrained model

### Training Details

* Loss Function: CrossEntropyLoss

* Optimizer: Adam

* Learning Rate: 0.0001

* Batch Size: 32
