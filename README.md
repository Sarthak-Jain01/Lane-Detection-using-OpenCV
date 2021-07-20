# Lane-Detection-using-OpenCV
I used Python and OpenCV to detect lane lines on the road. I developed a processing pipeline that works on a series of individual images, and applied the result to a video stream.
# Pipeline architecture:
1. Load test images.
2. Apply Color Selection
3. Apply Canny edge detection.
  3.1. Apply gray scaling to the images.
  3.2. Apply Gaussian smoothing.
  3.3. Perform Canny edge detection.
4. Determine the region of interest.
5. Apply Hough transform.
6. Average and extrapolating the lane lines.
7. Apply on video streams.
