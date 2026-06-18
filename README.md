# Dental Radiograph Analysis using Machine Learning and Deep Learning

## Project Highlights

* Institution: Indian Institute of Science (IISc), Bangalore
* Research Area: Biocomputation and Biomedical Image Analysis
* Dataset Size: 5,403 dental radiographic images
* Feature Extraction: HOG (Histogram of Oriented Gradients)
* Texture Analysis: LBP (Local Binary Patterns)
* Dimensionality Reduction: Principal Component Analysis (PCA)
* Visualization: t-SNE
* Clustering Algorithms: K-Means and DBSCAN
* Anomaly Detection: Isolation Forest
* Deep Learning: VGG16-based Feature Extraction
* Segmentation Components
* Programming Language: Python
* Frameworks: TensorFlow, Scikit-Learn, OpenCV
* Development Environment: Google Colab

---

## Overview

This project was developed during my summer research internship at the Indian Institute of Science (IISc), Bangalore, as part of a biocomputation-focused study exploring machine learning and deep learning approaches for biomedical image analysis.

The work investigates dental radiograph analysis using a combination of classical image processing, machine learning, and deep learning techniques. The workflow integrates feature extraction, dimensionality reduction, clustering, anomaly detection, visualization, and transfer learning approaches to explore patterns within dental radiographic datasets and establish a foundation for future AI-assisted dental imaging applications.

---

## Objectives

* Perform preprocessing of dental radiographs
* Extract structural and texture-based image features
* Explore feature-space visualization techniques
* Identify image clusters using unsupervised learning
* Detect anomalous image patterns
* Compare classical and deep-learning feature representations
* Investigate segmentation approaches for dental imaging
* Establish a foundation for future AI-assisted dental diagnosis systems

---

## Dataset

### Combined Dental Radiograph Dataset

The project utilizes a combined collection of publicly available dental radiographic datasets.

### Dataset Statistics

* Total Images: 5,403
* Dental Radiography Dataset: 1,269 images
* Teeth Segmentation Dataset: 3,588 images
* Additional Dental Collection Dataset: 128 images
* Image Type: Dental X-rays
* Modality: 2D Radiographic Images

---

## Methodology

### Image Preprocessing

All images underwent preprocessing before feature extraction and analysis.

#### Preprocessing Steps

* Image resizing
* Grayscale conversion
* Normalization
* Visualization and quality inspection
* Dataset preparation

---

### Feature Extraction

Two complementary image descriptors were implemented.

#### Histogram of Oriented Gradients (HOG)

HOG was used to capture structural information and edge orientation patterns within dental radiographs.

* Feature Vector Length: 512

#### Local Binary Patterns (LBP)

LBP was used to capture local texture information and grayscale intensity variations.

* Feature Vector Length: 18

#### Combined Feature Representation

* Total Features: 530

---

### Dimensionality Reduction

#### Principal Component Analysis (PCA)

To reduce computational complexity and improve visualization:

* Input Features: 530
* Principal Components Retained: 50

#### t-SNE Visualization

t-SNE was applied to visualize feature distributions and explore underlying image relationships within lower-dimensional feature spaces.

---

### Unsupervised Learning

#### K-Means Clustering

* Pattern Discovery
* Image Grouping
* Cluster Analysis

#### DBSCAN Clustering

* Density-Based Clustering
* Outlier Identification
* Non-linear Cluster Discovery

---

### Anomaly Detection

#### Isolation Forest

Isolation Forest was employed to identify anomalous radiographs and investigate unusual feature-space distributions.

Applications included:

* Outlier Detection
* Image Quality Assessment
* Exploratory Pattern Analysis

---

### Deep Learning

#### VGG16 Feature Extraction

Transfer learning using a pre-trained VGG16 architecture was explored to generate high-level feature representations from dental radiographs.

Applications:

* Deep Feature Embedding
* Representation Learning
* Comparative Feature Analysis

---

### Segmentation Components

Preliminary segmentation experiments were conducted to investigate region-based analysis and future tooth-segmentation workflows.

---

## Experimental Workflow

1. Dataset Collection and Preparation
2. Image Preprocessing
3. HOG Feature Extraction
4. LBP Feature Extraction
5. Feature Vector Construction
6. PCA Dimensionality Reduction
7. K-Means Clustering
8. DBSCAN Clustering
9. Isolation Forest Anomaly Detection
10. t-SNE Visualization
11. VGG16 Deep Feature Extraction
12. Segmentation Analysis
13. Results Evaluation

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
* PCA
* K-Means
* DBSCAN
* Isolation Forest

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
* Computer Vision
* Pattern Recognition
* Anomaly Detection
* Dental Informatics
* Computer-Aided Diagnosis
* Healthcare AI

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

```text
dental-radiograph-analysis/

├── README.md
├── Dental_Radiograph_Analysis.ipynb
├── requirements.txt
└── LICENSE
```

---

## Research Significance

Dental imaging datasets often contain large variations in image quality, anatomical structure, and acquisition conditions. This project demonstrates how machine learning, computer vision, and deep learning techniques can be combined to extract meaningful information from dental radiographs and explore image patterns without requiring extensive manual annotations.

The workflow provides a foundation for future research in automated dental image analysis, segmentation, anomaly detection, and AI-assisted diagnostic systems.

---

## Conclusion

This project demonstrates the application of classical machine learning, computer vision, and deep learning techniques to dental radiograph analysis. By combining feature extraction, dimensionality reduction, clustering, anomaly detection, visualization, and transfer learning, the workflow establishes a robust foundation for future AI-assisted dental imaging research.

---

## Author

Priyabrata Das

B.Tech, Biomedical Engineering

National Institute of Technology Rourkela

Summer Research Intern, Indian Institute of Science (IISc), Bangalore

GitHub: https://github.com/PriyabrataDas1

LinkedIn: https://www.linkedin.com/in/priyabrata-das-74244033b/

---

## Keywords

Dental Radiography, Biomedical Image Analysis, Machine Learning, Deep Learning, Computer Vision, HOG, LBP, PCA, t-SNE, K-Means, DBSCAN, Isolation Forest, VGG16, Healthcare AI

---

## Citation

If you use this repository in academic work, research, or educational projects, please cite:

Das, P. *Dental Radiograph Analysis using Machine Learning and Deep Learning*. GitHub Repository, 2026.

---

## License

This project is released under the MIT License.
