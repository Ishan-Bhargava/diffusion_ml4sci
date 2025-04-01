# Gravitational Lensing Image Generation with Diffusion Models

## Overview
This repository contains an implementation of a **Denoising Diffusion Probabilistic Model (DDPM)** to generate realistic strong gravitational lensing images. The goal is to simulate lensing images with high realism and diversity using a diffusion-based generative model.

---

## Specific Test IV: Diffusion Models

### Task
Develop a generative model to simulate realistic strong gravitational lensing images using a **diffusion model**.

### Dataset
- The dataset consists of **10,000 strong lensing images** for training.
- Images represent different gravitational lensing effects.

### Approach
- **Preprocessing**: Standardized and normalized input images.
- **Model Architecture**: Implemented a **Denoising Diffusion Probabilistic Model (DDPM)**.
- **Training**: 
  - Used a progressive denoising approach.
  - Experimented with different hyperparameters and network configurations.
  - Trained using a multi-step noise reduction strategy.
- **Evaluation**: 
  - Assessed image quality using **Fréchet Inception Distance (FID)**.
  - Conducted qualitative analysis of generated images.

### Results
- **FID Score:** **99.576**
- Generated images closely resemble real strong lensing images.

## Evaluation
- **Diffusion Model:** Evaluated using **FID Score** and qualitative assessments.

---

## Additional Work: Multi-Class Classification (Common Test I)
While the primary focus is on **image generation**, this repository also contains a classification model to categorize strong lensing images into three classes:
- No substructure
- Subhalo substructure
- Vortex substructure


