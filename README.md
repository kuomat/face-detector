# Face Detector

The face_detector method is a function that can detect faces in a video and output the results as a json object.

## Requirements
- Python 3.x
- OpenCV 2 or 3
- Pandas

## Installation
### OpenCV
To install OpenCV, run the following command:
```pip install opencv-python```

### Pandas
```pip install pandas```

### Numpy
```pip install numpy```

### IMUtils
```pip install imutils```

## Usage
To use the face_detector method, follow these steps:
Call the face_detector method with the following arguments:
- filename: Name of the file
- filepath: The path to the video file.
- start_time (optional): The start time (in seconds) of the video.
- end_time (optional): The end time (in seconds) of the video.
- start_frame (optional): The start frame of the video.
- end_frame (optional): The end frame of the video.

## Example
```json = face_detector("test_name", "./video.mp4")```