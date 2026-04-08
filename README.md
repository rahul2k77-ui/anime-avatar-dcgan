# Anime Avatar Generator (DCGAN) 🎨

An implementation of a Deep Convolutional Generative Adversarial Network (DCGAN) using PyTorch, designed to generate high-quality anime-style character avatars from random noise.

## 📌 Project Overview
This project trains a generator and discriminator network adversarially on the `cartoon_20000` dataset. The model learns the underlying distribution of anime facial features, styles, and colors, allowing it to synthesize entirely new, unique anime faces by sampling from a latent space.

### Key Features:
* **Custom DCGAN Architecture:** Built from scratch using `torch.nn`.
* **Optimized Data Pipeline:** Utilizes PyTorch `DataLoader` and `torchvision.transforms` for efficient batching and image preprocessing (e.g., center cropping, normalization).
* **GPU Acceleration:** Fully configured to leverage CUDA for rapid training iterations.
* **Latent Space Exploration:** Demonstrates how manipulating the latent vector ($z$) alters specific visual features in the generated outputs.

---

## 🛠️ Technologies Used
* **Framework:** PyTorch (`torch`, `torchvision`)
* **Language:** Python 3
* **Data Visualization:** Matplotlib, NumPy
* **Environment:** Jupyter Notebook

---
