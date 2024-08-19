# License-Plate-Recognition
This project is a simple license plate recognition system that detects and reads license plates from images or video feeds. It is built using Python and leverages OpenCV for image processing and EasyOCR for text recognition.

![download (2)](https://github.com/user-attachments/assets/b8025633-df33-4d90-98e4-47c5e252e370)

# Workflow
### Capture Image from Webcam or Upload it Directly from a Dataset

You can either capture a live image from your webcam or upload an image directly from a dataset.

### Read in image, Grayscale and Blur

Converts the image to grayscale and applies a blur to reduce noise.

### Apply filter and find edges for localization

Applies edge detection to highlight the contours of the license plate.

### Find Contours and Apply Mask

Detects the contours of the plate and applies a mask to isolate it.

### Use Easy OCR To Read Text

Reads the text from the isolated license plate using EasyOCR.

### Render Result

Displays the original image with the detected license plate text overlaid.
