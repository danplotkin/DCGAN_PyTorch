# Deep Convolution GAN (DCGAN) in PyTorch

## Introduction

This project implements a Deep Convolutional Generative Adversarial Network (DCGAN) based on the [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/pdf/1511.06434.pdf) paper by Radford et al. The DCGAN incorporates deep convolutional neural networks (CNNs) in both the generator and discriminator. The goal is to generate realistic images from random noise vectors.

## Prepare your dataset

The current implementation uses the LFW (Labeled Faces in the Wild) dataset from the `torchvision.datasets` library. If you want to use a different dataset, make sure to modify the data loading code accordingly.

