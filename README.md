# Image Processing Using the Heat Equation

This project explores image smoothing through **partial differential equations (PDEs)**, with a focus on the **heat equation** and its role in **isotropic** and **anisotropic diffusion** for image processing.

## Overview

Image diffusion methods treat an image as a continuous surface whose intensity values evolve over time.

- **Isotropic diffusion** follows the classical heat equation, which smooths the image uniformly over time.
- **Anisotropic diffusion** adjusts the smoothing process according to local image gradients, reducing noise while preserving significant edge structures.

This notebook demonstrates how diffusion-based methods can be used to balance:

- Noise reduction  
- Edge preservation  
- Progressive smoothing over time  

## Project Objectives

The notebook implements and compares:

- Numerical solution of the **heat equation** for isotropic diffusion  
- **Gradient-dependent anisotropic diffusion**
- Comparison of smoothing performance
- Visualization of image evolution over time

## Features

- Grayscale image preprocessing
- Finite difference discretisation
- Time evolution of diffusion
- Side-by-side comparison of methods
- Visual analysis of edge preservation

## Technologies Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## Results

The project highlights the trade-off between:

| Method | Noise Removal | Edge Preservation |
|--------|--------------|------------------|
| Isotropic Diffusion | Strong | Weak |
| Anisotropic Diffusion | Strong | Better |

## Applications

Diffusion-based image processing can be applied to:

- medical imaging
- computer vision
- image denoising
- feature extraction
