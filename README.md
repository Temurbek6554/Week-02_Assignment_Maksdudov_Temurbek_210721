# Week-02_Assignment_Maksdudov_Temurbek_210721
Image I/O, grayscale/binary, cropping (ROI), color spaces, and basic arithmetic operations

Report:

In this lab, I learned the fundamental operations used in digital image processing with Python, NumPy, and OpenCV. I worked with image loading, saving, and visualization, and gained a clear understanding of how images are represented as arrays. I explored pixel inspection, grayscale conversion, binary thresholding, cropping regions of interest (ROI), and color space conversion from RGB to HSV. Additionally, I applied basic arithmetic operations such as addition, subtraction, multiplication, and division to adjust image brightness and contrast.

The most useful operations were grayscale conversion and thresholding, as they are essential for simplifying images and preparing them for further analysis such as object detection. HSV color space visualization was also very useful because it separates color information from brightness, making color-based processing more robust to lighting changes. Arithmetic operations helped me understand how pixel intensity values directly affect image appearance.

Several issues were encountered during the lab. One common problem was the difference in color channel order between OpenCV (BGR) and Matplotlib (RGB), which caused incorrect colors until proper conversion was applied. Handling data types was also important, as arithmetic operations on uint8 images can cause overflow or underflow if not managed correctly. Converting images to float and clipping values helped avoid these issues.
