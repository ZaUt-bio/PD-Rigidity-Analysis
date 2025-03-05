# PD-Rigidity-Analysis
**Sensor-Based Estimation of Upper Limb Rigidity in Parkinson’s Disease**  

This repository contains the code, models, and datasets used in the research work on estimating upper limb rigidity in Parkinson’s Disease (PD) using motion sensors and machine learning techniques, including weak supervision learning.

---

## 📌 Project Overview  
Parkinson’s Disease (PD) is characterized by motor symptoms such as rigidity, tremor, and bradykinesia. This study introduces a **hybrid framework** combining **model-driven** and **data-driven** approaches to assess rigidity using wearable motion sensors and a weak supervision framework. The methodology includes:  
- Feature extraction from **motion sensor and EMG data**  
- Binary label generation using **weak supervision**  
- **Denoising network** for refining classification  
- **Machine learning models** to classify PD vs. Healthy Control (HC) subjects  

---

## 📂 Repository Structure  

---
## 🔬 Methodology
🏷️ Feature Extraction

-    Model-Driven Features: Damping ratio, decay rate, natural frequency
-    Data-Driven Features: AUC, variance, dominant frequency component

🏗️ Weak Supervision & Denoising Network

-    Weak supervision is used to generate probabilistic labels based on extracted features.
-    A denoising network refines these labels by learning improved thresholds and minimizing noise in classification.

 ## 📊 Results

The integrated weakly supervised approach achieved a 10% improvement in accuracy (0.71) compared to data-driven methods (0.64), while model-driven approaches achieved a similar performance (0.70).
This work presents a scalable and interpretable approach for remote rigidity assessment, providing a promising solution for early diagnosis and monitoring of Parkinson's Disease (PD).
