# ComputerVision

This repository contains Jupyter notebooks covering a wide range of computer vision topics including transfer learning, generative models, autoencoders, image segmentation, and medical image analysis.

## Contents

### Notebooks

| File | Description |
|------|-------------|
| `transfer_learning.ipynb` | Comprehensive guide to transfer learning and fine-tuning neural networks using Keras. Covers feature extraction, fine-tuning, the `trainable` attribute, and an end-to-end cats vs. dogs example. |
| `Fine_Tuning.ipynb` | TensorFlow tutorial on transfer learning and fine-tuning using MobileNetV2. Covers data preprocessing, feature extraction, freezing/unfreezing layers, and performance evaluation. |
| `resnets_transfer_learning.ipynb` | Deep dive into Residual Networks (ResNets) and transfer learning techniques. Part of CE477 Machine Learning course materials. Compares plain CNNs vs. ResNets and explores pre-trained ResNet18. |
| `segmentation.ipynb` | TensorFlow tutorial on semantic image segmentation using the Oxford-IIIT Pets dataset. Implements a U-Net-style model and covers class imbalance handling. |
| `autoencoder.ipynb` | Introduction to autoencoders covering three use cases: basic autoencoder for reconstruction, convolutional autoencoder for image denoising, and anomaly detection on ECG data. |
| `cvae.ipynb` | Convolutional Variational Autoencoder (CVAE) trained on MNIST. Covers the reparameterization trick, ELBO loss, and visualization of the 2D latent space manifold. |
| `dcgan.ipynb` | Deep Convolutional Generative Adversarial Network (DCGAN) trained on MNIST. Covers the generator, discriminator, adversarial loss functions, and training loop. |
| `pix2pix.ipynb` | Image-to-image translation using a conditional GAN (pix2pix). Covers the U-Net generator, PatchGAN discriminator, and paired image training. |
| `Skin Lesion Segmentation.ipynb` | Skin lesion segmentation using the ISIC (International Skin Imaging Collaboration) dataset. Implements deep learning models for medical image analysis. |
| `Skin_Lesion_Segmentation.ipynb` | Alternative version of the skin lesion segmentation notebook. |

### Other Files

| File | Description |
|------|-------------|
| `Generative Models.pdf` | Reference material on generative models. |

## Topics Covered

- **Transfer Learning & Fine-tuning**: Using pre-trained models (MobileNetV2, ResNet, VGG, etc.) for new tasks, feature extraction, and layer freezing
- **Residual Networks (ResNets)**: Architecture details and comparison with plain CNNs
- **Autoencoders**: Basic autoencoders, denoising autoencoders, and anomaly detection
- **Variational Autoencoders (VAEs)**: Convolutional VAEs and latent space visualization
- **Generative Adversarial Networks (GANs)**: DCGAN and conditional GAN (pix2pix)
- **Image Segmentation**: Semantic segmentation and medical image segmentation
- **Medical Image Analysis**: Skin lesion detection and segmentation (ISIC dataset)

## Requirements

To run these notebooks, you'll need:

- Python 3.x
- Jupyter Notebook or JupyterLab
- TensorFlow / Keras
- NumPy, Matplotlib, and standard scientific Python libraries

### Installation

```bash
pip install tensorflow keras jupyter numpy pandas matplotlib scikit-learn
```

## How to Run

### Option 1: Local

```bash
pip install notebook
jupyter notebook
```
Open any notebook in your browser at `http://localhost:8888`.

### Option 2: Google Colab

All notebooks are configured to run on Google Colab:
1. Open the notebook on GitHub
2. Click the **Open in Colab** badge, or upload directly to [colab.research.google.com](https://colab.research.google.com)

### Option 3: Kaggle

Some notebooks can be opened on Kaggle via the **Open in Kaggle** badge where available.

## Dataset Information

- **Oxford-IIIT Pets** — used in `segmentation.ipynb` (auto-downloaded via TensorFlow Datasets)
- **MNIST** — used in `cvae.ipynb` and `dcgan.ipynb` (auto-downloaded via TensorFlow Datasets)
- **ISIC Skin Lesion Dataset** — used in skin lesion notebooks
  - Source: ISBI2016 ISIC Part1 Training Data & Ground Truth Masks

## License

Please refer to individual notebooks for license information. Several notebooks are based on TensorFlow official tutorials under Apache License 2.0.
