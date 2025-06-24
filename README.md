"SigSynth: Signature Generation using VAE and GAN Architectures"

🧬 Detailed Description:
SigSynth explores the generative capabilities of deep learning models to synthesize realistic handwritten signatures. The project involves the implementation of two generative models—Variational Autoencoder (VAE) and Generative Adversarial Network (GAN)—to learn and recreate the distribution of genuine signature images.

📌 Project Objectives:
Implement and train a VAE and a simple GAN separately to generate synthetic signatures.

Perform data augmentation (scaling, rotation, translation, noise addition, etc.) to enhance dataset diversity and training performance.

Sample from the latent space to generate new, unseen signature samples.

Evaluate model performance using:

Reconstruction loss (for VAE)

Visual fidelity (for GAN)

Latent space visualization

Optional: Fréchet Inception Distance (FID) or other similarity metrics if applicable

Compare the quality of generated signatures with real ones on a held-out test set.

Plot and analyze:

Training loss curves (generator, discriminator, VAE losses)

Generated vs. real image comparisons

Augmentation examples used in training

📂 Dataset:
Source: Signature Verification Dataset on Kaggle

Includes genuine and forged signatures across multiple identities, suitable for generative modeling tasks.

🛠 Key Components:
VAE Architecture:

Encoder–Decoder with Gaussian latent space

KL Divergence + Reconstruction loss

Simple GAN Architecture:

Generator and Discriminator networks trained adversarially

Image augmentation pipeline

Signature generation pipeline from latent space sampling

📈 Deliverables:
Trained VAE and GAN models with loss visualization.

Dataset augmentation code and examples.

Generated signature image sets.

Comparison between real and synthetic signatures.

A comprehensive report with:

Architectural diagrams

Model training behavior

Visual and quantitative evaluations
