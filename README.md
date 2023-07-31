Adaptive Thresholding
Image thresholding is a fundamental technique in image processing that plays a pivotal role in enhancing the clarity of images and facilitating object segmentation. It allows us to convert grayscale or color images into binary representations, where pixels are classified into two distinct groups based on their intensity values - foreground (object of interest) and background (everything else). By defining a threshold value, we can partition the image, thereby isolating the relevant features and reducing complexity for subsequent analyses.

In this assignment,it's required to use OpenCV to apply adaptive thresholding to the attached image "practice.jpg". We will experiment with different parameter settings and observe their impact on the resulting binary image. Along the way, we will provide insightful comments on each case, explaining the rationale behind the parameter choices and how they affect the thresholding outcome.

Assignment:

Import Libraries and Load the Image:

Import the necessary libraries: cv2, numpy, and matplotlib.
Load the input image using OpenCV's cv2.imread() function.
Convert the image to grayscale for thresholding.
Apply Global Thresholding:

Apply global thresholding (cv2.threshold()) to the grayscale image.
Comment on the results, discussing its limitations in handling varying lighting conditions.
Apply Adaptive Thresholding:

Experiment with different adaptive thresholding methods using cv.adaptiveThreshold(), and comment on the results difference between adaptive and global thresholding:

cv2.ADAPTIVE_THRESH_MEAN_C
cv2.ADAPTIVE_THRESH_GAUSSIAN_C
Varying Block Sizes:

Apply adaptive thresholding with different constant values (e.g., 5, 10, 20). And comment on the results for each case
