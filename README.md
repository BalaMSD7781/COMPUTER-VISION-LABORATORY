# Computer Vision Laboratory

Twelve lab experiments in classical computer vision, written in Python with OpenCV. They start with pixel-level operations and work up to feature extraction, segmentation and video analysis. Every notebook was run and still has its outputs, so you can read the results on GitHub without running anything.

## Experiments

| # | Experiment | Techniques |
|---|---|---|
| 01 | [Image processing basics](notebooks/ex01_image_processing_basics.ipynb) | RGB→grayscale (built-in and manual), histograms, histogram equalization, resizing |
| 02 | [Color models](notebooks/ex02_color_models.ipynb) | RGB↔CMY, RGB↔HSV, channel splitting and merging |
| 03 | [Image transformations](notebooks/ex03_image_transformations.ipynb) | Arithmetic and geometric transformations |
| 04 | [Histogram processing](notebooks/ex04_histogram_processing.ipynb) | Contrast stretching, frequency domain (DFT magnitude spectrum) |
| 05 | [Image restoration & edge detection](notebooks/ex05_image_restoration_edge_detection.ipynb) | Gaussian noise, denoising filters, Sobel operator |
| 06 | [Canny, LoG & DoG](notebooks/ex06_canny_log_dog.ipynb) | Gaussian blur, gradient magnitude and phase, Canny, Laplacian of Gaussian, Difference of Gaussians |
| 07 | [Roberts & Prewitt operators](notebooks/ex07_roberts_prewitt_operators.ipynb) | Custom convolution kernels with `filter2D` |
| 08 | [Hough transform & Harris corners](notebooks/ex08_hough_transform_harris_corners.ipynb) | Probabilistic Hough lines, Harris corner detection, contours |
| 09 | [Feature extraction & classification](notebooks/ex09_feature_extraction_classification.ipynb) | HOG, SIFT keypoints, bag of visual words (K-Means), PCA, Random Forest |
| 10 | [Image segmentation](notebooks/ex10_image_segmentation.ipynb) | Thresholding, K-Means color segmentation, mean shift, GrabCut |
| 11 | [Background subtraction & scene change](notebooks/ex11_background_subtraction_scene_change.ipynb) | MOG2 background subtraction, frame differencing |
| 12 | [Optical flow](notebooks/ex12_optical_flow_lucas_kanade.ipynb) | Shi-Tomasi features, Lucas–Kanade sparse optical flow tracking |

## Running locally

```bash
git clone https://github.com/BalaMSD7781/COMPUTER-VISION-LABORATORY.git
cd COMPUTER-VISION-LABORATORY
pip install opencv-python numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook
```

The notebooks load images and videos from local paths such as `C:\Users\...\lena.jpg`. Change those paths to point at your own files before you run them. You can also open any notebook in Google Colab and upload the images there.

## Tech stack

Python · OpenCV · NumPy · Matplotlib · scikit-learn
