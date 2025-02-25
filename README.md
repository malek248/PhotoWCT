# PhotoWCT: Photorealistic Image Stylization

This repository contains an implementation of the paper **"A Closed-form Solution to Photorealistic Image Stylization"** by Li et al. The project features a complete pipeline for photorealistic style transfer using:
- **PhotoWCT** with semantic segmentation (sky vs. ground)
- **Graph-based smoothing** in Lab color space
- Optional blending to recover fine details

The implementation is demonstrated via a Jupyter Notebook that processes two distinct content/style pairs, randomly selected from online image searches, to test the method on novel data. The notebook presents side-by-side comparisons of the original content and style images along with the final smoothed results, clearly illustrating the entire transformation process.

![Stylized Result 1](https://raw.githubusercontent.com/malek248/PhotoWCT/main/photos/results/results_1.png)
![Stylized Result 2](https://raw.githubusercontent.com/malek248/PhotoWCT/main/photos/results/results_2.png)


**Note:** The scripts `photo_wct.py`, `photo_smooth.py`, and the model files were obtained from the original [FastPhotoStyle repository](https://github.com/NVIDIA/FastPhotoStyle). Slight modifications were made to `photo_smooth.py` to ensure compatibility with current libraries.

## Step by Step

**1. Clone the repository:**
```bash
git clone https://github.com/malek248/PhotoWCT.git
cd PhotoWCT
```

**2. Install dependencies:**
Please install the following Python packages manually (if not already installed):

- Python 3.x
- NumPy
- OpenCV-Python
- Matplotlib
- PyTorch
- Pillow

For example, you can run:
`pip install numpy opencv-python matplotlib torch pillow`

**3. Run the Jupyter Notebook:**
Open `PhotoWCT_Pipeline.ipynb` in Jupyter Notebook or VSCode and run all cells.

