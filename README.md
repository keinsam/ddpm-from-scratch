# Denoising Diffusion Probabilistic Models (DDPM) in PyTorch

## Overview

This repository contains an implementation of **Denoising Diffusion Probabilistic Models (DDPM)** using PyTorch, based on the original paper by **Ho et al. (2020)**.

## Features

- Implementation of a **DDPM** in PyTorch.
- Training on the **MNIST and CIFAR-10** datasets.
- Logging with TensorBoard.

## Usage

To train the DDPM, run:
```bash
python run.py
```
This script will:
- Train the model.
- Save the trained model in `MODEL_DIR`.
- Log the loss values and generated samples in TensorBoard.

To see the plotted loss functions the generated samples, run ```tensorboard --logdir=logs``` in the terminal.

## References

- **Denoising Diffusion Probabilistic Models** – Ho et al. (2020) [[Paper](https://arxiv.org/abs/2006.11239)]