# Palmprint Recognition (Gabor + PCA + KNN / SVM)

This project was conducted during my second undergraduate year as part of my early AI learning journey, under the guidance of Professor Jizhao Liu.

It presents a classical palmprint recognition pipeline based on Gabor feature extraction and PCA + KNN / PCA + SVM classification.  
All code was implemented and executed on **Google Colab**, and can be run directly.

---

## Overview

- Hand-crafted feature extraction using **Gabor filters**
- Dimensionality reduction via **PCA**
- Classification using **KNN** and **SVM**
- Dataset includes palmprint data from **Hong Kong Polytechnic University** and my own collected samples

The complete pipeline (feature extraction, training, and testing) is provided in `final.ipynb`, excluding the initial raw data preprocessing.

---

## Dataset

- **101 subjects**
- **6 images per subject** (total **606 images**)

Data split:
- First **5 images per subject** → training / validation
- Last **1 image per subject** → final testing (101 images)

Training takes approximately **1 minute** on **Google Colab (TPU)**.

Due to GitHub file size limits, the dataset and intermediate files are hosted on Google Drive:

👉 https://drive.google.com/drive/folders/1yfT0I9lCGvcaNuiCcEzSNtlbPGl-NzZa?usp=sharing

---

## Repository Structure

.
├── makenpy.ipynb # Gabor feature extraction & feature file generation
├── final.ipynb # PCA + KNN/SVM training and evaluation
└── README.md


---

## Acknowledgements

- **Professor Jizhao Liu** — supervision and guidance  
- **Hong Kong Polytechnic University Palmprint Dataset**
