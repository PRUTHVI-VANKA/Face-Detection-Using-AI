# Face-Detection-Using-AI

## README: Simple Face Detection

This Python script detects faces in an image using OpenCV's Haar cascade classifier.

### Key Steps:

1.  **Import Libraries**: Imports OpenCV (cv2) and Matplotlib.
2.  **Load Image**: Loads an image file (hrx.jpeg).
3.  **Convert to Grayscale**: Converts the image to grayscale for face detection.
4.  **Load Haar Cascade**: Loads the Haar cascade classifier for frontal face detection. Ensure 'haarcascade\_frontalface\_default.xml' is in the same directory.
5.  **Detect Faces**: Detects faces in the grayscale image using the Haar cascade classifier.
6.  **Draw Rectangles**: Draws rectangles around the detected faces.
7.  **Display Image**: Displays the image with the detected faces using Matplotlib.

To run, ensure OpenCV and Matplotlib are installed, and update the image path if needed.
