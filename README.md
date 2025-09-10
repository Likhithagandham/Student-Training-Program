Project: Image Compression using PCA

Overview
This project demonstrates how Principal Component Analysis (PCA) can be used for image compression. Instead of storing every pixel value, PCA identifies the most important directions of variance in the data and reconstructs the image using fewer components. This reduces file size while retaining much of the original image quality.

Implementation

Built in Google Colab using Python, scikit-learn, and matplotlib.

Input: User uploads a color image (high resolution supported).

Process:

Convert image to grayscale or handle each color channel separately.

Apply PCA to reduce dimensionality.

Reconstruct the compressed image.

Output: Displays the reconstructed image and prints file size comparison (original vs. compressed).

Key Learnings

PCA is not just for numerical datasets but can be applied to images.

Higher number of PCA components → clearer image, larger file size.

Lower number of PCA components → blurrier image, smaller file size.

There’s a trade-off between image clarity and compression ratio.

Resume Value
This project highlights practical application of ML concepts in real-world tasks like image storage optimization. It shows understanding of unsupervised learning, dimensionality reduction, and the ability to implement ML models in Python.
