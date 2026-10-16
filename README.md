# Fashion-MNIST CNN Classifier in PyTorch

A custom Convolutional Neural Network (CNN) built from scratch using PyTorch to classify the Fashion-MNIST dataset. This project demonstrates foundational deep learning concepts, custom training loops, and hardware performance profiling.

## Project Overview
This repository contains a complete PyTorch workflow for image classification. It features a custom CNN architecture, rigorous performance metric tracking, and parameter/MAC (Multiply-Accumulate) profiling.

## Key Features & Skills Demonstrated
*   **Custom Neural Network Architecture:** Built using `torch.nn.Module` with convolutional layers, max pooling, batch normalization, and fully connected layers.
*   **Custom Training & Validation Loops:** Implemented standard deep learning loops from scratch, utilizing `optimizer.zero_grad()`, `loss.backward()`, and `torch.no_grad()` for efficient validation.
*   **Hardware Profiling:** Utilized `thop` (Flop counter for PyTorch) and `torchinfo` to extract precise parameter counts and MAC operations, demonstrating an awareness of computational efficiency and AI architecture optimization.
*   **Model Serialization:** Safely saving and loading model states (`state_dict`).

## Tech Stack
*   **Framework:** PyTorch, Torchvision
*   **Profiling:** Thop, Torchinfo
*   **Visualization:** Matplotlib, scikit-learn

## Results
The model successfully achieved ~90% accuracy on the Fashion-MNIST validation dataset, demonstrating effective learning and generalization.
