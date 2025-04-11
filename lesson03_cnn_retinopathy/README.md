🧠 Lesson 3 - CNNs & Retinopathy Classification for Medical Imaging

This notebook series is part of an AI for Medical Imaging course. In this module, we explored **Convolutional Neural Networks (CNNs)** for medical image classification and applied the techniques to **pneumonia diagnosis (CXR)** and **diabetic retinopathy classification** (Kaggle dataset with 5 severity levels).

---

 📚 What I Learned

- CNN model structure: `Conv2d`, `MaxPool2d`, `Flatten`, `Linear`
- Building CNN using `torch.nn.Sequential`
- Avoiding overfitting using:
  - Dropout
  - Batch Normalization
  - Early Stopping
- Data augmentation:
  - `torchvision.transforms`
  - `imgaug`
  - `albumentations`
- Medical applications:
  - Pneumonia classification (chest X-rays)
  - Diabetic retinopathy classification (Kaggle competition)

---

🛠️ Tools Used

- Google Colab  
- PyTorch  
- Torchvision  
- Matplotlib  
- Albumentations / ImgAug  

---

📁 Files

- `01_PyTorch-CNN-Pneumonia.ipynb`: Basic CNN model for pneumonia detection
- `02_PyTorch-CNN-Pneumonia-Tips.ipynb`: Tips on overfitting control and regularization
- `03_Data Augmentation.ipynb`: Apply various image augmentation techniques
- `[HW] Retinopathy classificationV3.ipynb`: Kaggle DR classification task (5 classes)
- `[HW][HINT] Retinopathy classificationV3.ipynb`: Guided hints notebook for DR classification

---

🏆 Outcome

This lesson marks the transition from foundational ML to real-world medical imaging projects using CNNs and open medical datasets. Through hands-on experience with Kaggle, I improved my skills in model design, augmentation, and evaluation—laying the groundwork for AI-based pathology research.
