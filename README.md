# Dental Radiograph Analysis using Machine Learning and Deep Learning

## Project Highlights

* Dataset Size: 5,403 dental radiographic images
* Feature Extraction: HOG (Histogram of Oriented Gradients)
* Texture Analysis: LBP (Local Binary Patterns)
* Dimensionality Reduction: Principal Component Analysis (PCA)
* Visualization: t-SNE
* Clustering Algorithms: K-Means and DBSCAN
* Anomaly Detection: Isolation Forest
* Deep Learning: VGG16-based Feature Extraction
* Image Segmentation Components
* Programming Language: Python
* Frameworks: TensorFlow, Scikit-Learn, OpenCV
* Development Environment: Google Colab

---

## Overview

Dental radiographs are widely used for the diagnosis and assessment of oral health conditions. This project explores a combination of classical machine learning, computer vision, and deep learning approaches for dental image analysis.

The workflow investigates multiple strategies for feature extraction, dimensionality reduction, clustering, anomaly detection, visualization, and deep feature learning. The objective is to understand patterns within dental radiographs and establish a computational pipeline for future diagnostic and segmentation applications.

---

## Objectives

* Perform preprocessing of dental radiographs
* Extract structural and texture-based image features
* Explore feature-space visualization
* Identify image clusters using unsupervised learning
* Detect anomalous image patterns
* Compare classical and deep-learning feature representations
* Establish a foundation for future dental AI applications

---

## Dataset

### Combined Dental Radiograph Dataset

The project utilizes a combined collection of publicly available dental radiographic datasets.

### Dataset Statistics

* Total Images: 5,403
* Dental Radiography Dataset: 1,269 images
* Teeth Segmentation Dataset: 3,588 images
* Additional Dental Collection: 128 images
* Image Type: Dental X-rays
* Modality: 2D Radiographic Images

---

## Methodology

### Image Preprocessing

* Image loading and cleaning
* Resizing and normalization
* Grayscale conversion
* Visualization and quality inspection

### Feature Extraction

#### Histogram of Oriented Gradients (HOG)

* Structural feature extraction
* Edge and shape representation
* Feature Vector Length: 512

#### Local Binary Patterns (LBP)

* Texture feature extraction
* Local intensity pattern analysis
* Feature Vector Length: 18

#### Combined Feature Representation

* Total Feature Length: 530

---

### Dimensionality Reduction

#### Principal Component Analysis (PCA)

* Input Features: 530
* Reduced Feature Space: 50 Components

#### t-SNE Visualization

* Non-linear visualization of image distributions
* Cluster exploration in low-dimensional space

---

### Unsupervised Learning

#### K-Means Clustering

* Cluster Identification
* Pattern Discovery
* Image Grouping

#### DBSCAN Clustering

* Density-Based Clustering
* Outlier Detection
* Non-linear Cluster Identification

---

### Anomaly Detection

#### Isolation Forest

* Detection of anomalous radiographs
* Feature-space outlier analysis
* Unsupervised abnormality identification

---

### Deep Learning

#### VGG16 Feature Extraction

* Transfer Learning
* Deep Feature Embedding
* High-level Image Representation

#### Segmentation Components

* Preliminary segmentation experiments
* Region-based image analysis
* Foundation for future dental segmentation models

---

## Experimental Workflow

1. Dataset Collection and Preparation
2. Image Preprocessing
3. HOG Feature Extraction
4. LBP Feature Extraction
5. PCA Dimensionality Reduction
6. K-Means Clustering
7. DBSCAN Clustering
8. Isolation Forest Anomaly Detection
9. t-SNE Visualization
10. VGG16 Deep Feature Extraction
11. Segmentation Analysis
12. Results Evaluation

---

## Technologies Used

### Programming

* Python

### Computer Vision

* OpenCV
* scikit-image
* Pillow

### Machine Learning

* Scikit-Learn
* Isolation Forest
* PCA
* K-Means
* DBSCAN

### Deep Learning

* TensorFlow
* Keras
* VGG16

### Data Processing

* NumPy
* Pandas

### Visualization

* Matplotlib
* Seaborn

### Development Environment

* Google Colab

---

## Applications

* Dental Image Analysis
* Biomedical Image Processing
* Pattern Recognition
* Anomaly Detection
* Computer-Aided Diagnosis
* Healthcare AI
* Dental Informatics

---

## Future Work

Potential future extensions include:

* CNN-Based Classification
* U-Net Tooth Segmentation
* GAN-Based Data Augmentation
* Dental Disease Detection
* Explainable AI (Grad-CAM)
* Multi-Class Dental Diagnosis
* Clinical Validation Studies

---

## Repository Structure

dental-radiograph-analysis/

├── README.md

├── DENTAL_MRI.ipynb

├── requirements.txt

└── LICENSE

---

## Conclusion

This project demonstrates the application of classical machine learning, computer vision, and deep learning techniques to dental radiograph analysis. By combining feature extraction, clustering, anomaly detection, visualization, and deep feature learning, the workflow provides a foundation for future research in AI-assisted dental diagnostics and biomedical image analysis.

---

## Author

Priyabrata Das

Biomedical Engineering

National Institute of Technology Rourkela

GitHub: https://github.com/PriyabrataDas1

LinkedIn: https://www.linkedin.com/in/priyabrata-das-74244033b/

---

## Keywords

Dental Radiography, Machine Learning, Deep Learning, HOG, LBP, PCA, t-SNE, K-Means, DBSCAN, Isolation Forest, VGG16, Biomedical Image Analysis, Computer Vision, Healthcare AI

---

## Citation

If you use this repository in academic work, research, or educational projects, please cite:

Das, P. Dental Radiograph Analysis using Machine Learning and Deep Learning. GitHub Repository, 2026.

---

## License

This project is released under the MIT License.

