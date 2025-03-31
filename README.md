# Denoising Diffusion Probabilistic Models (DDPM) in PyTorch

## Overview

This repository contains an implementation of **Denoising Diffusion Probabilistic Models (DDPM)** using PyTorch, based on the original paper by **Ho et al. (2020)**.

## Features

- Implementation of a **DDPM** in PyTorch.
- Training on the **CIFAR-10 dataset**.
- Logging with TensorBoard.
- Generation of images with visualization in Plotly.

## Usage

### Training
To train the DDPM, run:
```bash
python train.py
```
This script will:
- Train the model.
- Save the trained model in `MODEL_DIR`.
- Log the loss values in TensorBoard.

To see the plotted loss functions, run ```tensorboard --logdir=logs``` in the terminal.

### Inference
To visualize generated images from the trained model, run:
```bash
python infer.py
```
This script will:
- Load the trained model.
- Display generated images.

## References

- **Denoising Diffusion Probabilistic Models** – Ho et al. (2020) [[Paper](https://arxiv.org/abs/2006.11239)]