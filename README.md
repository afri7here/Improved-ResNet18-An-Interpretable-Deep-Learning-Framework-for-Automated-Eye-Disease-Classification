# 👁️ Improved ResNet18 for Eye Disease Classification

## 📄 Publication

**Improved ResNet18: An Interpretable Deep Learning Framework for Automated Eye-Disease Classification**

📚 **2026 IEEE Madhya Pradesh Section Conference (MPCON)**

🔗 **[Read the Published Paper](https://doi.org/10.1109/MPCON69668.2026.11508167)**  
🔖 **DOI:** [10.1109/MPCON69668.2026.11508167](https://doi.org/10.1109/MPCON69668.2026.11508167)

**Authors:** A. A. Lamia · O. Rayhan · S. Sharif

This project develops a **deep learning-based system for classifying five eye diseases from simple RGB eye images**. Multiple CNN, Transformer, and hybrid architectures were compared, with an **optimized ResNet18** achieving the best overall performance. 
### Dataset Used: https://data.mendeley.com/datasets/n9zp473wfw/1
## ✨ Key Highlights

- 🩺 **5-class classification:** Cataract, Conjunctivitis, Eyelid, Normal & Uveitis
- 🧠 Compared **6 deep learning architectures**
- ⚡ **97.44% Test Accuracy**
- 🎯 **95.11% Sensitivity | 99.36% Specificity**
- 🔍 **Grad-CAM** for interpretable predictions
- 🔄 **5-Fold Cross-Validation**
- 📊 **McNemar Test & 95% Confidence Intervals**
- 🚀 ResNet18 achieved the **fastest training and inference**

## 🔬 Methodology

**Eye Images → Preprocessing → Augmentation → Model Training → Evaluation → Explainability**

### Preprocessing
- RGB conversion
- Resize to **224×224**
- Grayscale conversion
- CLAHE contrast enhancement
- Gaussian filtering
- Data augmentation

## 🤖 Models Compared

- ResNet18
- Swin-Tiny
- DeiT-Tiny
- LeViT-256
- MobileViT-XS
- ShuffleNetV2

## 📈 Results

| Model | Test Accuracy |
|---|---:|
| 🥇 **ResNet18** | **97.44%** |
| MobileViT-XS | 95.73% |
| Swin-Tiny | 94.44% |
| LeViT-256 | 94.02% |
| DeiT-Tiny | 93.59% |
| ShuffleNetV2 | 93.59% |

ResNet18 also showed stable performance across 5-fold cross-validation, with validation accuracy ranging approximately from **96.5% to 97.4%**.

## 🔍 Explainable AI

**Grad-CAM** was used to visualize the regions influencing model predictions. The model primarily focused on clinically relevant eye regions such as the **iris, cornea, and lens**, improving the interpretability of its predictions.

## 🛠️ Tech Stack

**Python • PyTorch • ResNet18 • CNN • Vision Transformers • OpenCV • Grad-CAM • SMOTE • NVIDIA Tesla P100**

## 🎯 Objective

The goal is to develop a **high-performing, statistically validated, and interpretable** deep learning framework for automated eye-disease classification using simple eye images.

> ⚠️ **Disclaimer:** This research model is limited to the five disease classes in the dataset and is intended for research and automated screening purposes, not as a replacement for professional medical diagnosis.
