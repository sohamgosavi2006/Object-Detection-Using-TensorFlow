# Object-Detection-Using-TensorFlow
Object Detection is a core task in Computer Vision (CV) that involves not only classifying objects in an image but also localizing them by drawing bounding boxes around detected instances. This project implements object detection using TensorFlow 2.x and pre-trained models from TensorFlow Hub. By leveraging state-of-the-art architectures such as SSD (Single Shot Detector) and Faster R-CNN, the model can detect multiple objects in an image, assign class labels, and provide confidence scores for each detection.

The workflow covers the end-to-end pipeline:
1.) Loading and preprocessing input images.
2.) Running inference using a pre-trained detection model.
3.) Visualizing results by overlaying bounding boxes, class names, and scores.

This project serves as a starting point for building practical computer vision applications such as autonomous vehicles, surveillance, retail analytics, and smart city systems, where object recognition and localization are essential.


Training Dataset to detect Digits ->
<img width="1398" height="528" alt="Screenshot 2025-08-25 at 11 12 15 AM" src="https://github.com/user-attachments/assets/1ec55bd0-f0d6-4627-8007-7d047c06accb" />

Validation Dataset to detect Digits ->
<img width="1399" height="539" alt="Screenshot 2025-08-25 at 11 13 03 AM" src="https://github.com/user-attachments/assets/099210c4-b489-41af-8bd0-98d4dfd6a93c" />


🚀 Features

Uses TensorFlow Hub pre-trained models (e.g., SSD, Faster R-CNN).
Loads and preprocesses images for inference.
Runs object detection to identify multiple objects in an image.
Visualizes predictions with bounding boxes and labels using PIL & Matplotlib.
End-to-end pipeline: load image → detect objects → show results.

📈 Results --->

Successfully detects multiple objects per image.
Output is bounding boxes with confidence scores.
I am showing if it is able to detect digits within the bounding boxes.
But it also can ...
Sample Scenario ->
Input: street image with cars and people.
Output: detected cars, pedestrians, traffic lights with bounding boxes.
