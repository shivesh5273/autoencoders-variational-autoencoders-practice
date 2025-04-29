# Autoencoders & Variational Autoencoders Practice

This project explores Autoencoders and Variational Autoencoders (VAEs) using Keras and TensorFlow on the MNIST dataset. The focus is on denoising, model structure comparison, latent space behavior, and image generation.

---

## 🔍 Project Breakdown

### 🧼 1. Denoising Autoencoder
- Built a convolutional autoencoder to clean noise from MNIST digits (1, 2, 4, 5, 9).
- Experimented with different bottleneck sizes: 64, 32, 16, and 8.
- Compared reconstruction quality visually and numerically.

### 🧠 2. Conv2D vs Dense Autoencoders
- Rebuilt the model using Conv2D + MaxPool2D instead of Dense layers.
- Compared output image quality and model performance.

### 🧬 3. Variational Autoencoder (VAE)
- Constructed VAE using Conv2D/Transpose layers.
- Experimented with latent dimensions = 2 and 8.
- Compared VAE output to traditional autoencoder output.

### 🔗 4. Latent Space Interpolation
- Used encoder to extract mean codings for selected digits.
- Interpolated across latent space between digit pairs (2 → 5 and 1 → 4).
- Visualized the morphing effect between digits using the decoder.

---

## 📁 Files Included

- `autoencoder-denoising-mnist.html`
- `autoencoder-conv2d-vs-dense.html`
- `vae-conv2d-latent-experiments.html`
- `vae-latent-space-interpolation.html`
- `autoencoders-vae-overview.docx`

---

## 🛠 Tools & Libraries

- Python 3.x  
- Keras / TensorFlow  
- Google Colab  
- NumPy / Matplotlib  
- MNIST Dataset

---

> This project strengthened my intuition about bottlenecks, overfitting control, and latent space representations in generative models.
