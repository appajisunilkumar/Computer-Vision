To Detect Persons in Image ive used HOG(Histograms of Oriented Gradients) person detector using OpenCV.

How it works:

1.Detect key point

2.For every key point, select a surrounding patch.

3.Compute the orientation and magnitude to get a HOG.

4.This gives histogram that we can compare between frames.

Compute net average IOU:

1.Ive used labelmg to generate ground truth.

2.then caleculated the IOU using detected bounding box with ground truth.#   C o m p u t e r   V i s i o n  
 