# To Detect Persons in Image ive used HOG(Histograms of Oriented Gradients) person detector using OpenCV.

## How it works:

1.Detect key point

2.For every key point, select a surrounding patch.

3.Compute the orientation and magnitude to get a HOG.

4.This gives histogram that we can compare between frames.

## Compute net average IOU:

1.Ive used labelmg to generate ground truth.

2.then calculated the IOU using detected bounding box with ground truth.# Computer Vision

# Extract text overlay

1.Set a threshold to change pixel value which were below threshold to 0, otherwise highest value 255

2.Performed smoothening and removed noise.

3.Extracted text using pytesseract.


