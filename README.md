# MEDIGAN-Medical-Image-Generator-Streamlit-App-
This project provides a simple Streamlit interface for generating synthetic medical images using MEDIGAN, a library of GAN‑based medical image generators. Users can select a model ID, choose how many images to generate, and view the results directly in the browser

Features
Choose from multiple MEDIGAN generator models
Generate 1–7 synthetic medical images
Supports both sample and mask outputs
Automatic preprocessing and grid visualization
Clean, interactive Streamlit interface

How It Works
The app loads MEDIGAN generators via Generators(), retrieves synthetic images through a PyTorch dataloader, converts outputs to PIL format, arranges them into grids, and displays them in the browser.

Structure
main() — Streamlit UI
torch_images() — loads MEDIGAN models & preprocesses outputs
generate_images() — displays generated images

Summary
A simple, fast way to explore MEDIGAN’s medical image GANs without writing code — ideal for research, experimentation, and dataset augmentation.
