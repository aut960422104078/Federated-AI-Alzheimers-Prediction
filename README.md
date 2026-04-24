# # Federated Explainable AI-based Alzheimer's Disease Prediction with Multi-Modal Data

## 📌 Project Overview
B.E Computer Science Final Year Project 2026. This research project focuses on early prediction of Alzheimer's Disease using **Federated Learning** and **Explainable AI (XAI)** on multi-modal medical data including MRI scans and clinical data.

**Problem Statement:** Traditional ML models require centralized patient data which violates privacy. Our federated approach trains models without sharing raw data, making it HIPAA compliant.

## 🛠️ Tech Stack & Architecture
- **Framework:** Python, TensorFlow Federated, Keras, NumPy, Pandas
- **Deep Learning Models:** CNN for MRI Image Analysis, LSTM for Clinical Time-Series Data
- **XAI Tools:** LIME, SHAP for model interpretability and doctor trust
- **Federated Learning:** FedAvg Algorithm for decentralized training
- **Dataset:** ADNI (Alzheimer's Disease Neuroimaging Initiative) Dataset

## 🎯 Key Features & Innovation
1. **Privacy Preserving:** Patient MRI data never leaves local hospitals using Federated Learning
2. **Explainable AI:** Doctors can understand WHY the model predicted Alzheimer's using SHAP values on hippocampus region
3. **Multi-Modal Fusion:** Combines MRI + Clinical data for 96.3% accuracy vs 89% with single mode
4. **Scalable Healthcare Solution:** Multiple hospitals can collaborate without data sharing

## 📊 Results & Performance
- **Accuracy:** 96.3% on validation set
- **Precision:** 95.1% | **Recall:** 97.2%
- **Privacy Guarantee:** Zero raw data shared between clients
- **Dataset Size:** 5000+ samples from ADNI
- **Explainability:** SHAP plots show hippocampus atrophy as key biomarker

## 🎓 My Role & Contribution
- Implemented Federated Learning pipeline using TensorFlow Federated framework<img width="1014" height="576" alt="1000356383" src="https://github.com/user-attachments/assets/eacf737b-3b63-4bf9-ad8e-60fb29dc0801" />

- Designed multi-modal CNN-LSTM fusion architecture for MRI + Clinical data
- Integrated SHAP for explainability to meet medical compliance requirements
- Achieved 7% higher accuracy than baseline centralized CNN model
- Led data preprocessing and augmentation pipeline for 3D MRI scans



**Project Duration:** Aug 2025 - Mar 2026 | **Team Size:** 4 | **Academic Guide:** Dr. Javira Briskila. ME. phd

**Note:** Due to ADNI dataset privacy policy and academic guidelines, full source code and dataset are available on request. Demo can be arranged during technical interview.
Federated Explainable AI for Alzheimer's Disease Prediction using Multi-Modal Data | B.E Final Year Project 2026
