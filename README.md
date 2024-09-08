# Car-Number-Plate-Detection-
Number Plate Detection is car license plate identification system made using OpenCV in python. It can be used to detect number plate from video as well as from image.

Detecting car number plates using OpenCV in Python typically involves the following steps:

1.Image Preprocessing: Convert the image to grayscale and apply some smoothing techniques to reduce noise.
2.Edge Detection: Use edge detection to identify the boundaries of objects in the image.
3.Contour Detection: Find the contours of the number plate.
4.Plate Extraction: Extract the region that contains the number plate.
5.Text Recognition: Use Optical Character Recognition (OCR) to read the text on the number plate.


Key Components:
1.Image Preprocessing:

Grayscale conversion makes edge detection more effective.
Gaussian blur smooths the image and reduces noise.
2.Edge Detection:

Canny edge detection is used to detect edges of the number plate.
3.Contour Detection:

Contours are used to detect areas that look like a number plate (approximating rectangular shapes).
4.Text Recognition:

pytesseract is used to extract the text from the detected number plate .
