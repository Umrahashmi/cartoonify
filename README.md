# Cartoonify Images using Python & OpenCV

This project converts real-world images into cartoon-style visuals using **Computer Vision** techniques. Implemented entirely in **Python** using **OpenCV**, **NumPy**, and **Matplotlib**, and runs seamlessly on **Google Colab**.

## Features
- **Edge Detection**: Detects prominent edges using Adaptive Thresholding.
- **Color Quantization**: Reduces color palette via K-Means clustering for a posterized look.
- **Noise Reduction**: Applies Bilateral Filtering to smooth colors while preserving edges.
- **Cartoon Effect**: Combines processed edges and colors to create a cartoon-style image.

## Tech Stack
- Python
- OpenCV
- NumPy
- Matplotlib
- Google Colab

## How to Run
1. Open the notebook directly in Google Colab:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1gd3lZEx9zIapJqedAWIGVObns0cRxAfC?usp=sharing)
2. Upload an image in the notebook.
3. Run all cells to generate the cartoonified image.

## Sample Output
Original Image             |  Cartoonified Image
:-------------------------:|:-------------------------:
![Original](sample_original.jpg) | ![Cartoon](sample_cartoon.jpg)

## Applications
- Fun photo filters for apps.
- Artistic image editing tools.
- AR/VR content stylization.

---

### Author
**Umra Hashmi**  
- [GitHub](https://github.com/Umrahashmi)
