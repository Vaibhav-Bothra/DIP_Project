## Curved Lane Detection and Turn Prediction
- Lane detection plays a vital role in the functionality of autonomous vehicles, offering significant real-world applications. 
- It enables vehicles to remain within their designated lane, maintain safe speeds, and manage appropriate distances from other cars, ensuring secure navigation.
- This system leverages computer vision techniques to identify and monitor road lanes and surrounding vehicles.
- By analyzing video frames captured by a camera, the goal is to develop a real-time solution that can be integrated into autonomous vehicles.

For setting up the project, do the following steps:
1. The DIP_Report is the report file that gives the idea and solution to the curved lane and turn prediction problem.
2. In Lane_Detection.py, there is a line which takes the video file as input written as
```
input_video = cv2.VideoCapture('input_video_name.mp4')
```
and output file as 
```
out = cv2.VideoWriter('output_video_name.avi', fourcc, 20.0, (width, height)) 
```
3. The input files are curved_lane, curved_lane1 and straight_lane that are used by us.
4. The output files are curved_lane_output, curved_lane1_output and straight_lane_output.

## References:
1. Edge Detection - https://blog.roboflow.com/edge-detection/#:~:text=Edge%20detection%20works%20by%20looking,etc.%2C%20as%20detailed%20above
2. Perspective Transformation - https://www.geeksforgeeks.org/perspective-transformation-python-opencv/
3. Histogram Equalization Clahe - https://www.geeksforgeeks.org/clahe-histogram-eqalization-opencv/
