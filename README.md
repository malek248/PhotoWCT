# PhotoWCT: Photorealistic Image Stylization

This repository contains a complete implementation of the paper **"A Closed-form Solution to Photorealistic Image Stylization"** by Li et al. The project features a full pipeline for photorealistic style transfer using:
- **PhotoWCT** with semantic segmentation (sky vs. ground)
- **Graph-based smoothing** in Lab color space
- Optional blending to recover fine details

The implementation is demonstrated through a Jupyter Notebook that processes two different content/style pairs and includes side-by-side comparisons to illustrate the transformation from content and style images to the final smoothed results.

## Repository Structure

- **code/**: Python scripts (e.g., `photo_wct.py`, `photo_smooth.py`) modified for this project.
- **models/**: Pretrained model weights.
- **photos/**: Sample content and style images for two experimental sets.
- **notebook/**: Jupyter Notebook with the full pipeline implementation.
- **report/**: Synthesis report in LaTeX.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/malek248/PhotoWCT.git
   cd PhotoWCT
