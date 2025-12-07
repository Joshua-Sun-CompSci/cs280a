# CS 280A: Computer Vision Portfolio

A comprehensive collection of computer vision projects exploring fundamental and advanced techniques in image processing, 3D reconstruction, and generative AI.

## 🎯 Projects

### [Project 1: Prokudin-Gorskii Colorizing](https://joshua-sun-compsci.github.io/cs280a/1/index.html)
Automatic color image recovery from digitized glass plate photographs using multi-scale pyramid search technique.

**Key Techniques:** Image Alignment • Normalized Cross-Correlation (NCC) • Pyramid Search • Image Enhancement
- Multi-scale alignment with coarse-to-fine refinement
- Automatic contrast, white balance, and color correction
- Canny edge-based feature matching for robust alignment

### [Project 2: Fun with Filters & Frequencies](https://joshua-sun-compsci.github.io/cs280a/2/index.html)
Explore edge detection, image sharpening, hybrid images, and multiresolution blending using Laplacian stacks.

**Key Techniques:** Convolution • Gaussian Pyramids/Laplacian Stacks • Frequency Filtering • Hybrid Images
- 2D convolution from scratch with zero-padding
- Derivative of Gaussian (DoG) for edge detection
- Unsharp mask for image sharpening
- Multiresolution blending for seamless image composition

### [Project 3: Image Mosaicing](https://joshua-sun-compsci.github.io/cs280a/3/b/index.html)
Manual and automatic image stitching using homography estimation, feature detection, and RANSAC for robust alignment.

**Key Techniques:** Homography • RANSAC • Harris Corner Detection • Feature Descriptors
- Single-scale and multi-scale homography computation
- Harris corner detection with Adaptive Non-Maximal Suppression (ANMS)
- 8×8 feature descriptor extraction and matching
- Cylindrical warping for wide field-of-view stitching

### [Project 4: Neural Radiance Fields (NeRF)](https://joshua-sun-compsci.github.io/cs280a/4/index.html)
3D scene reconstruction from multi-view images using machine learning, ray sampling, and volumetric rendering techniques.

**Key Techniques:** NeRF • PyTorch • Machine Learning • Volumetric Rendering
- Multi-view camera calibration with ArUco markers
- 2D neural field fitting with sinusoidal positional encoding
- Full 3D NeRF training on multi-view datasets
- Novel view synthesis and depth map rendering

### [Project 5: Diffusion Models & Generative AI](https://joshua-sun-compsci.github.io/cs280a/5/a/index.html)
Explore diffusion models for image generation, editing, and synthesis including text-to-image and visual anagrams.

**Key Techniques:** Diffusion Models • Classifier-Free Guidance • SDEdit • Image Inpainting
- Forward and reverse diffusion processes
- Iterative denoising with and without text conditioning
- Image-to-image translation and style transfer
- Visual anagrams and hybrid image generation

## 📋 Technical Highlights

- **Python & PyTorch** — Deep learning implementations
- **NumPy** — Numerical computing and signal processing
- **OpenCV** — Computer vision algorithms
- **Image Processing** — Filtering, registration, reconstruction
- **Deep Learning** — Neural networks for vision tasks
- **Optimization** — RANSAC, pyramid search, gradient descent

## 🚀 Getting Started

Each project folder contains:
- `index.html` — Interactive project report with visualizations
- Results and comparisons
- Bells & whistles

To view the portfolio:
```bash
# Simply open the portfolio page in a browser
open portfolio_index.html
```

Or navigate to each project individually via the links above.

## 🎓 Course Information

**CS 280A: Computer Vision** — UC Berkeley

This course covers fundamental and advanced topics in computer vision including:
- Image formation and geometry
- Feature detection and description
- Image alignment and registration
- 3D reconstruction
- Neural approaches to vision tasks

## 📝 License

This portfolio contains course projects from UC Berkeley's CS 280A. Please refer to course policies regarding academic integrity and code sharing.

---

**Author:** Joshua Sun  
**Institution:** UC Berkeley  
**Year:** 2025