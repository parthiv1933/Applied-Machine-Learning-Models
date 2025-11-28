# Applied-Machine-Learning-Models
# CS5691: Pattern Recognition and Machine Learning Assignments

This repository contains the reports for the programming assignments completed for the course **CS5691: Pattern Recognition and Machine Learning** during the July-November 2024 semester.

The assignments explore fundamental concepts in pattern recognition and machine learning, including regression, classification techniques, dimensionality reduction, and neural networks.



---



The following reports detail the implementation, results, and analysis for each programming assignment:

### 1. Assignment 1: Linear Regression and Regularization
**File:** `A1_Linear_Regression_Report.pdf`
* [cite_start]**Focus:** Implementation of linear regression models using polynomial basis functions[cite: 9].
* [cite_start]**Key Topics:** Quadratic regularization [cite: 10][cite_start], model complexity (polynomial degree), and performance evaluation using ERMS tables[cite: 134, 271].
* [cite_start]**Datasets:** Univariate (Dataset 1: 10 and 50 examples), Bivariate (Dataset 2: 25 and 100 examples), and Multivariate (Dataset 3)[cite: 12, 14, 15, 17, 18, 20].

### 2. Assignment 2: Probabilistic and Distance-Based Classifiers
**File:** `A2_Probabilistic_Classifiers_Report.pdf`
* **Focus:** Evaluation of various classifiers on linearly and nonlinearly separable data.
* **Key Classifiers:**
    * [cite_start]**K-nearest Neighbors (KNN)** [cite: 508]
    * [cite_start]**K-nearest Representatives** [cite: 907]
    * [cite_start]**Bayes Classifier** (with same and different covariance matrices for all classes) [cite: 626, 724]
    * [cite_start]**Naive-Bayes Classifier** (with same and different covariance matrices for all classes) [cite: 1139, 1211]
* [cite_start]**Datasets:** Linearly Separable (Dataset 1: 3 Classes), Nonlinearly Separable (Dataset 2: 2 Classes), and Image Data (Dataset 3: 5 Classes)[cite: 506, 816, 1286].

### 3. Assignment 3: Neural Networks and Gaussian Mixture Models (GMM)
**File:** `A3_Neural_Networks_GMM_Report.pdf`
* **Focus:** Function approximation and classification using Multilayer Feedforward Neural Networks (MLFFNN) and GMM-based classifiers.
* **Key Tasks:**
    * [cite_start]**Function Approximation:** MLFFNN with one hidden layer on Dataset 1 [cite: 1658] [cite_start]and two hidden layers on Dataset 2[cite: 1747].
    * [cite_start]**Classification:** GMM-based and MLFFNN-based classifiers on Dataset 3 (Nonlinearly Separable) and Dataset 4 (Image Data)[cite: 1812, 2027].
* **Metrics:** Training error vs. epoch plots, confusion matrices, and decision region/surface plots.

### 4. Assignment 4: Support Vector Machines (SVM) and PCA
**File:** `A4_SVM_PCA_Report.pdf`
* **Focus:** Implementation of SVMs with various kernels and dimensionality reduction using Principal Component Analysis (PCA).
* **Key Tasks:**
    * [cite_start]**Linear Kernel SVM:** Classifier for Dataset 1 (Linearly Separable)[cite: 2091].
    * [cite_start]**Kernel SVMs:** Polynomial and Gaussian kernels for Dataset 2 (Nonlinearly Separable) [cite: 2153] [cite_start]and Dataset 3 (High-Dimensional Image Data)[cite: 2286].
    * [cite_start]**PCA:** Analysis on Dataset 3 to select a reduced dimension ($l=20$ for 85% variance)[cite: 2399, 2427, 2429].
    * [cite_start]**Reduced Dimension Classification:** Using GMM, MLFFNN, and SVM on the PCA-reduced Dataset 3[cite: 2432].

---



The reports are in PDF format and can be viewed directly. The figures and tables provide detailed results, confusion matrices, decision regions, and level curves for each experiment.
