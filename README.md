# Image-dimensionality-reduction

Project Description
This project aims to perform image dimensionality reduction by converting an image to grayscale and then to black and white. The approach uses only Numpy and Matplotlib libraries, without the need for TensorFlow. The code is modularized into a class, making it easy to reuse and adapt for different images and scenarios.
Objectives
The main objective of this project is to demonstrate dimensionality reduction on images, with two main stages:
1. Conversion to grayscale using a weighted RGB formula to simulate human color perception.
2. Conversion to black and white by applying a threshold to binarize the image.
Technologies Used
- Numpy: For data manipulation and image processing.
- Matplotlib: For image display.
- Google Colab: For image file upload.
Code Structure
The code is structured into a class called 'ImageProcessor', which contains the following methods:

1. `__init__(image_path)`: Initializes the object with the image path.
2. `normalize_image()`: Normalizes the image values to the range [0, 1].
3. `to_grayscale()`: Converts the image to grayscale.
4. `to_black_and_white(threshold)`: Converts the image to black and white by applying a threshold.
5. `show_image(img, title)`: Displays the given image using Matplotlib.
6. `process_image(threshold)`: Processes the entire image (normalization, conversion to grayscale, and binarization).
How to Use
1. Upload the image using the `files.upload()` method in Google Colab.
2. Create an instance of the `ImageProcessor` class by providing the image path.

