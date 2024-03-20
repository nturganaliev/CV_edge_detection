Project Description:

The project aims to perform edge detection on an image of Al Pacino using the Canny edge detection algorithm. The final output is saved as a PNG image and displayed using Matplotlib.

Methodology:

    Import Libraries: Import the necessary libraries, including OpenCV (cv2) for image processing and Matplotlib (plt) for visualization.
    Read Image: Use cv2.imread to read the input image ('alpacino.jpeg') into a NumPy array.
    Display Original Image: Use Matplotlib to display the original image using plt.imshow.
    Apply Canny Edge Detection: Use cv2.Canny to perform Canny edge detection on the image with specified parameters (100 and 200 thresholds, 3x3 Sobel kernel, and L2 gradient calculation).
    Save and Display Edges: Save the resulting edges as 'alpacino.png' using plt.imsave and display the edges using plt.imshow.

Tools Used:

    OpenCV (cv2): Used for reading and processing images, as well as applying the Canny edge detection algorithm.
    Matplotlib (plt): Used for displaying and saving images, as well as visualizing the edge-detected output.
    Use requirements.txt file to install above dependencies.