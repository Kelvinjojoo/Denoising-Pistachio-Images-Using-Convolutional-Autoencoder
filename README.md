# 🥜 Denoising Pistachio Images Using Convolutional Autoencoder

This project implements a **convolutional autoencoder** to remove noise from pistachio images. The model learns to reconstruct clean images from noisy input, enhancing visual quality and preserving key features.

---

## 🧠 Project Overview

- Used a **convolutional autoencoder** architecture for image denoising
- Trained the model on pistachio dataset with added synthetic noise
- Compared performance of baseline vs modified model architectures

---

## 🧪 Model Architecture

- **Encoder:** Convolutional layers to compress image features
- **Decoder:** Transposed convolutions to reconstruct the denoised image
- Used **ReLU** and **Sigmoid** activations
- Loss: **Mean Squared Error (MSE)**  
- Evaluation Metric: **SSIM (Structural Similarity Index)**

---

## 📊 Evaluation Results

| Model            | SSIM Score |
|------------------|------------|
| Baseline Model   | 0.9534     |
| Modified Model   | 0.9579     |
| **Improvement**  | **+0.46%** |

✅ The modified model achieves better structural similarity, resulting in cleaner and more accurate image reconstruction.
