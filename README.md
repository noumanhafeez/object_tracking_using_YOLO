# object_tracking_using_YOLO

### YOLO (You Only Look Once) is a state-of-the-art object detection algorithm that can detect objects in real time. It works by first dividing the image into a grid, and then running a neural network on each grid cell to predict whether or not there is an object in that cell, and if so, what class of object it is.

### DeepSORT (Simple Online and Realtime Tracking with a Deep Association Metric) is a tracking algorithm that can track multiple objects in a video. It works by first associating each detection from YOLO with a track ID, and then using a Kalman filter to predict the location of each track in the next frame. It also uses a deep association metric to match detections to tracks across frames.

### Here are the steps involved in your project:

### 1.Import the YOLO and DeepSORT models.
### 2. Read the video into memory.
### 3. For each frame in the video:
###     3.1 Run YOLO on the frame to detect objects.
###     3.2 Associate each detection with a track ID.
###     3.3 Use DeepSORT to predict the location of each track in the next frame.
###     3.4 Match detections to tracks across frames.
### 4. Visualize the tracked objects on the video.
