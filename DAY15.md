📝 Summary of the Day

Today, I worked on understanding and implementing basic image preprocessing and edge detection using OpenCV in Python. I focused on converting images to grayscale, applying Gaussian blur, and detecting edges using the Canny edge detector.

🔍 Detailed Activities

Image Preprocessing with OpenCV

I followed a step-by-step approach to preprocess images and detect edges:

Read an Image: Loaded an image using cv2.imread('/content/pexels-photo-1427430.jpeg').

Convert to Grayscale: Converted the image to grayscale using cv2.cvtColor(image, cv2.COLOR_BGR2GRAY).

Apply Gaussian Blur: Applied Gaussian blur to reduce noise using cv2.GaussianBlur(gray_image, (5, 5), 0).

Edge Detection: Detected edges using the Canny edge detector with cv2.Canny(blurred_image, 50, 150).

Display Results: Displayed the original, grayscale, and edge-detected images using Matplotlib.
