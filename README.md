# Lane-Detection-using-OpenCV
I used Python and OpenCV to detect lane lines on the road. I developed a processing pipeline that works on a series of individual images, and applied the result to a video stream.
![output_example](https://user-images.githubusercontent.com/86313081/126274111-8e1daa84-5983-4e6d-8600-96b09cd6ff05.jpg)

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
