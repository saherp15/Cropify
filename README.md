# Cropify

This code demonstrates how to crop images using NumPy in Python. The code is written in a Jupyter Notebook and uses Matplotlib to display the images.<br>

## Getting Started
Before running the code, make sure you have the following libraries installed:

* NumPy
* Matplotlib


## Usage
*1. The code reads the input image and displays it using Matplotlib. You can use the plt.imshow() function to visualize the image.

*2. The code also demonstrates how to crop images using NumPy arrays. You can use the img[x1:x2, y1:y2, :] syntax to crop the image.

## Examples
The code includes examples for cropping the following images:

* Fruits (fruits.png)
* Emma Stone (emma_stone.jpeg)

## Notes
Color dimensions in images are always in 3D, while black and white images are 2D.
Brighter the intensity, more color is used. Darker the intensity, less color is used.
The code uses np.transpose() to rotate the image.
The code uses img.copy() to make a copy of the original image before cropping.
