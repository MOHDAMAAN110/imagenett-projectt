# Imagenette2 Custom Model Training

This repository contains my implementation for training a custom neural network on the **Imagenette2** dataset.  
The key parts of this project include:
- Custom `DataLoader` for the Imagenette2 dataset
- Modified pooling layers in the model architecture
- Minimal, clean notebook output for better readability

---

## 📂 Dataset
- Dataset: [Imagenette2](https://s3.amazonaws.com/fast-ai-imageclas/imagenette2.tgz)  
- Imagenette is a subset of ImageNet with 10 easily classified classes, useful for quick experimentation.

---

## 🛠 Features
- **Custom DataLoader** built using `torch.utils.data.Dataset`  
- **Model Architecture** with modified pooling layers for experimentation  
- **Clean & minimal outputs** (removal of unnecessary print statements)  
- Training for 10 epochs with configurable parameters

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/imagenette2-custom-model.git
   cd imagenette2-custom-model
