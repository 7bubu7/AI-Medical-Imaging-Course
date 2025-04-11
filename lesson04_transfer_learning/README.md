🧠 Lesson 4 - Transfer Learning & Classic CNNs in Medical Imaging

This lesson dives into **transfer learning** and **classic CNN architectures** such as AlexNet, VGG, Inception, and ResNet. We explored how to leverage pretrained models from ImageNet for diabetic retinopathy classification and learned how to fine-tune or freeze different layers depending on dataset size and similarity.

---

 📚 What I Learned

- Overview of classic CNNs:
  - AlexNet, VGG16/VGG19, Inception, ResNet50, SENet
- Vision model repositories:
  - `torchvision.models`
  - `timm` (PyTorch Image Models)
- Global average pooling, 1x1 convolution, bottleneck blocks
- Transfer learning:
  - Feature extractor vs. full fine-tuning
  - Freezing layers to reduce overfitting and computational cost
  - When to fine-tune and when to use fixed features
- Application to Kaggle DR classification dataset

---

 🛠️ Tools Used

- Google Colab  
- PyTorch  
- Torchvision  
- timm  
- Matplotlib  

---

 📁 Files

- `01_CNN models-PyTorch.ipynb`: Build AlexNet/VGG manually in PyTorch
- `02_Transfer learning-PyTorch.ipynb`: Step-by-step guide to model finetuning
- `[HW]Retinopathy classificationV3_Transfer.ipynb`: Homework using pretrained CNNs for DR classification
- `[Optional] timm basic.ipynb`: Explore `timm` pretrained models in one line

---

 🏁 Outcome

This lesson marks the transition to **real-world efficient deep learning** by leveraging existing pretrained weights. The retinopathy classification task reinforces practical understanding of transfer learning in medical imaging, a vital skill for resource-limited clinical datasets.
