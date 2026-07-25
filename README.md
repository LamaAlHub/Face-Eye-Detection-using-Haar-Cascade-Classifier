# Face & Eye Detection using Haar Cascade Classifier

This project demonstrates face and eye detection in static images using **OpenCV** and **Haar Cascade Classifiers**.

## Features

* Detects human faces in images.
* Detects eyes within the detected face.
* Draws bounding boxes around detected faces and eyes.
* Uses pre-trained Haar Cascade XML classifiers provided by OpenCV.

## Technologies

* Python
* OpenCV
* Haar Cascade Classifiers

## How It Works

1. Load an input image.
2. Convert the image to grayscale.
3. Detect faces using the Haar Cascade face classifier.
4. Detect eyes inside each detected face.
5. Display the output image with bounding boxes.

## Output

The program returns the original image with rectangles highlighting the detected faces and eyes.
