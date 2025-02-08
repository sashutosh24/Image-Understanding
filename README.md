Description
This script focuses on image understanding by detecting faces and analyzing emotions within an image using computer vision and deep learning libraries.

Key Functionalities:
Image Loading and Preprocessing:

Loads an image file using OpenCV.
Converts the image to grayscale to simplify face detection.
Face Detection:

Uses a pre-trained face detection model (haarcascade_frontalface_default.xml) from OpenCV to identify faces in the image.
Outputs the number of faces detected.
Draws bounding rectangles around detected faces for visualization.
Emotion Detection:

Integrates the DeepFace library to perform emotion analysis on the detected faces.
Analyzes emotions such as happiness, sadness, anger, etc., for each face detected.
Visualization:

Uses Matplotlib to display the image with annotated rectangles showing the detected faces.
Customizability:

The script accepts a file path for the input image (image_path) and processes it to detect faces and emotions.
Libraries Used:
cv2 (OpenCV): For image processing and face detection.
DeepFace: For advanced face and emotion analysis.
matplotlib.pyplot: For visualizing processed images.
Applications:
Face Detection and Annotation: Identify and mark faces in images.
Emotion Analysis: Determine emotional states for applications like surveillance, behavioral studies, or user sentiment tracking.
Computer Vision Projects: Forms a foundation for more complex image-processing tasks.
Let me know if you need help with:
