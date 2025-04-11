 🧠 Lesson 6 - Medical Image Segmentation & Annotation Tools

This lesson focuses on medical image segmentation using PyTorch and how to prepare your own labeled datasets using tools like Labelme. We implemented multiple architectures for tumor and vessel segmentation, and converted JSON annotations into multi-label PNG masks.

---

📚 What I Learned

- Brain tumor segmentation using:
  - U-Net
  - ResUNet
  - ResNet + UNet hybrid
  - FusionNet architecture
- Retina vessel segmentation with PyTorch
- How to convert manual annotations (JSON) into mask images
- Visualizing multi-organ segmentation from CT images (e.g., kidneys, spleen)

---

🛠️ Tools Used

- Google Colab / Jupyter Notebook  
- PyTorch  
- Torchvision  
- PIL / OpenCV  
- Labelme  
- Matplotlib  

---


 🧪 Notebooks

- `01_Brain Tumor segmentation.ipynb`: Baseline tumor segmentation using U-Net  
- `02_ResUNet.ipynb`: Add ResNet-style blocks to U-Net  
- `03_ResNet+UNet.ipynb`: Combine feature extractors with UNet decoder  
- `04_fusionlab_segmentation.ipynb`: Implement FusionNet-style segmentation  
- `HW_Retina_Vessel_Segmentation_PyTorch.ipynb`: Homework on vessel segmentation  
- `labelme_json_to_mask.ipynb`: Convert Labelme JSON to PNG masks for training  

---

 🏁 Outcome

This lesson gave me hands-on experience with segmentation architectures and helped me understand how to build my own training datasets from scratch. This foundational workflow will support future applications in organ segmentation, tumor detection, and AI-assisted clinical tools.
