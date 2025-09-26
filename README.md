# Brain Tumor MRI Classification - Akbank Deep Learning Bootcamp

## Project Overview
This project develops a deep learning model for brain tumor classification using MRI images, as part of the Akbank Deep Learning Bootcamp.

## Dataset
- **Source:** [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- **Classes:** Glioma, Meningioma, Pituitary, No Tumor
- **Total Images:** 7,022 MRI scans
- **Pre-split:** Training and testing sets provided

## Methods
- **CNN Architecture:** Custom convolutional neural network
- **Transfer Learning:** VGG16 with fine-tuning
- **Data Augmentation:** Rotation, flipping, zooming
- **Hyperparameter Optimization:** Keras Tuner integration

## Results
- **Custom CNN Test Accuracy:** 68.57%
- **VGG16 Transfer Learning Accuracy:** 82.46%

## Project Structure
```
brain-tumor-classification/
├── Akbank_Brain_Tumor_Classification.ipynb
├── requirements.txt
├── README.md
└── models/
    ├── brain_tumor_cnn.h5
    └── brain_tumor_vgg.h5
```

## Requirements
```
tensorflow>=2.8.0
matplotlib>=3.5.0
seaborn>=0.11.0
scikit-learn>=1.0.0
opencv-python>=4.5.0
numpy>=1.21.0
pandas>=1.3.0
```

## Usage
1. Clone the repository
2. Install requirements: `pip install -r requirements.txt`
3. Open and run the Jupyter notebook

## Links
- **Kaggle Notebook:** https://www.kaggle.com/code/berfintavan/deep-learning-project-brain-tumor-mri-data-set-cnn/edit
- **GitHub Repository:** https://github.com/berffin/brain-tumor-classification

---
**Akbank Deep Learning Bootcamp - September 2025**
