
# Generative Adversarial Network (GAN) for Image Synthesis

This Jupyter notebook demonstrates training a **Generative Adversarial Network (GAN)** on the **MNIST** dataset using **TensorFlow / Keras**. It includes data preparation, generator and discriminator definitions, the adversarial training loop, and visualization of generated samples.

> Project file: `Использование_GAN,_генерирование_образцов_одежды.ipynb`

## 🧰 Tech stack
- `tensorflow`, `tensorflow.keras`
- `tensorflow_datasets` (MNIST loading)
- `numpy`
- `matplotlib`

## 📦 Data
- Dataset: **MNIST** (loaded via `tensorflow_datasets`).
- Preprocessing: normalization of images to `[-1, 1]` to stabilize GAN training.

## 🏗️ Architecture
- **Generator**: Keras (Sequential) network with transposed convolutions / dense layers that maps a latent vector to an image.
- **Discriminator**: convolutional / dense network that classifies images as real or fake.
- **Optimizers & losses**: standard GAN training setup implemented with Keras.

## 🚀 Experiment flow
1. Load and prepare MNIST (`tensorflow_datasets`).
2. Define generator and discriminator (Keras).
3. Train the GAN adversarially (training loop).
4. Visualize training progress and generated samples.

## 📊 Outputs
- Saved/plotted generated images produced during training.
- Visual inspection of sample quality and training dynamics via plots.

## 📄 Contents
- Notebook: `Использование_GAN,_генерирование_образцов_одежды.ipynb` — includes data prep, model definitions, and the training loop.


