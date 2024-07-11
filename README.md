# Image Compression and Reconstruction Using PCA
This project conducts Principal Component Analysis (PCA) on images to explore the optimal number of components needed for accurate image reconstruction. The analysis includes visualizing the images in 2D and 3D, reconstructing the images using different numbers of components, and determining the optimal number of components.

## Files

- `Code.ipynb`

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- scikit-learn
- PIL
- resizeimage

## Installation

1. Clone the repository or download the files.
2. Install the required libraries using pip:

    ```sh
    pip install numpy matplotlib scikit-learn pillow python-resize-image
    ```

## Usage

### Running the Analysis

1. Open the `Code.ipynb` notebook using Jupyter Notebook or JupyterLab.
2. Run all the cells to execute the PCA analysis and image reconstruction. The notebook will:
    - Import and preprocess the images.
    - Perform PCA to reduce the dimensionality of the images.
    - Visualize the images in 2D and 3D PCA space.
    - Reconstruct the images using 2, 3, and the optimal number of components.

### Viewing the Report

For a detailed explanation of the project, including the methodology, results, and analysis, refer to the `CS156 LBA PDF.pdf` file.

## Project Structure

### Image Preprocessing

The images are imported, converted to grayscale, resized to 512x512 pixels, and flattened into vectors for PCA analysis.

### PCA Analysis

- **2D PCA**: The images are projected onto a 2D space using PCA.
- **3D PCA**: The images are projected onto a 3D space using PCA.

### Image Reconstruction

The images are reconstructed using:
- 2 PCA components
- 3 PCA components
- The optimal number of PCA components determined by the explained variance

### Visualization

The reconstructed images are visualized alongside the original images to compare the quality of reconstruction with different numbers of PCA components.

## Conclusion

This project demonstrates how PCA can be used for image compression by reducing the dimensionality of image data and reconstructing the images with minimal loss of quality. The optimal number of PCA components provides a balance between compression and image quality.
