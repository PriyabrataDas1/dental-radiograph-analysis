# Dental Radiograph Analysis using Machine Learning

## Project Highlights

* Dataset Size: 5,403 dental radiographic images
* Feature Extraction: HOG (Histogram of Oriented Gradients)
* Texture Analysis: LBP (Local Binary Patterns)
* Dimensionality Reduction: Principal Component Analysis (PCA)
* Clustering Algorithm: K-Means Clustering
* Programming Language: Python
* Frameworks: OpenCV, Scikit-Learn, NumPy, Matplotlib
* Development Environment: Google Colab

---

## Overview

Dental radiographs provide valuable information for the diagnosis and assessment of oral health conditions. Manual interpretation of large image datasets can be time-consuming and subject to variability. This project explores the application of classical machine learning and image-processing techniques for dental radiograph analysis.

The workflow combines feature extraction, dimensionality reduction, clustering, and visualization methods to identify patterns within dental X-ray datasets. The project serves as an introduction to computational dental imaging and demonstrates how machine learning techniques can be applied to biomedical image analysis problems.

---

## Objectives

* Perform preprocessing of dental radiographs
* Extract structural and texture-based image features
* Compare feature representations using HOG and LBP
* Reduce feature dimensionality using PCA
* Explore image grouping using clustering techniques
* Visualize feature distributions and image relationships

---

## Dataset

### Dental Radiograph Dataset

The project utilizes a combined collection of publicly available dental radiographic images.

### Dataset Statistics

* Total images: 5,403
* Dental Radiography Dataset: 1,269 images
* Teeth Segmentation Dataset: 3,588 images
* Dental Collection Dataset: 128 images
* Image Type: Dental X-rays
* Modality: 2D Radiographic Images

---

## Methodology

The workflow consists of four major stages:

### Image Preprocessing

All images undergo preprocessing before feature extraction.

#### Preprocessing Steps

* Image resizing
* Grayscale conversion
* Normalization
* Data cleaning
* Visualization

---

### Feature Extraction

Two complementary image descriptors were used.

#### Histogram of Oriented Gradients (HOG)

HOG captures structural information and edge orientation patterns present in dental radiographs.

* Feature Vector Length: 512

#### Local Binary Patterns (LBP)

LBP captures local texture information and grayscale intensity variations.

* Feature Vector Length: 18

#### Combined Feature Vector

* Total Features: 530

---

### Dimensionality Reduction

To reduce computational complexity and improve visualization, Principal Component Analysis (PCA) was applied.

#### PCA Configuration

* Input Features: 530
* Principal Components Retained: 50

PCA enabled visualization of complex image features while preserving important variance within the dataset.

---

### Unsupervised Learning

K-Means clustering was employed to identify image groups based on extracted features.

#### Clustering Configuration

* Number of Clusters: 5
* Input: PCA-reduced feature space

The clustering analysis helped identify similarities and variations among dental radiographs without requiring manual labels.

---

## Experimental Workflow

1. Dental radiograph collection and preprocessing
2. HOG feature extraction
3. LBP feature extraction
4. Feature vector concatenation
5. PCA dimensionality reduction
6. K-Means clustering
7. Visualization of clusters and feature distributions
8. Analysis of image groupings

---

## Key Results

* Successfully processed 5,403 dental radiographs
* Extracted 530-dimensional feature representations
* Reduced feature space to 50 principal components
* Identified image groupings using K-Means clustering
* Demonstrated the applicability of classical machine learning techniques to dental imaging datasets

---

## Technologies Used

### Programming

* Python

### Computer Vision

* OpenCV
* NumPy

### Machine Learning

* Scikit-Learn

### Data Visualization

* Matplotlib

### Development Environment

* Google Colab

---

## Applications

* Dental Image Analysis
* Biomedical Image Processing
* Pattern Recognition
* Dental Informatics
* Computer-Aided Diagnosis
* Healthcare AI

---

## Future Work

Potential future extensions include:

* CNN-based classification
* Deep Learning feature extraction
* Dental disease detection
* Tooth segmentation using U-Net
* GAN-based augmentation
* Explainable AI techniques
* Automated diagnosis systems

---

## Repository Structure

dental-radiograph-analysis/

├── README.md

├── Dental_Radiograph_Analysis.ipynb

├── requirements.txt

└── LICENSE

---

## Conclusion

This project demonstrates how classical machine learning and image-processing techniques can be applied to dental radiographs for exploratory analysis and pattern discovery. The workflow establishes a foundation for future research involving deep learning, segmentation, classification, and computer-aided dental diagnosis systems.

---

## Author

Priyabrata Das

Biomedical Engineering

National Institute of Technology Rourkela

GitHub: https://github.com/PriyabrataDas1

LinkedIn: https://www.linkedin.com/in/priyabrata-das-74244033b/

---

## Keywords

Dental Radiography, Machine Learning, HOG, LBP, PCA, K-Means Clustering, Biomedical Image Analysis, Computer Vision, Healthcare AI, Dental Informatics

---

## Citation

If you use this repository in academic work, research, or educational projects, please cite:

Das, P. Dental Radiograph Analysis using Machine Learning. GitHub Repository, 2026.

Repository:

https://github.com/PriyabrataDas1/dental-radiograph-analysis

---

## License

This project is released under the MIT License.
