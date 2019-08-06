# face-eye-det
Face and eye detection using openCV. Used Haar feature-based cascade classifiers.

STEPS:
1. Import cv2

2. Retrieve dataset(change file path name)

3. Take input from webcam

4. Read continous input from webcam

5. Convert to grayscale (It is converted to grayscale because the haar cascade classifier takes decisions based on the light intensity. For eg., the eye area is darker compared to forehead). The colour just adds noise to the image. To eliminate it, we convert it to grayscale.

6. Detect faces through haar cascade classifier

7. Construct rectangle around the face if detected. The arguments for cv2.rectangle are- the image, top-left corner, bottom-right corner, color based on (B,G,R) and thickness of line.

8. Mark the ROI(region of interest)

9. Detect eyes in the ROI.

10. Construct rectangle for the eyes as we did for the face.

11. Display image on a window. To quit user must press the key 'q'.

12. When the user hits 'q', an image with the filename given is saved in the folder where the code is present.

13. Close window.

