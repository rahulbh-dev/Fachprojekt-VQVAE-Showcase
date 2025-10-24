# Fachprojekt-VAE\VQVAE-Showcase
Implemented a standard Variational Autoencoder and Vector-Quantized Variational Autoencoder for CIFAR-10, MNIST and CelebA datasets; handled data preprocessing, training, and model evaluation.


**University:** TU Dortmund University  
**Semester:** Summer 2025  
**Team Size:** 3 students  
**Languages:** Python  
**Frameworks:** PyTorch, NumPy, Matplotlib  

---

## Project Overview

This project was developed as part of the Fachprojekt module in Computer Science at TU Dortmund University.  
Our goal was to implement and analyze **Vector-Quantized Variational Autoencoders (VQ-VAE)** and **standard VAEs** on benchmark image datasets such as **CIFAR-10**, **MNIST**, and **CelebA**.

We explored the differences in reconstruction quality, latent space structure, and compression capability between discrete and continuous latent representations.

---

##  Key Contributions

- Implemented and trained **VAE** and **VQ-VAE** models from scratch in PyTorch  
- Built reusable dataset pipelines for CIFAR-10 and CelebA  
- Added support for **gradient accumulation** and **logging** for training monitoring  
- Visualized latent space interpolations and image reconstructions  
- Presented results and analysis in a final report and presentation

---

## Results

- Reconstruction quality significantly improved with VQ-VAE  
- CelebA dataset generated smoother, more detailed outputs  
- Implemented logging, interpolation GIFs, and training metrics tracking  

*(For confidentiality reasons, source code remains private in the university repository.)*

---

## Example Outputs
Reconstructions:
Model: VAE on MNIST dataset
<img width="590" height="590" alt="sample_vae_mnist_mlp" src="https://github.com/user-attachments/assets/449be63b-6b24-4c59-bd84-7c0201ab7c85" />

---

Model: VQ-VAE on CIFAR-10 dataset
<img width="274" height="70" alt="recon_vq_cnn" src="https://github.com/user-attachments/assets/2ba4fb33-9972-45a0-a909-ae6cfbcd0264" />

---


Model: VAE on CIFAR dataset
<img width="636" height="658" alt="vae_cifar" src="https://github.com/user-attachments/assets/166da710-3132-4fc2-81f1-8f6541ec414e" />

---


Model: VQ-VAE on CELEB-A dataset
<img width="1189" height="343" alt="vqvae_celebA" src="https://github.com/user-attachments/assets/2ddb0c9b-cc0e-44d3-a934-25ef4af428c2" />

These are just some of the samples from the project.


##  Private Repository
The complete implementation is hosted privately under the **TU-Dortmund-Fachprojekt-ML-SS25** organization.  
Access can be granted upon request for academic or professional review.

