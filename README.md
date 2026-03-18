# ComputerVision

This repository contains Jupyter notebooks covering various computer vision topics including transfer learning, image segmentation, and skin lesion analysis.

## Contents

### Notebooks

| File | Description |
|------|-------------|
| `transfer_learning.ipynb` | Comprehensive guide to transfer learning and fine-tuning neural networks using Keras. Covers feature extraction, fine-tuning, and practical applications. |
| `resnets_transfer_learning.ipynb` | Deep dive into Residual Networks (ResNets) and transfer learning techniques. Part of CE477 Machine Learning course materials. |
| `segmentation.ipynb` | TensorFlow tutorial on image segmentation, including semantic segmentation techniques for computer vision tasks. |
| `Skin Lesion Segmentation.ipynb` | Skin lesion segmentation using the ISIC (International Skin Imaging Collaboration) dataset. Implements deep learning models for medical image analysis. |
| `Skin_Lesion_Segmentation.ipynb` | Alternative version of the skin lesion segmentation notebook. |

## Requirements

To run these notebooks, you'll need:

- Python 3.x
- Jupyter Notebook or JupyterLab
- TensorFlow
- Keras
- Other dependencies (see individual notebooks for details)

### Installation

```bash
# Install required packages
pip install tensorflow keras jupyter numpy pandas matplotlib scikit-learn
```

## How to Run

### Option 1: Local Installation

1. Install Jupyter Notebook:
```bash
pip install notebook
```

2. Start Jupyter:
```bash
jupyter notebook
```

3. Open any notebook in your browser (typically at `http://localhost:8888`)

### Option 2: Google Colab

All notebooks are configured to run on Google Colab. You can:

1. Open the notebook in GitHub
2. Click the "Open in Colab" badge at the top of each notebook
3. Or upload the notebook directly to Google Colab

### Option 3: Kaggle

Some notebooks can also be opened on Kaggle by clicking the "Open in Kaggle" badge (where available).

## Dataset Information

### ISIC Skin Lesion Dataset

The skin lesion segmentation notebooks use the ISIC Archive dataset:
- Training data: ISBI2016 ISIC Part1 Training Data
- Ground truth masks: ISBI2016 ISIC Part1 Training GroundTruth
- Source: https://isic-archive.s3.amazonaws.com/

## Topics Covered

- **Transfer Learning**: Using pre-trained models (VGG, ResNet, etc.) for new tasks
- **Fine-tuning**: Adapting pre-trained models to new datasets
- **Image Segmentation**: Semantic and instance segmentation techniques
- **Medical Image Analysis**: Skin lesion detection and segmentation

## License

Please refer to individual notebooks for license information. The transfer learning notebook is based on materials by François Chollet under Apache License 2.0.