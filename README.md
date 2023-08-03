# Image Processing with Otsu's Algorithm
This repository contains an implementation of Otsu's algorithm for image processing. Otsu's algorithm is a thresholding technique that automatically finds an optimal threshold value for image segmentation.

## Implementation Details
For the implementation, we made the following modifications:

Adjusted Image Dimensions: To optimize calculation time, we resized the input images to 200x250 pixels.

Otsu's Algorithm: We have implemented Otsu's algorithm for thresholding. The algorithm divides the input image into regions based on a histogram, aiming to maximize the variance between regions while minimizing the variance within each region. It assumes that the image's histogram has two distinct peaks and uniform brightness.

inputs images:
![image](https://github.com/mohammadalire94/Implementation-of-otsu-algorithm/assets/103526640/a00b0b47-4b84-46c8-ad2a-cb218f32202b)
![image](https://github.com/mohammadalire94/Implementation-of-otsu-algorithm/assets/103526640/2b751d0b-0587-4197-b919-e0ce3f7fda9a)


output images:
![image](https://github.com/mohammadalire94/Implementation-of-otsu-algorithm/assets/103526640/43af6a31-73eb-4744-b614-e79f52424056)
![Uploading image.png…]()





