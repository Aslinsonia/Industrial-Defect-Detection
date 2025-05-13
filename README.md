# Industrial-Defect-Detection
1. Purpose:
The purpose of this project is to detect industrial defects in objects or products using computer vision techniques. By analyzing images or real-time webcam feeds, the system aims to:

Identify defects like scratches, dents, or incorrect shapes.

Detect edges and contours that indicate structural issues.

Recognize abnormal features, such as missing or damaged parts.

Support quality control in manufacturing processes.

2. Technology Used:
Python Programming Language

OpenCV (Open Source Computer Vision Library):

cv2.imread(), cv2.Canny(), cv2.findContours() for edge and contour detection.

cv2.CascadeClassifier() for object (face) detection – extendable to defect detection.

Image filtering techniques like Gaussian Blur, Median Blur, and Average Blur to reduce noise.

HSV color filtering for identifying color-based anomalies.

Google Colab: For running and visualizing the code online.

Webcam Integration: Live video processing using cv2.VideoCapture().

3. Usage:
Edge Detection: Helps identify boundaries and sharp changes which may represent cracks or misalignments.

Contour Detection: Useful for detecting missing components or shape deformities in manufactured products.

Face Detection (as a placeholder): Demonstrates object detection, which can be retrained or replaced with a defect-specific classifier.

Color Filtering (HSV Masking): Detects color-based defects, such as discoloration or paint inconsistencies.

Blurring Techniques:

Smoothens images to remove minor irregularities.

Preprocessing step before edge detection or classification.

Live Camera Feed: Enables real-time defect monitoring during production.

4. Conclusion:
This project demonstrates a foundational approach to industrial defect detection using computer vision. By combining edge detection, contour analysis, object recognition, and color segmentation, the system provides an efficient way to identify potential defects in images or real-time video. With further refinement, such as training on defect-specific data and integrating machine learning, this solution can be scaled for automated quality inspection in manufacturing industries.

