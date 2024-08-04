# KMeans-Image-Compression

This project demonstrates the use of the K-means clustering algorithm for image compression and visualizes the clustering process on a synthetic dataset.

## Overview

The project includes two main parts:
1. **Clustering Data Visualization**: Uses K-means to cluster a synthetic dataset and visualizes the process.
2. **Image Compression**: Applies K-means clustering to compress an image by reducing the number of colors.

## Files

- `C3_W1_KMeans_Assignment.ipynb`: The main Jupyter notebook containing the code and explanations for the K-means clustering and image compression tasks.
- `bird_small.png`: The original image used for the compression task.
- `ex7_X.npy`: The synthetic dataset used for clustering.
- `figure 1.png`: Visualization of the K-means clustering process on the synthetic dataset.
- `figure 2.png`: The original 128x128 image used for compression.
- `figure 3.png`: Comparison of the original and compressed images.
- `public_tests.py`: Public tests for validation.
- `utils.py`: Utility functions used in the notebook.

## Clustering Data Visualization

The synthetic dataset is clustered into three groups using the K-means algorithm. The process is visualized, showing the movement of centroids and the formation of clusters. Below is a sample output:

![Clustering Visualization](figure%201.png)

## Image Compression

The image compression task involves reducing the number of colors in an image using K-means clustering. The original image is compressed to use only 16 colors, significantly reducing its size while retaining visual quality. Below is a comparison of the original and compressed images:

Original Image:
![Original Image](figure%202.png)

Compressed Image:
![Compressed Image](figure%203.png)

## Running the Notebook

To run the notebook and see the results:

1. Clone the repository:
   ```bash
   git clone https://github.com/regmibhuwan/KMeans-Image-Compression.git
   cd KMeans-Image-Compression

2. Install the required dependencies. You will need:

numpy
matplotlib
jupyter

### Install them using pip:

pip install numpy matplotlib jupyter

3. Open the Jupyter notebook:

jupyter notebook C3_W1_KMeans_Assignment.ipynb

4. Follow the instructions in the notebook to execute the cells and observe the outputs.

## Conclusion
This project showcases the power of K-means clustering for both data visualization and practical applications like image compression. Through visualizations and practical examples, it provides a comprehensive understanding of how K-means works and its potential applications.
