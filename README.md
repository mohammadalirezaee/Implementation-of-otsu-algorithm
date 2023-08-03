# Image Processing with Otsu's Algorithm
This repository contains an implementation of Otsu's algorithm for image processing. Otsu's algorithm is a thresholding technique that automatically finds an optimal threshold value for image segmentation.

## Implementation Details
For the implementation, we made the following modifications:

Adjusted Image Dimensions: To optimize calculation time, we resized the input images to 200x250 pixels.

Otsu's Algorithm: We have implemented Otsu's algorithm for thresholding. The algorithm divides the input image into regions based on a histogram, aiming to maximize the variance between regions while minimizing the variance within each region. It assumes that the image's histogram has two distinct peaks and uniform brightness.

inputs images:
![Uploading image.png…]()

