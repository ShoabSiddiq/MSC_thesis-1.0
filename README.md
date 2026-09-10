# MSC_thesis-1.0

MSc Artificial Intelligence and Data Science — Keele University Author: Md Shoab Siddiq (25026645) Supervisor: Dr Marco Ortolani

This repository contains the code and notebooks for my MSc dissertation, which compares four pre-trained convolutional neural networks for classifying lung histopathology images from the LC25000 dataset, and analyses the best model through an ablation and hyperparameter study.

Overview
Task: classify lung tissue patches into three classes — adenocarcinoma, benign tissue, and squamous cell carcinoma.
Dataset: LC25000 (lung subset), 15,000 images, 5,000 per class.
Split: 70% train / 10% validation / 20% test (10,500 / 1,500 / 3,000 images).
Approach: feature-extraction transfer learning — the ImageNet-pretrained base is frozen and only a custom classifier head is trained.
Best model: ResNet50, with 98.90% test accuracy.
