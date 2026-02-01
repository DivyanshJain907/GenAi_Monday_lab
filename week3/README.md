Variational Autoencoder (VAE) – Image Generation
Objective

Implement and train a Variational Autoencoder (VAE) to learn latent representations of image data, reconstruct inputs, and generate new handwritten digit images using the MNIST dataset.

Overview

A Variational Autoencoder (VAE) is a generative model that learns a probability distribution in its latent space, enabling the generation of new and diverse samples rather than memorizing training data.

Model Architecture

Encoder

Input: 28×28 grayscale image

Outputs: Latent mean (μ) and log-variance (log σ²)

Reparameterization

Samples latent vector using:
z = μ + σ × ε

Decoder

Input: Latent vector

Output: Reconstructed 28×28 image

Implementation Details

Dataset: MNIST

Batch Size: 128

Epochs: 20

Latent Dimension: 2

Optimizer: Adam

Loss Function

Reconstruction Loss (Binary Cross-Entropy)

KL Divergence Loss

Results

Accurate reconstruction of input images

Generation of new handwritten digits

Stable training with decreasing loss

Conclusion

This project demonstrates how Variational Autoencoders can effectively learn a structured latent space for image reconstruction and generation.
