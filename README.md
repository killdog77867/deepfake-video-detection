# Deepfake Video Detection

A deep learning-based system that detects deepfakes in videos using frame-level spatial inconsistencies. The project explores CNN-based and transformer-based approaches including ResNet50, GAN architectures, and Vision Transformers (ViT).

## 🧠 Project Overview

Deepfakes pose a rising threat in digital media. This system analyzes individual frames from videos to classify content as either real or fake using different model architectures.

### 🔍 Key Features
- Frame-level video analysis for deepfake detection
- Comparative approach using:
  - GAN-based models
  - ResNet-50 (CNN-based)
  - Vision Transformer (ViT)
- Implemented in Jupyter notebooks for easy experimentation

## 🗂️ Project Structure
```
deepfake-video-detection/
├── deepfake-detection-gan.ipynb # GAN-based detection
├── deepfake-detection-resnet50.ipynb # CNN-based detection using ResNet-50
├── deepfake-detection-vit.ipynb # Transformer-based detection using ViT
├── README.md # Project documentation

```

## 🎥 Input & Output

- **Input**: Extracted video frames (from real or deepfake videos)
- **Output**: Classification (`Real` / `Fake`) with prediction confidence

## 📊 Models Used

- **ResNet-50**: CNN architecture for spatial feature extraction
- **GAN**: Adversarial learning to discriminate real vs fake patterns
- **Vision Transformer (ViT)**: Attention-based feature modeling for video frames


