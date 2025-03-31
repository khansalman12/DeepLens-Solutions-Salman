# DeepLens Solutions  
**Deep Learning for Gravitational Lensing Image Analysis**  

## Project Overview
This repository contains deep learning solutions for analyzing gravitational lensing images, focusing on:
1. **Multi-Class Classification** - Categorizing lensing images by substructure type
2. **Super-Resolution** - Enhancing low-resolution lensing images

## Repository Structure
DeepLens-Solutions/
├── Classification/
│ ├── best_model.pth # Trained classifier weights
│ └── classification.ipynb # Classification notebook
│
├── Super_Resolution_EDSR/
│ ├── best_edsr_model.pth # EDSR model weights
│ └── edsr_super_resolution.ipynb # EDSR implementation
│
└── Super_Resolution_Alternative/
├── best_model.pth # Alternative model weights
└── super_resolution_alt.ipynb # Alternative approach


## Requirements
```bash
pip install torch torchvision numpy matplotlib scikit-image


Usage

bash
Copy
git clone https://github.com/yourusername/DeepLens-Solutions.git
Run notebooks:

bash
Copy
jupyter notebook

License
MIT License
