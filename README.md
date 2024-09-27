# Autoencoder for Fashion MNIST

## Overview

This project focuses on building and optimizing an autoencoder for the **Fashion MNIST** dataset, specifically classifying **T-shirts/tops (class 0)** and **Trousers (class 1)**. The goal is to explore deep learning techniques, such as autoencoders, for image reconstruction and to optimize model performance using both manual and hyperparameter tuning methods.

## Goals

The primary goals of this project include:

- **Image Reconstruction**: To reconstruct input images (T-shirts and Trousers) using an autoencoder architecture.
- **Model Optimization**: To explore various optimization techniques, including manual tuning and hyperparameter tuning, to improve the model's performance.
- **Comparison of Tuning Methods**: To analyze the differences between manual tuning and hyperparameter tuning using structural similarity index (SSIM) scores.
![image](https://github.com/user-attachments/assets/d57fb9ba-9bfc-4aa7-88b6-929a91635a58)

## Results Summary

After training and evaluating the autoencoder model, the **manual tuning approach** yielded a **Structural Similarity Index (SSIM) score of 0.9090** on the test dataset, indicating higher quality reconstructions. Meanwhile, the **hyperparameter tuning approach** achieved an **SSIM score of 0.8731**, demonstrating reasonable performance but slightly lower reconstruction quality compared to manual tuning.

## Conclusion

The project demonstrates that while both tuning methods result in effective image reconstructions, manual tuning produced slightly better results in this particular case. However, hyperparameter tuning could be further optimized with more trials to potentially close the gap in performance.

---

For more information, check the following resources:
- [Autoencoder Overview](https://en.wikipedia.org/wiki/Autoencoder)
- [Fashion MNIST Dataset](https://github.com/zalandoresearch/fashion-mnist)
