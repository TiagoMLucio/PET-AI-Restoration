# AI Techniques for Low-Count PET/MRI Restoration

This repository contains the presentation slides for a seminar project conducted at RWTH Aachen University as part of the course **Intelligent Processing and Analysis of Data** (Winter 2024/2025).

## Overview

This seminar project analyzes state-of-the-art Artificial Intelligence techniques for restoring low-count whole-body PET/MRI images based on the research paper:

**Yan-Ran Wang et al., "Low-count whole-body PET/MRI restoration: an evaluation of dose reduction spectrum and five state-of-the-art artificial intelligence models", European Journal of Nuclear Medicine and Molecular Imaging (2023).**

Low-count PET imaging reduces the radioactive tracer dose, improving patient safety and reducing costs, but leads to increased noise and reduced image quality. The analyzed study evaluates how modern AI models can restore image quality under these conditions.

This project focused on understanding the methodology, models, evaluation framework, and limitations of the study, as well as discussing the challenges of applying AI in medical image restoration.

## Methods Covered

The presentation reviews several state-of-the-art models analyzed in the paper:

- U-Net (Convolutional Neural Network)
- EDSR (Enhanced Deep Super-Resolution Network)
- GAN (Generative Adversarial Network)
- EDSR-ViT (Hybrid CNN–Transformer)
- SwinIR (Transformer-based image restoration)

## Evaluation Framework

The analyzed study evaluates model performance using:

- SSIM (Structural Similarity Index)
- PSNR (Peak Signal-to-Noise Ratio)
- VIF (Visual Information Fidelity)
- Diagnostic Image Quality (DIQ)
- SUV measurements for metabolic activity

## Key Insights

- AI methods enable significant radiotracer dose reduction while maintaining diagnostic image quality.
- SwinIR achieved the best quantitative performance, while U-Net achieved comparable diagnostic quality.
- Restoration is effective down to approximately **6.25% dose level**, while **1% dose produces unreliable reconstructions**.
- Important open challenges include model generalization, dataset bias, and the limitations of simulated training data.

## Files

- [slides.pdf](slides.pdf) – Seminar presentation slides