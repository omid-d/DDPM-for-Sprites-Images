# Denoising Diffusion Probabilistic Model (DDPM) on Sprites Dataset

This project implements a **Denoising Diffusion Probabilistic Model (DDPM)** using **PyTorch** to learn the distribution of sprite images and generate new ones from noise.  
The model’s performance is evaluated using the **Fréchet Inception Distance (FID)** score to assess the realism of generated images.

---

## 📘 Overview
DDPMs are a class of **generative models** that learn data distributions by gradually denoising Gaussian noise through a diffusion process.  
This notebook trains a **U-Net–based DDPM** on the **Sprites dataset**, demonstrating image synthesis capabilities in a compact, interpretable setup.

---

## ⚙️ Setup

It is recommended to run this notebook on **Google Colab** for GPU acceleration.

```bash
# Clone or download this notebook
!git clone <repo-link>

# Install dependencies
!pip install torch torchvision numpy matplotlib tqdm Pillow
