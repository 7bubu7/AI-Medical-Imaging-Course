📦 Lesson 08 – 3D Imaging, ECG Classification, and Explainable AI (XAI)

🔍 Overview

This lesson covers advanced topics in medical AI, including:

- 3D medical image segmentation and classification
- ECG (electrocardiogram) signal classification
- Explainable AI (XAI) using Grad-CAM
- ML pipeline and data annotation challenges in medical imaging

---


 📘 Notebooks

- `3D Brain Tumor Segmentation.ipynb`  
  ▶️ Demonstrates 3D segmentation using volumetric data with 3D CNNs (`nn.Conv3d`, `nn.ConvTranspose3d`).

- `3D Chest CT Classification.ipynb`  
  ▶️ Classifies diseases based on 3D CT scans using video-based pretrained models like `r3d_18`.

- `ECG Classification.ipynb`  
  ▶️ Classifies arrhythmia types from 1D ECG signal data using 1D CNNs (`nn.Conv1d`).

- `GradCAM.ipynb`  
  ▶️ Applies Grad-CAM to highlight the regions contributing to classification decisions (explainability in AI).

---

🎯 Key Concepts

- **3D Convolution**: Use of 3D CNNs for volumetric medical images (e.g., MRI, CT).
- **1D Convolution**: Temporal signal processing, especially for ECG analysis.
- **Explainable AI**: Interpretability tools like Grad-CAM for clinical validation.
- **Annotation Challenges**:
  - Small labeled datasets
  - Class imbalance
  - Cross-domain variability
  - Federated Learning for privacy-preserving training

---
🔗 References

- [r3d_18 in torchvision](https://pytorch.org/vision/stable/models/generated/torchvision.models.video.r3d_18.html)
- [ECG classification Kaggle](https://www.kaggle.com/c/sai-ecg-classification)
- [GradCAM paper](https://arxiv.org/abs/1610.02391)
- [Explainable AI – Prof. Hung-Yi Lee](https://speech.ee.ntu.edu.tw/~hylee/ml/2021-spring.html)

---

📬 This project was completed as part of the **Advanced AI for Medical Imaging** course taught by **Dr. Chih-Yang Li**.  
Special thanks to Dr. Li for providing a clear and inspiring learning path that helped me build up Python and deep learning skills from scratch.

You can find more of his work and teaching resources here:  
📘 GitHub: [taipingeric](https://github.com/taipingeric)  
🎥 YouTube: [FusionLab](https://www.youtube.com/@fusionlab7360)  



