Que: Which Python libraries did you use in this project and why?
Ans: I used OpenCV (cv2) for image processing, NumPy for numerical operations, and optionally
Tkinter or Streamlit for GUI or web interfaces.

Que: What are the basic steps involved in converting an image to a pencil sketch?
Ans: 1. Read the image. 
     2. Convert to grayscale. 
     3. Invert the grayscale image. 
     4. Apply Gaussianblur. 
     5. Invert the blurred image. 
     6. Blend with the grayscale image using cv2.divide().
