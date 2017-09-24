#**Detecting-Lane-Lines**

<img src="laneLines_thirdPass.jpg" width="480" alt="Combined Image" />

The pipeline here is the basic skeleton to detect lane lines. It doesn't use the advanced way of slope finding and extrapolating the line in the draw_lines function. The algorithm also would have problems when there is a car or an object in region of interest and the algorithm would have more lines detected than usual. If the car changes lanes the algorithm would have the same issue with many lines detected. Also the curved roads with curved lane lines will have issue with error. As the radius of curvature of the curve increases the error on the lane lines increases. Different lighting conditions would have different tuning of the threshold and other parameters.
