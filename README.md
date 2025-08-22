## 1. Introduction

This project explores the application of Quantum Neural Networks (QNNs) for breast cancer detection using the BreastMNIST dataset. The main goal is to evaluate the feasibility and potential of quantum machine learning in healthcare, particularly in medical image classification under resource-constrained scenarios.

Objective: Detect breast cancer (benign vs malignant) from X-ray images.

Quantum Model: QNN built with Qiskit.

Benchmark: Compared against a classical neural network trained on the same features.

Focus: Circuit depth optimization, feature encoding strategies, and scalability analysis.

## 2. Dataset

Dataset: BreastMNIST (MedMNIST collection)

Samples: 7,780 mammogram images.

Task: Binary classification (benign vs malignant).

Preprocessing: Extracted statistical features (mean, std, entropy) for both classical and quantum pipelines.

## 3. Notebooks

This project includes three main notebooks:

QuantumSimulation.ipynb

Implements a QNN with Qiskit on raw BreastMNIST features.

Establishes baseline performance of quantum circuits without feature selection.

QuantumSimulationUsingFeatureSelectedFile.ipynb

Incorporates feature selection (mean, std, entropy) prior to quantum encoding.

Reduces circuit depth and improves QNN performance and training stability.

TrichXuatDacTrung_ModelTruyenThong.ipynb

Implements a classical neural network (PyTorch) trained on the same extracted features.

Provides a benchmark to compare classical vs quantum approaches.

## 4. Results

QNN demonstrates feasibility in binary medical classification tasks under feature-reduced settings.

Classical NN generally achieves higher accuracy but QNN shows promising scalability.

Results highlight the potential role of QNNs in future medical diagnostic pipelines.

## 5. Future Work

Library migration: Transitioning to PennyLane for improved flexibility and hybrid training.

Optimization: Experimenting with circuit depth reduction and feature maps for larger datasets.

Applications: Integrating QNN pipelines into broader healthcare AI research (Project 2).

## 6. Author

Nguyễn Hoàng Nam

Nguyễn Thái Nguyên

Email: 

ng.h.nam0802@gmail.com (Nguyễn Hoàng Nam)


LinkedIn: www.linkedin.com/in/nghnam0802
