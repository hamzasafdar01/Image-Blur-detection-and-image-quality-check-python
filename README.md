# Image-Blur-and-image-quality
This code use calculation of Laplacian's variance method to detect blur in the image.
It also use Image Quality Assessment : BRISQUE to calculate quality of image in a range of 0-100. Lower number is greater is the quality of image and vice versa.

## Installation Instructions
**Requirements**
* [Python](https://www.python.org/)
* [opencv-python](https://pypi.python.org/pypi/opencv-python)
* [imutils](https://pypi.python.org/pypi/imutils)

**Python 3.x LIVSVM Installation**

For Python 3.x :

1. `cd Python/libsvm/`
2. `make`
3. `cd python`
4. `make`

## Usage 
Go to `Python/libsvm/python/` and run the following command.
`python3 brisquequality.py --image <image_path>`

If you want to use your own threshold for blur detetction you can add a flag of -t which have the default value of 100.0
`python3 brisquequality.py --image <image_path> -t <value>`
